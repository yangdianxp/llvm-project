add_custom_target(Toy2)
set_target_properties(Toy2 PROPERTIES FOLDER "LLVM/Examples")

macro(add_toy2_chapter name)
  add_dependencies(Toy2 ${name})
  add_llvm_example(${name} EXPORT_SYMBOLS ${ARGN})
endmacro(add_toy2_chapter name)

add_subdirectory(Chapter2)
