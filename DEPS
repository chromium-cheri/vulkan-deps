# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'fb0e4983e44de7f4933a60acec467a8d600247c1',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '05ac99ae2310bbfbbc3e28895dbc3159e4f5033d',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'ae217c17809fadb232ec94b29304b4afcd417bb4',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'f125452cf8fc3d359a388402812cda76ca167c98',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '31dfaa4c632eec61f273f87d920237f0c7163dcf',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '393e75ebc44e6bba44dd52d290c5cc5d799e7969',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '75b3bbac3e1f2c0dafb62c2a61420bbf2879d6b1',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '4fe8edd7974b474e8d4773d0ce788bb1e6d5aa62',
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
