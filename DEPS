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
  'spirv_cross_revision': 'e4243b898ca5e1e19e48725a991ada1e5744691c',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '19e8350415ed9516c8afffa19ae2c58559495a67',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '35fd0e17d081b28a0ff15b376329205c20c7d1f8',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'dd99e0f51fa86210da384d0f17c036fa45475e12',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '61688e09fecf7f8b7749644110be9a806d4b0f4d',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '7001f2eb37d151c5fec082e6b1a683cf7c6d85f9',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '3c5dee2b6cb6cf8dafbbe9531d9a0ed56164a76b',
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
