# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '9158061398a96033c990e69156bd28c67114544b',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '18f3cd681003d25af2224db65eeae8055898d06a',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'cf653e4ca4858583802b0d1656bc934edff6bd7f',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'd9f89257855a2784323512cd9568b6610bcae581',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '872fa25bb6df67e1b338c1533ad55244b6ff8994',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'a0c69f0d3a3d7610b87c49f36df44a990d6c6eec',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '33a87ce6daecf60742277408ca9fa7ec6a4a5aae',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '8c765ba0252fc5c773bddbfdcb44ea8e4384c0cf',
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
