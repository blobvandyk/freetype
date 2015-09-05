project('freetype', 'c')

incdir = include_directories('include')

build_flags = '-DFT2_BUILD_LIBRARY'

subdir('src')

freetype_dep = declare_dependency(link_with: libfreetype,
        include_directories: incdir)

