cmake_minimum_required (VERSION 2.8)

project (cpp-exp)

add_subdirectory(sse_bubble_sort)

add_executable(cpp-exp
	main.cpp
)

target_link_libraries (cpp-exp sse_bubble_sort)