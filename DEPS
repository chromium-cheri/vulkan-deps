# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'bc6b2bc17adef055e540ac607aa2ce10916449d1',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '4faeb81f3fb489248a6b633ed2662271777756e3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'f7e1a2ef5630417e70a6286011edf9a6e4b725c3',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '2189ad7a5aadc2accb9250a1e7ed08e3b49df01b',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '870a531486f77dfaf124395de80ed38867400d31',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'ab6f4023be659a23e9cdc8c04e64316a1c429301',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'b647be6419696dac2f5e009d7e27913d987f037b',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'c15c9d7b24fc8a640fe2564f077beeedb4df1826',
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
