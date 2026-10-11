# 本机视觉资源

- Runtime: `@mediapipe/tasks-vision` 1.1.0 npm 包的 `wasm/` 文件（Apache-2.0）。升级 npm 版本时同步更新这四个运行时文件。
- Model: Google 官方 EfficientDet Lite0 float32 v1。
- Source: https://storage.googleapis.com/mediapipe-models/object_detector/efficientdet_lite0/float32/1/efficientdet_lite0.tflite
- Guide: https://developers.google.com/edge/mediapipe/solutions/vision/object_detector/web_js

资源随项目部署，不从第三方 CDN 运行时加载；图片与摄像头帧在本地 Web Worker 推理，不上传。不是安全避障、测距或定位导航模型。
