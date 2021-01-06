# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '480f6039e072cced267e79a46366fc5caaa5c90a',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '7b7a21c4058c4ef457a793b186224aba6837638c',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'f027d53ded7e230e008d37c8b47ede7cd308e19d',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'aa005e8bd435fc52249a9975e835d8ba93cda7e2',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '9efc4a631161eeea11082bbd16d605cca0b7a01e',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '9ba835885ffe6007c2e6d40c216a087fdd495d0e',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '4cc0932495ec1eb132c309473b8efc0b6b0d75b3',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'cc435b55410ac50a137010aa1346d15c320e1713',
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
