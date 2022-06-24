# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'b2d2c9dd3d77c6adadff37309aa58a181bafc5f9',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'e6925974d1ff5cb6b6472b20eed380889cde2ae8',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '36c0c1596225e728bd49abb7ef56a3953e7ed468',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'c4ed5157dc36bb6469ef97e4c044a138866ae5d7',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '3be1df310be8963c29125c35fce25ee0af12ff70',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '865626abbafda93a236398ac35627407d62dbe6f',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '6f57b1fa230f4ba88c34eeed9af31a4257df7fe8',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'e32ec7b0514ed94e24dce04968909a9b30a0f57e',
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
