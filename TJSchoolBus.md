TONGJI SCHOOL BUS
================================

*GET*

`http://202.120.164.35:8080/cws/ws/rest/saveticket?startArea={}&endArea={}&startTime={}&startDate={}&line={}&sno={}&sname={}&reservetime={}&carid={}&_jsonp=callback&_=1476174899645`

    startArea: 四平/嘉定
    endArea: 四平/嘉定
    startTime: HH:MM
    startDate: YYYY-MM-DD
    line: 中环直达
    sno: 你的学号
    sname: 你的姓名 （学号作为唯一的身份识别，姓名对错并不影响）
    reservetime： YYYY-MM-DD_HH:MM (日期和时间中间一个空格；如果你的浏览器不支持空格，可以手动编码一下，把空格换成%20）（最好改成前一天显得你是前一天订的)
    carid: 车次（1， ∞） （如果返回结果为code:null且订票不成功，把车次往后改几班就好）

因为请求车次和验票员的不一致，所以会导致验票员的终端上本次名单没有你的

但是不要慌，可以让验票员扫二维码上车，生成二维码是有效可用的
