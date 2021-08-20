if(BUILD_LIBRARY)
	set(CMAKE_POSITION_INDEPENDENT_CODE ON)
endif()

add_library(jsoncpp jsoncpp.cpp)
target_link_libraries(jsoncpp)

