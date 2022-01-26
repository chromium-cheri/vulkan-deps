# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '81cc10a498b25a90147cccd6e8939493c1e9e20e',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '53d94a982e1d654515b44db5391de37f85489204',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'b42ba6d92faf6b4938e6f22ddd186dbdacc98d78',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '73735db943d7165d725883a1da0ad9eac79c1e34',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '1dace16d8044758d32736eb59802d171970e9448',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '356945ba6607b238929ed80e2181dadd123079c8',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'bc44326c93a1ee3fe7adce2bb7d9699386e9225a',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'a6c1ddca49331d8addde052554487180ee8aec13',
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
