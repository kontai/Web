# CSS



## 使用CSS完成網站首頁的優化

需求分析:

​	由於使用表格布局存在缺陷,那麼我們要可慮使用DIV+CSS來對育面進行優化

表格布局的缺陷:

	 1. 嵌套層級太多,一旦出現嵌套順序錯亂,整個葉面達不到預期效果
	 2. 採用表格布局,頁面不夠靈活,牽一髮動全身


CSS浮動：浮動的元素會脫離正常的文檔流，在正常的文檔流中不占空間。

- float屬性: 
	- left 
    - right  

- clear屬性:清除浮動
    - both:	兩邊都不允許浮動
    - left:	左邊不允許浮動
    - right:	右邊不允許浮動

- CSS中的其他選擇器
    - 選擇器分組:選擇器1,選擇器2(屬性的名稱:屬性值)
    - 屬性選擇器:
```
    a[title]
    a[title='aaa']
    a[href][title]
    a[href][title='aaa]
```
- CSS 链接    
    设置链接的样式    
    能够设置链接样式的 CSS 属性有很多种（例如 color, font-family, background 等等）。
    链接的特殊性在于能够根据它们所处的状态来设置它们的样式。

链接的四种状态：    
- a:link - 普通的、未被访问的链接
- a:visited - 用户已访问的链接
- a:hover - 鼠标指针位于链接的上方
- a:active - 链接被点击的时刻

实例
```
a:link {color:#FF0000;}		/* 未被访问的链接 */
a:visited {color:#00FF00;}	/* 已被访问的链接 */
a:hover {color:#FF00FF;}	/* 鼠标指针移动到链接上 */
a:active {color:#0000FF;}	/* 正在被点击的链接 */
```


    
    
    
    
    
    
    
    
    