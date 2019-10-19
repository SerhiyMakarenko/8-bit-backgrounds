dataconf = configuration_data()
dataconf.set('BACKGROUNDDIR', backgrounddir)

8-bit_xml = configure_file(
  input: '8-bit-backgrounds.xml.in',
  output: '8-bit-backgrounds.xml',
  configuration: dataconf
)

backgrounds = [
  'what-space-really-looks-like.jpg'
]

install_data([8-bit_xml] + backgrounds, install_dir: backgrounddir)
install_data([8-bit_xml], install_dir: metadatadir_gnome)
