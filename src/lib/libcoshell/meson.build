libcoshell_files = [
    'coclose.c', 'codata.c', 'coexec.c', 'coexport.c', 'coinit.c',
    'cokill.c', 'coopen.c', 'coquote.c', 'costash.c', 'cosync.c',
    'cowait.c', 'procrun.c', 'system.c'
]

libcoshell_c_args = ['-D_BLD_coshell']

libcoshell_incdir = include_directories('../libast/include',
                                        '../libast/features/',
                                        '../../cmd/ksh93/features/')

libcoshell = library('coshell', libcoshell_files,
                     include_directories: libcoshell_incdir,
                     c_args: libcoshell_c_args,
                     link_with: libast,
                     install: true)
