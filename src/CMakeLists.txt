add_executable(fastd fastd.c handshake.c method_null.c queue.c task.c)
target_link_libraries(fastd rt)