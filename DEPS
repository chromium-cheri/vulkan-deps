# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '2be1561b918d5760ca8559914ff3009713c5cab9',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '50b4d5389b6a06f86fb63a2848e1a7da6d9755ca',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'b2a156e1c0434bc8c99aaebba1c7be98be7ac580',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'b930e734ea198b7aabbbf04ee1562cf6f57962f0',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '245d25ce8c3337919dc7916d0e62e31a0d8748ab',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'd86dc61e76f66b32b6955e8e7cbfa3edc7ed7b32',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'dd7e8d2fbbdaca099e9ada77fec178e12a6b37d5',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '3294edd9f106d413029a481f9316b425ecdd9346',
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
