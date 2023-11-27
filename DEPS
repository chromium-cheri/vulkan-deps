# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '920a1424c998c4c09f35cdf80ebb482d626e655f',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '3717660e1400400bc7d9d9ca7f4c2b3853a3b456',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'cca08c63cefa129d082abca0302adcb81610b465',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '2a238ed24dffd84fe3ed2e60d7aa5c28e2acf45a',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '9d27c893cdfc8d96bc8ad5f6f4d88743f958305e',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '0e7cf57a2954f5b2dbb0fbf8327bf7d9401cfc26',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '9ef6c05af3ed1a30b6345a19deb1ddfc409e52bd',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '228f7487ddef12e55ee2c608dbf345eb042870b5',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '690a5c98e16f84c75640152c8523b0c54061cdb6',
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
