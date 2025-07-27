add_library(connection-pool INTERFACE)
target_include_directories(connection-pool INTERFACE ${CMAKE_CURRENT_SOURCE_DIR})

add_library(active911::connection-pool ALIAS connection-pool)
