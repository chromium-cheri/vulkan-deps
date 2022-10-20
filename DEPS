# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '980ac50813fb567b6af6b89282eae850b328c967',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '57639196694a8b5c572c9358f5d9cb443dd341e5',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '85a1ed200d50660786c1a88d9166e871123cce39',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'ecd5b9c167ad03dcd4b3211d209581f40e03c608',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '98f440ce6868c94f5ec6e198cc1adda4760e8849',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'ae54ca0d01f0259441a93b7681eebb28102f28d8',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'e52fa1cf2d95503d28f9d020800cbab15aaa304b',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '5e5391eed5a66c4061bec761d107edb1f425765a',
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
