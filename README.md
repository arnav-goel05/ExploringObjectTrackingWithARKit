# Vision Pro Hand Dexterity Assessment

A visionOS research prototype developed with the National University Hospital Department of
Rehabilitation to support more precise hand-dexterity assessment during stroke rehabilitation.

Clinical hand-dexterity assessments often rely on observation, which can make small movement
deviations difficult to quantify consistently or compare across sessions. This application guides a
patient through structured movement tasks in 3D and records how closely their fingertip follows the
intended path.

## What the application does

- Calibrates and tracks fingertip movement using ARKit hand tracking.
- Renders straight-line and zigzag movement tasks in an immersive RealityKit scene.
- Measures movement distance and deviation from the intended path.
- Presents an assessment summary and supports structured result export.

## Technology

- Swift and SwiftUI
- visionOS
- ARKit and RealityKit
- `simd` for spatial calculations

## Project status

The prototype was developed through requirements gathering, design, implementation, and patient
testing with clinical stakeholders. It is currently being evaluated in clinical trials with NUH, and
the underlying assessment method is patent pending.

## Running the project

Open `ObjectTracking.xcodeproj` in a version of Xcode with visionOS support, select the
`ObjectTracking` scheme, and choose a compatible visionOS destination.

## License and attribution

This repository includes code derived from Apple sample material. See [`LICENSE.txt`](LICENSE.txt)
for the applicable Apple terms.
