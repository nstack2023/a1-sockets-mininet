project(iPerfer)
SET(CMAKE_CXX_STANDARD 23)
add_executable(iPerfer)
target_link_libraries(iPerfer spdlog::spdlog cxxopts::cxxopts)