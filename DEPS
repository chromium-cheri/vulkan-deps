# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'b38100f6bc005c63cef32a20fa1463aceb867ee6',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '2e1b5fb39ebc2ef4cb77005f8267e4f3a6241ba1',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '07f259e68af3a540038fa32df522554e74f53ed5',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '5dd2f76918bb2d0d67628e338f60f724f3e02e13',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '37164a5726f7e6113810f9557903a117498421cf',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '3bdb32d29f2d96b34e2865dc4a2f2be8eb457e1d',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'a680671d95bf7b3846cb20f1cbfc1c405db0511b',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '16db450293205d275664064d91a8b8c3a30ede22',
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
