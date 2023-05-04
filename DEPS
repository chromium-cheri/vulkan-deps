# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'bc6b2bc17adef055e540ac607aa2ce10916449d1',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '4faeb81f3fb489248a6b633ed2662271777756e3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '268a061764ee69f09a477a695bf6a11ffe311b8d',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '01055c60cfc0cddd2724dc674ed73d09df992360',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'bae9700cd9425541a0f6029957f005e5ad3ef660',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '22f10ad7b2e3b3c57377f7a9e40b5e5eeefb9332',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'ebf2caea656df8b0959487045dcdbb32ed5ba609',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '3e8236e9aefbbc6cacf575cb8e23547b9a7b92ea',
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
