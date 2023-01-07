#生成一个静态库
add_library(hiredis STATIC
        hiredis.c
        net.c
        dict.c
        net.c
        sds.c
        async.c
        )