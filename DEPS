# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '604904fb931ad90a25001a4a22477e9a832e64f8',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b3ff97d0feafd2b7ca72aec7215cfc3d0998fb79',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'b765c355f488837ca4c77980ba69484f3ff277f5',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'c26712784629f54c71b84b07bf161eabc0342ebe',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '245d25ce8c3337919dc7916d0e62e31a0d8748ab',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '2d1565377360833be414d49fc39c4d23f71a9f89',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '6be9971a3737857d91d199a9b8df09471f477d47',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'ac73fbe123d0cbe2c93c3939f9c1331774e53ae4',
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
