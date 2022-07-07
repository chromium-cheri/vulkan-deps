# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '503dd243782ce6793c04eca551feef1985e3dcf1',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'd8d051381f65b9606fb8016c79b7c3bab872eec3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '0bcc624926a25a2a273d07877fd25a6ff5ba1cfb',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'bc5c8760af8375a0e92ee3318bda15ed9a165ef1',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '9f73b931f402f23554a60015924e7e35c7047487',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '9ce0cf688b753a94478f0477bf50e89ee8b47ca6',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'ffc961dbd741a7891c96196a67246fc5cb16a5b2',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'c9ceaf94e88b63f723d9c7c1fd28e3d247f8b45b',
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
