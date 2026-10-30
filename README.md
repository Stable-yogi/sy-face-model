# SY Face Model

One small face-finder file for the optional "Face Detect SY" node in [SY Nodes](https://github.com/Stable-yogi/sy-comfyui-nodes).

The node works without this file. It has a built-in finder. This file finds faces more reliably.

## Get it

Download `face_detection_yunet_2023mar.onnx` (233 KB) from this page.

## Install

1. Put the file in `ComfyUI/models/sy_face_detect/`. Make the folder if it is not there.
2. Restart ComfyUI.
3. In Face Detect SY, open the `detector` list and pick `face_detection_yunet_2023mar.onnx`.

## Where it comes from

This is the YuNet face detector, version 2023mar, from the OpenCV Model Zoo. It is not our work. The file is unchanged. Licence: MIT, copyright Shiqi Yu. The licence text is in `LICENSE`.

Put together by Stable Yogi.
