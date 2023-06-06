# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'a6662c53ced629a9d94611276743cbcde896b6af',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'a20fc9ac5819666d97f5ba3d5d5aad02e133039b',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '8e2ad27488ed2f87c068c01a8f5e8979f7086405',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '5ed21eb1e2f4b11dea5c840fc6c2fe805ed751f1',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '605dc6d3e789630d24310435121cd0c7d51b6483',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '711626c27223e55c4993622ace70351e3fc2d7d6',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '2c83dd6cb2ef710bab843b69776997d6f2c12ba4',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '1b23b771d8ba76084cf70a622d3528115933449b',
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
