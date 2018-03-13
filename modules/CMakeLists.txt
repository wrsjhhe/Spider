project(domainlimit C)
set(domainlimit domainlimit.cpp)
set(CMAKE_LIBRARY_OUTPUT_DIRECTORY ${PROJECT_SOURCE_DIR}/../libs/)
add_library(domainlimit SHARED ${domainlimit})


project(headerfilter C)
set(headerfilter headerfilter.cpp)
set(CMAKE_LIBRARY_OUTPUT_DIRECTORY ${PROJECT_SOURCE_DIR}/../libs/)
add_library(headerfilter SHARED ${headerfilter})

project(maxdepth C)
set(maxdepth maxdepth.cpp)
set(CMAKE_LIBRARY_OUTPUT_DIRECTORY ${PROJECT_SOURCE_DIR}/../libs/)
add_library(maxdepth SHARED ${maxdepth})

project(savehtml C)
set(savehtml savehtml.cpp)
set(CMAKE_LIBRARY_OUTPUT_DIRECTORY ${PROJECT_SOURCE_DIR}/../libs/)
add_library(savehtml SHARED ${savehtml})

project(saveimage C)
set(saveimage saveimage.cpp)
set(CMAKE_LIBRARY_OUTPUT_DIRECTORY ${PROJECT_SOURCE_DIR}/../libs/)
add_library(saveimage SHARED ${saveimage})