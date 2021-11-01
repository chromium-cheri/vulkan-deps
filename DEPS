# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '77d680e1c3cc82a46290a92fad1d4549c07dc122',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '061397e32efd31259e731115d705e7c6bef68907',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '1380cbbec10756b492e9397d03c4250887e15090',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '1082de6bb32fc425623a6a218c5295bfd4db9a09',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'd594f70127b4198286b3472a48bee56e341259cd',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '830a0724aa281d7cad98eda59b850871f024bb41',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '7001f2eb37d151c5fec082e6b1a683cf7c6d85f9',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '6fca9899aa70934d37e7c395276620790fd4749c',
}

deps = {
  'glslang/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/glslang@{glslang_revision}',
  },

  'spirv-cross/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Cross@{spirv_cross_revision}',
  },

  'spirv-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Headers@{spirv_headers_revision}',
  },

  'spirv-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Tools@{spirv_tools_revision}',
  },

  'vulkan-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Headers@{vulkan_headers_revision}',
  },

  'vulkan-loader/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Loader@{vulkan_loader_revision}',
  },

  'vulkan-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Tools@{vulkan_tools_revision}',
  },

  'vulkan-validation-layers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-ValidationLayers@{vulkan_validation_revision}',
  },
}
