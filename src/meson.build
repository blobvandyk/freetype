subdir('base')
subdir('truetype')

libfreetype = shared_library('freetype',
        [
            base_src,
            truetype_src
        ],
        include_directories: incdir,
        c_args: build_flags)

