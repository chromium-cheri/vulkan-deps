# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '65397339c5033cc612519a29f3896bbd3dcd2d08',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b43c1a1e63ca7ac967c3b0e71ba29dbe08aa3dc0',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '51b106461707f46d962554efe1bf56dee28958a3',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'd52c39c37d4d7aece12e6177203cc3d733e8b772',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '9c37439a7952c204150863fc35569dd864dbd599',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '4854d84904676676a90885e4100ad4b690366b51',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'e69a7c71c52c2e9316f4bd7f95af7a084a1a2870',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'a65eb0e392aca7f7e8fe7642915a7498574ac22d',
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
