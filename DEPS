# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'fe82779952349597ae08416538c5ba05aa716c88',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b43c1a1e63ca7ac967c3b0e71ba29dbe08aa3dc0',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '51b106461707f46d962554efe1bf56dee28958a3',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'ec90d2872acbb4802661c9186a1e0fce8924e97b',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'cb7b123f2ddc04b86fd106c3a2b2e9872e8215b5',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '84b63d45489ed3a58c557d22381e5e1deffc0a32',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'e69a7c71c52c2e9316f4bd7f95af7a084a1a2870',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '4a151a50c174a89df875e0899117c47bedaa0940',
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
