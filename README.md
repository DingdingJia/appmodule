# appmodule 安卓app模块

一.appmoduleqrcode 扫码组件

介绍：  
二维码扫描与生成，跳转到扫描二维码扫描的界面，扫描二维码  
使用流程：   
1.依赖appmoduleqrcode 库  
2.跳转到CaptureActivity扫描二维码



二：appmoduleclipimg 上传头像组件

介绍：  
调用系统相册选择图片,将图片裁剪成正方形图片,上传得到的正方形图片地址给服务器    
使用流程：   
1.依赖appmoduleclipimg库   
2.继承ClipImgActivity类  
3.重写onSaveImage(String path)方法  
4.得到path图片地址   



三：appmoduledsbridge JSBridge组件

介绍：  
统一web端与android端交互逻辑  
使用流程：   
WebView.callHandler("web方法", new Object[] { 传输参数 });



四：appmodulephotoupload 图片上传组件

介绍：  
在选择图片页面选择多张图片，上传得到的多张图片地址给服务器    
使用流程：   
1.依赖appmodulephotoupload库    
2.继承PhotoPickerActivity类    
3.重写onSaveImgClick()方法    
4.得到mSelectList多张图片地址    




五：appmodulerecordwechat 上传语音组件

介绍：  
在发送语音页面录制语音,将录制好的语音上传到服务器,得到语音地址收听      
使用流程：   
1.依赖appmodulerecordwechat 库    
2.继承RecordFragment类    
3.重写onRecordFinished()方法    
4.得到filePath上传的语音地址    

