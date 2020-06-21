# 表单标签form <br /> 
 action: 直接提交的地址 <br />
 method:
     <li> get 方式  默认提交方式 ,会将参数拼接在链接后面 , 有大小限制 ,4k</li>
      <li>post 方式  会将参数封装在请求体中, 没有这样的限制</li>
      
### input.  

      type: 指定输入项的类型
      text : 文本
      password :  密码框
      radio :		单选按钮
      checkbox :  复选框
      file 	 : 上传文件
      submit   : 提交按钮
      button 	 : 普通按钮
      reset	 : 重置按钮
      hidden  : 隐藏域
      date    : 日期类型
      tel     : 手机号
      number   : 只允许输入数字
      placeholder : 指定默认的提示信息
      name : 在表单提交的时候,当作参数的名称
      id : 给输入项取一个名字, 以便于后期我们去找到它,并且操作它

### textarea : 文本域, 可以输入一段文本
      cols : 指定宽度
      rows : 指定的是高度

### select  : 下拉列表
      option : 选择项
