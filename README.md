# ZhiHu_Invitees_Actions
Actions工具人知乎问题自动邀请

## 第八套中小学生广播体操，现在开始...
第一节，_φ(❐_❐✧ 人丑就要多读书

┏(＾0＾)┛   ┏(´0｀)┛   ┏(´0｀)┛   ┏(´0｀)┛

┗(＾0＾)┏   ┗(｀0´)┏   ┗(｀0´)┏   ┗(｀0´)┏

┗(＾0＾)┛   ┏(´0｀)┛   ┏(´0｀)┛   ┗(｀0´)┏   ┗(｀0´)┏

_(:ι」∠)_好饿，但是不想动

睡觉没前途(￣o￣) . z Z　

## 运行环境

 - Github Actions

## 更改执行时间

在【***.github/workflows/python-packetage.yml***】更改如下代码

```python
on:
  schedule:
    - cron: '0 0 * * *'  # 每天运行（UTC时间），BeiJing时区 +8
```

## Secrets参数说明
 - COOKIE：***COOKIE（知乎获取）***
 - QuestionsID:***https://www.zhihu.com/question/xxxxxx（知乎获取）***
