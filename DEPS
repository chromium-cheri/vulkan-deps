# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '9e41635d74f48fac0e1706cc4f3266defc76aea0',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b43c1a1e63ca7ac967c3b0e71ba29dbe08aa3dc0',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'f1ba373ef03752ee9f6f2b898bea1213f93e1ef2',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '4b6bd5a665ba0529747af3a0bc808732b7e78f48',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '6eee20744f23424ef6088167aae1b52dfbcc1385',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '6837a92c34e6440f556b6fdd3374e991b52b8267',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '6e7fa4d975f44f1050e554180636dca3fd51fb44',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '58ec88862fed4c658369efa655031272822352d9',
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
