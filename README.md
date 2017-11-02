# FBAudienceNetwork.podspec.json 修正后
pod install的时候 遇到安装FBAudienceNetwork的问题，原来里面的
FBAudienceNetwork.podspec.json的source指向的是http://develop.facebook.com
ss翻墙后只能是浏览器http可以用，curl 终端还是不能翻墙，找了挺久的

我的路径是 spec>2>1>5>FB**** 
source修正为：https://github.com/weizeng/facebook/raw/master/FBAudienceNetwork-4.26.0.zip

FBAudienceNetwork-4.26.0 库放到这里
