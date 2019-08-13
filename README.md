# DailyMail

每日暖心邮件
## 安装与使用
如果你觉得这封邮件的内容适合你发送的对象，可以按照以下步骤，改少量参数即可运行程序；

1. git clone https://github.com/Vincedream/NodeMail
2. 打开main.js，修改配置项

``` javascript
//纪念日
let startDay = "2016/6/24";

//当地拼音,需要在下面的墨迹天气url确认
const local = "zhejiang/hangzhou";

//发送者邮箱厂家
let EmianService = "163";
//发送者邮箱账户SMTP授权码
let EamilAuth = {
  user: "xxxxxx@163.com",
  pass: "xxxxxx"
};
//发送者昵称与邮箱地址
let EmailFrom = '"name" <xxxxxx@163.com>';

//接收者邮箱地
let EmailTo = "like@vince.studio";
//邮件主题
let EmailSubject = "一封暖暖的小邮件";

//每日发送时间
let EmailHour = 6;
let EmialMinminute= 30;
```
3. 终端输入`npm install`安装依赖，再输入`node main.js`，运行脚本
