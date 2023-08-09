# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '76b52ebf77833908dc4c0dd6c70a9c357ac720bd',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'bccaa94db814af33d8ef05c153e7c34d8bd4d685',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '124a9665e464ef98b8b718d572d5f329311061eb',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '13892fe8671ea6dd44c98bcee2980e204b42b0b1',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '450ead13e1064584da027d91192bd7bfb724640f',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'acff43362515f7714f8dfcd3740b0bb805997222',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '1d8188a974ccd08caffb5bd7fec58751e0c7d786',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '9c6d93cb01b31d8e8f4f31df5c0dfbe1c929c179',
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
