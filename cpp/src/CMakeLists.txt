project(iPerfer)
add_executable(iPerfer iPerfer.cpp)
target_compile_features(iPerfer PUBLIC cxx_std_23)
target_link_libraries(iPerfer spdlog::spdlog cxxopts::cxxopts)