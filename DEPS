# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '43d40e80adaf6f1fa04c0c5651b7167fd4523e55',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'fe5a0aa72fd855d03f16ff7b93de95722be5a9c8',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'b8047fbe45f426f5918fadc67e8408f5b108c3c9',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '8fda47ca08cff2494e068745aa0619280113baf7',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '0873a22a11ec7e3f13762900ad0da39206189886',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '1fb56971c5246ac1e1ca0ebe3ee5dc84d15cb711',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'd15ff77bda1ef895ea5cf23d19472b7442e878cb',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '8c380b92c500e8b693c40cb6292a42881b2b6235',
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
