project(glad)

add_library(glad STATIC
	"include/KHR/khrpltform.h"
	"include/glad/gl.h"
	"src/gl.c"
)

target_include_directories(glad PUBLIC
	"include/"
)

