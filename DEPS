# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'e0771b5d4c7e64a4354e1aa93fb2a673b2a08010',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'c2500e504d2b823d73d2f129e4f4f050e9618ecb',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '0d3c45cdbb4563b95be9037ea967aac815caf78f',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '013b1f3d6d9cf9eee14a50a5cfe50b5e9300043e',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '4fee3efc189c83ccd26a9cd8265185c98458c94d',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'e1dc222803390e8e18e4a9a211609341ea34ccab',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'f4974ccd170cf2338c0582f607af5d8dfc3dac51',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '4295bdf12d7c8f2707e41d2fe763c5112e39c3ac',
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
