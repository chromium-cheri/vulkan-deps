# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '0e1396862cc8631ee6606910c95ad6a13088942f',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'e9cc6403341baf0edd430a4027b074d0a06b782f',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '29414ae1fd07a43cf8fe29b4437bfe8475cdd0d8',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'd0a827a9f313954935e3d9edb0c063fd8625a22e',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'ea61f32f24d2ce28b358e154910fb4eb410ffd79',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '36cc5816218b598ab21864ad678cdc2464d1cbb9',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'b50a0f786efc0b70ae05a9b1e1cc0526e43ee7d1',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'c6bafff88f7e7354944273cc151bd6358f28fe1b',
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
