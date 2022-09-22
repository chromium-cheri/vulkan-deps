# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '8243ca3c30527152c909b100292e4360e189663f',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '81ba8f78f6646e5635129bd738f25bb3f43bbdb9',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '4bd8fc0c8c266ecc6fc50193e65fe6a2fff8e4bc',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'f98473ceeb1d33700d01e20910433583e5256030',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '5177b119bbdf463b7b909855a83230253c2d8b68',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '3090fc12bd202eeb6792a59480a4217a250cb9a4',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '5b4f2218195eaebf8aa19f870ff7b1ee0064ac60',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'db7cc3d338e3a5a8c274dfd59e89c48e26218c75',
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
