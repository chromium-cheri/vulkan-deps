# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '2af597d1a84f62acee1fe4a63e9248548719756b',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b43c1a1e63ca7ac967c3b0e71ba29dbe08aa3dc0',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'f1ba373ef03752ee9f6f2b898bea1213f93e1ef2',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '6c7e1acc5f9921b9a609dce62f30620bd6855764',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '6eee20744f23424ef6088167aae1b52dfbcc1385',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'fdae336d4f701cfca867d97fc348ef44741acb26',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '9ded295c5b35ed21dab93b0227b1a9f49714758b',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '11831dcaf02d3538764024c271fd232e9eee43f4',
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
