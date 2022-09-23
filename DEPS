# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '8243ca3c30527152c909b100292e4360e189663f',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '81ba8f78f6646e5635129bd738f25bb3f43bbdb9',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '4bd8fc0c8c266ecc6fc50193e65fe6a2fff8e4bc',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '265b455c996f7314ff995ecc3f5e3548365dbe87',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '39bcdfe388a5a88d34a941a9f75b2fd576da92cc',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'f755a87bf8ee8c83311f478c9d3a5a404697e886',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'facac95131acfa1594c6eae82916e24641d93358',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '3ef1524fc9ed2ecd7df5cb4ee7022c3d5598962b',
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
