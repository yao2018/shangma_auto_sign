## 上马自动签到 [![Run Auto Sign](https://github.com/angyyang/shangma_auto_sign/actions/workflows/auto-sign.yaml/badge.svg)](https://github.com/angyyang/shangma_auto_sign/actions/workflows/auto-sign.yaml)

## 上马2025年6月改版后原有代码无法自动签到了，重新分析新的签到接口后对代码做了改动，需要重新配置系统参数来签到，此代码可运行。具体使用方式待更新。 20250707

## 具体使用方式已更新。 20250708

## 2025没中签，感觉今年抽签积分的作用不大。

### 基于 Node.js + GitHub Action 实现上海马拉松官网每日签到

### Use 使用

1. Fork本项目（顺手点Star以示鼓励～🥳）
2. //在Repo的Setting页面，添加名为上马官网的用户名：`SM_USERNAME`和密码：`SM_PASSWORD`的Secret
3. 在Repo的Setting页面，Secrets and Variables添加如下actions变量：登陆信息`SM_LOGIN`和上马用户id：`SM_USER_ID`
    登陆信息获取方式：登陆上马网： https://static.shang-ma.com/web/login/index.html 找到login的请求，把request payload整个复制出来放入SM_LOGIN
   ![image](https://github.com/user-attachments/assets/537f5ed0-f6ba-48fb-972a-2a3d19ded875)
   找到一个纯数字的请求，把这个数字复制出来放入SM_USER_ID
   ![image](https://github.com/user-attachments/assets/463f04e8-f6e6-419d-876a-de9211ee594d)




5. 手动测试运行
<img width="1444" alt="image" src="https://github.com/zhaohongxuan/shangma_auto_sign/assets/8613196/695683c9-fbc2-4cab-9ef8-41e2ddf59b78">
在控制台应该能看到 `签到成功/请勿重复签到` 的提示
<img width="990" alt="image" src="https://github.com/zhaohongxuan/shangma_auto_sign/assets/8613196/399e89f7-2ad6-486e-9e67-8953564ec528">


### 关于Job执行时间
签到Job执行时间是**UTC时间0点**，也就是**北京时间8点**执行，**不过由于GitHub的负载比较重**，真正签到时间可能延后一段时间，一般是几十分钟，这个延迟时间取决于GitHub Action的负载。

### 申明
- 本项目仅做学习交流, 禁止用于各种非法途径

- Auto Sign-in run successful on Wed Dec 31 00:49:48 UTC 2025
- Auto Sign-in run successful on Thu Jan  1 00:55:12 UTC 2026
- Auto Sign-in run successful on Fri Jan  2 00:49:53 UTC 2026
- Auto Sign-in run successful on Sat Jan  3 00:45:08 UTC 2026
- Auto Sign-in run successful on Sun Jan  4 00:55:16 UTC 2026
- Auto Sign-in run successful on Mon Jan  5 00:54:27 UTC 2026
- Auto Sign-in run successful on Tue Jan  6 00:49:49 UTC 2026
- Auto Sign-in run successful on Wed Jan  7 00:49:46 UTC 2026
- Auto Sign-in run successful on Thu Jan  8 00:49:50 UTC 2026
- Auto Sign-in run successful on Fri Jan  9 00:49:45 UTC 2026
- Auto Sign-in run successful on Sat Jan 10 00:47:48 UTC 2026
- Auto Sign-in run successful on Sun Jan 11 00:54:54 UTC 2026
- Auto Sign-in run successful on Mon Jan 12 00:52:57 UTC 2026
- Auto Sign-in run successful on Tue Jan 13 00:44:31 UTC 2026
- Auto Sign-in run successful on Wed Jan 14 00:51:59 UTC 2026
- Auto Sign-in run successful on Thu Jan 15 00:46:39 UTC 2026
- Auto Sign-in run successful on Fri Jan 16 00:50:47 UTC 2026
- Auto Sign-in run successful on Sat Jan 17 00:47:18 UTC 2026
- Auto Sign-in run successful on Sun Jan 18 00:54:12 UTC 2026
- Auto Sign-in run successful on Mon Jan 19 00:53:43 UTC 2026
- Auto Sign-in run successful on Tue Jan 20 00:48:10 UTC 2026
- Auto Sign-in run successful on Wed Jan 21 00:51:29 UTC 2026
- Auto Sign-in run successful on Thu Jan 22 00:50:06 UTC 2026
- Auto Sign-in run successful on Fri Jan 23 00:51:15 UTC 2026
- Auto Sign-in run successful on Sat Jan 24 00:48:00 UTC 2026
- Auto Sign-in run successful on Sun Jan 25 00:55:56 UTC 2026
- Auto Sign-in run successful on Mon Jan 26 00:54:54 UTC 2026
- Auto Sign-in run successful on Tue Jan 27 00:53:21 UTC 2026
- Auto Sign-in run successful on Wed Jan 28 00:50:42 UTC 2026
- Auto Sign-in run successful on Thu Jan 29 00:58:10 UTC 2026
- Auto Sign-in run successful on Fri Jan 30 00:58:03 UTC 2026
- Auto Sign-in run successful on Sat Jan 31 00:55:39 UTC 2026
- Auto Sign-in run successful on Sun Feb  1 01:08:32 UTC 2026
- Auto Sign-in run successful on Mon Feb  2 01:01:27 UTC 2026
- Auto Sign-in run successful on Tue Feb  3 01:02:10 UTC 2026
- Auto Sign-in run successful on Wed Feb  4 00:57:37 UTC 2026
- Auto Sign-in run successful on Thu Feb  5 00:59:59 UTC 2026
- Auto Sign-in run successful on Fri Feb  6 00:57:50 UTC 2026
- Auto Sign-in run successful on Sat Feb  7 00:57:00 UTC 2026
- Auto Sign-in run successful on Sun Feb  8 01:17:53 UTC 2026
- Auto Sign-in run successful on Mon Feb  9 01:03:54 UTC 2026
- Auto Sign-in run successful on Mon Feb  9 08:01:44 UTC 2026
- Auto Sign-in run successful on Tue Feb 10 01:52:02 UTC 2026
- Auto Sign-in run successful on Wed Feb 11 01:48:27 UTC 2026
- Auto Sign-in run successful on Thu Feb 12 01:28:37 UTC 2026
- Auto Sign-in run successful on Fri Feb 13 01:44:08 UTC 2026
- Auto Sign-in run successful on Sat Feb 14 01:23:20 UTC 2026
- Auto Sign-in run successful on Sun Feb 15 01:43:09 UTC 2026
- Auto Sign-in run successful on Mon Feb 16 01:27:05 UTC 2026
- Auto Sign-in run successful on Tue Feb 17 01:26:40 UTC 2026
- Auto Sign-in run successful on Wed Feb 18 01:28:59 UTC 2026
- Auto Sign-in run successful on Thu Feb 19 01:28:44 UTC 2026
