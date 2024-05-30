set(header_path "${${PROJECT_NAME}_SOURCE_DIR}/include")
set(header ${header_path}/circle.h)
set(src circle.cpp)
set(header ${header_path}/circle.h
        ${header_path}/task.h)
set(src circle.cpp
        tasks.cpp)

add_library(${PROJECT_NAME} SHARED
  ${header})
