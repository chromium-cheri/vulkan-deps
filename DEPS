# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '3de5cfe50edecd001e6d703555284d9b10b3dd57',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '820179bf4689aca0e8e13d3ecf9b57fcd39cf067',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'f027d53ded7e230e008d37c8b47ede7cd308e19d',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'cec658c11603a5411a38f0f86d0ecc04250df4b7',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '9efc4a631161eeea11082bbd16d605cca0b7a01e',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '9ba835885ffe6007c2e6d40c216a087fdd495d0e',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'c86cec54abe675845e709ad0b362bd8bffe18bf2',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '586c46b96b62ac866848bad9df9284a0d44c121a',
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
