project(iPerfer)
target_compile_features(iPerfer PUBLIC cxx_std_23)
add_executable(iPerfer apps/iPerfer.cpp)
target_link_libraries(iPerfer spdlog::spdlog cxxopts::cxxopts)