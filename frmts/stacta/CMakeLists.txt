add_gdal_driver(TARGET gdal_STACTA SOURCES stactadataset.cpp STRONG_CXX_WFLAGS PLUGIN_CAPABLE NO_DEPS)
gdal_standard_includes(gdal_STACTA)
