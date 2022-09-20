### label标签通常是写在表单（form）内的，他与一个普通的span最大的不同，就是可以和表单元素配对，比如文本框，单选框，复选框。而配对的方法，就是通过label的for属性。
```html
	<div>
			<input type = "text" name = "" id = "text"><label for = "text">測試Label(使用for與ID配對)</label>
			<br>
			<input type = "text" name = "" id = "span1"><span for = "span1">測試span</span>
			<br>
		</div>
```
### 如果你不想给label加for，但又想把input元素后面的文字和input本身关联起来，那你也可以这样：
#### <span style="color:red">注意:  label包input的方法，在IE6下无效！
```html
			<label>
				<input type = "text" name = "" id = "">另一種方法(不使用for)
			</label>
```
