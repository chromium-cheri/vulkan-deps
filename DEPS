# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '9aaba3766512bea5c7723c9c56926d232a9a730a',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '03b485dc47c6e84a15936601e8b121d84d8ddadf',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '1c9115b562bab79ee2160fbd845f41b815b9f21f',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'a8afbe941a1cf442dd3de3d474b1680a72fc17be',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '5a5c9a643484d888873e32c5d7d484fae8e71d3d',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'd4b42874cc2447aca1183a6a8fa8d6400e93b0f2',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '3af5fdabdd9fed697b01f18b1fad0ee00f86268e',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '86de0a0a9dc09520644bfb6b2f49e919134fe86d',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'd357f14c88e4c862e94d17bb7c79ac6bfd134deb',
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
