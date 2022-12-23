# README

## 网站说明

- 进入主页面后会自动跳转至登陆注册页面（基于LocalStorage）                

  - 根据提示**点击**，可以自动生成注册账号并登陆，点击顺序如下：

  - - 点击**sign up**按钮
    
      <img src="D:\Code\web\U-YOUNG\images\md\image-20221223204136831.png" alt="image-20221223204136831" style="zoom:60%;" />
    
    - 点击登陆/注册提示中的**“我”**自动生成账号密码
    
      <img src="D:\Code\web\U-YOUNG\images\md\image-20221223204207203.png" alt="image-20221223204207203" style="zoom:60%;" />
    
    - 点击**确认注册**按钮
    
      <img src="D:\Code\web\U-YOUNG\images\md\image-20221223204258156.png" alt="image-20221223204258156" style="zoom:60%;" />
    
    - 点击登陆注册提示中
      - **是**，以自动生成的账号登陆
      - **否**，以游客身份登陆
      
      <img src="D:\Code\web\U-YOUNG\images\md\image-20221223204410162.png" alt="image-20221223204410162" style="zoom:60%;" />

- Travel一栏为列表页 ，显示了不同的                

  - 行程名称

  - 行程创建时间

  - 行程的喜欢数

  - 行程的评论数

    点击详情页中的**喜欢**和**评论**按钮，列表页的**评论数**和**喜欢数**会相应更新

- Travel下的Add New按钮为表单页

  - 点击提交后可以在列表页新增相应的项目
  - 点击该新添加的项目也可以生成相应的详情页，使用基于LoacalStorage的动态增删改可以进行针对该新增项目详细信息的修改

- 详情页为前端模板自动生成的html页面
  每个详情页均可以实现基于LocalStorage的动态增删改