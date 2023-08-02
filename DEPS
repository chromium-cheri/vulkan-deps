# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '396596ca4a5fa12872783505568aac9c6bdd9d1d',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'bccaa94db814af33d8ef05c153e7c34d8bd4d685',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'ae89923fa781650569ca15e5b498a9e4e46ee9c9',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '47fff21d526c907a782550a39daf3931ec803e2c',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'a3b683653e6a498514ef8a1865594810e91c594c',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '0ec23bb3518ebdf026b379d9b2a58ef9bc5711b7',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'adf8532bc503066a9c4cf8ea30cc0f8217044f0f',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '7aabb7cdd79a621d07c9ae3e1ab17384a830fbf2',
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
