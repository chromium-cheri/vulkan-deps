# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '2bfacdac91d5d9ba6bab7b4da52eb79c2300cd45',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '6e1fb9b09efadee38748e0fd0e6210d329087e89',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '79743b899fde5c954897b2694291002626358fac',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'ee7598d49798e7bf34fabe55b5a438a381d450c8',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'df60f0316899460eeaaefa06d2dd7e4e300c1604',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'c47c78c8fe980350cff91d0c3879049766d3a72d',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '04b4832c8790c32ea15523f4adb219a04a6adbc7',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'fb09bb3bc4e27a1f9dd2d9db735296340d817a03',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '98abcb5eebfb2b4c29122ccbdf693fc8b08a5942',
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
