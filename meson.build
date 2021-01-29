project('patch', 'c')
bsd = dependency('libbsd')

source_files = [
  'backupfile.c',
  'inp.c',
  'mkpath.c',
  'util.c',
  'patch.c',
  'pch.c'
]

executable('patch', source_files, dependencies : bsd)
install_man('patch.1')
