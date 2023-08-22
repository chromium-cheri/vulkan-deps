# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'db8719ae079665ffab564c614b8614e56f325aea',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '633dc301350952a9a895c8db42eed371ea969a64',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'b8b9eb8640c8c0107ba580fbcb10f969022ca32c',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '2601f644eeb33e0c3a9ff97173a7df3aaa1c1281',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '85c2334e92e215cce34e8e0ed8b2dce4700f4a50',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'dd8332d253cfaf3a9be306af4194e4dffc2e3b3c',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'b441f434a036d6fe463ba944c8d7e0a9cd30faa6',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '8ec738d7571aa1e9c848450de942388e8326d6ea',
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
