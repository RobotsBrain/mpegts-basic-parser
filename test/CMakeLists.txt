set(EXECUTABLE_OUTPUT_PATH ${OUTDIR}/test)

include_directories(
    ${TOPDIR}/include/
)

link_directories(
)


#################################
add_executable(tsunpacker tsunpacker.c)
target_link_libraries(tsunpacker tsparser)
