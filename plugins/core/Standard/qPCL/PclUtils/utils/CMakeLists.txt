
target_sources( ${PROJECT_NAME}
	PUBLIC
		${CMAKE_CURRENT_LIST_DIR}/sm2cc.h
		${CMAKE_CURRENT_LIST_DIR}/PCLCloud.h
		${CMAKE_CURRENT_LIST_DIR}/PCLConv.h
		${CMAKE_CURRENT_LIST_DIR}/copy.h
		${CMAKE_CURRENT_LIST_DIR}/my_point_types.h
		${CMAKE_CURRENT_LIST_DIR}/cc2sm.h
	PRIVATE
		${CMAKE_CURRENT_LIST_DIR}/sm2cc.cpp
		${CMAKE_CURRENT_LIST_DIR}/copy.cpp
		${CMAKE_CURRENT_LIST_DIR}/cc2sm.cpp
)

target_include_directories( ${PROJECT_NAME}
	PUBLIC
		${CMAKE_CURRENT_LIST_DIR}
)
