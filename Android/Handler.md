## Looper

系统会自动为主线程开启消息循环，同时创建looper对象

子线程中需要在handler前调用Looper.prepare();

handler后调用Looper.loop();

