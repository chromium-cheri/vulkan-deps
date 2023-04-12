# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'a270fdae552489950604ef2971a703639d6bc946',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'fc9bee27f445644635e83ef111ef54944bb6e3af',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'cfbe4feef20c3c0628712c2792624f0221e378ac',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '31c546e316592b6e394a8fc55f1e9f91a0df9ac2',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '63af1cf1ee906ba4dcd5a324bdd0201d4f4bfd12',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '8c8619df2dfb693d8ce4d5b1904a4b7694d45fbd',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '4e17c284d67de468d62ec79fb0b4a3eff76447ea',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'd3e1a08df96a21331a918902e8ce55bb96877358',
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
