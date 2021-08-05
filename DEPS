# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'e0f3fdf43385061a1e3a049208e98527ee6af4af',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'bab4e5911b1bfa5a86bc80006b7301ae48363844',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'e7b49d7fb59808a650618e0a4008d4bae927e112',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '3ab6fb9c0328d30e4f2ee529a47f748b58755fde',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '9fe958cdabcaf87650a4517b27df1ec2034d051f',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '4c901a731a63baf5e6049e1a976a6655fb83be01',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '8dca1fa770824124d0240032c58254d1b0e4b8ff',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '5111d5aea9fbc8d1d88e5de2ac4f755978db6fee',
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
