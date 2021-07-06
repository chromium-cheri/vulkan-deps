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
  'spirv_cross_revision': '1ae2b58f19a935494363559f2fb41d7154261933',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'f95c3b3761ee1b1903f54ae69b526ed6f0edc3b9',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '9ce7a2fb62eb843882fd39c24c08d27d503fa378',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '0193e158bc9f4d17e3c3a61c9311a0439ed5572d',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '3bdb32d29f2d96b34e2865dc4a2f2be8eb457e1d',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '697cc6c387fd3019c37a01d6d18309916d1cc44d',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '054383987078f837c99b952f9e6c5233971fb255',
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
