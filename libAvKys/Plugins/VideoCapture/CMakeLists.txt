# Webcamoid, webcam capture application.
# Copyright (C) 2021  Gonzalo Exequiel Pedone
#
# Webcamoid is free software: you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation, either version 3 of the License, or
# (at your option) any later version.
#
# Webcamoid is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with Webcamoid. If not, see <http://www.gnu.org/licenses/>.
#
# Web-Site: http://webcamoid.github.io/

cmake_minimum_required(VERSION 3.16)

project(VideoCapture)

add_subdirectory(src)
add_subdirectory(src/capture/androidcamera)
add_subdirectory(src/capture/avfoundation)
add_subdirectory(src/capture/cmio)
add_subdirectory(src/capture/dshow)
add_subdirectory(src/capture/libuvc)
add_subdirectory(src/capture/mediafoundation)
add_subdirectory(src/capture/ndkcamera)
add_subdirectory(src/capture/v4l2sys)
add_subdirectory(src/capture/v4lutils)
add_subdirectory(src/convert/ffmpeg)
add_subdirectory(src/convert/generic)
add_subdirectory(src/convert/gstreamer)
