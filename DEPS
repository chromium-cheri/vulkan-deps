# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'fb2882a3c34fe451d0d22fbaabef025a8c6f77b9',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '54997fb4bc3adeb47b9b9f7bb67f1c25eaca2204',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'd790ced752b5bfc06b6988baadef6eb2d16bdf96',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '47b63a4d7da04ae8d3f50a5df560c4b879308257',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '4f51aac14f65629dfe83702b806f740dbd7bd701',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '7eb9da1e5e9f261c50eefa727ac010ff23f851f1',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'e50622314dfc8efa00e2e5f824a63464f1a94665',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '6710b67cde2f56074e5757426c65eaba70078939',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '53da55c4832be4dfc1e5bcc10841e8d148f8fb71',
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
