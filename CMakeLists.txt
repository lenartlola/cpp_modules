cmake_minimum_required(VERSION 3.20.2)
project(cpp_module)

set(CMAKE_CXX_STANDARD 14)

include_directories(module00/ex01)

add_executable(cpp_module
#        module00/ex00/megaphone.cpp
        module00/ex01/Contact.cpp
        module00/ex01/Contact.h
        module00/ex01/main.cpp
        module00/ex01/PhoneBook.cpp
        module00/ex01/PhoneBook.h
#        module00/ex02/Account.cpp
#        module00/ex02/Account.h
        #module00/ex02/tests.cpp
        )
