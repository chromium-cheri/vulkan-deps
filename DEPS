# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '6bdcb4be344d7903bd92fd464e496c3199b91484',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'a6ce49ca242019410abc5c359ed2c57e48e59883',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'bcf55210f13a4fa3c3d0963b509ff1070e434c79',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'ec1bc3e2e5678f2c72c0d3b196780a17df637d60',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '7fe877c90abf00bc71b3c68f49db4c9bb1010411',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '3bdb32d29f2d96b34e2865dc4a2f2be8eb457e1d',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '4e4619ae690a6f76f76b6d61f98bb95bbd0cb0f2',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '93883725f2d9a764f65b286bd63b6de39adabcf7',
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
