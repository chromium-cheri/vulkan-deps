# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '4e9cde50bb76c2b941b2edba8a073c70476e698e',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'eb9b2732982b8eea3395216be825a74dd84fe4be',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'aa331ab0ffcb3a67021caa1a0c1c9017712f2f31',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'af15e5adeabfa629b1e2b6f88d31f853f64a2daa',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'a49166a89a1abc6df2d5147bd06bd4c5b7c4d010',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '0a2c1bece62909bfbe740cb81243e93d4c1c8629',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '80e16af0fd8f1f03374e4cc4eea4822520967e08',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '79e1676ae6c1ba6740176a13bc0e78ccd5cac58f',
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
