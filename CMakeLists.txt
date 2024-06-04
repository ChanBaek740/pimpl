cmake_minimum_required(VERSION 3.2)

enable_language(CXX)

project(impl CXX) #指定工程名称
 

add_executable(test_impl
    book.cpp
    main.cpp
)