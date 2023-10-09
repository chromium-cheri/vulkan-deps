# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '277d09e679f0f4d9469c463c00cb11c6a040e65f',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '37fee00a71b5a47247c1cf20256a3f794537c6c0',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'e867c06631767a2d96424cbec530f9ee5e78180f',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '933db564ca660477b360480b8a1d7589d7c6694e',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'bbe0f575ebd6098369f0ac6c6a43532732ed0ba6',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '520eaa5a525adce0cdbdc7b8c7f7d8f0375340a6',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '730234d8e46f6eea3622a4a90a1f4ce537cf2321',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '9e088360b535a22d3ba8c7400ec5c5ec5028c998',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'f850358f567c84f7d604379d09b208cbc8e5c8fc',
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

  'vulkan-utility-libraries/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Utility-Libraries@{vulkan_utility_libraries_revision}',
  },

  'vulkan-validation-layers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-ValidationLayers@{vulkan_validation_revision}',
  },
}
