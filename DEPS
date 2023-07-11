# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'eaa705776839225b506193bba7daf44360a3c264',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8e742c91ba47eb3238c939ee11ec9ba2ba247bf',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'd0006a3938d7acedffb26ab517fe3e95b5288cc6',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '0530a532fc7a21c2065042580f3e3f6102dbdebf',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '2565ffa31ea67650f95f65347ed8f5917c651fac',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '8b94e87bff136d1d1e4a076c2d3ce8e09ba71546',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '6e7fa4d975f44f1050e554180636dca3fd51fb44',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '0f12b9d4e2f712bf5f7726a12b5d3137ba643e9c',
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
