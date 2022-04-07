# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '9bb8cfffb0eed010e07132282c41d73064a7a609',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '0d4ce028bf8b8a94d325dc1e1c20446153ba19c4',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '9c3fd01c8a91761b6e4be97ff4f13de76e779128',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '67fdf940975eef1a09cc5e6e00ffa7323bf845c4',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '76f00ef6cbb1886eb1162d1fa39bee8b51e22ee8',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '859fb722c2726f2e013e9c6c88491d160e634b35',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '38f9ee7a5bc8f137dc98a74698826f7fa53e3fd8',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '0474a0430abb650c7bfec8192b6025aec250006d',
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
