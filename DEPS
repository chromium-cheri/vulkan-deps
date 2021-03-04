# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '159b05708055fdb7cb2f01005d7c35545be6852f',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'd57ab68a219831900fa2b8a3bd529413e01f3b9f',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'faa570afbc91ac73d594d787486bcf8f2df1ace0',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'f7043c0de6712bc9afa8beabe0d10dcb40b1811e',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '4fe5828a0295a3c29a266e446ac6a6b51d768e48',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '237d3dcb5c67575db335bbc226c8fff23925bf49',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '461b33cfa2726ed65fdf3308d0303ae18a879c49',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '0ec2c7a6935ac58178f4099b3087f73b34701ad4',
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
