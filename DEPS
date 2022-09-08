# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '7757cbebe45296d4ab9182525e1fcc1c4a4caf31',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '210a80013067672b52847ec7aa70ff78b2f4d77e',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '87d5b782bec60822aa878941e6b13c0a9a954c9b',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'f5b27b6513afdfbe923f10336454e0d6c467031f',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '88ebcb08cb131ca278af6e7a26887fe59b25ec1c',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '23043a5c87029fbd662fcdc992a8f0fd8c318437',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'd9f4641f9006f96def1376774be6f6403a56712b',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'dd32ac341e8e775e3e95fc1380be4494b47925c4',
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
