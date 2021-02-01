# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '5c4f421121c4d24aad23a507e630dc5dc6c92c7c',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '4741bbaa641d118ca1864094decd1ba977316161',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'faa570afbc91ac73d594d787486bcf8f2df1ace0',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'd61a7d110d93c244222364d67099bd3bbba1c307',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '9166a0677e4412edbdcc774bdcd7c74cefc74ae5',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '2b9a7b114eaae7387cc7e738a47a12c2b33685f8',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'a03938051ff67dac3e13dd011238fccc529e1fa5',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'aa59169d542d29c9511122fe101f3758dcc52458',
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
