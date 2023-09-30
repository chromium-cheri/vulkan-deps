# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'b0ed4788858157e271779a7726cccc1149a05407',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '6e1fb9b09efadee38748e0fd0e6210d329087e89',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '79743b899fde5c954897b2694291002626358fac',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '1bc0e6f59abc3c9cd75f93baef47e9612a448045',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '7e691380166fb1cd9b193ac9db896bc23a4ea9ad',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '9e33cfc66f88c863e9a13492b8045ca28118ebbf',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '3a19c1973f0e4732b8f3746593aee2ac425ecb78',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'fd80ac354313d190eeaa33180ededa4de8c474b4',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '39234d2e19d67713cdf659d34912a66f99145a8f',
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
