set(SOURCES
  test3.cpp
)

add_executable(paltest_snwprintf_test3
  ${SOURCES}
)

add_dependencies(paltest_snwprintf_test3 coreclrpal)

target_link_libraries(paltest_snwprintf_test3
  ${COMMON_TEST_LIBRARIES}
)
