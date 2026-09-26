add_library(mage main.cpp)

target_include_directories(mage PUBLIC ../include)

# Link external libraries.
target_link_libraries(mage PRIVATE glfw)

target_link_libraries(mage PRIVATE miniaudio)

target_link_libraries(mage PRIVATE volk)

target_link_libraries(mage PRIVATE VulkanMemoryAllocator)

target_compile_features(mage PUBLIC cxx_std_20)