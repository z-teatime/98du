# 开发采坑记

> 记录开发总遇到的坑. 



## H5-活动

1. 所有页面 `http` 协议改成 `https`. [禅道任务][1]
2. active 项目打包要拷贝到 ballVide-H5 下. 
3. ballVideo 上线要对 active 做不同的打包.
4. 开发完后, app确认没啥问题. 直接上线, 不用等. 

```html
<string name="about_url">http://h5xy.uheixia.com/XYAppErtongguoxue/About.html</string> 
<string name="contact_url">http://h5xy.uheixia.com/XYAppErtongguoxue/ContactUs.html</string> 
<string name="protocol_url">http://h5xy.uheixia.com/XYAppErtongguoxue/UserProtocol.html</string> 
<string name="policy_url">http://h5xy.uheixia.com/XYAppErtongguoxue/PrivacyPolicy.html</string> 
<string name="tortsstatement_url">http://h5xy.uheixia.com/XYAppErtongguoxue/Tortsstatement.html</string>
```



---

[1]: http://zt.98du.com/index.php?m=task&f=view&taskID=816