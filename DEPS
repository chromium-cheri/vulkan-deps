# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '6624e1367309630b2f6df3cf93a5f864e89973f9',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '53d94a982e1d654515b44db5391de37f85489204',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'b42ba6d92faf6b4938e6f22ddd186dbdacc98d78',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '8a40f6de57d7b78bc431678d90aa8a570d1631f2',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '0873a22a11ec7e3f13762900ad0da39206189886',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '60d17fe6c65befa0a738b6c33da2eb0670055f3b',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '2ee12e8ba3b306b7e8aa71695cbe0e2ff451cf3f',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '81c943ed943f9c78d79ca1cc8efc9170ae0009b4',
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
