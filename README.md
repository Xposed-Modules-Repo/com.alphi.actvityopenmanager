# Activity链式启动管理器
这是一个拦截三方App自动启动另一个三方App的模块，当存在三方app启动另一个三方App该模块会弹出一个对话框征求自己意见，同时也可以设置自定义规则。 欢迎尝试吧！  
如果你觉得这个模块好用，您可打开应用打赏支持作者，要是能打赏一杯咖啡6.66，一顿晚餐12.00🍯，一顿烧烤66.66... 那真是太棒了！  
您的支持就是作者更新维护的动力！（每次更新需重启手机）  

### 自定义规则说明
自定义规则可以灵活的配置各种应用（暂不支持配置系统应用），有三种指令，指令中`allow` `ask` `deny`分别是允许、询问、拒绝  
规则模板1：`allow  包名A  包名B` &nbsp;允许应用A启动应用B，不会弹出启动对话框  
规则模板2：`deny  包名C  A:活动D`&nbsp;拒绝应用C启动应用活动D，不会弹出启动对话框（注意Activity活动名前面要加`A:`）  
更多高级规则模板请打开应用查看注释  

- 图标计划 如果你有好的图标设计建议，您可提一个[Issue建议](https://github.com/Xposed-Modules-Repo/com.alphi.actvityopenmanager/issues)，图标前提要求是前景（矢量图标）与背景分离。

|![pic_20240730011109](https://github.com/user-attachments/assets/6c49a861-8faf-4fa7-be59-cddabc0d941c)|![7c87e62ca148b140ae3f56107d7f6b2](https://github.com/user-attachments/assets/4b4cf852-9732-48f3-b637-190baff93d46)|
|:---:|:---:|
