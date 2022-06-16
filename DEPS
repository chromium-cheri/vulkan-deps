# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'bffcf209cb67f718bd8faafd43d0379f943c116f',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '89b1c24bdced198bf5eeb8d6052eafeb4a5219f9',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '36c0c1596225e728bd49abb7ef56a3953e7ed468',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'fbcb6cf4c820ec83d0eff650a8323b8f92c137c9',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '3be1df310be8963c29125c35fce25ee0af12ff70',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'e26be655eb804381e6fe081f84a95681f4daeef4',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '2661f654ad5df0e02ae04f6bdbe9be51864c8d6a',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'd060c3f1b29a89387e6ab6de8db3725ea65d5abd',
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
