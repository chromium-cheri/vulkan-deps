# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '54726b3c1c5cb70043174365750ab0f1b7e1a6a0',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'bccaa94db814af33d8ef05c153e7c34d8bd4d685',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'ae89923fa781650569ca15e5b498a9e4e46ee9c9',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'e68fe9be4e6ca63097ac4305d7552ad29afd5004',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '94bb3c998b9156b9101421f7614617dfcf7f4256',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'bf59b6347ea69e18b2655dbbda6b350c65910b5d',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'ab9d7a042d152f0f36ef7e43cf33edea438fc6ab',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'c320ff46b5a914dafe7e0512a6395ecd643de457',
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
