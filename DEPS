# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '728c689574fba7e53305b475cd57f196c1a21226',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'c77b09b57c27837dc2d41aa371ed3d236ce9ce47',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'c214f6f2d1a7253bb0e9f195c2dc5b0659dc99ef',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'd9446130d5165f7fafcb3599252a22e264c7d4bd',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'b092b2fccc812453c1d0ec0a829eb8f34f174803',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '76529312e0b872e86f60519243ee66a209461996',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '0a122e62b8f62dd52b7731b58c1385312f2834aa',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'c8b044ccd7b5292948b2a92921813b244e978a85',
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
