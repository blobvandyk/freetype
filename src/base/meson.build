if target_machine.system() == 'osx'
    system_src = ['base/frmac.c']
elif target_machine.system() == 'linux'
    system_src = ['../builds/unix/ftsystem.c']
else
    system_src = ['base/ftsystem.c']
endif

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
    system_src
    ]

