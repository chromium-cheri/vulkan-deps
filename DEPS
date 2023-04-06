# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'bdba39bae63802c75a577cd6b753385f8057578b',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '3327924addfcffe8f1a4119cb09c1ad353fe1190',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '29ba2493125effc581532518add689613cebfec7',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '048faf2e530ff398d4e0700867a4734dcfe9c983',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '63af1cf1ee906ba4dcd5a324bdd0201d4f4bfd12',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '8c8619df2dfb693d8ce4d5b1904a4b7694d45fbd',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '6b0935cecee90ae9c6b42c43f663e793c68fc67d',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '4ee65679bb24a86437477630e319c88cbf3ed7b6',
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
