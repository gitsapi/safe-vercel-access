# Vercel 安全访问
## 为您的 Vercel 访问部署添加密码
### 使用方法
在部署项目时，只需选择添加环境变量：
```
// 将 NEXT_PUBLIC_ACCESSURL 设置为您的访问 URL 环境变量，例如 https://domain.com/
let target = process.env.NEXT_PUBLIC_ACCESSURL;

// 将 NEXT_PUBLIC_SAFEPWD 设置为您的密码环境变量
const PASSWORD = process.env.NEXT_PUBLIC_SAFEPWD;
```
对于 https://www.google.com/ 首次访问并验证密码后，需要关闭网页后，重新打开。

# vercel safe access
## add a password for u vercel access deploy
### how to use
Just choose to add  environment variable when you deploy the project:
```
// set NEXT_PUBLIC_ACCESSURL as u access url environment variable,such as https://domain.com/
let target = process.env.NEXT_PUBLIC_ACCESSURL;

// set NEXT_PUBLIC_SAFEPWD as u password environment variable
const PASSWORD = process.env.NEXT_PUBLIC_SAFEPWD;
```
for https://www.google.com/, close and refresh web page is required after the first access and password verification.
