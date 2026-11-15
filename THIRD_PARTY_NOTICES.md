# Third-party inventory for the camera preview

This inventory is not a commercial licensing clearance or an endorsement by any upstream project.

## Flutter and Dart packages

- Flutter SDK used for this build: 3.44.8, with Dart 3.12.2. Flutter license: https://github.com/flutter/flutter/blob/3.44.8/LICENSE
- The SDK's Flutter and flutter_localizations packages, and their locked dependencies, are listed in pubspec.lock.
- package:web 1.1.1, BSD-style license: https://pub.dev/packages/web/versions/1.1.1/license
- Flutter's generated third-party license bundle is retained in the published assets/NOTICES or assets/NOTICES.Z. Material icon and rendering-engine assets retain their generated notices.

## MediaPipe runtime and models

- JavaScript/WASM runtime: @mediapipe/tasks-vision 0.10.14, fetched from jsDelivr at runtime. Upstream license: https://github.com/google-ai-edge/mediapipe/blob/v0.10.14/LICENSE
- Face model: https://storage.googleapis.com/mediapipe-models/face_landmarker/face_landmarker/float16/1/face_landmarker.task
- Body model: https://storage.googleapis.com/mediapipe-models/pose_landmarker/pose_landmarker_lite/float16/1/pose_landmarker_lite.task
- Upstream face model information: https://ai.google.dev/edge/mediapipe/solutions/vision/face_landmarker
- Upstream pose model information: https://ai.google.dev/edge/mediapipe/solutions/vision/pose_landmarker

The runtime and model files are downloaded from their existing upstream locations; this repository does not vendor or modify those binaries. Precise model/bundle licensing, transitive notices and source-asset rights remain review items before commercial distribution. No model accuracy or medical measurement claim is made.

## SORI assets

The camera bridges and adapters were adapted from the owner's existing SORI project. The operational SORI repository and customer data are not deployed with this preview. No project-wide open-source license is granted by this notice.
