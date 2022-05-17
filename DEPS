# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '2f5bc0b7414f5d063b9c2fcf231469aec1e549d3',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'd0c8dc30450351321e611b2888a48f8410226a4c',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'b765c355f488837ca4c77980ba69484f3ff277f5',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '98340ec500e92a534dc8384d5c45d2f488e40f6a',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '1b4f46a3cc698eff1eb76aa2cd5a05736cd16857',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'ad05e878ee8309cfaac62f869f9d4f6431471321',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'a9bee4cbb2fcb6dc38ef2424711225f8abb2d941',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '0f5044267aae488f152ea170b55f5ee2945c350a',
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
