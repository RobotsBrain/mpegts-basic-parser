include_directories(
	${TOPDIR}/include/
)

file(GLOB_RECURSE HEADERFILES "../include/*")
aux_source_directory(. DIR_SRCS)

add_library(tsparser ${DIR_SRCS} ${HEADERFILES})
