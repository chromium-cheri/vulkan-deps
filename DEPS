# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '9c7fd1a33e5cecbe465e1cd70170167d5e40d398',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'fc9bee27f445644635e83ef111ef54944bb6e3af',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '7f1d2f4158704337aff1f739c8e494afc5716e7e',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '6110f30a36775e4d452968407f12b16694df2cc8',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '870a531486f77dfaf124395de80ed38867400d31',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'f035e57c171ce9009f2c47b5488a66c653843501',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'df10a2759b4b60d59b735882217a749d8e5be660',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '646992d284be9528bcf78129a1db6c652f50682f',
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
