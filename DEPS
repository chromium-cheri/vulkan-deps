# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'a9a262541601fd08cc30a9a449dc7fba82303980',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b43c1a1e63ca7ac967c3b0e71ba29dbe08aa3dc0',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'f1ba373ef03752ee9f6f2b898bea1213f93e1ef2',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '6c7e1acc5f9921b9a609dce62f30620bd6855764',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '6eee20744f23424ef6088167aae1b52dfbcc1385',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '1bb7cec71caf3cada50c554da8dae7c40771755f',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '9ded295c5b35ed21dab93b0227b1a9f49714758b',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '02ce5a81fb2d3eb582404f37f7a0b814a2b31a1b',
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
