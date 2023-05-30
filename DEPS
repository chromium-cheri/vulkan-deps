# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'b587425025dc6547a2cdbc27220c845fa21ff861',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '12542fc6fc05000e04742daf93892a0b10edbe80',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '69155b22b3b1f2d0cfed48f59167d9792de1fd79',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '673d8bfcb6b1cd18977da539d8809237f7fb14e1',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '3df77fb3e4e0961f7f01de9a9ae20dfdcfc4910a',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '3382accd2328be9bb5c0d3caff6bca4250028633',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '845f0fc359ec64f33b591aa8bf29c76c7d09f07c',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'a218291816a1da4b60a2b5cc34bb56cd2ff8a199',
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
