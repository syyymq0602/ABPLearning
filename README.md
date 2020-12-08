# Asp.net core Learning

Study for the .net core

### RazorPageMoive
1. 教程参考官网 [Razor](https://docs.microsoft.com/zh-cn/aspnet/core/tutorials/razor-pages/?view=aspnetcore-5.0) 。
2. 具体功能的实现是做了一个简单的Web前后端应用程序，通过URL对应的请求把数据存取到本地MySQL中。
3. 相对于官网教程有改动：删除了Pages/Shared/_Layout.cshtml文件关于Home组件的显示，并加上了Pages/Movies/Index的组件，通过组件可以直接进入到Movies的索引界面，不需要再手动输入改变URL跳转。

### MvcMovie
1. 教程参考官网 [Mvc](https://docs.microsoft.com/zh-cn/aspnet/core/tutorials/first-mvc-app/start-mvc?view=aspnetcore-5.0&tabs=visual-studio) 。

### TodoAPI
1. 编写了Web后端，Controller负责处理HTTP请求逻辑，TodoItemDTO负责页面显示。
2. 加入了使用JS的前端代码，前端样式有待改善。