# bilibili-tools

[bilibili-tools](https://github.com/Dawnnnnnn/bilibili-tools)的修改版本，例用[Github action](https://github.com/features/actions)实现自动化，每天自动做每日任务：

- 每日投币
- 每日登录
- 每日分享
- 每日观看

需要在**Settings-Secrets**配置参数：

参数名|描述|必需
-----|---|-----
B_USERNAME|用户名|是
B_PASSWORD|密码|是
IS_DISABLE_COIN|是否取消自动投币，“是”设置为1，否不设置|否
IS_DISABLE_SHARE|是否取消自动分享，“是”设置为1，否不设置|否
IS_DISABLE_WATCH|是否取消自动观看，“是”设置为1，否不设置|否
