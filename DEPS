# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '9575e33186c74a68831c469f7271edf386ea43a5',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'aafcc207ea82308722124db2575aa95f42cb99c9',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '3469b164e25cee24435029a569933cb42578db5d',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'e090ce9c40fb484b24a8f0e5735eb7629661c06c',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '9b834aa4436b880a43e0bcc8cd8161d2906929e7',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'a1d9d485ce1a66adc9a584ea79bc3829203863b6',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '247c806c93c720488daa0bc86acd5b6f3a0e14f9',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '8ce6ecc9c911345ee8254a9e0d11da54341679f5',
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
