# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Overridden in the parent repos (e.g. Chromium or ANGLE)
  'vulkan_deps_root': '.',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'c594de23cdd790d64ad5f9c8b059baae0ee2941d',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'f38cbeb814c73510b85697adbe5e894f9eac978f',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '05836bdba63e7debce9fa9feaed42f20cd43af9d',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '671914c28e8249f0a555726a0f3f38691fe5c1df',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '30e70cbd9850560cb55bffadb8017e90c04c42f5',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '02a49daeeeceb077e5ab8c80e87c22dcbb4a102b',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '0e8c2a5ca5f302f0137550bca1d8557cbaf87ad7',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'ce0450b9e8e54f0b8c6fff185166e1e42e0cf7c2',
}

deps = {
  '{vulkan_deps_root}/glslang/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/glslang@{glslang_revision}',
  },

  '{vulkan_deps_root}/spirv-cross/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Cross@{spirv_cross_revision}',
  },

  '{vulkan_deps_root}/spirv-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Headers@{spirv_headers_revision}',
  },

  '{vulkan_deps_root}/spirv-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Tools@{spirv_tools_revision}',
  },

  '{vulkan_deps_root}/vulkan-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Headers@{vulkan_headers_revision}',
  },

  '{vulkan_deps_root}/vulkan-loader/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Loader@{vulkan_loader_revision}',
  },

  '{vulkan_deps_root}/vulkan-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Tools@{vulkan_tools_revision}',
  },

  '{vulkan_deps_root}/vulkan-validation-layers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-ValidationLayers@{vulkan_validation_revision}',
  },
}
