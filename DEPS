# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '854db99ff1371995e015a65dfd88556c5af01027',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '42aac916ab5db0cbaf55c2d41f4d063f4ce3955a',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'cca08c63cefa129d082abca0302adcb81610b465',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '2a238ed24dffd84fe3ed2e60d7aa5c28e2acf45a',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'af4fb97d7bde80997b0f61d53bb50bd6c56b8f50',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '19e9e53255a525e1b96b71306bb8bc00870aade6',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'ae2a2dc99bc01417d2c80e81078a5672e9d31d0b',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'e4ceafdd0645fc843327a11d025e6113360dff0b',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '1cbb2c8ffa4fa4fcc7dfc3a9e3ee2be40a645a19',
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
