project(cparse)
add_library(${PROJECT_NAME} SHARED builtin-features.cpp shunting-yard.cpp packToken.cpp functions.cpp containers.cpp)
