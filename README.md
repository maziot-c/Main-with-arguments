### 程序说明

解析带有参数的 main 函数。

### 编译执行

    user@ubuntu:~/work/c-study/Main-with-arguments$ ./app 
    argc = 1
    argv[0] = ./app
    user@ubuntu:~/work/c-study/Main-with-arguments$ ./app a b c d e f g
    argc = 8
    argv[0] = ./app
    argv[1] = a
    argv[2] = b
    argv[3] = c
    argv[4] = d
    argv[5] = e
    argv[6] = f
    argv[7] = g

    user@ubuntu:~/work/c-study/Main-with-arguments$ ./app "this is the string"
    argc = 2
    argv[0] = ./app
    argv[1] = this is the string
