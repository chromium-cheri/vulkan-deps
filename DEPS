# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '042aaea51616671cb9a9ae617637aeb90a5d79fa',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '37dfb3f45f4fc47c841f81e618c602f6f3de0f17',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '814e728b30ddd0f4509233099a3ad96fd4318c07',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '8c155b364ca8585b74c5541c9a238c2f24a0921c',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'a15237165443ba1ef430ed332745f9a99ec509ad',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'ef2429635dfdf3b9a91dc070368c536ac228b858',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'a01b76b1686f882e2a0ec05426ab2bff58580c92',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'dcd1e40ebb6c38e31f9847c299ea164af81c578b',
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
