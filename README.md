#任务队列
>

说明
    
    基于PHP+Redis开发的单线程任务队列.
    
    本程序为测试项目,适合小型任务队列.并且因过于简陋,所以请确保你扩展的服务可以正常运行,否则致命错误将可能导致程序终止运行.
    若需要配合Mysql等数据库或其他扩展请自行在服务中处理.不推荐写在主文件中.
    
    本程序没有处理redis关闭问题,请确保启动redis后运行本程序并且保持redis运行,否则将出错.
