set(LLVM_LINK_COMPONENTS
  Analysis
  Core
  ExecutionEngine
  InstCombine
  Object
  OrcJIT
  Passes
  RuntimeDyld
  ScalarOpts
  Support
  native
  )

add_toy2_chapter(Toy2-Ch2
  toy.cpp
  )

