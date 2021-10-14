# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'b9ba4c5743997abbc0df858f2458a86d62af6a25',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'e4243b898ca5e1e19e48725a991ada1e5744691c',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '19e8350415ed9516c8afffa19ae2c58559495a67',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '3e6a85303dfb72d8768da651da946913bac6f05e',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'dd99e0f51fa86210da384d0f17c036fa45475e12',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '6d9e5b07d6623d17070169c12fe8cc8eaca4274f',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'e8b24f02d17dde8ba703353aa21ed5b08ca32f3b',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '14940720ac85cdc400b4da5a197feb6c321db78d',
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
