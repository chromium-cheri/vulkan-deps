# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '2742e959347ae2fac58acd0d022c92a0ff1f24bf',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '1a36968e5d92e08ba38335ad00701da21c627a13',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'b42ba6d92faf6b4938e6f22ddd186dbdacc98d78',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '845f3efb8a4eb32e5f484aa6ea9b9e3716d6f7ec',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '1dace16d8044758d32736eb59802d171970e9448',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '7df1967e402c4a13efb150557294cc3ad4e3541a',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'bb32aa13d4920261b5086219028ef329605d0126',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '54c295b067de5531867a842b4b3579ee1d3c8545',
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
