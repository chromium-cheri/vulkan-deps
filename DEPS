# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'a6662c53ced629a9d94611276743cbcde896b6af',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '12542fc6fc05000e04742daf93892a0b10edbe80',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '8e2ad27488ed2f87c068c01a8f5e8979f7086405',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'c7e436921a148ebf1ad38720e4f8677366b54792',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '3df77fb3e4e0961f7f01de9a9ae20dfdcfc4910a',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'fa5fb6f9e11cdc9b05ceedfc56015cacc4c2fcc2',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '9a252664d779bc726cc97a85ca407641bf148e83',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'a140018e6218ac2fdfeb09611774bd8747bcf8d4',
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
