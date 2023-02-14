# AutoPackAPK
用Actions自动打安卓包的项目测试

##### 生成base64 key
openssl base64 < autopack.jks | tr -d '\n' | tee autopack.jks.base64.txt