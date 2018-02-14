dataconf = configuration_data()
dataconf.set('BACKGROUNDDIR', backgrounddir)

evergro_xml = configure_file(
  input: 'evergro-backgrounds.xml.in',
  output: 'evergro-backgrounds.xml',
  configuration: dataconf
)

backgrounds = [
  'Dragonfly.jpg',
  'Forest-Falls.jpg',
  'Iguana.jpg',
  'River.jpg',
  'Snow-Leopard.jpg',
  'Spider.jpg',
  'Stone-Beach.jpg',
  'Tukan.jpg',
  'White-Tiger.jpg',
  'Wind-Farm.jpg'
]

install_data([evergro_xml] + backgrounds, install_dir: backgrounddir)
install_data([evergro_xml], install_dir: metadatadir_gnome)
install_data([evergro_xml], install_dir: metadatadir_cinnamon)
install_data([evergro_xml], install_dir: metadatadir_mate)
