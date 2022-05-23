cmake_minimum_required(VERSION 3.22)
project(card_number)
add_executable(card_number main.cpp)
find_package( OpenCV REQUIRED )
target_link_libraries( card_number ${OpenCV_LIBS} )

