# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '4c57db1595462c51d5080893f65c42fc1f318146',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '5e963d62fa3f2f0ff891c9f9ca150097127c3aad',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '79743b899fde5c954897b2694291002626358fac',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'ee7598d49798e7bf34fabe55b5a438a381d450c8',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '4f51aac14f65629dfe83702b806f740dbd7bd701',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '4f8c7962f4745d3a7126b5f31d58a42026369642',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'c92c1e0654045eccca6a7f2559102d5264ee938f',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'f867a2ff9232e6bc897497cd42726035af609563',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '237ee3f7dc292b305739ca8f8b6b042013d3ae54',
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

  'vulkan-utility-libraries/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Utility-Libraries@{vulkan_utility_libraries_revision}',
  },

  'vulkan-validation-layers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-ValidationLayers@{vulkan_validation_revision}',
  },
}
