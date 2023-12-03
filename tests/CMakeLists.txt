INCLUDE_DIRECTORIES(
   # ${googletest_SOURCE_DIR}/googletest/include
)

add_executable(
  hello_test
  hello_test.cc
)

target_link_libraries(hello_test gtest)

gtest_discover_tests(hello_test) 