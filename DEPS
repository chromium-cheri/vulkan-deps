# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '69ae9e7460499b488cb2d32edae623a95264db14',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'c93ee9261ed38be0b37b7cc40e2c5c47eaf5615d',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '87d5b782bec60822aa878941e6b13c0a9a954c9b',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '33113abf453572d3cf61b58d4378bbacb4206b1a',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '9f4c61a31435a7a90a314fc68aeb386c92a09c0f',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '823078c862f2d6deff673ca8d45a591f620f5712',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '088cfe80472564874bb45fe818e6c2440bf35b80',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'e5ac2812699382a399fef4bfc6d930ad45466ee3',
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
