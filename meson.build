project('freetype', 'c')

incdir = include_directories('include')

subdir('src')

freetype_dep = declare_dependency(link_with: libfreetype,
        include_directories: incdir)

