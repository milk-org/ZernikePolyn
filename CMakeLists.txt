project(lib_ZernikePolyn_project)

include_directories ("${PROJECT_SOURCE_DIR}/src")
include_directories ("${PROJECT_SOURCE_DIR}/..")
add_library(ZernikePolyn SHARED ZernikePolyn.c)

install(TARGETS ZernikePolyn DESTINATION lib)
install(FILES ZernikePolyn.h DESTINATION include)

