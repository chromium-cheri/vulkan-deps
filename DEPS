# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '8c3dbb3596e552d8e89c16350b07373ac36262bb',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '1c9115b562bab79ee2160fbd845f41b815b9f21f',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '6c11c2bd46dba5b68bf62fc7d1195ebc7aa3694a',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '5a5c9a643484d888873e32c5d7d484fae8e71d3d',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'd4b42874cc2447aca1183a6a8fa8d6400e93b0f2',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'f24bab1ea1c521cd77991260cad1b11384eec5f0',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '86de0a0a9dc09520644bfb6b2f49e919134fe86d',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'fc8d7a55fafd65f3ab2148f4c7eeeb35ec36e00d',
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
