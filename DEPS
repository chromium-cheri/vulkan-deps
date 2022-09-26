# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '8ba94fc9dee702f6bd7f0fdade66034e06120143',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '81ba8f78f6646e5635129bd738f25bb3f43bbdb9',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '4bd8fc0c8c266ecc6fc50193e65fe6a2fff8e4bc',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '49230a2307a53a99ad699f729b6a2cc8850f754c',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '39bcdfe388a5a88d34a941a9f75b2fd576da92cc',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '9c40a28e3ee654cd5997570d26eb87062017647e',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'facac95131acfa1594c6eae82916e24641d93358',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'b7b7167ad50e8cea27600f402fb3ddfa909b2045',
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
