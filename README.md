# Visor

The Vulkan Ignoble Software Rasterizer.

Just a little for-fun side project to experiment with making a full software ICD for Vulkan. No grand plans for a fully compliant or optimised ICD.

# Enable Visor

set VK_ICD_FILENAMES=/path/to/visor.json

# llvm
  cmake .. -DCMAKE_BUILD_TYPE=Debug -DLLVM_TARGETS_TO_BUILD=host -DLLVM_ENABLE_ASSERTIONS=ON

  https://llvm.org/docs/LangRef.html