add_unit_test(CRITERION LIBTEST TARGET test_wildcard_source DEPENDS affile)
add_unit_test(CRITERION TARGET test_directory_monitor DEPENDS affile)
add_unit_test(CRITERION TARGET test_collection_comporator DEPENDS affile)
add_unit_test(CRITERION TARGET test_file_opener
  INCLUDES "${CMAKE_SOURCE_DIR}/modules"
  DEPENDS affile)
