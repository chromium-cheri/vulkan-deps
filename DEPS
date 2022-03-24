# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '6d937739953b871453dbca46d91268901ac51b85',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '44691aa9754d9db9f8c0828e5ca6d2909c671200',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '4995a2f2723c401eb0ea3e10c81298906bf1422b',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'cab0b7715a951d5b542980fb1f7503b8d449a256',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'b6554a7ff352dcaba44c1a1a7fbfd8b54dda4136',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'c03954e124347b3254773c22ed868e9c7fb6cc2c',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '3758a53671b0cb16a74b6780609e58be4741ad9e',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '32a8a87308b3180a4689996eed1cd2574cc4d09c',
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
