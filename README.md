# Kernal-Threads-xv6
Implemented a new system call to create a kernel thread, called clone() , 
as well as one to wait for a thread called join() . 
Then, using clone() to build a little thread library, with a thread_create() , thread_exit(), thread_join()
implmeneted locks -lock_acquire() , and lock_release()
locks are implemented using x86 atomic xchg(exchange) instruction