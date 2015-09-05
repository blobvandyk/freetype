#if compiling_for_osx
#base_mac_src = ['ftmac.c']
#else
    base_mac_src = []
#endif

base_src = [
    'base/ftinit.c',
    'base/ftadvanc.c',
    'base/ftcalc.c',
    'base/ftdbgmem.c',
    'base/ftgloadr.c',
    'base/ftobjs.c',
    'base/ftoutln.c',
    'base/ftrfork.c',
    'base/ftsnames.c',
    'base/ftstream.c',
    'base/fttrigon.c',
    'base/ftutil.c',
    'base/basepic.c',
    'base/ftpic.c',
    'base/ftbitmap.c',
    '../builds/unix/ftsystem.c',
    base_mac_src
    ]

#libbase_static = static_library('base',
#[base_src, base_mac_src],
#include_directories: incdir,
#c_args: build_flags)


