# Copyright © 2021, United States Government, as represented by the Administrator of the 
# National Aeronautics and Space Administration. All rights reserved.
#
# The “ISAAC - Integrated System for Autonomous and Adaptive Caretaking platform” software is 
# licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License. 
#
# You may obtain a copy of the License at
#
# http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software distributed under the 
# License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, 
# either express or implied. See the License for the specific language governing 
# permissions and limitations under the License.
#

FROM node:12
USER root
WORKDIR /app
COPY package.json .
RUN npm i
COPY . .
# TODO compile openmct here instead of commiting compiled code
EXPOSE 8080
CMD npm start

