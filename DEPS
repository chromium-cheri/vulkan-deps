# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '2fb89a0072ae7316af1c856f22663fde4928128a',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '0e2880ab990e79ce6cc8c79c219feda42d98b1e8',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '449bc986ba6f4c5e10e32828783f9daef2a77644',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '702e6af3800bb1799a66129c5c12c32dd86549b0',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '9e62d027636cd7210f60d934f56107ed6e1579b8',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '4e55fdb4d272c384dbad853c6c843e2d71e948a2',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '6c444b2c9f7b44fbfe246151d46f201cd1057000',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'dcb314106222d6c9e9251e9e2d85aa5c1bfe1f3d',
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
