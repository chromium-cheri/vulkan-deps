# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '7ca4dfa06158b923a122922a268c80d9d2e32a3f',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'bab4e5911b1bfa5a86bc80006b7301ae48363844',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'e71feddb3f17c5586ff7f4cfb5ed1258b800574b',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'b2e36b67eca055e4338d260cf5bc23c12420494d',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'c5b7a2fa18750e435e91e06a50cdc5451c5b9abd',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '8a3a1676ef16ee389289022339c8850565df7724',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '415320f80f74890561df8e52deb0024ecf1cadca',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '23df061eea2367b799aa59dfcd9843c0df3d32ba',
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
