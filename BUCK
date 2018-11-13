prebuilt_cxx_library(
  name = 'utility', 
  header_namespace = 'boost', 
  header_only = True, 
  exported_headers = subdir_glob([
    ('include/boost', '**/*.hpp'), 
  ]), 
  deps = [
    'buckaroo.github.buckaroo-pm.boost-config//:config', 
    'buckaroo.github.buckaroo-pm.boost-detail//:detail', 
    'buckaroo.github.buckaroo-pm.boost-preprocessor//:preprocessor', 
  ], 
  visibility = [
    'PUBLIC', 
  ], 
)
