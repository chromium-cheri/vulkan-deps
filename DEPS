# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'abc87e98fd6049d878f8addb319f470c1dc3c70a',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '3f855646f0c5d55d0fd935c7e96919f93de87ae8',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '5a121866927a16ab9d49bed4788b532c7fcea766',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '088cb1a5c81f45c8e778c4305e8668f3380401e8',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '245d25ce8c3337919dc7916d0e62e31a0d8748ab',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'fc48c8640bb99e1782b02740cc7e285c5246fa8b',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '903245157779ba52ed4be78969797947e2dc372a',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'a0571b1ea88e4180594965679de56bbfedec6b78',
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
