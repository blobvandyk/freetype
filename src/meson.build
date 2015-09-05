subdir('base')
subdir('truetype')

configure_file(
        input: '../builds/unix/ftconfig.meson.in',
        output: 'ftconfig.h',
        configuration: configuration_data())

build_flags = '-DFT2_BUILD_LIBRARY -DHAVE_FCNTL_H -DHAVE_UNISTD_H'

libfreetype = shared_library('freetype',
        [
            base_src,
            truetype_src
        ],
        include_directories: incdir,
        c_args: build_flags)

