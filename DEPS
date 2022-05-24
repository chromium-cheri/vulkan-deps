# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '86ff4bca1ddc7e2262f119c16e7228d0efb67610',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b3ff97d0feafd2b7ca72aec7215cfc3d0998fb79',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'b765c355f488837ca4c77980ba69484f3ff277f5',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '98340ec500e92a534dc8384d5c45d2f488e40f6a',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '245d25ce8c3337919dc7916d0e62e31a0d8748ab',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '2e5d77b6ef57619a23ab448a4c1b5c58cd1903ea',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '689140c20446ce8b1a7dc8f4ca553d49bb4d53a4',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'a7b92cd6ed0d8dc9b25e61a36e3980f8759b08eb',
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
