# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'bb5b3575503d285c15dadb479e2eea38b02e0dd7',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '2e0fb3a7784011ebd3c25cd1252beca0819fd1de',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'b8bc8cae7d3b402a7c07ec717b268211f3f1dfda',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '352a411278e1934995ed3ad4f55fe854353acca8',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '8c1c27d5a9b9de8a17f500053bd08c7ca6bba19c',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'bed7a5c6594ad7ac5ccaa85ffb7bff2e5ee18d3d',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '691252756218fcbd1f0f8d7cc14e753123f08940',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '8f58bbd613ebc42bc78153a8f023e9a4e8a19739',
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
