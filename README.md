C:\Program Files (x86)\ADB and Fastboot++>adb logcat -d -b crash -t 200
--------- beginning of crash
08-19 20:37:07.491  6135  6170 E AndroidRuntime: *** FATAL EXCEPTION IN SYSTEM PROCESS: ActivityManager
08-19 20:37:07.491  6135  6170 E AndroidRuntime: java.lang.SecurityException: Permission Denial: Component com.google.android.gms/.chimera.container.router.SingletonComponentRouterProvider requests FLAG_SINGLE_USER, but app does not hold android.permission.INTERACT_ACROSS_USERS
08-19 20:37:07.491  6135  6170 E AndroidRuntime:        at com.android.server.am.ActivityManagerService.isSingleton(ActivityManagerService.java:13773)
08-19 20:37:07.491  6135  6170 E AndroidRuntime:        at com.android.server.am.ContentProviderHelper.isSingletonOrSystemUserOnly(ContentProviderHelper.java:2022)
08-19 20:37:07.491  6135  6170 E AndroidRuntime:        at com.android.server.am.ContentProviderHelper.lambda$installEncryptionUnawareProviders$2(ContentProviderHelper.java:1421)
08-19 20:37:07.491  6135  6170 E AndroidRuntime:        at com.android.server.am.ContentProviderHelper.$r8$lambda$Ybb6ASgJllmnwf29cCLpR_JR-Yg(ContentProviderHelper.java:0)
08-19 20:37:07.491  6135  6170 E AndroidRuntime:        at com.android.server.am.ContentProviderHelper$$ExternalSyntheticLambda4.accept(R8$$SyntheticClass:0)
08-19 20:37:07.491  6135  6170 E AndroidRuntime:        at com.android.server.am.PackageList.forEachPackage(PackageList.java:80)
08-19 20:37:07.491  6135  6170 E AndroidRuntime:        at com.android.server.am.ContentProviderHelper.installEncryptionUnawareProviders(ContentProviderHelper.java:1410)
08-19 20:37:07.491  6135  6170 E AndroidRuntime:        at com.android.server.am.UserController$Injector.installEncryptionUnawareProviders(UserController.java:4025)
08-19 20:37:07.491  6135  6170 E AndroidRuntime:        at com.android.server.am.UserController.finishUserUnlocked(UserController.java:827)
08-19 20:37:07.491  6135  6170 E AndroidRuntime:        at com.android.server.am.UserController.handleMessage(UserController.java:3569)
08-19 20:37:07.491  6135  6170 E AndroidRuntime:        at android.os.Handler.dispatchMessage(Handler.java:105)
08-19 20:37:07.491  6135  6170 E AndroidRuntime:        at android.os.Looper.loopOnce(Looper.java:232)
08-19 20:37:07.491  6135  6170 E AndroidRuntime:        at android.os.Looper.loop(Looper.java:317)
08-19 20:37:07.491  6135  6170 E AndroidRuntime:        at android.os.HandlerThread.run(HandlerThread.java:85)
08-19 20:37:07.491  6135  6170 E AndroidRuntime:        at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-19 20:37:07.828  7285  7285 E AndroidRuntime: FATAL EXCEPTION: main
08-19 20:37:07.828  7285  7285 E AndroidRuntime: Process: org.lineageos.settings.doze, PID: 7285
08-19 20:37:07.828  7285  7285 E AndroidRuntime: DeadSystemException: The system died; earlier logs will point to the root cause
08-19 20:37:07.828  7321  7321 E AndroidRuntime: FATAL EXCEPTION: main
08-19 20:37:07.828  7321  7321 E AndroidRuntime: PID: 7321
08-19 20:37:07.828  7321  7321 E AndroidRuntime: DeadSystemException: The system died; earlier logs will point to the root cause
08-19 20:37:07.828  7289  7289 E AndroidRuntime: FATAL EXCEPTION: main
08-19 20:37:07.828  7289  7289 E AndroidRuntime: Process: org.lineageos.audiofx, PID: 7289
08-19 20:37:07.828  7289  7289 E AndroidRuntime: DeadSystemException: The system died; earlier logs will point to the root cause
08-19 20:37:07.831  7275  7275 E AndroidRuntime: FATAL EXCEPTION: main
08-19 20:37:07.831  7275  7275 E AndroidRuntime: Process: com.android.nfc, PID: 7275
08-19 20:37:07.831  7275  7275 E AndroidRuntime: DeadSystemException: The system died; earlier logs will point to the root cause
08-19 20:37:07.831  7264  7264 E AndroidRuntime: FATAL EXCEPTION: main
08-19 20:37:07.831  7264  7264 E AndroidRuntime: Process: org.lineageos.profiles, PID: 7264
08-19 20:37:07.831  7264  7264 E AndroidRuntime: DeadSystemException: The system died; earlier logs will point to the root cause
08-19 20:37:34.155  8625  8853 E AndroidRuntime: FATAL EXCEPTION: LightweightExecutor #1
08-19 20:37:34.155  8625  8853 E AndroidRuntime: Process: com.android.vending, PID: 8625
08-19 20:37:34.155  8625  8853 E AndroidRuntime: java.lang.SecurityException: Calling identity is not authorized
08-19 20:37:34.155  8625  8853 E AndroidRuntime:        at android.os.Parcel.createExceptionOrNull(Parcel.java:3231)
08-19 20:37:34.155  8625  8853 E AndroidRuntime:        at android.os.Parcel.createException(Parcel.java:3215)
08-19 20:37:34.155  8625  8853 E AndroidRuntime:        at android.os.Parcel.readException(Parcel.java:3198)
08-19 20:37:34.155  8625  8853 E AndroidRuntime:        at android.os.Parcel.readException(Parcel.java:3140)
08-19 20:37:34.155  8625  8853 E AndroidRuntime:        at android.app.admin.IDevicePolicyManager$Stub$Proxy.getDeviceOwnerComponent(IDevicePolicyManager.java:7907)
08-19 20:37:34.155  8625  8853 E AndroidRuntime:        at android.app.admin.DevicePolicyManager.getDeviceOwnerComponentInner(DevicePolicyManager.java:9551)
08-19 20:37:34.155  8625  8853 E AndroidRuntime:        at android.app.admin.DevicePolicyManager.getDeviceOwnerComponentOnAnyUser(DevicePolicyManager.java:9516)
08-19 20:37:34.155  8625  8853 E AndroidRuntime:        at wig.j(PG:3)
08-19 20:37:34.155  8625  8853 E AndroidRuntime:        at wig.i(PG:7)
08-19 20:37:34.155  8625  8853 E AndroidRuntime:        at bdjq.d(PG:28)
08-19 20:37:34.155  8625  8853 E AndroidRuntime:        at tlp.b(PG:115)
08-19 20:37:34.155  8625  8853 E AndroidRuntime:        at tlp.kC(PG:76)
08-19 20:37:34.155  8625  8853 E AndroidRuntime:        at tmz.b(PG:357)
08-19 20:37:34.155  8625  8853 E AndroidRuntime:        at tmz.a(PG:171)
08-19 20:37:34.155  8625  8853 E AndroidRuntime:        at cffs.ag(PG:15)
08-19 20:37:34.155  8625  8853 E AndroidRuntime:        at ceps.bq(PG:53)
08-19 20:37:34.155  8625  8853 E AndroidRuntime:        at azzg.b(PG:44)
08-19 20:37:34.155  8625  8853 E AndroidRuntime:        at azzg.kC(PG:16)
08-19 20:37:34.155  8625  8853 E AndroidRuntime:        at bpul.b(PG:100)
08-19 20:37:34.155  8625  8853 E AndroidRuntime:        at bpul.kC(PG:18)
08-19 20:37:34.155  8625  8853 E AndroidRuntime:        at azzf.b(PG:3)
08-19 20:37:34.155  8625  8853 E AndroidRuntime:        at tmz.b(PG:176)
08-19 20:37:34.155  8625  8853 E AndroidRuntime:        at ceyt.x(PG:5)
08-19 20:37:34.155  8625  8853 E AndroidRuntime:        at cfgb.run(PG:109)
08-19 20:37:34.155  8625  8853 E AndroidRuntime:        at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1145)
08-19 20:37:34.155  8625  8853 E AndroidRuntime:        at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:644)
08-19 20:37:34.155  8625  8853 E AndroidRuntime:        at wkg.run(PG:543)
08-19 20:37:34.155  8625  8853 E AndroidRuntime:        at java.lang.Thread.run(Thread.java:1117)
08-19 20:37:34.155  8625  8853 E AndroidRuntime:        Suppressed: kotlinx.coroutines.internal.DiagnosticCoroutineContextException: [cfig{Cancelling}@85b620d, Executor: LightweightExecutor xnk@9d6e5c2[Running, pool size = 4, active threads = 1, queued tasks = 0, completed tasks = 78]]
08-19 20:37:34.155  8625  8853 E AndroidRuntime: Caused by: android.os.RemoteException: Remote stack trace:
08-19 20:37:34.155  8625  8853 E AndroidRuntime:        at com.android.internal.util.Preconditions.checkCallAuthorization(Preconditions.java:254)
08-19 20:37:34.155  8625  8853 E AndroidRuntime:        at com.android.server.devicepolicy.DevicePolicyManagerService.getDeviceOwnerComponent(DevicePolicyManagerService.java:10121)
08-19 20:37:34.155  8625  8853 E AndroidRuntime:        at android.app.admin.IDevicePolicyManager$Stub.onTransact(IDevicePolicyManager.java:3693)
08-19 20:37:34.155  8625  8853 E AndroidRuntime:        at android.os.Binder.execTransactInternal(Binder.java:1391)
08-19 20:37:34.155  8625  8853 E AndroidRuntime:        at android.os.Binder.execTransact(Binder.java:1335)
08-19 20:37:34.155  8625  8853 E AndroidRuntime:
08-19 20:37:37.362  9335  9335 E AndroidRuntime: FATAL EXCEPTION: main
08-19 20:37:37.362  9335  9335 E AndroidRuntime: Process: com.android.vending, PID: 9335
08-19 20:37:37.362  9335  9335 E AndroidRuntime: java.lang.RuntimeException: Unable to create application com.google.android.finsky.application.classic.ClassicApplication: java.lang.SecurityException: You either need MANAGE_USERS or CREATE_USERS permission to: query users
08-19 20:37:37.362  9335  9335 E AndroidRuntime:        at android.app.ActivityThread.handleBindApplication(ActivityThread.java:7592)
08-19 20:37:37.362  9335  9335 E AndroidRuntime:        at android.app.ActivityThread.-$$Nest$mhandleBindApplication(Unknown Source:0)
08-19 20:37:37.362  9335  9335 E AndroidRuntime:        at android.app.ActivityThread$H.handleMessage(ActivityThread.java:2449)
08-19 20:37:37.362  9335  9335 E AndroidRuntime:        at android.os.Handler.dispatchMessage(Handler.java:109)
08-19 20:37:37.362  9335  9335 E AndroidRuntime:        at android.os.Looper.loopOnce(Looper.java:232)
08-19 20:37:37.362  9335  9335 E AndroidRuntime:        at android.os.Looper.loop(Looper.java:317)
08-19 20:37:37.362  9335  9335 E AndroidRuntime:        at android.app.ActivityThread.main(ActivityThread.java:8787)
08-19 20:37:37.362  9335  9335 E AndroidRuntime:        at java.lang.reflect.Method.invoke(Native Method)
08-19 20:37:37.362  9335  9335 E AndroidRuntime:        at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:591)
08-19 20:37:37.362  9335  9335 E AndroidRuntime:        at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:871)
08-19 20:37:37.362  9335  9335 E AndroidRuntime: Caused by: java.lang.SecurityException: You either need MANAGE_USERS or CREATE_USERS permission to: query users
08-19 20:37:37.362  9335  9335 E AndroidRuntime:        at android.os.Parcel.createExceptionOrNull(Parcel.java:3231)
08-19 20:37:37.362  9335  9335 E AndroidRuntime:        at android.os.Parcel.createException(Parcel.java:3215)
08-19 20:37:37.362  9335  9335 E AndroidRuntime:        at android.os.Parcel.readException(Parcel.java:3198)
08-19 20:37:37.362  9335  9335 E AndroidRuntime:        at android.os.Parcel.readException(Parcel.java:3140)
08-19 20:37:37.362  9335  9335 E AndroidRuntime:        at android.os.IUserManager$Stub$Proxy.getUsers(IUserManager.java:2374)
08-19 20:37:37.362  9335  9335 E AndroidRuntime:        at android.os.UserManager.getUsers(UserManager.java:4981)
08-19 20:37:37.362  9335  9335 E AndroidRuntime:        at android.os.UserManager.getUsers(UserManager.java:4922)
08-19 20:37:37.362  9335  9335 E AndroidRuntime:        at android.os.UserManager.getUserCount(UserManager.java:4895)
08-19 20:37:37.362  9335  9335 E AndroidRuntime:        at aosg.ay(PG:13)
08-19 20:37:37.362  9335  9335 E AndroidRuntime:        at tvp.a(PG:104)
08-19 20:37:37.362  9335  9335 E AndroidRuntime:        at qav.<init>(PG:9)
08-19 20:37:37.362  9335  9335 E AndroidRuntime:        at qbk.apply(PG:235)
08-19 20:37:37.362  9335  9335 E AndroidRuntime:        at j$.util.Map$-CC.$default$computeIfAbsent(r8-map-id-a2d9e3422447ac3db16d65a558da8ff6b2f60c40439835e6e36c7e4d74018829:10)
08-19 20:37:37.362  9335  9335 E AndroidRuntime:        at j$.util.Map$-EL.computeIfAbsent(r8-map-id-a2d9e3422447ac3db16d65a558da8ff6b2f60c40439835e6e36c7e4d74018829:23)
08-19 20:37:37.362  9335  9335 E AndroidRuntime:        at atpt.k(PG:15)
08-19 20:37:37.362  9335  9335 E AndroidRuntime:        at atpt.j(PG:13)
08-19 20:37:37.362  9335  9335 E AndroidRuntime:        at qar.a(PG:3)
08-19 20:37:37.362  9335  9335 E AndroidRuntime:        at tvj.a(PG:11)
08-19 20:37:37.362  9335  9335 E AndroidRuntime:        at tvj.t(PG:1)
08-19 20:37:37.362  9335  9335 E AndroidRuntime:        at qaz.F(PG:39)
08-19 20:37:37.362  9335  9335 E AndroidRuntime:        at qaz.I(PG:1)
08-19 20:37:37.362  9335  9335 E AndroidRuntime:        at apxh.a(PG:28)
08-19 20:37:37.362  9335  9335 E AndroidRuntime:        at rgc.ad(PG:44)
08-19 20:37:37.362  9335  9335 E AndroidRuntime:        at rhs.k(PG:988)
08-19 20:37:37.362  9335  9335 E AndroidRuntime:        at rhs.onCreate(PG:23)
08-19 20:37:37.362  9335  9335 E AndroidRuntime:        at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1388)
08-19 20:37:37.362  9335  9335 E AndroidRuntime:        at android.app.ActivityThread.handleBindApplication(ActivityThread.java:7586)
08-19 20:37:37.362  9335  9335 E AndroidRuntime:        ... 9 more
08-19 20:37:37.362  9335  9335 E AndroidRuntime: Caused by: android.os.RemoteException: Remote stack trace:
08-19 20:37:37.362  9335  9335 E AndroidRuntime:        at com.android.server.pm.UserManagerService.checkCreateUsersPermission(UserManagerService.java:4006)
08-19 20:37:37.362  9335  9335 E AndroidRuntime:        at com.android.server.pm.UserManagerService.getUsers(UserManagerService.java:1473)
08-19 20:37:37.362  9335  9335 E AndroidRuntime:        at android.os.IUserManager$Stub.onTransact(IUserManager.java:1102)
08-19 20:37:37.362  9335  9335 E AndroidRuntime:        at android.os.Binder.execTransactInternal(Binder.java:1391)
08-19 20:37:37.362  9335  9335 E AndroidRuntime:        at android.os.Binder.execTransact(Binder.java:1335)
08-19 20:37:37.362  9335  9335 E AndroidRuntime:
08-19 20:37:41.065  8242  9740 E AndroidRuntime: FATAL EXCEPTION: [com.google.android.gms.chimera.container.intentoperation.GmsIntentOperationChimeraService-Executor] idle
08-19 20:37:41.065  8242  9740 E AndroidRuntime: Process: com.google.android.gms, PID: 8242
08-19 20:37:41.065  8242  9740 E AndroidRuntime: java.lang.SecurityException: You either need MANAGE_USERS, CREATE_USERS, or QUERY_USERS permission to: query user
08-19 20:37:41.065  8242  9740 E AndroidRuntime:        at android.os.Parcel.createExceptionOrNull(Parcel.java:3231)
08-19 20:37:41.065  8242  9740 E AndroidRuntime:        at android.os.Parcel.createException(Parcel.java:3215)
08-19 20:37:41.065  8242  9740 E AndroidRuntime:        at android.os.Parcel.readException(Parcel.java:3198)
08-19 20:37:41.065  8242  9740 E AndroidRuntime:        at android.os.Parcel.readException(Parcel.java:3140)
08-19 20:37:41.065  8242  9740 E AndroidRuntime:        at android.os.IUserManager$Stub$Proxy.getUserInfo(IUserManager.java:2615)
08-19 20:37:41.065  8242  9740 E AndroidRuntime:        at android.os.UserManager.getUserInfo(UserManager.java:3916)
08-19 20:37:41.065  8242  9740 E AndroidRuntime:        at android.os.UserManager.isMainUser(UserManager.java:2914)
08-19 20:37:41.065  8242  9740 E AndroidRuntime:        at blwo.t(:com.google.android.gms@262634035@26.26.34 (260400-945364269):12)
08-19 20:37:41.065  8242  9740 E AndroidRuntime:        at ahyk.<init>(:com.google.android.gms@262634035@26.26.34 (260400-945364269):1)
08-19 20:37:41.065  8242  9740 E AndroidRuntime:        at ahyk.a(:com.google.android.gms@262634035@26.26.34 (260400-945364269):33)
08-19 20:37:41.065  8242  9740 E AndroidRuntime:        at com.google.android.gms.auth.frp.FrpUpdateIntentOperation.b(:com.google.android.gms@262634035@26.26.34 (260400-945364269):15)
08-19 20:37:41.065  8242  9740 E AndroidRuntime:        at apgo.b(:com.google.android.gms@262634035@26.26.34 (260400-945364269):3)
08-19 20:37:41.065  8242  9740 E AndroidRuntime:        at com.google.android.gms.auth.account.AuthInitIntentOperation.b(:com.google.android.gms@262634035@26.26.34 (260400-945364269):43)
08-19 20:37:41.065  8242  9740 E AndroidRuntime:        at bepf.onHandleIntent(:com.google.android.gms@262634035@26.26.34 (260400-945364269):60)
08-19 20:37:41.065  8242  9740 E AndroidRuntime:        at com.google.android.gms.auth.account.AuthInitIntentOperation.onHandleIntent(:com.google.android.gms@262634035@26.26.34 (260400-945364269):51)
08-19 20:37:41.065  8242  9740 E AndroidRuntime:        at com.google.android.gms.auth.account.Priority100AuthInitIntentOperation.onHandleIntent(:com.google.android.gms@262634035@26.26.34 (260400-945364269):7)
08-19 20:37:41.065  8242  9740 E AndroidRuntime:        at com.google.android.chimera.IntentOperation.onHandleIntent(:com.google.android.gms@262634035@26.26.34 (260400-945364269):1)
08-19 20:37:41.065  8242  9740 E AndroidRuntime:        at bevr.onHandleIntent(:com.google.android.gms@262634035@26.26.34 (260400-945364269):88)
08-19 20:37:41.065  8242  9740 E AndroidRuntime:        at abno.run(:com.google.android.gms@262634035@26.26.34 (260400-945364269):58)
08-19 20:37:41.065  8242  9740 E AndroidRuntime:        at abnn.run(:com.google.android.gms@262634035@26.26.34 (260400-945364269):132)
08-19 20:37:41.065  8242  9740 E AndroidRuntime:        at hjbx.run(:com.google.android.gms@262634035@26.26.34 (260400-945364269):23)
08-19 20:37:41.065  8242  9740 E AndroidRuntime:        at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1145)
08-19 20:37:41.065  8242  9740 E AndroidRuntime:        at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:644)
08-19 20:37:41.065  8242  9740 E AndroidRuntime:        at java.lang.Thread.run(Thread.java:1117)
08-19 20:37:44.213  9871 10073 E AndroidRuntime: FATAL EXCEPTION: [com.google.android.gms.chimera.container.intentoperation.GmsIntentOperationChimeraService-Executor] idle
08-19 20:37:44.213  9871 10073 E AndroidRuntime: Process: com.google.android.gms, PID: 9871
08-19 20:37:44.213  9871 10073 E AndroidRuntime: java.lang.SecurityException: isSafetyCenterEnabled requires any of: [android.permission.READ_SAFETY_CENTER_STATUS, android.permission.SEND_SAFETY_CENTER_UPDATE], but none were granted
08-19 20:37:44.213  9871 10073 E AndroidRuntime:        at android.os.Parcel.createExceptionOrNull(Parcel.java:3231)
08-19 20:37:44.213  9871 10073 E AndroidRuntime:        at android.os.Parcel.createException(Parcel.java:3215)
08-19 20:37:44.213  9871 10073 E AndroidRuntime:        at android.os.Parcel.readException(Parcel.java:3198)
08-19 20:37:44.213  9871 10073 E AndroidRuntime:        at android.os.Parcel.readException(Parcel.java:3140)
08-19 20:37:44.213  9871 10073 E AndroidRuntime:        at android.safetycenter.ISafetyCenterManager$Stub$Proxy.isSafetyCenterEnabled(ISafetyCenterManager.java:423)
08-19 20:37:44.213  9871 10073 E AndroidRuntime:        at android.safetycenter.SafetyCenterManager.isSafetyCenterEnabled(SafetyCenterManager.java:343)
08-19 20:37:44.213  9871 10073 E AndroidRuntime:        at com.google.android.gms.accountsettings.operations.ModuleInitializer.f(:com.google.android.gms@262634035@26.26.34 (260400-945364269):11)
08-19 20:37:44.213  9871 10073 E AndroidRuntime:        at com.google.android.gms.accountsettings.operations.ModuleInitializer.b(:com.google.android.gms@262634035@26.26.34 (260400-945364269):21)
08-19 20:37:44.213  9871 10073 E AndroidRuntime:        at bepf.onHandleIntent(:com.google.android.gms@262634035@26.26.34 (260400-945364269):60)
08-19 20:37:44.213  9871 10073 E AndroidRuntime:        at com.google.android.chimera.IntentOperation.onHandleIntent(:com.google.android.gms@262634035@26.26.34 (260400-945364269):1)
08-19 20:37:44.213  9871 10073 E AndroidRuntime:        at bevr.onHandleIntent(:com.google.android.gms@262634035@26.26.34 (260400-945364269):88)
08-19 20:37:44.213  9871 10073 E AndroidRuntime:        at abno.run(:com.google.android.gms@262634035@26.26.34 (260400-945364269):58)
08-19 20:37:44.213  9871 10073 E AndroidRuntime:        at abnn.run(:com.google.android.gms@262634035@26.26.34 (260400-945364269):132)
08-19 20:37:44.213  9871 10073 E AndroidRuntime:        at hjbx.run(:com.google.android.gms@262634035@26.26.34 (260400-945364269):23)
08-19 20:37:44.213  9871 10073 E AndroidRuntime:        at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1145)
08-19 20:37:44.213  9871 10073 E AndroidRuntime:        at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:644)
08-19 20:37:44.213  9871 10073 E AndroidRuntime:        at java.lang.Thread.run(Thread.java:1117)
08-19 20:37:44.213  9871 10073 E AndroidRuntime: Caused by: android.os.RemoteException: Remote stack trace:
08-19 20:37:44.213  9871 10073 E AndroidRuntime:        at com.android.safetycenter.SafetyCenterService$Stub.enforceAnyCallingOrSelfPermissions(SafetyCenterService.java:690)
08-19 20:37:44.213  9871 10073 E AndroidRuntime:        at com.android.safetycenter.SafetyCenterService$Stub.isSafetyCenterEnabled(SafetyCenterService.java:295)
08-19 20:37:44.213  9871 10073 E AndroidRuntime:        at android.safetycenter.ISafetyCenterManager$Stub.onTransact(ISafetyCenterManager.java:240)
08-19 20:37:44.213  9871 10073 E AndroidRuntime:        at android.os.Binder.execTransactInternal(Binder.java:1391)
08-19 20:37:44.213  9871 10073 E AndroidRuntime:        at android.os.Binder.execTransact(Binder.java:1335)
08-19 20:37:44.213  9871 10073 E AndroidRuntime:
08-19 20:37:44.963  8154  8902 E AndroidRuntime: FATAL EXCEPTION: highpool[5]
08-19 20:37:44.963  8154  8902 E AndroidRuntime: Process: com.google.android.gms.persistent, PID: 8154
08-19 20:37:44.963  8154  8902 E AndroidRuntime: java.lang.SecurityException: Permission denial, must have one of: [android.permission.WRITE_SECURE_SETTINGS]
08-19 20:37:44.963  8154  8902 E AndroidRuntime:        at android.os.Parcel.createExceptionOrNull(Parcel.java:3231)
08-19 20:37:44.963  8154  8902 E AndroidRuntime:        at android.os.Parcel.createException(Parcel.java:3215)
08-19 20:37:44.963  8154  8902 E AndroidRuntime:        at android.os.Parcel.readException(Parcel.java:3198)
08-19 20:37:44.963  8154  8902 E AndroidRuntime:        at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:203)
08-19 20:37:44.963  8154  8902 E AndroidRuntime:        at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:155)
08-19 20:37:44.963  8154  8902 E AndroidRuntime:        at android.content.ContentProviderProxy.call(ContentProviderNative.java:764)
08-19 20:37:44.963  8154  8902 E AndroidRuntime:        at android.provider.Settings$NameValueCache.putStringForUser(Settings.java:3460)
08-19 20:37:44.963  8154  8902 E AndroidRuntime:        at android.provider.Settings$Secure.putStringForUser(Settings.java:7093)
08-19 20:37:44.963  8154  8902 E AndroidRuntime:        at android.provider.Settings$Secure.putStringForUser(Settings.java:7074)
08-19 20:37:44.963  8154  8902 E AndroidRuntime:        at android.provider.Settings$Secure.putString(Settings.java:7067)
08-19 20:37:44.963  8154  8902 E AndroidRuntime:        at dvsz.b(:com.google.android.gms@262634035@26.26.34 (260400-945364269):231)
08-19 20:37:44.963  8154  8902 E AndroidRuntime:        at dvsy.a(:com.google.android.gms@262634035@26.26.34 (260400-945364269):13)
08-19 20:37:44.963  8154  8902 E AndroidRuntime:        at dvyv.run(:com.google.android.gms@262634035@26.26.34 (260400-945364269):3)
08-19 20:37:44.963  8154  8902 E AndroidRuntime:        at blvq.c(:com.google.android.gms@262634035@26.26.34 (260400-945364269):50)
08-19 20:37:44.963  8154  8902 E AndroidRuntime:        at blvq.run(:com.google.android.gms@262634035@26.26.34 (260400-945364269):90)
08-19 20:37:44.963  8154  8902 E AndroidRuntime:        at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1145)
08-19 20:37:44.963  8154  8902 E AndroidRuntime:        at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:644)
08-19 20:37:44.963  8154  8902 E AndroidRuntime:        at bmbk.run(:com.google.android.gms@262634035@26.26.34 (260400-945364269):8)
08-19 20:37:44.963  8154  8902 E AndroidRuntime:        at java.lang.Thread.run(Thread.java:1117)
08-19 20:37:44.963  8154  8902 E AndroidRuntime:        Suppressed: hjck:
08-19 20:37:44.963  8154  8902 E AndroidRuntime:                at tk_trace.nearby-NearbySharingChimeraService_onCreate(Unknown Source:0)
08-19 20:37:44.963  8154  8902 E AndroidRuntime:                at tk_trace.container-GmsApiChimeraService_onBind(Unknown Source:0)
08-19 20:37:45.151 10296 10296 E AndroidRuntime: FATAL EXCEPTION: main
08-19 20:37:45.151 10296 10296 E AndroidRuntime: PID: 10296
08-19 20:37:45.151 10296 10296 E AndroidRuntime: java.lang.SecurityException: Permission Denial: Component com.google.android.gms/.chimera.container.router.SingletonComponentRouterProvider requests FLAG_SINGLE_USER, but app does not hold android.permission.INTERACT_ACROSS_USERS
08-19 20:37:45.151 10296 10296 E AndroidRuntime:        at android.os.Parcel.createExceptionOrNull(Parcel.java:3231)
08-19 20:37:45.151 10296 10296 E AndroidRuntime:        at android.os.Parcel.createException(Parcel.java:3215)
08-19 20:37:45.151 10296 10296 E AndroidRuntime:        at android.os.Parcel.readException(Parcel.java:3198)
08-19 20:37:45.151 10296 10296 E AndroidRuntime:        at android.os.Parcel.readException(Parcel.java:3140)
08-19 20:37:45.151 10296 10296 E AndroidRuntime:        at android.app.IActivityManager$Stub$Proxy.attachApplication(IActivityManager.java:6223)
08-19 20:37:45.151 10296 10296 E AndroidRuntime:        at android.app.ActivityThread.attach(ActivityThread.java:8475)
08-19 20:37:45.151 10296 10296 E AndroidRuntime:        at android.app.ActivityThread.main(ActivityThread.java:8774)
08-19 20:37:45.151 10296 10296 E AndroidRuntime:        at java.lang.reflect.Method.invoke(Native Method)
08-19 20:37:45.151 10296 10296 E AndroidRuntime:        at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:591)
08-19 20:37:45.151 10296 10296 E AndroidRuntime:        at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:871)
08-19 20:37:45.151 10296 10296 E AndroidRuntime: Caused by: android.os.RemoteException: Remote stack trace:
08-19 20:37:45.151 10296 10296 E AndroidRuntime:        at com.android.server.am.ActivityManagerService.isSingleton(ActivityManagerService.java:13773)
08-19 20:37:45.151 10296 10296 E AndroidRuntime:        at com.android.server.am.ContentProviderHelper.generateApplicationProvidersLocked(ContentProviderHelper.java:1270)
08-19 20:37:45.151 10296 10296 E AndroidRuntime:        at com.android.server.am.ActivityManagerService.attachApplicationLocked(ActivityManagerService.java:4571)
08-19 20:37:45.151 10296 10296 E AndroidRuntime:        at com.android.server.am.ActivityManagerService.attachApplication(ActivityManagerService.java:4799)
08-19 20:37:45.151 10296 10296 E AndroidRuntime:        at android.app.IActivityManager$Stub.onTransact(IActivityManager.java:2883)
08-19 20:37:45.151 10296 10296 E AndroidRuntime:
08-19 20:37:45.871 10235 10358 E AndroidRuntime: FATAL EXCEPTION: [com.google.android.gms.chimera.container.intentoperation.GmsIntentOperationChimeraService-Executor] idle
08-19 20:37:45.871 10235 10358 E AndroidRuntime: Process: com.google.android.gms, PID: 10235
08-19 20:37:45.871 10235 10358 E AndroidRuntime: java.lang.SecurityException: You either need MANAGE_USERS, CREATE_USERS, or QUERY_USERS permission to: query user
08-19 20:37:45.871 10235 10358 E AndroidRuntime:        at android.os.Parcel.createExceptionOrNull(Parcel.java:3231)
08-19 20:37:45.871 10235 10358 E AndroidRuntime:        at android.os.Parcel.createException(Parcel.java:3215)
08-19 20:37:45.871 10235 10358 E AndroidRuntime:        at android.os.Parcel.readException(Parcel.java:3198)
08-19 20:37:45.871 10235 10358 E AndroidRuntime:        at android.os.Parcel.readException(Parcel.java:3140)
08-19 20:37:45.871 10235 10358 E AndroidRuntime:        at android.os.IUserManager$Stub$Proxy.getUserInfo(IUserManager.java:2615)
08-19 20:37:45.871 10235 10358 E AndroidRuntime:        at android.os.UserManager.getUserInfo(UserManager.java:3916)
08-19 20:37:45.871 10235 10358 E AndroidRuntime:        at android.os.UserManager.isMainUser(UserManager.java:2914)
08-19 20:37:45.871 10235 10358 E AndroidRuntime:        at blwo.t(:com.google.android.gms@262634035@26.26.34 (260400-945364269):12)
08-19 20:37:45.871 10235 10358 E AndroidRuntime:        at ahyk.<init>(:com.google.android.gms@262634035@26.26.34 (260400-945364269):1)
08-19 20:37:45.871 10235 10358 E AndroidRuntime:        at ahyk.a(:com.google.android.gms@262634035@26.26.34 (260400-945364269):33)
08-19 20:37:45.871 10235 10358 E AndroidRuntime:        at com.google.android.gms.auth.frp.FrpUpdateIntentOperation.onCreate(:com.google.android.gms@262634035@26.26.34 (260400-945364269):1)
08-19 20:37:45.871 10235 10358 E AndroidRuntime:        at com.google.android.chimera.IntentOperation.init(:com.google.android.gms@262634035@26.26.34 (260400-945364269):4)
08-19 20:37:45.871 10235 10358 E AndroidRuntime:        at bevr.init(:com.google.android.gms@262634035@26.26.34 (260400-945364269):17)
08-19 20:37:45.871 10235 10358 E AndroidRuntime:        at bevo.c(:com.google.android.gms@262634035@26.26.34 (260400-945364269):25)
08-19 20:37:45.871 10235 10358 E AndroidRuntime:        at abnm.b(:com.google.android.gms@262634035@26.26.34 (260400-945364269):66)
08-19 20:37:45.871 10235 10358 E AndroidRuntime:        at abnt.run(:com.google.android.gms@262634035@26.26.34 (260400-945364269):542)
08-19 20:37:45.871 10235 10358 E AndroidRuntime:        at abnn.run(:com.google.android.gms@262634035@26.26.34 (260400-945364269):44)
08-19 20:37:45.871 10235 10358 E AndroidRuntime:        at hjbx.run(:com.google.android.gms@262634035@26.26.34 (260400-945364269):23)
08-19 20:37:45.871 10235 10358 E AndroidRuntime:        at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1145)
08-19 20:37:45.871 10235 10358 E AndroidRuntime:        at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:644)
08-19 20:37:45.871 10235 10358 E AndroidRuntime:        at java.lang.Thread.run(Thread.java:1117)
08-19 20:37:47.503 10405 10480 E AndroidRuntime: FATAL EXCEPTION: [com.google.android.gms.chimera.container.intentoperation.GmsIntentOperationChimeraService-Executor] idle
08-19 20:37:47.503 10405 10480 E AndroidRuntime: Process: com.google.android.gms, PID: 10405
08-19 20:37:47.503 10405 10480 E AndroidRuntime: java.lang.SecurityException: You either need MANAGE_USERS, CREATE_USERS, or QUERY_USERS permission to: query user
08-19 20:37:47.503 10405 10480 E AndroidRuntime:        at android.os.Parcel.createExceptionOrNull(Parcel.java:3231)
08-19 20:37:47.503 10405 10480 E AndroidRuntime:        at android.os.Parcel.createException(Parcel.java:3215)
08-19 20:37:47.503 10405 10480 E AndroidRuntime:        at android.os.Parcel.readException(Parcel.java:3198)
08-19 20:37:47.503 10405 10480 E AndroidRuntime:        at android.os.Parcel.readException(Parcel.java:3140)
08-19 20:37:47.503 10405 10480 E AndroidRuntime:        at android.os.IUserManager$Stub$Proxy.getUserInfo(IUserManager.java:2615)
08-19 20:37:47.503 10405 10480 E AndroidRuntime:        at android.os.UserManager.getUserInfo(UserManager.java:3916)
08-19 20:37:47.503 10405 10480 E AndroidRuntime:        at android.os.UserManager.isMainUser(UserManager.java:2914)
08-19 20:37:47.503 10405 10480 E AndroidRuntime:        at blwo.t(:com.google.android.gms@262634035@26.26.34 (260400-945364269):12)
08-19 20:37:47.503 10405 10480 E AndroidRuntime:        at ahyk.<init>(:com.google.android.gms@262634035@26.26.34 (260400-945364269):1)
08-19 20:37:47.503 10405 10480 E AndroidRuntime:        at ahyk.a(:com.google.android.gms@262634035@26.26.34 (260400-945364269):33)
08-19 20:37:47.503 10405 10480 E AndroidRuntime:        at com.google.android.gms.auth.frp.FrpUpdateIntentOperation.onCreate(:com.google.android.gms@262634035@26.26.34 (260400-945364269):1)
08-19 20:37:47.503 10405 10480 E AndroidRuntime:        at com.google.android.chimera.IntentOperation.init(:com.google.android.gms@262634035@26.26.34 (260400-945364269):4)
08-19 20:37:47.503 10405 10480 E AndroidRuntime:        at bevr.init(:com.google.android.gms@262634035@26.26.34 (260400-945364269):17)
08-19 20:37:47.503 10405 10480 E AndroidRuntime:        at bevo.c(:com.google.android.gms@262634035@26.26.34 (260400-945364269):25)
08-19 20:37:47.503 10405 10480 E AndroidRuntime:        at abnm.b(:com.google.android.gms@262634035@26.26.34 (260400-945364269):66)
08-19 20:37:47.503 10405 10480 E AndroidRuntime:        at abnt.run(:com.google.android.gms@262634035@26.26.34 (260400-945364269):542)
08-19 20:37:47.503 10405 10480 E AndroidRuntime:        at abnn.run(:com.google.android.gms@262634035@26.26.34 (260400-945364269):44)
08-19 20:37:47.503 10405 10480 E AndroidRuntime:        at hjbx.run(:com.google.android.gms@262634035@26.26.34 (260400-945364269):23)
08-19 20:37:47.503 10405 10480 E AndroidRuntime:        at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1145)
08-19 20:37:47.503 10405 10480 E AndroidRuntime:        at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:644)
08-19 20:37:47.503 10405 10480 E AndroidRuntime:        at java.lang.Thread.run(Thread.java:1117)
08-19 20:38:35.441 12491 12664 E AndroidRuntime: FATAL EXCEPTION: LightweightExecutor #2
08-19 20:38:35.441 12491 12664 E AndroidRuntime: Process: com.android.vending, PID: 12491
08-19 20:38:35.441 12491 12664 E AndroidRuntime: java.lang.RuntimeException: Exception in LightweightExecutor Runnable: java.util.concurrent.ThreadPoolExecutor$Worker
08-19 20:38:35.441 12491 12664 E AndroidRuntime:        at wkg.run(PG:570)
08-19 20:38:35.441 12491 12664 E AndroidRuntime:        at java.lang.Thread.run(Thread.java:1117)
08-19 20:38:35.441 12491 12664 E AndroidRuntime: Caused by: java.lang.SecurityException: You either need MANAGE_USERS or CREATE_USERS permission to: query users
08-19 20:38:35.441 12491 12664 E AndroidRuntime:        at android.os.Parcel.createExceptionOrNull(Parcel.java:3231)
08-19 20:38:35.441 12491 12664 E AndroidRuntime:        at android.os.Parcel.createException(Parcel.java:3215)
08-19 20:38:35.441 12491 12664 E AndroidRuntime:        at android.os.Parcel.readException(Parcel.java:3198)
08-19 20:38:35.441 12491 12664 E AndroidRuntime:        at android.os.Parcel.readException(Parcel.java:3140)
08-19 20:38:35.441 12491 12664 E AndroidRuntime:        at android.os.IUserManager$Stub$Proxy.getUsers(IUserManager.java:2374)
08-19 20:38:35.441 12491 12664 E AndroidRuntime:        at android.os.UserManager.getUsers(UserManager.java:4981)
08-19 20:38:35.441 12491 12664 E AndroidRuntime:        at android.os.UserManager.getUsers(UserManager.java:4922)
08-19 20:38:35.441 12491 12664 E AndroidRuntime:        at android.os.UserManager.getUserCount(UserManager.java:4895)
08-19 20:38:35.441 12491 12664 E AndroidRuntime:        at aosg.ay(PG:13)
08-19 20:38:35.441 12491 12664 E AndroidRuntime:        at tvp.a(PG:104)
08-19 20:38:35.441 12491 12664 E AndroidRuntime:        at qav.<init>(PG:9)
08-19 20:38:35.441 12491 12664 E AndroidRuntime:        at qbk.apply(PG:235)
08-19 20:38:35.441 12491 12664 E AndroidRuntime:        at j$.util.Map$-CC.$default$computeIfAbsent(r8-map-id-a2d9e3422447ac3db16d65a558da8ff6b2f60c40439835e6e36c7e4d74018829:10)
08-19 20:38:35.441 12491 12664 E AndroidRuntime:        at j$.util.Map$-EL.computeIfAbsent(r8-map-id-a2d9e3422447ac3db16d65a558da8ff6b2f60c40439835e6e36c7e4d74018829:23)
08-19 20:38:35.441 12491 12664 E AndroidRuntime:        at atpt.k(PG:15)
08-19 20:38:35.441 12491 12664 E AndroidRuntime:        at atpt.j(PG:13)
08-19 20:38:35.441 12491 12664 E AndroidRuntime:        at ppm.run(PG:541)
08-19 20:38:35.441 12491 12664 E AndroidRuntime:        at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1145)
08-19 20:38:35.441 12491 12664 E AndroidRuntime:        at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:644)
08-19 20:38:35.441 12491 12664 E AndroidRuntime:        at wkg.run(PG:543)
08-19 20:38:35.441 12491 12664 E AndroidRuntime:        ... 1 more
08-19 20:38:35.447 12491 12663 E AndroidRuntime: FATAL EXCEPTION: LightweightExecutor #1
08-19 20:38:35.447 12491 12663 E AndroidRuntime: Process: com.android.vending, PID: 12491
08-19 20:38:35.447 12491 12663 E AndroidRuntime: java.lang.SecurityException: You either need MANAGE_USERS or CREATE_USERS permission to: query users
08-19 20:38:35.447 12491 12663 E AndroidRuntime:        at android.os.Parcel.createExceptionOrNull(Parcel.java:3231)
08-19 20:38:35.447 12491 12663 E AndroidRuntime:        at android.os.Parcel.createException(Parcel.java:3215)
08-19 20:38:35.447 12491 12663 E AndroidRuntime:        at android.os.Parcel.readException(Parcel.java:3198)
08-19 20:38:35.447 12491 12663 E AndroidRuntime:        at android.os.Parcel.readException(Parcel.java:3140)
08-19 20:38:35.447 12491 12663 E AndroidRuntime:        at android.os.IUserManager$Stub$Proxy.getUsers(IUserManager.java:2374)
08-19 20:38:35.447 12491 12663 E AndroidRuntime:        at android.os.UserManager.getUsers(UserManager.java:4981)
08-19 20:38:35.447 12491 12663 E AndroidRuntime:        at android.os.UserManager.getUsers(UserManager.java:4922)
08-19 20:38:35.447 12491 12663 E AndroidRuntime:        at android.os.UserManager.getUserCount(UserManager.java:4895)
08-19 20:38:35.447 12491 12663 E AndroidRuntime:        at aosg.ay(PG:13)
08-19 20:38:35.447 12491 12663 E AndroidRuntime:        at tvp.a(PG:104)
08-19 20:38:35.447 12491 12663 E AndroidRuntime:        at qav.<init>(PG:9)
08-19 20:38:35.447 12491 12663 E AndroidRuntime:        at qbk.apply(PG:235)
08-19 20:38:35.447 12491 12663 E AndroidRuntime:        at j$.util.Map$-CC.$default$computeIfAbsent(r8-map-id-a2d9e3422447ac3db16d65a558da8ff6b2f60c40439835e6e36c7e4d74018829:10)
08-19 20:38:35.447 12491 12663 E AndroidRuntime:        at j$.util.Map$-EL.computeIfAbsent(r8-map-id-a2d9e3422447ac3db16d65a558da8ff6b2f60c40439835e6e36c7e4d74018829:23)
08-19 20:38:35.447 12491 12663 E AndroidRuntime:        at atpt.k(PG:15)
08-19 20:38:35.447 12491 12663 E AndroidRuntime:        at atpt.j(PG:13)
08-19 20:38:35.447 12491 12663 E AndroidRuntime:        at qar.a(PG:3)
08-19 20:38:35.447 12491 12663 E AndroidRuntime:        at aoux.b(PG:241)
08-19 20:38:35.447 12491 12663 E AndroidRuntime:        at rgc.M(PG:118)
08-19 20:38:35.447 12491 12663 E AndroidRuntime:        at ppm.run(PG:660)
08-19 20:38:35.447 12491 12663 E AndroidRuntime:        at tlp.b(PG:181)
08-19 20:38:35.447 12491 12663 E AndroidRuntime:        at tlp.kC(PG:93)
08-19 20:38:35.447 12491 12663 E AndroidRuntime:        at axsn.b(PG:256)
08-19 20:38:35.447 12491 12663 E AndroidRuntime:        at ceyt.x(PG:5)
08-19 20:38:35.447 12491 12663 E AndroidRuntime:        at cfgb.run(PG:109)
08-19 20:38:35.447 12491 12663 E AndroidRuntime:        at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1145)
08-19 20:38:35.447 12491 12663 E AndroidRuntime:        at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:644)
08-19 20:38:35.447 12491 12663 E AndroidRuntime:        at wkg.run(PG:543)
08-19 20:38:35.447 12491 12663 E AndroidRuntime:        at java.lang.Thread.run(Thread.java:1117)
08-19 20:38:35.447 12491 12663 E AndroidRuntime:        Suppressed: kotlinx.coroutines.internal.DiagnosticCoroutineContextException: [cfig{Cancelling}@8782342, Executor: LightweightExecutor xnk@cf14f53[Running, pool size = 4, active threads = 3, queued tasks = 0, completed tasks = 109]]
08-19 20:38:58.546  8335  8444 F libc    : Fatal signal 6 (SIGABRT), code -1 (SI_QUEUE) in tid 8444 (enableInternal), pid 8335 (com.android.nfc)
08-19 20:38:59.911 14245 14245 F DEBUG   : *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
08-19 20:38:59.911 14245 14245 F DEBUG   : LineageOS Version: 'unknown'
08-19 20:38:59.911 14245 14245 F DEBUG   : Build fingerprint: 'samsung/lineage_a21s/a21s:15/AP4A.250205.002/61e53241d0:userdebug/release-keys'
08-19 20:38:59.911 14245 14245 F DEBUG   : Revision: '6'
08-19 20:38:59.911 14245 14245 F DEBUG   : ABI: 'arm64'
08-19 20:38:59.911 14245 14245 F DEBUG   : Timestamp: 2026-08-19 20:38:58.698265673+0330
08-19 20:38:59.911 14245 14245 F DEBUG   : Process uptime: 92s
08-19 20:38:59.911 14245 14245 F DEBUG   : Cmdline: com.android.nfc
08-19 20:38:59.911 14245 14245 F DEBUG   : pid: 8335, tid: 8444, name: enableInternal  >>> com.android.nfc <<<
08-19 20:38:59.911 14245 14245 F DEBUG   : uid: 1027
08-19 20:38:59.911 14245 14245 F DEBUG   : signal 6 (SIGABRT), code -1 (SI_QUEUE), fault addr --------
08-19 20:38:59.911 14245 14245 F DEBUG   : Abort message: 'JNI FatalError called: enableInternal'
08-19 20:38:59.911 14245 14245 F DEBUG   :     x0  0000000000000000  x1  00000000000020fc  x2  0000000000000006  x3  00000079bb7511b0
08-19 20:38:59.911 14245 14245 F DEBUG   :     x4  0000007c8fe7d000  x5  0000007c8fe7d000  x6  0000007c8fe7d000  x7  000000000001594c
08-19 20:38:59.911 14245 14245 F DEBUG   :     x8  00000000000000f0  x9  49e373340cb068cc  x10 000000ff00000020  x11 fffffffffffffffd
08-19 20:38:59.911 14245 14245 F DEBUG   :     x12 00000079bb74fff0  x13 000000000000003b  x14 00000079bb7500a0  x15 0000426c0e755b56
08-19 20:38:59.911 14245 14245 F DEBUG   :     x16 0000007c81f91048  x17 0000007c81f7d240  x18 000000795e3b0008  x19 000000000000208f
08-19 20:38:59.911 14245 14245 F DEBUG   :     x20 00000000000020fc  x21 00000000ffffffff  x22 0000007b17e46a90  x23 0000000000000028
08-19 20:38:59.911 14245 14245 F DEBUG   :     x24 00000079bb751a80  x25 0000007c84e0a878  x26 0000007c84e0af80  x27 000000000000000e
08-19 20:38:59.911 14245 14245 F DEBUG   :     x28 00000079bb751490  x29 00000079bb751230
08-19 20:38:59.911 14245 14245 F DEBUG   :     lr  0000007c81f1c230  sp  00000079bb7511b0  pc  0000007c81f1c254  pst 0000000000000000
08-19 20:38:59.911 14245 14245 F DEBUG   : 14 total frames
08-19 20:38:59.911 14245 14245 F DEBUG   : backtrace:
08-19 20:38:59.911 14245 14245 F DEBUG   :       #00 pc 000000000005b254  /apex/com.android.runtime/lib64/bionic/libc.so (abort+156) (BuildId: d2b63e277d4fb6976635d39171f71be5)
08-19 20:38:59.912 14245 14245 F DEBUG   :       #01 pc 0000000000011f24  /system/lib64/libbase.so (android::base::DefaultAborter(char const*)+12) (BuildId: 1e3272de22c80b5f47243af802f93e73)
08-19 20:38:59.912 14245 14245 F DEBUG   :       #02 pc 000000000009cbf0  /system/lib64/libbinder.so (android::base::SetAborter(std::__1::function<void (char const*)>&&)::$_0::__invoke(char const*) (.__uniq.304115623023563947864004479300660821567)+60) (BuildId: fa9b0b5331021c64e2dc28feac02b067)
08-19 20:38:59.912 14245 14245 F DEBUG   :       #03 pc 0000000000013304  /apex/com.android.art/lib64/libbase.so (android::base::LogMessage::~LogMessage()+524) (BuildId: 1e3272de22c80b5f47243af802f93e73)
08-19 20:38:59.912 14245 14245 F DEBUG   :       #04 pc 00000000008377c8  /apex/com.android.art/lib64/libart.so (art::JNI<false>::FatalError(_JNIEnv*, char const*)+164) (BuildId: 834808097feb70e98ed7d66cc1b1be8a)
08-19 20:38:59.912 14245 14245 F DEBUG   :       #05 pc 000000000011d9c4  /system/lib64/libnfc_nci_jni.so (android::nfcManager_doAbort(_JNIEnv*, _jobject*, _jstring*)+60) (BuildId: 406ede6d9fec3afbdc1e625a4e0d1dc7)
08-19 20:38:59.912 14245 14245 F DEBUG   :       #06 pc 000000000009ccbc  /system/framework/arm64/boot.oat (art_jni_trampoline+124) (BuildId: 6f605e05aaae0b7162b8a553e2cc2db21c0ed399)
08-19 20:38:59.912 14245 14245 F DEBUG   :       #07 pc 000000000071ec90  /apex/com.android.art/lib64/libart.so (nterp_helper+7712) (BuildId: 834808097feb70e98ed7d66cc1b1be8a)
08-19 20:38:59.912 14245 14245 F DEBUG   :       #08 pc 000000000010788e  /system/priv-app/NfcNci/NfcNci.apk (com.android.nfc.NfcService$WatchDogThread.run+178)
08-19 20:38:59.912 14245 14245 F DEBUG   :       #09 pc 00000000003f5594  /apex/com.android.art/lib64/libart.so (art_quick_invoke_stub+612) (BuildId: 834808097feb70e98ed7d66cc1b1be8a)
08-19 20:38:59.912 14245 14245 F DEBUG   :       #10 pc 0000000000242a34  /apex/com.android.art/lib64/libart.so (art::ArtMethod::Invoke(art::Thread*, unsigned int*, unsigned int, art::JValue*, char const*)+132) (BuildId: 834808097feb70e98ed7d66cc1b1be8a)
08-19 20:38:59.912 14245 14245 F DEBUG   :       #11 pc 00000000004725e4  /apex/com.android.art/lib64/libart.so (art::Thread::CreateCallback(void*)+1100) (BuildId: 834808097feb70e98ed7d66cc1b1be8a)
08-19 20:38:59.912 14245 14245 F DEBUG   :       #12 pc 000000000006af80  /apex/com.android.runtime/lib64/bionic/libc.so (__pthread_start(void*)+132) (BuildId: d2b63e277d4fb6976635d39171f71be5)
08-19 20:38:59.912 14245 14245 F DEBUG   :       #13 pc 000000000005e1e0  /apex/com.android.runtime/lib64/bionic/libc.so (__start_thread+64) (BuildId: d2b63e277d4fb6976635d39171f71be5)
08-19 20:39:05.515 13676 13713 E AndroidRuntime: FATAL EXCEPTION: LightweightExecutor #3
08-19 20:39:05.515 13676 13713 E AndroidRuntime: Process: com.android.vending, PID: 13676
08-19 20:39:05.515 13676 13713 E AndroidRuntime: java.lang.RuntimeException: Exception in LightweightExecutor Runnable: java.util.concurrent.ThreadPoolExecutor$Worker
08-19 20:39:05.515 13676 13713 E AndroidRuntime:        at wkg.run(PG:570)
08-19 20:39:05.515 13676 13713 E AndroidRuntime:        at java.lang.Thread.run(Thread.java:1117)
08-19 20:39:05.515 13676 13713 E AndroidRuntime: Caused by: java.lang.SecurityException: You either need MANAGE_USERS or CREATE_USERS permission to: query users
08-19 20:39:05.515 13676 13713 E AndroidRuntime:        at android.os.Parcel.createExceptionOrNull(Parcel.java:3231)
08-19 20:39:05.515 13676 13713 E AndroidRuntime:        at android.os.Parcel.createException(Parcel.java:3215)
08-19 20:39:05.515 13676 13713 E AndroidRuntime:        at android.os.Parcel.readException(Parcel.java:3198)
08-19 20:39:05.515 13676 13713 E AndroidRuntime:        at android.os.Parcel.readException(Parcel.java:3140)
08-19 20:39:05.515 13676 13713 E AndroidRuntime:        at android.os.IUserManager$Stub$Proxy.getUsers(IUserManager.java:2374)
08-19 20:39:05.515 13676 13713 E AndroidRuntime:        at android.os.UserManager.getUsers(UserManager.java:4981)
08-19 20:39:05.515 13676 13713 E AndroidRuntime:        at android.os.UserManager.getUsers(UserManager.java:4922)
08-19 20:39:05.515 13676 13713 E AndroidRuntime:        at android.os.UserManager.getUserCount(UserManager.java:4895)
08-19 20:39:05.515 13676 13713 E AndroidRuntime:        at aosg.ay(PG:13)
08-19 20:39:05.515 13676 13713 E AndroidRuntime:        at tvp.a(PG:104)
08-19 20:39:05.515 13676 13713 E AndroidRuntime:        at qav.<init>(PG:9)
08-19 20:39:05.515 13676 13713 E AndroidRuntime:        at qbk.apply(PG:235)
08-19 20:39:05.515 13676 13713 E AndroidRuntime:        at j$.util.Map$-CC.$default$computeIfAbsent(r8-map-id-a2d9e3422447ac3db16d65a558da8ff6b2f60c40439835e6e36c7e4d74018829:10)
08-19 20:39:05.515 13676 13713 E AndroidRuntime:        at j$.util.Map$-EL.computeIfAbsent(r8-map-id-a2d9e3422447ac3db16d65a558da8ff6b2f60c40439835e6e36c7e4d74018829:23)
08-19 20:39:05.515 13676 13713 E AndroidRuntime:        at atpt.k(PG:15)
08-19 20:39:05.515 13676 13713 E AndroidRuntime:        at atpt.j(PG:13)
08-19 20:39:05.515 13676 13713 E AndroidRuntime:        at ppm.run(PG:541)
08-19 20:39:05.515 13676 13713 E AndroidRuntime:        at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1145)
08-19 20:39:05.515 13676 13713 E AndroidRuntime:        at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:644)
08-19 20:39:05.515 13676 13713 E AndroidRuntime:        at wkg.run(PG:543)
08-19 20:39:05.515 13676 13713 E AndroidRuntime:        ... 1 more

C:\Program Files (x86)\ADB and Fastboot++>











































































