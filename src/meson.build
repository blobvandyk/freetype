subdir('base')
subdir('truetype')

subdir('pcf')
subdir('pfr')
subdir('psaux')
subdir('psnames')
subdir('raster')
subdir('sfnt')
subdir('smooth')
subdir('type1')
subdir('type42')
subdir('winfonts')

#subdir('autofit')
#subdir('bdf')
#subdir('bzip2')
#subdir('cache')
#subdir('cff')
#subdir('cid')
#subdir('gxvalid')
#subdir('gzip')
#subdir('lzw')
#subdir('otvalid')
#subdir('pshinter')
#subdir('tools')

configure_file(
        input: '../builds/unix/ftconfig.meson.in',
        output: 'ftconfig.h',
        configuration: configuration_data())

build_flags = '-DFT2_BUILD_LIBRARY'

libfreetype = shared_library('freetype',
        [
            base_src,
            truetype_src,
            pcf_src,
            pfr_src,
            psaux_src,
            psnames_src,
            raster_src,
            sfnt_src,
            smooth_src,
            type1_src,
            type42_src,
            winfonts_src
        ],
        include_directories: incdir,
        c_args: build_flags)

