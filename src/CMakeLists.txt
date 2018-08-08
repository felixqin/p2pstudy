
set(EXECUTABLE_OUTPUT_PATH ${OUTDIR}/bin)


include_directories(
        ${TOPDIR}/prebuilts/pj/include
)

link_directories(
        ${TOPDIR}/prebuilts/pj/lib
)

add_executable(icedemo icedemo.c)

target_link_libraries(icedemo
        pjnath-x86_64-unknown-linux-gnu
        pjlib-util-x86_64-unknown-linux-gnu
        pj-x86_64-unknown-linux-gnu
        uuid pthread m
        )

