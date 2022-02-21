# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'd15deba1d8c7da7336945a80eccbf875ae884648',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '188dc8b13c29f8547c8fb52182111c9ada741a70',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '6a55fade62dec6a406a5a721148f88a2211cbefa',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'd18d0d92e55f44da6af0dc87fb0e3c8034e9a3ac',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'aa18f182ebba65438b1cfdbd571f020bb2e34d04',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '4c90ec3310776e3ebcd49d65b8ce82aacf9a81c3',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '3a60ee90c184790b47d7c8fa58d3030a248ce33e',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '0df8b17c340318ee6debaba25c980a98350bb8f7',
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
