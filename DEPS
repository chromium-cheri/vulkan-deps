# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '204812694c6e6338d24f40c507335062463db5d5',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '7512345f61e5f9b543ebb87df678f3fe7735587b',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '295cf5fb3bfe2454360e82b26bae7fc0de699abe',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '3033cf428e6de3e5766f85caa9dbaab0f57a51ea',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'a3dd2655a3a68c2a67c55a0f8b77dcb8b166ada2',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '3db19f3e3d8b0c96dc1ffcb5888c06e306df478c',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '5bcfa1605e110150710170bfe199aa60e7f048fe',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'd61b1d713a4a502ce91cf62a794c438e05636d02',
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
