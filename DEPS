# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'b70669a0593f022af1d10f77d29856e24cfaaa50',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'bccaa94db814af33d8ef05c153e7c34d8bd4d685',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '45fc02a6c67016b3e5ff6e4896a61544a40f90f8',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '89ca3aa571fe238944b31e88d5d8fe75fab0227a',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '85c2334e92e215cce34e8e0ed8b2dce4700f4a50',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '4830af39dce87b415de1c99edbc3283844d38903',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '300d9bf6b3cf7b237ee5e2c1d0ae10b9236f82d3',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'd42a0c5d828ee69fa033401826a12f8c3185b308',
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
