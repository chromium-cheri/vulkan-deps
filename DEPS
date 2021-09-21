# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '6baa85f6ceec5fddd2e13b43dd1edc944dd930af',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b81334a513e357cc15d6e93b9395b7733056f993',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '635049b5e1451d846d5d307def8c78328aaeb342',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '59f51bb4f8389713ec6136f09441c10c2da62727',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'c519fd7a3f3b3baf0df16395356cecf4bfee2a8c',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '2d69d5c7d438f14eaa43b874802688684a4912bb',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '5a070f287d30f149ba3e2e713edcb76765f6b1cc',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '306dc4c1010a500784d7b745146afcc9f99202cb',
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
