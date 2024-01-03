add_library(ppm2pnglib)
target_sources(ppm2pnglib PUBLIC
FILE_SET cxx_modules
TYPE CXX_MODULES
FILES gdiplusinitialize.ixx image.ixx)
