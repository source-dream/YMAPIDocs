# 成都理工大学非官方接口

## 登录接口

### 介绍

登录成都理工大学教务处(维护中)

### 请求URL

https://api.sourcedream.cn/cdut/login

### 请求方式

POST

### 请求参数

|参数名|必选|类型|说明|
|:--:|:--:|:--:|:--:|
|username|是|string|用户名|
|password|是|string|用户名|

### 请求示例

```uniapp
```

### 返回参数

|参数名|类型|说明|
|:--:|:--:|:--:|
|code|int|412-账号密码错误|
|cookies|string|cookies|

### 返回示例



### 备注

<hr>

## 课程表获取接口(正常)

获取当学期课程表信息

### 请求URL

https://api.sourcedream.cn/cdut/timetable

### 请求方式

POST

### 请求参数

|参数名|必选|类型|说明|
|:--:|:--:|:--:|:--:|
|username|是|string|用户名|
|password|是|string|用户名|
|type|否|int|返回值类型|

### 请求示例

### 返回参数

参数名|类型|说明
:--:|:--:|:--:
code|int|200-正常 412-密码错误
schedule|list|课程信息

### 返回示例

```json
{"code": 200,"schedule": [{'name': '计算机视觉', 'teacher': '邱吉刚', 'room': '（宜）乙401', 'weekday': 1, 'start': 1, 'end': 2, 'week': [1, 2, 3, 4, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17]}, {'name': 'Python语言程序设计', 'teacher': '温泉', 'room': '（宜）综B202（计算机）', 'weekday': 2, 'start': 1, 'end': 2, 'week': [2, 3, 4, 6]}]}
```

### 备注



name-课程名字 teacher-邱吉刚 room-教室位置 weekday-课程所在星期 start-课程开始节数 end-课程结束节数 week-课程开设周数

<hr>

## 成绩信息获取接口(维护中)

获取所有学期成绩信息

### 请求URL

### 请求方式

### 请求参数

### 请求示例

### 返回参数

### 返回示例

### 备注

<hr>

## 考试信息获取接口(维护中)

获取考试时间地址信息

### 请求URL

### 请求方式

### 请求参数

### 请求示例

### 返回参数

### 返回示例

### 备注

<br>

## 教务处通知接口(维护中)

获取教务处通知

### 请求URL

https://api.sourcedream.cn/cdut/notice

### 请求方式

### 请求参数

### 请求示例

### 返回参数

### 返回示例

### 备注