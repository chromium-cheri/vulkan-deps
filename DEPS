# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'f9b760e6c73bca9cba4b8a7e8d18993b89d62dd4',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'a89dea3c499b1e322b39c7e6127af2777c4aa49b',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '34d04647d384e0aed037e7a2662a655fc39841bb',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '6b2318aec8d4e60386669da1281074a23d5f5ac8',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '75a6b83f213da085ba33b82f053b956219a48730',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '96488e2b2e0dadd37e2caaa67f8fa010b2b1902e',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'dda9ae0f9113ad3816ba5f84e1a59b1529e82630',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '3784a0d8b8a5121b9f17ba58a8bbc6138ec59a48',
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
