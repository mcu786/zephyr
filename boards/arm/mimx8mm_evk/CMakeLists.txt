#
# Copyright (c) 2020, Manivannan Sadhasivam <mani@kernel.org>
#
# SPDX-License-Identifier: Apache-2.0
#

zephyr_library()
zephyr_library_include_directories(${ZEPHYR_BASE}/drivers)
zephyr_library_sources(pinmux.c)
