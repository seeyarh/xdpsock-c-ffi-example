set(CMAKE_INCLUDE_CURRENT_DIR ON)

set(SOURCE main.c)
set(XSK_SO "libxsk_rs_ffi.so")
add_executable(ffi ${SOURCE})
target_link_libraries(ffi ${XSK_SO})

