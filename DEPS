# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '0fedf7d95ad9c183279c279f3912c2da6d7fd0a5',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '9da5f7ce45f8642affec51168e3a4e61f7b13215',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '1c6bb2743599e6eb6f37b2969acc0aef812e32e3',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '6b4f0c9d0b7d02db5ed0b03433ae62c03bbff722',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '19a863ccce773ff393b186329478b1eb1a519fd3',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '81c4aa292c3d479349f8c63ae13e25a89b4f5bbc',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '1ee9eea9f1f58fe0677703eb121ae445e6513b9a',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '2feac587338c7e1b631b2ef9bd6e894d7ad7f56d',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '44a2d874ac6618b3ce89e2670ec7e63027619749',
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
