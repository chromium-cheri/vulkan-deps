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
  'spirv_tools_revision': '5d3c8b73f70aecedbdeccbacdc4872507429f8b9',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '5a5c9a643484d888873e32c5d7d484fae8e71d3d',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '90b990e43ba591d7a67ceda16f4600a3dd7e3507',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '5a5e17fbcc09d189f8b730d042af4a2c79920cc7',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'b6f52799ec558808c7cad9522cf3b4fe75ee97d5',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'a76def3d2b6cd811da18fb5a99d97d0d37926323',
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
