# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '9e78bc8108a13d4d4ed860b2c5547092059ed83e',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'c93ee9261ed38be0b37b7cc40e2c5c47eaf5615d',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '93754d52d6cbbfd61f4e87571079e8a28e65f8ca',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'd51dc53d2caf25024c7721647ed2a23819bd509c',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '715673702f5b18ffb8e5832e67cf731468d32ac6',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '095a7bf60b22bf595e9866441059057c56086b52',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '77cf67df0795d0bceb51fe6737b4c9aed6694572',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'd8c7808f8716798fdb10cd4fd24f4cc46c669f51',
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
