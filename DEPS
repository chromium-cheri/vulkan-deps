# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'ae2a562936cc8504c9ef2757cceaff163147834f',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '9338996f3b2bec5ef1b401c208baa8178843e38b',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'f95c3b3761ee1b1903f54ae69b526ed6f0edc3b9',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '237173a07083a81199ffdaa8325037abbf09aebe',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'a8964617af6b104d0341874e9b4776d82f80f9af',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '3bdb32d29f2d96b34e2865dc4a2f2be8eb457e1d',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '8926213dd0088f91e4be9bbe770a5b11b1316897',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'c09be02a362fe178b221c9ab8e7316ccbda7302f',
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
