# Copyright 2016 Google Inc.
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#      http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
#
################################################################################

# Workspace should contain directories:
# - libfuzzer-bot (checkout of https://github.com/google/libfuzzer-bot/)
# - libarchive (checkout of https://github.com/libarchive/libarchive.git)
FROM libfuzzer/base-fuzzer

MAINTAINER ochang@google.com

RUN apt-get install -y autoconf libtool pkg-config

CMD /workspace/libfuzzer-bot/dockerfiles/lcms2/build.sh
