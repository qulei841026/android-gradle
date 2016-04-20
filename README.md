# android-gradle

关于Gradle在Android studio中的使用，结合项目实际场景配置Gradle需求。

###配置keystore文件信息
    关于Keystrore安全问题，项目中不应该将如下文件上传到代码仓库中：[test_keystore.jks] [keystore.properties] 
    本文只是为了展示可调用的文件路径而使用的，请大家使用上注意这一点。
感谢安全的keystore[原作者](http://blog.mosil.biz/2015/08/android-keystore-info-extra-from-build-gradle/)

###增量版本号控制
    通过配置文件记录版本增量，组合参数生产版本名称。

##问题反馈
如有任何问题，欢迎反馈给我，可以用以下联系方式跟我交流

* 邮件(267023750#qq.com, 把#换成@)
* QQ: 267023750