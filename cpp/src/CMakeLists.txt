project(iPerfer)
SET(CMAKE_CXX_STANDARD 23)
add_executable(iPerfer apps/iPerfer.cpp)
target_link_libraries(iPerfer spdlog::spdlog cxxopts::cxxopts)