# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '1e4955adbcd9b3f5eaf2129e918ca057baed6520',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '7cb2f62e3ba4d9acff27fea40ddc5a2844f39d5e',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '268a061764ee69f09a477a695bf6a11ffe311b8d',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '17a26b45ffdad78c3468f8ffdded3bcf24afa2bb',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '9e61870ecbd32514113b467e0a0c46f60ed222c7',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '6c787b7fb34a4b5f25d95d9d2cefdd4df38332d2',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'fec27a3f6e3bae96a8f3e784d6d643afb41989d6',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '6ac7a562eb311676e6325e54d8c18ef6ad6406f8',
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
