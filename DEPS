# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '6351fcef2888cf76a4405d756642c1e1ba2b4169',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '6d13c992738c67445c90c659491583c56307c10b',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '92f21c9b214178ce67cf1e31a00a33312590403a',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'f3fbd98ff52da2c56f706be7ee09d9a09dcb4742',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'dd99e0f51fa86210da384d0f17c036fa45475e12',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'b35527922c54d58e5d2afb1af9cf06bc40cc7fc7',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '7001f2eb37d151c5fec082e6b1a683cf7c6d85f9',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '01da631b1556ecf4fec8d74d7bf81625dc9675e5',
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
