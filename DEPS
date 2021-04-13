# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'e6a0e7fc766420cc1d81f41a5b86c3414fd7e32e',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'd2e1e7ba989135618f82bfeb6d97695d0d9bb9f5',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'bcf55210f13a4fa3c3d0963b509ff1070e434c79',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'a02a9205ff495c05ec18d2cdede6d8fc94201dec',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'e01b00657664ac34389d51b04c58dff3eb19a026',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '64cc17099c41622646e81d5b46cc537e47361f28',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'a746136a81cc8ecb1c31f824b88242f820c1fb09',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '7699b91798eb0cc43d8be031e457bcc21a7f91d5',
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
