# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'a36d91e5acdbcece9c3ea3186fca185199827797',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '60aa24566e0189a83797abb7c3d0453b20e5f1f8',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'faa570afbc91ac73d594d787486bcf8f2df1ace0',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '5d8c40399e1a483c168246215e4637e19551cd4f',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '89d366355e6fe1221c9be40bb2cf3716449e9a7e',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '1353e80d87b4dfdce64d735b930983c21676b166',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'd1cd2653949dff9d6da6ca2a9b422350ec288f8f',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'be60dd27b119afa5cac6f0cc8c4123b25e9c33cd',
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
