cmake_minimum_required(VERSION 3.14)
project(YelowBeltFinal)

set(CMAKE_CXX_STANDARD 17)

add_executable(YelowBeltFinal main.cpp token.cpp token.h condition_parser.cpp condition_parser.h date.cpp date.h database.cpp database.h node.cpp node.h test_runner.cpp test_runner.h)