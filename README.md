- 👋 Hi, I’m @Lixuechong
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Lixuechong/Lixuechong is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
java.lang.RuntimeException: Unable to start activity ComponentInfo{com.meitu.skin.doctor/com.matisse.ucrop.UCropActivity}: java.lang.NullPointerException: Attempt to invoke interface method 'java.lang.Object kotlin.jvm.functions.Function2.invoke(java.lang.Object, java.lang.Object)' on a null object reference
        at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:3747)
        at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:3905)
        at android.app.servertransaction.LaunchActivityItem.execute(LaunchActivityItem.java:85)
        at android.app.servertransaction.TransactionExecutor.executeCallbacks(TransactionExecutor.java:135)
        at android.app.servertransaction.TransactionExecutor.execute(TransactionExecutor.java:95)
        at android.app.ActivityThread$H.handleMessage(ActivityThread.java:2312)
        at android.os.Handler.dispatchMessage(Handler.java:106)
        at android.os.Looper.loop(Looper.java:257)
        at android.app.ActivityThread.main(ActivityThread.java:8178)
        at java.lang.reflect.Method.invoke(Native Method)
        at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:626)
        at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1015)
     Caused by: java.lang.NullPointerException: Attempt to invoke interface method 'java.lang.Object kotlin.jvm.functions.Function2.invoke(java.lang.Object, java.lang.Object)' on a null object reference
        at com.matisse.ucrop.UCropActivity.configActivity(UCropActivity.java:71)
        at com.matisse.ui.activity.BaseActivity.onCreate(BaseActivity.kt:26)
        at android.app.Activity.performCreate(Activity.java:8119)
        at android.app.Activity.performCreate(Activity.java:8103)
        at android.app.Instrumentation.callActivityOnCreate(Instrumentation.java:1309)
        at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:3720)
        at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:3905) 
        at android.app.servertransaction.LaunchActivityItem.execute(LaunchActivityItem.java:85) 
        at android.app.servertransaction.TransactionExecutor.executeCallbacks(TransactionExecutor.java:135) 
        at android.app.servertransaction.TransactionExecutor.execute(TransactionExecutor.java:95) 
        at android.app.ActivityThread$H.handleMessage(ActivityThread.java:2312) 
        at android.os.Handler.dispatchMessage(Handler.java:106) 
        at android.os.Looper.loop(Looper.java:257) 
        at android.app.ActivityThread.main(ActivityThread.java:8178) 
        at java.lang.reflect.Method.invoke(Native Method) 
        at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:626) 
        at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1015) 
