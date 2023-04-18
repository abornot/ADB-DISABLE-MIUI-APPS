# MIUI 14 禁用 App 列表

### 1. 禁用列表

|  名称   | 包名  |
|  ----  | ----  |
| 系统广告解决方案  | com.miui.systemAdSolution |
| 广告分析  | com.miui.analytics |
| 游戏服务  | com.xiaomi.gamecenter.sdk.service|
| 搜狗输入法小米版  | com.sohu.inputmethod.sogou.xiaomi |
| 音乐  | com.miui.player |
| 小米视频  | com.miui.video |
| 金山翻译  | com.miui.translation.kingsoft |
| 电子邮件  | com.android.email |
| 快应用服务框架  | com.miui.hybrid |
| 用户反馈  | com.miui.bugreport |
| 投屏  | com.milink.service |
| 浏览器  | com.android.browser |
| 生活黄页  | com.miui.yellowpage |
| 米币支付  | com.xiaomi.payment |
| 小爱同学  | com.miui.voiceassist |
| 悬浮球  | com.miui.touchassistant |
| 服务与反馈  | com.miui.miservice |
| 小米商城系统组件  | com.xiaomi.ab |
| AI虚拟助手  | com.xiaomi.aiasst.service |
| Joyose  | com.xiaomi.joyose |
| 小米互联通信服务  | com.xiaomi.mi_connect_service |
| 小米支付  | com.miui.nextpay |
| 智能助理  | com.miui.personalassistant |

### 2. 查看 App 列表命令

./adb shell pm list package

### 3. 禁用命令

./adb shell pm disable-user com.miui.systemAdSolution

### 4. 启用命令

./adb shell pm enable com.miui.systemAdSolution

### 5. 注意

安装 App 时提示 Failure [INSTALL_FAILED_USER_RESTRICTED: Install canceled by user]，关闭启用 MIUI 优化即可。
