# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '51b86c1a2b77f612293abe0a86425e82353ac3c1',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '5789e3eed9bcfad6edee7987ec825e3ac5811cd8',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'faa570afbc91ac73d594d787486bcf8f2df1ace0',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'c79edd260c2b503f0eca57310057b4a100999cc5',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '1d99b835ec3cd5a7fb2f2a2dd9a615ee2d1f0101',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'c5678a03db383fd0dc5bfb8e9a383043bdbcb57b',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '6952dfcc1df5a0f41dc55a168d87c10942f66416',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'c62432713f23faa066923f421d8bf5b04d532a55',
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
