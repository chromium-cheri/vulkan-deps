# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'b9ba4c5743997abbc0df858f2458a86d62af6a25',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '97a438d214b24e4958ca137a18639670648cedd0',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '19e8350415ed9516c8afffa19ae2c58559495a67',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'b46995741b97c714e211fe5df8590991ae998475',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'fa27a13cf74080df2ad421a788299db1276f17a7',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'aeffbbd6b9075478c932b1d244f8f221d80a07ea',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '6ca43559e0eb9b23e59e9a978adf58cc6214d20f',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '51279399eaecf651d176544d8197f91f48637b2f',
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
