# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '302a663a38b89e4d8c3ac8edf754ca4f2d78538c',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '637cff3d05892801daa43c93907e17151c7dfd31',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '88bc5e321c2839707df8b1ab534e243e00744177',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'c87755bb9fb5df188775738996d0eac56b2ebcb9',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'aff5071d4ee6215c60a91d8d983cad91bb25fb57',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '9f257b620d2fc5f0f7dba115fc135c5cc8eaccc6',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '116b6b1513d33f2414ddc4db01a7244d6e021ba6',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '5b3147a535e28a48ae760efacdf97b296d9e8c73',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '85727dcf62eaa73123163b568c991999d0eb6bae',
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

  'vulkan-utility-libraries/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Utility-Libraries@{vulkan_utility_libraries_revision}',
  },

  'vulkan-validation-layers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-ValidationLayers@{vulkan_validation_revision}',
  },
}
