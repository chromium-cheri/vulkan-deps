# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '7eea61b5a3e197b92bda6d0ae3563a19082e030e',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '03b485dc47c6e84a15936601e8b121d84d8ddadf',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'ae6a8b39717523d96683bc0d20b541944e28072f',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'ef2f4323640beddf3bab855c5535b0c3e8c7d878',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'ea45703effcb01df0856628286f8a890dd313ecd',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'ca4c1e6e42e511e4f71bb3b168738845ee56b5b7',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '7c6d640a5ca3ab73c1f42d22312f672b54babfaf',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '822dd7f3a6b71fef472e26406fb93900e5ed0a7b',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'f7b510ffada10c5c7fe6d3774a6e8c82980c5c3b',
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

  'vulkan-utility-libraries/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Utility-Libraries@{vulkan_utility_libraries_revision}',
  },

  'vulkan-validation-layers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-ValidationLayers@{vulkan_validation_revision}',
  },
}
