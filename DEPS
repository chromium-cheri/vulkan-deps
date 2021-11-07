# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'eb92526d5e04572fdf1d15d2f3ae10a967c2f46f',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'f1d4aff85ef9a1edfa595ef800f8c5a69e5a362b',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '29817199b7069bac971e5365d180295d4b077ebe',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '339d4475c1a806c187c57678af26733575d1cecd',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '51a326d756d279652187d0e66433a7b10660f311',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'd5bb7a92160cf34e81ed39d3454c65024cdf09ea',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'aa16057108c4f2ed8a1a25e7175ee1bfbc195e90',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '3511e319ff8b19cbb7c8e8d07a090f86aa7a49e0',
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
