# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '36d08c0d940cf307a23928299ef52c7970d8cee6',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '2de1265fca722929785d9acdec4ab728c47a0254',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '4183b260f4cccae52a89efdfcdd43c4897989f42',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '5bb595091b3048d20afeb37a9a193350dccd607d',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'f4bfcd885214675a6a0d7d4df07f52b511e6ea16',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'e0423d550ece88bdec05c1968cb9fd4bfa3f748b',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '58eb5fd87d6b60e7766ebdb9160662334d0df6b6',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'f56dfa0fe04ba25f7c7a6c851c128e15012d25d9',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '1e113e4cbfdfa2930ab29dc0e453e9974155dbae',
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
