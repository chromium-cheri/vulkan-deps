# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'abbe466451ca975fecfdba453ef9073df52aefc5',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '0d4ce028bf8b8a94d325dc1e1c20446153ba19c4',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '4995a2f2723c401eb0ea3e10c81298906bf1422b',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'eed5c76a57bb965f2e1b56d1dc40b50910b5ec1d',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '628eaec640e117b859cfd80e4b1abb2570e08ccd',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '469aead205e9a097b7c2846bd2de1fa73d37c85f',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '0265f2e00b5b35b2629ab80c9a9b3bd0f3098a94',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '68d43d39159d4b2334a9ede71259605cf3761b4a',
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
