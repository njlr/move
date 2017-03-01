include_defs('//BUCKAROO_DEPS')

prebuilt_cxx_library(
  name = 'boost-move',
  header_only = True,
  header_namespace = 'boost/move',
  exported_headers = subdir_glob([
    ('include/boost/move', '**/*.hpp'),
  ]),
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)
