# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '6d41bb9c557c5a0eec61ffba1f775dc5f717a8f7',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '5e512971183aa64040a49933994a3ab5003d1c10',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'aa331ab0ffcb3a67021caa1a0c1c9017712f2f31',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '987a5f1367e5db5b8eba82018b7250ec58606099',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '6c683158492d6b2d35fccab6dae784fef87eaf99',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '3ba0bf51633034bbac22da3c729ef2487ac98725',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '33f41f56840b063ba99f025c68af69eabc06d568',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'ff7cfc5327017330e508efe84e9a16fa2cbc8721',
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
