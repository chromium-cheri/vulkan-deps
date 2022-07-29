# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'f0ce653a25726000d4f37d94de33b95f942ff657',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '0cccd0a65a67f33922f8d0742b5930fd15353fa7',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '0bcc624926a25a2a273d07877fd25a6ff5ba1cfb',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '8dc0030ecbf8109c802a9919c378948c68042a2c',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'ff92049ebd7e2f7013bb9d3b0450097561cee352',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '0bcddf345feb45e19441025de6a256e19b44f88d',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'e734be0bb5aed1e542fad19ba91e93e1812de0ee',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '2f5947d981e354172778d8448c8ea8f91ccf5e5e',
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
