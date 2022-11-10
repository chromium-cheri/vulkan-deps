# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '2b2523fb951f63f072cfba514c26f2feea5f4329',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'edd66a2fc9e932ad0d3dce78f2627eeae91c2660',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '47f2465ee3e78ec5ec38f00b2c405d9475797228',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'aae7d413257181a46a0f79a4dcff7acc3092a918',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'f97f29836cb9c8c5657979f1aeac42b46d4e51d0',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '0df63661a5facd7084189a774e181b67a37ac034',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'e8234991418c5b0536e342bc849d5f8ed9eb6d6f',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '983b408199f28f9224e83eeb94526a19c4e65755',
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
