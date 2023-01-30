# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '4e9cde50bb76c2b941b2edba8a073c70476e698e',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '199d0cb8a9a5dc6ec5cbb45088413aae04493cb8',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'aa331ab0ffcb3a67021caa1a0c1c9017712f2f31',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'fcfc3c580c75be90a33711dd894dec58ebde9eec',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'c594930fa4fcf5db80808bbe5931bd3276fecd99',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '11883676188f55a15c76433ba9eb02abb3384c5b',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'df9d118bb17ee04398036e2f9bb69fe8bd219c23',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'f4a429fe01ccc4f12b4ab69f3efb68e688ded1cf',
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
