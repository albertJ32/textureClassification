cmake_minimum_required(VERSION 2.8)
project(gaussian_log_gabor)
find_package(OpenCV REQUIRED)
add_executable(gaussian_log_gabor gaussian_log_gabor.cpp)
target_link_libraries(gaussian_log_gabor ${OpenCV_LIBS})
