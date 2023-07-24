tomato_sources = [
  'main.vala',
  'application.vala',
  'window.vala',
]

tomato_deps = [
  dependency('gtk4'),
]

tomato_sources += gnome.compile_resources('tomato-resources',
  'tomato.gresource.xml',
  c_name: 'tomato'
)

executable('tomato', tomato_sources,
  dependencies: tomato_deps,
       install: true,
)
