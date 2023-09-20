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
  'spirv_headers_revision': 'f8a4f5d876e56c9930344041171192f04f244f61',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'a40483d313bdfa7f9873883284c86f6e9a3294be',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '4f51aac14f65629dfe83702b806f740dbd7bd701',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '9dc0e31574b6f038e11cc2ee77a6e0358599851f',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '8a9f85e7125615995af864fd47f5e64e0aa9bc9c',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'fefcc37fc1bd1276cee554a285f9f657e1fa4676',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '48499f79ab629455469e5d05615f44169340e410',
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
