# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '9575e33186c74a68831c469f7271edf386ea43a5',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '2d3a152081ca6e6bea7093940d0f81088fe4d01c',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '3469b164e25cee24435029a569933cb42578db5d',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'daee1e7d34704d5f9966f221a1ae060b7438329b',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'c1a8560c5cf5e7bd6dbc71fe69b1a317411c36b8',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'b02d69f3a1d54e9a1f9d957bd1a389a481aa1d25',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '07924a8a495dd8bcda112597da1bbc9b28f9bf63',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '53d210ecc1b13224e402cc18d1f0ef11e5b0a5aa',
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
