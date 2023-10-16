# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'fd1f96d2020496760290e5cef5d68ae83e5dd5c4',

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
  'vulkan_tools_revision': '1532001f7edae559af1988293eec90bc5e2607d5',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'c9ca4ac620a238a93c65d864f2eaa33954d74509',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '48c6a2941043c6ba41396f035c9f74b6f2f68d99',
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
