  add_executable(ForTuple main.cpp tuple_example.f90)
  target_link_libraries(ForTuple cabanacore)
  add_test(NAME Fortran_tutorial_02 COMMAND ForTuple)
