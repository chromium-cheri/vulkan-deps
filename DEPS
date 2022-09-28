# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '2ab42a9a1f1a6cdc2ea9db88e9f5eeac57196233',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '81ba8f78f6646e5635129bd738f25bb3f43bbdb9',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '4bd8fc0c8c266ecc6fc50193e65fe6a2fff8e4bc',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'e1a8b5d60dbf44aa76913d86dae203b7e2dbc884',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '39bcdfe388a5a88d34a941a9f75b2fd576da92cc',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '9c40a28e3ee654cd5997570d26eb87062017647e',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'facac95131acfa1594c6eae82916e24641d93358',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '99c443f5d61cd7711a4df18af796df52ec3eeca9',
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
