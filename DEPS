# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '719b6b7debbfe75bd427daa0e39c347fce16cf9a',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'a3da0e87fa1a6aacdf32c5e729a653b60afe82af',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'cca08c63cefa129d082abca0302adcb81610b465',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'f4a73dd7a0cadfa9a9ea384b609e0e6a2cb71f5b',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '9d27c893cdfc8d96bc8ad5f6f4d88743f958305e',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'cf32131e121d931795add2aa6e56ac5b1d0a45e5',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '98d168c168041bc026bb55b11c59b256f8162791',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '1fb77ad1d40ee127834436d92efc3a0e626dd91f',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'f686789d7d52e6866c9c4574fdb75449bccca8da',
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
