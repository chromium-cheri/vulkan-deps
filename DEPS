# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '48fd6c82b3fefb38e59dd799d8b12fddddf8e63c',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '0d4ce028bf8b8a94d325dc1e1c20446153ba19c4',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '9c3fd01c8a91761b6e4be97ff4f13de76e779128',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '92c17edde79a3afae2aee810da4ce03bc7088531',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '76f00ef6cbb1886eb1162d1fa39bee8b51e22ee8',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '859fb722c2726f2e013e9c6c88491d160e634b35',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '5f3ce24e7a530d089842c8192c2565a672555250',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '9dbebff4420be361ee25f4dd31382b45c6a1de20',
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
