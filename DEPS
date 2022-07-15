# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '7e6b7c26a2a565c677b93f1c1769977cadced306',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'd8d051381f65b9606fb8016c79b7c3bab872eec3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '0bcc624926a25a2a273d07877fd25a6ff5ba1cfb',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'e2cf7693026bb53f5590193f8c2853d1b34d74d5',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '16847a61009f23b73b6de658a64e42926efc1ea9',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '30cb46bf7e52db51d43138c8128489ab36bcc4b6',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '8b603f8d06ac951c22f87545c8bfff0dffac81e7',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '427d39742fda764ed0727f2c36957c8eb84efcb0',
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
