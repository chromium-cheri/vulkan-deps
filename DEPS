# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '4aa56496d6e7428e07b0a614da6aa5428ff87587',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b43c1a1e63ca7ac967c3b0e71ba29dbe08aa3dc0',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '51b106461707f46d962554efe1bf56dee28958a3',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '35d8b05de4212276d03a5d67201398fd49849896',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'cb7b123f2ddc04b86fd106c3a2b2e9872e8215b5',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '220a00bf952328dee273fff1e8f61b158c26dc0d',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'ed6820d508fd24b1a50166a600dbf7ee8300e9d9',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '86e69de0b4a6ad5401e03f70dbbbbc9bd7829d68',
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
