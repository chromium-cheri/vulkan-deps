# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '4b7b86d568b40f4b076259dc2fc4cdd006340f34',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'be3988b13cb73dc007cab9291e7ce3b3456bf7c2',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'ddf3230c14c71e81fc0eae9b781cc4bcc2d1f0f5',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '2299b710de6cac0e883b5e4d5ef231ba8c01a9d9',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '0193e158bc9f4d17e3c3a61c9311a0439ed5572d',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '7033871e47d66a1e978d882b6262bdad116f2c16',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '8b86fbac17b9f990f653f534e9cc57b34c5572eb',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '5bdd45ecca5f39d4499e3ec2688c626b14399810',
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
