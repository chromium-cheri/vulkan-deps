# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  'chromium_cheri_git': 'https://github.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'a5bf69936ddebd45370c2e2c392b4b6f26296bad',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '12542fc6fc05000e04742daf93892a0b10edbe80',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'bdbfd019be6952fd8fa9bd5606a8798a7530c853',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '6cda1525981c4d4e58a4a4ff30f6749d1a8d428c',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'baf6b7cc8fa2080e59398f39dfcd343ca95d3bf7',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '538d8ee5162f1da4188902aceecd906bfed3088e',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '80b010b1e1b08c1f092fb2bfa337faadf8ea1ba3',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '69915053427de929ac1e659a8c834f37dc2181db',
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
    'url': '{chromium_cheri_git}/chromium-cheri/SPIRV-Tools@{spirv_tools_revision}',
  },

  'vulkan-headers/src': {
    'url': '{chromium_cheri_git}/chromium-cheri/Vulkan-Headers@{vulkan_headers_revision}',
  },

  'vulkan-loader/src': {
    'url': '{chromium_cheri_git}/chromium-cheri/Vulkan-Loader@{vulkan_loader_revision}',
  },

  'vulkan-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Tools@{vulkan_tools_revision}',
  },

  'vulkan-validation-layers/src': {
    'url': '{chromium_cheri_git}/chromium-cheri/Vulkan-ValidationLayers@{vulkan_validation_revision}',
  },
}
