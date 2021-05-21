# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '6fe560f74f472726027e4059692c6eb1e7d972dc',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'faec1a8643d260b0fe1df4c106e6abce97532c7f',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'bcf55210f13a4fa3c3d0963b509ff1070e434c79',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'f0d110e3058bba9a31f9bd0a8727bdd0a559af82',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '9af411e83fb08cd2bddc3ec771de89416a96cb91',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'a132dee142c0d6bf54d09d50ed7fff28f4b491ef',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '72c2d5f0b0e59bf429144d2e60d8fd6ce1710887',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '9326420ac7effad9d269172b61275fb40d192361',
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
