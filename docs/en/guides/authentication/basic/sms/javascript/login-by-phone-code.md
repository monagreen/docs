!!!include(common/init-js-auth-sdk.md)!!!

首先调用发送短信验证码接口发送短信验证码，然后使用 `loginByPhoneCode` 方法：

```javascript
authenticationClient.loginByPhoneCode("176xxxx6754", "1234");
```