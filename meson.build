project('8-bit-backgrounds',
  version: '0.0.1',
  license: [
    'GPL-2.0',
  ],
  meson_version: '>= 0.40.0'
)

# Dependencies
dep_glib = dependency('glib-2.0', version: '>= 2.48.0')

# Global paths
prefix = get_option('prefix')
datadir = join_paths(prefix, get_option('datadir'))
backgrounddir = join_paths(datadir, 'backgrounds', '8-bit')
metadatadir_gnome = join_paths(datadir, 'gnome-background-properties')

# Sub directories
subdir('backgrounds')

# Extra-dist files
extra_dist = [
  'AUTHORS',
  'COPYING',
]

install_data(extra_dist, install_dir: backgrounddir)
