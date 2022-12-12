# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'c6b3f279a7aa5b37efa8b468332589c07c753805',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'c77b09b57c27837dc2d41aa371ed3d236ce9ce47',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '70ff9d939cd7fd0c758756ac57ab0c7c6d6c64d6',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '43c99b5ee087704a5ae0909d0ce7be3eff416905',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '9b48e83ef8c318739f38a07e4cd15473ff09ad86',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '96488e2b2e0dadd37e2caaa67f8fa010b2b1902e',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'ffa89a44472a60d05705bbfb61ef8376babe9a34',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '46f343d06003fdbdafa9d5c9d14a11a08006bc1e',
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
