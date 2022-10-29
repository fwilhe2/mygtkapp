mygtkapp_sources = [
  'main.vala',
  'application.vala',
  'window.vala',
]

mygtkapp_deps = [
  dependency('gtk4'),
]

mygtkapp_sources += gnome.compile_resources('mygtkapp-resources',
  'mygtkapp.gresource.xml',
  c_name: 'mygtkapp'
)

executable('mygtkapp', mygtkapp_sources,
  dependencies: mygtkapp_deps,
       install: true,
)
