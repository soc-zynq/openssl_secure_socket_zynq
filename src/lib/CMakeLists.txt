# Create a library called "openssl_secure_socket_zynq"
add_library(openssl_secure_socket_zynq_lib openssl_secure_socket_zynq.cpp)

# Specify include directories for the library
target_include_directories(openssl_secure_socket_zynq_lib PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/../../include)
