# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '88c5373ee4fb78888fa8c9668500bd1d03760ecf',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'f349c91274b91c1a7c173f2df70ec53080076191',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '1c6bb2743599e6eb6f37b2969acc0aef812e32e3',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'f0cc85efdbbe3a46eae90e0f915dc1509836d0fc',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '80207f9da86423ce33aff8328a792fd715f3c08f',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'a3b11f1fcc1f704b89a71ec1cfb1116173004a2f',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'e21dc3deb042f6354320222903214f491b7b6ad0',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'fce11d52fee0344bb10a098b0a398dff42cb5d51',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '98dea769721b40ed5402b35a84867f180d8955ef',
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
