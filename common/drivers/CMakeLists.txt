if (TARGET_DEVICE MATCHES "^(STM32F7)[0-9]+")
    add_subdirectory(platform/stm32F7)
endif()

# add_subdirectory(utils)

# add_library(driver INTERFACE)

# target_include_directories(driver INTERFACE
#     ${CMAKE_CURRENT_SOURCE_DIR}/bus
#     ${CMAKE_CURRENT_SOURCE_DIR}/io 
# )

# target_link_libraries(driver INTERFACE
#     hal
#     utils
# )