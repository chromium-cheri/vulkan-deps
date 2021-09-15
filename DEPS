# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '80dcc36907f65bbbd14eff2280f40e5ee82a9113',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b81334a513e357cc15d6e93b9395b7733056f993',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '635049b5e1451d846d5d307def8c78328aaeb342',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '9e65f054d1a13f64c2f1e4fa7b55791e35fbea6e',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'c519fd7a3f3b3baf0df16395356cecf4bfee2a8c',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '6e345ec185be4dae1875e07f857b32bb53b4a592',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'f4974ccd170cf2338c0582f607af5d8dfc3dac51',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '8083ce8439091c758522f2077816769bce818ac6',
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
