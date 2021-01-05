# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '9325cc013e3df4f85a457c2d43e831a9e93713e1',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '7b7a21c4058c4ef457a793b186224aba6837638c',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'f027d53ded7e230e008d37c8b47ede7cd308e19d',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '1bb80d2778a3d0362365b2490e2174bd56453036',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '85470b32ad5d0d7d67fdf411b6e7b502c09c9c52',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '66a23ac8c566299343668f094de50798a5f4a0e4',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '7554321b88aed733a8b2cfc618f42b43b52e6f11',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'aa076dae88e282d7b6cada4f900b2fa7dac8ed08',
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
