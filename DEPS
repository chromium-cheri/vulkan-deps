# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '88fd417b0bb7d91755961c70e846d274c182f2b0',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'edd66a2fc9e932ad0d3dce78f2627eeae91c2660',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'c214f6f2d1a7253bb0e9f195c2dc5b0659dc99ef',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '8ea3ae6be2b2409e6c44eba3c17006e2fa0845f2',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '29c0457cc167bfc9e9361a3818440e388986f5b5',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '27d86008d87581980c3c61730d8a44acc7e49ff1',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'c4839afe758d3c8fb5c46792398509b4fee0a28a',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '0f839617e939b5cf2c406fb00b1ed4533f695d71',
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
