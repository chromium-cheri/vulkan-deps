# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'f4cba22d08241cad63a270e33f4ef3384979982e',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'edd66a2fc9e932ad0d3dce78f2627eeae91c2660',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '47f2465ee3e78ec5ec38f00b2c405d9475797228',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '525bc38062ab082d5b540dfe9465231cfb94361d',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'ef96d229cb3d9d58b71c832aafd79f9dda306375',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '6442b72aea02ed762bbcc7c649840c0a8a092237',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '6e5bd86b76c092fcd5d8a873260a8a96f43705d5',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '212ea587c1003d122741dce70f6875361c3965fe',
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
