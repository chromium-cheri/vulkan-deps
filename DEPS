# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '41e39c615b1478c4cce2ca06a6f7f291e2249f83',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '72a2ec4c1b56ce233e0da97a36f87af98927256c',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'bcf55210f13a4fa3c3d0963b509ff1070e434c79',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '1020e394cb1267332d58497150d2b024371a8e41',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '3f437c4a94ae35af1eb93700d073e9d0e7adab3d',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '039cea5353be38656b67c683aa6325c01bce6e7e',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '4ee5f2a8bee064cdc338f80546b75cdebba171de',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '3fa29a63072b405a3f802ed3739ae99cd68f080f',
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
