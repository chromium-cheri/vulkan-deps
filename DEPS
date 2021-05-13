# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '202c8abae0a3cb1ae725b3c97e3be3b24d1dadb0',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '418542eaefdb609f548d25a1e3962fb69d80da63',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'bcf55210f13a4fa3c3d0963b509ff1070e434c79',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '18d45142e7a24070eab85982fa451a0d33f4c62b',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '9af411e83fb08cd2bddc3ec771de89416a96cb91',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'a132dee142c0d6bf54d09d50ed7fff28f4b491ef',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '1d176506710c4fabda4e0c4844b1f4ff77e106b7',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '2e2e61e6aeb434d7d661a1fb54e1e542b01cd52b',
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
