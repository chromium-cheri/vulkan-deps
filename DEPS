# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '68935bc2c68a520dfaa8b2c11a7ec181d17c683e',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'a89dea3c499b1e322b39c7e6127af2777c4aa49b',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '34d04647d384e0aed037e7a2662a655fc39841bb',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'd87f61605b3647fbceae9aaa922fce0031afdc63',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'fc90b60663965aec582d5bf7965f4e6b15173730',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'bf28c824b820eda6ea3286b301329d59686c4149',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'dda9ae0f9113ad3816ba5f84e1a59b1529e82630',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '4b0639f215f70ec127e5e611497aa6799325d0db',
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
