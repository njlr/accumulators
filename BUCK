include_defs('//BUCKAROO_DEPS')

prebuilt_cxx_library(
  name = 'accumulators',
  header_only = True,
  header_namespace = 'boost/accumulators',
  exported_headers = subdir_glob([
    ('include/boost/accumulators', '**/*.hpp'),
  ]),
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)
