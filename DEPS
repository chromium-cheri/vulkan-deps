# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '2fb89a0072ae7316af1c856f22663fde4928128a',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'd6fe75df106c62770159fa94985807c2784cd271',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '6cae8216a6ea19ff3f237af01e54378c1ff81fcd',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'bd3a271ce3fcc8b9ed8e6eb2e94392d1b220adc9',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '9e62d027636cd7210f60d934f56107ed6e1579b8',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '140738f852b369ecc387e9c031edaa15ebfb10b0',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'cf9d49e46157b4c2a0dcf3051679d550c5fb20a1',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '04bdaa2c45471a00a0cfde65dee5a735e0d6aa55',
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
