add_subdirectory(utils)

add_executable(
  0_naive_matmul
  test_MMult.c
  0_naive_matmul.c)

target_include_directories(
  0_naive_matmul
  PUBLIC
  ${PROJECT_SOURCE_DIR}/include
)

target_link_libraries(
  0_naive_matmul
  utils
)

add_executable(
  1_cal_element_per_loop
  test_MMult.c
  1_cal_element_per_loop.c)

target_include_directories(
  1_cal_element_per_loop
  PUBLIC
  ${PROJECT_SOURCE_DIR}/include
)

target_link_libraries(
  1_cal_element_per_loop
  utils
)

add_executable(
  2_combine_k_elements_per_loop
  test_MMult.c
  2_combine_k_elements_per_loop.c)

target_include_directories(
  2_combine_k_elements_per_loop
  PUBLIC
  ${PROJECT_SOURCE_DIR}/include
)

target_link_libraries(
  2_combine_k_elements_per_loop
  utils
)

add_executable(
  3_reduce_memory_load
  test_MMult.c
  3_reduce_memory_load.c)

target_include_directories(
  3_reduce_memory_load
  PUBLIC
  ${PROJECT_SOURCE_DIR}/include
)

target_link_libraries(
  3_reduce_memory_load
  utils
)

add_executable(
  4_use_pointer
  test_MMult.c
  4_use_pointer.c)

target_include_directories(
  4_use_pointer
  PUBLIC
  ${PROJECT_SOURCE_DIR}/include
)

target_link_libraries(
  4_use_pointer
  utils
)

add_executable(
  5_subblock_cal_element_per_loop
  test_MMult.c
  5_subblock_cal_element_per_loop.c)

target_include_directories(
  5_subblock_cal_element_per_loop
  PUBLIC
  ${PROJECT_SOURCE_DIR}/include
)

target_link_libraries(
  5_subblock_cal_element_per_loop
  utils
)

add_executable(
  6_subblock_combine_k_elements_per_loop
  test_MMult.c
  6_subblock_combine_k_elements_per_loop.c)

target_include_directories(
  6_subblock_combine_k_elements_per_loop
  PUBLIC
  ${PROJECT_SOURCE_DIR}/include
)

target_link_libraries(
  6_subblock_combine_k_elements_per_loop
  utils
)

add_executable(
  7_subblock_reduce_memory_load
  test_MMult.c
  7_subblock_reduce_memory_load.c)

target_include_directories(
  7_subblock_reduce_memory_load
  PUBLIC
  ${PROJECT_SOURCE_DIR}/include
)

target_link_libraries(
  7_subblock_reduce_memory_load
  utils
)

add_executable(
  8_subblock_use_pointer
  test_MMult.c
  8_subblock_use_pointer.c)

target_include_directories(
  8_subblock_use_pointer
  PUBLIC
  ${PROJECT_SOURCE_DIR}/include
)

target_link_libraries(
  8_subblock_use_pointer
  utils
)

add_executable(
  9_subblock_rerange
  test_MMult.c
  9_subblock_rerange.c)

target_include_directories(
  9_subblock_rerange
  PUBLIC
  ${PROJECT_SOURCE_DIR}/include
)

target_link_libraries(
  9_subblock_rerange
  utils
)

add_executable(
  10_subblock_simd
  test_MMult.c
  10_subblock_simd.c)

target_include_directories(
  10_subblock_simd
  PUBLIC
  ${PROJECT_SOURCE_DIR}/include
)

target_link_libraries(
  10_subblock_simd
  utils
)

add_executable(
  11_super_fast_matmul_idk
  test_MMult.c
  11_super_fast_matmul_idk.c)

target_include_directories(
  11_super_fast_matmul_idk
  PUBLIC
  ${PROJECT_SOURCE_DIR}/include
)

target_link_libraries(
  11_super_fast_matmul_idk
  utils
)