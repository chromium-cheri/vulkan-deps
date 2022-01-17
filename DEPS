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
  'spirv_cross_revision': '08d5f5ed181f489e77f94d168071fb5605f2792a',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'b8047fbe45f426f5918fadc67e8408f5b108c3c9',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '8a40f6de57d7b78bc431678d90aa8a570d1631f2',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '0873a22a11ec7e3f13762900ad0da39206189886',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '0fd1cf08c9b10db8f7de99290b4eb88662112725',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '2ee12e8ba3b306b7e8aa71695cbe0e2ff451cf3f',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '15ed1f653004a7b2936f71f8643851ba1011d954',
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
