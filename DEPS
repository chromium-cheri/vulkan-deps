# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '1a8869e4d1bee138f2813208777e1a58bebb9735',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '677299cc566898cc85a61e315cace3e5be933ea7',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '85a1ed200d50660786c1a88d9166e871123cce39',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'a52de681dd17f8b545ecd9ea2138f72b39bf449a',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'e12a8f8cde4047fb40c34bc1bf624e24c0d0c76e',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'a17d7fc737e650070e50655b877be1aa206a2031',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '292e6ed02141b015950d03390c6e8576b0673ef6',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '918d534ffdf828d7ede68cc2336c8910b3934d55',
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
