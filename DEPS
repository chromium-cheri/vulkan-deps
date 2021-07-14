# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '4b7b86d568b40f4b076259dc2fc4cdd006340f34',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'be3988b13cb73dc007cab9291e7ce3b3456bf7c2',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'ddf3230c14c71e81fc0eae9b781cc4bcc2d1f0f5',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '640b17b5fbc65f2aed9106ad96ba40c51fa20195',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '0193e158bc9f4d17e3c3a61c9311a0439ed5572d',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '15e1bbe99a09c1c454c9a33f2cc9b65667a9accc',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '33a87ce6daecf60742277408ca9fa7ec6a4a5aae',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'dada63db181a863f30c30f818f22f91e4b5a8202',
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
