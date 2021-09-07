# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'e0771b5d4c7e64a4354e1aa93fb2a673b2a08010',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'c2500e504d2b823d73d2f129e4f4f050e9618ecb',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '6cae8216a6ea19ff3f237af01e54378c1ff81fcd',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '7e860e3831439fe7f1e601766d3ad8374aa8a78c',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '4fee3efc189c83ccd26a9cd8265185c98458c94d',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '371000152173a9ef199d50103ec35b9e8d160578',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '967dbb875111a187109a0cf79eb08a6ca7f35e92',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '88c0e399b743292c8dcf722d8b11cdb714a3321b',
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
