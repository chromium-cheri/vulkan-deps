# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '3f04389a1806c74355236ecd0a2493d701b19d87',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'fe1af2ae72d8de17954757a91bc4dfdf79209c30',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'ae217c17809fadb232ec94b29304b4afcd417bb4',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '134d763f4593f823b5438cb856eb905904fa5756',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '31dfaa4c632eec61f273f87d920237f0c7163dcf',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '75431e4b1f9a19835d994a66be24b303278d2d0d',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '75b3bbac3e1f2c0dafb62c2a61420bbf2879d6b1',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'c872677e3d295d6128c5a689329632455364192b',
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
