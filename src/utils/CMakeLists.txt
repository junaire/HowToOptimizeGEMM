set(
    SOURCES
    copy_matrix.c
    print_matrix.c
    REF_MMult.c
    compare_matrices.c
    dclock.c
    random_matrix.c
)

add_library(utils ${SOURCES})

target_include_directories(utils PUBLIC ${PROJECT_SOURCE_DIR}/include)