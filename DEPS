# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'db4d6f85afb8cf6aa404a141855f556d172c1ed2',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'd9f4280f4511e9bff9bdd5147370b9ee49dbe2af',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '1bfd27101e4578d0284061bdf8f09fb4755c7c2d',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'c7affa1707b9c517ea028bf9070c97e6842a6749',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '80207f9da86423ce33aff8328a792fd715f3c08f',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '2aa686f45565b0a5bd74ab3b447833b26d708bad',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'e21dc3deb042f6354320222903214f491b7b6ad0',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'fce11d52fee0344bb10a098b0a398dff42cb5d51',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '474888add4e4d174a0be0a3a61ff56f8c14abbdb',
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

  'vulkan-utility-libraries/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Utility-Libraries@{vulkan_utility_libraries_revision}',
  },

  'vulkan-validation-layers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-ValidationLayers@{vulkan_validation_revision}',
  },
}
