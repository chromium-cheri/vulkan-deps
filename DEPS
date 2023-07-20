# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '77417d5c9e0a5d4c79ddd0285d530b45f7259f0d',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b43c1a1e63ca7ac967c3b0e71ba29dbe08aa3dc0',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '14914db17a1fc16e06c4e49e5353bb80b3267e9c',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '45f7e55af442a765c1a74994ffb79688d2e7437e',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '6eee20744f23424ef6088167aae1b52dfbcc1385',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'fdae336d4f701cfca867d97fc348ef44741acb26',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'c5ac1413f0108d111160711b00eec61c81c5e293',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '4f0c069b937ab229815f25bec06c17baef4066b1',
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
