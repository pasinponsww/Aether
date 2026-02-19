add_library(hal INTERFACE)

target_include_directories(hal INTERFACE
    .
    ${CMAKE_SOURCE_DIR}/common/core/utils
)

target_link_libraries(hal INTERFACE
    st_h7_support
    #core
)