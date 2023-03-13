# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'cd2082e0584d4e39d11e3f401184e0d558ab304f',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'd26c233e1c2629fec1ae1b6fdf538958e5d52bff',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '1feaf4414eb2b353764d01d88f8aa4bcc67b60db',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'a1f5556517e5d1d24b5282295e067db3634f96d7',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'd732b2de303ce505169011d438178191136bfb00',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'eb130942545f2d0f434fd310947ca787fcd9a7dd',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '5bcfa1605e110150710170bfe199aa60e7f048fe',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '6d950a35557401adc0a37187476de55334099a2e',
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
