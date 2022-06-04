人脸识别考勤管理系统

客户端Android



开发环境
java1.8
android-studio3.5

管理员功能设计
（1）管理员登录：管理员是系统的管理者，在登录系统后将获取系统的最高权限从而管理系统的数据。
（2）员工管理：员工注册后管理员可以对员工的账号信息以及人脸照片进行管理。
（3）部门管理：通过管理员去建立企业内部的部门信息实现员工账号和企业部门之间的绑定。
（4）考勤时间管理：每个企业的考勤时间都不一样，系统可以建立企业自定义考勤的时间管理。
（5）考勤信息管理：员工考勤的信息都会存储在数据库中，在服务端管理员可以通过统计功能查询出所有的考勤信息。
（6）请假管理：实现对员工请假信息的查询、审核以及回复等。
（7）账号管理：管理者可以对自己登录账号的信息以及账号密码的维护管理。


员工功能设计
（1）员工注册登录：员工使用安卓端通过管理员分配的工号和密码注册进行系统，并通过注册信息登录验证。
（2）考勤信息查询：员工进入系统后会查询当日所有考勤信息，包含考勤地点和时间等。
（3）员工考勤：员工进入考勤详情页面后会根据GPS进行位置的定位，点击考勤后通过人脸识别进行考勤打卡。
（4）员工请假：在手机端发起请假申请提交到服务端，管理员可以对员工的请假进行审批回复。
（5）我的考勤记录：员工在考勤记录模块可以查询出所有的考勤记录以及请假记录。
（6）账号管理：通过个人中心可以修改账号信息以及人脸照片和实现对账号密码的变更。
