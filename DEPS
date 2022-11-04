# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '5e08deae050c4a6d5b2ca92cb6cc52ccc5259bea',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'abc31207bffbc1bef4192746af44b3be1abcff17',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '747031e10dea9e6c5651bf11957a9dbcd379fa47',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'c8e1588cfa3ff9e3b5d600ef04f4261c4e68af90',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'd4c221772cb222117446521517254c91f9211801',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '374dbe9df7bdbaeba5edeadb3d4fc877a16047a3',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '6e5bd86b76c092fcd5d8a873260a8a96f43705d5',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '9a31edfa80d5c5c85b238a0ec3963320fdfc91f0',
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
