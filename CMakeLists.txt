cmake_minimum_required(VERSION 3.16)
project(linux-simple-port)






if(NOT ${HAS_SYSTEM_UNAC})

    add_subdirectory(base/unac)

endif()
