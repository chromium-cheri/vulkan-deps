# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'a8d39f97cdf08cf7eac4ae40dfe7b41420a3be30',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '4818f7e7ef7b7078a3a7a5a52c4a338e0dda22f4',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '38f39dae5baaa24431b24ac659054ebe972fa1e6',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '6b1e609ef1609ac695cc465374d7e50831c1937b',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'af4fb97d7bde80997b0f61d53bb50bd6c56b8f50',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '0b31098e538f79780ab14e4fc6b77c18b13694a9',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '90e25ec83a56f0e1c79480b934d7e255fde7869e',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '177e2312faf83374d049111a194954fcdfb84b73',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '0c7db85599ce2325b4f4b0fed5d444416acab7e7',
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
