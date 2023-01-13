# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '1fb2f1d7896627d62a289439a2c3e750e551a7ab',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '49e4117c5f56bec716ed00bcbf36d3a2e8efd90e',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'd13b52222c39a7e9a401b44646f0ca3a640fbd47',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '7e8813bb4cf32fd9c4d696c09d4e68e17a8f57f1',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '6ea9413be28455ab172af63d14927f8453cb25f1',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '366966e85b85fdfce8e365360cd37bb28bb9a642',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '6ef427d3b9877395e07f0618ada16d81c95ce974',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '30cce9e1cfef2cddd5ee73a6759f56096d8168f2',
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
