#
# Copyright (C) 2018-2020 Intel Corporation
#
# SPDX-License-Identifier: MIT
#

set(IGDRCL_SRCS_tests_gen9_bxt_windows
  ${CMAKE_CURRENT_SOURCE_DIR}/CMakeLists.txt
  ${CMAKE_CURRENT_SOURCE_DIR}/test_device_caps_bxt_windows.cpp
  ${CMAKE_CURRENT_SOURCE_DIR}/hw_info_config_tests_bxt.cpp
)

if(WIN32)
  target_sources(igdrcl_tests PRIVATE ${IGDRCL_SRCS_tests_gen9_bxt_windows})
endif()
