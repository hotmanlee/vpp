# Copyright (c) 2018 Cisco and/or its affiliates.
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at:
#
#     http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.

add_vpp_plugin(stn
  SOURCES
  stn.c
  stn_api.c

  API_FILES
  stn.api

  INSTALL_HEADERS
  stn.h
  stn_all_api_h.h
  stn_msg_enum.h

  API_TEST_SOURCES
  stn_test.c
)

