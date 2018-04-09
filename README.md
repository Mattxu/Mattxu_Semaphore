Mattxu_Semaphore
==============================================
#概念准备
>临界资源：一次只允许一个进程使用的资源
>
>临界区：访问临界资源的程序代码片段
>
#信号量
>信号量可以理解为一个计数器，可用来处理进程的同步或者资源共享问题，比如临界资源的同步访问
>
>简单理解：进程A和进程B都需要使用串口，当进程A通过调用函数获取串口资源时，如果资源没有被B
>
>占用，则进程A直接使用；如果资源已经被进程B占用，则进程A由运行态进入阻塞态，等待资源可用，
>
>一但获取了资源并使用完毕，需要通过调用函数释放掉资源。
