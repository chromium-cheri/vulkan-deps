# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'c2604615f4820be63d9ea205be9a796bfc309e4b',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b81334a513e357cc15d6e93b9395b7733056f993',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '635049b5e1451d846d5d307def8c78328aaeb342',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'a6c5056db218459d02aadbcb43821322f50430c8',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '31dfaa4c632eec61f273f87d920237f0c7163dcf',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '909ef587b902e8e56051597a6cb75c0739ad18e5',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'fd988fa88a34328f1b7d45c9c0d4f4e1319a441e',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'a7c3a35e8be6c9be8567d0c6e29ac3d0966851cb',
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
