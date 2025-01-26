cmake_minimum_required(VERSION 3.10)
target_compile_features(iPerfer PUBLIC cxx_std_23)
add_executable(iPerfer iPerfer.cpp)
target_link_libraries(iPerfer spdlog::spdlog cxxopts::cxxopts)