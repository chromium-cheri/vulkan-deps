# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'c43008e82993b460944533656a1d4a4467aa17af',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '09e60d74f6a1c8deed2c02c998661b2ec7dd712e',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '90547c54e24e01aae41a68124e7a304d0ec11dd0',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'b4e0850ef75cbf4f3e3a2340f4ee4c654a81d604',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '9b9fd871b08110cd8f0b74e721b03213d9cc3081',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'd72476300bedea334aa764c994dd191cb6d7088b',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '2062010d6119cb050376bd72ad634c993efb7aac',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '19bc01cc206036fb7277f0742f836f3c9def4011',
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
