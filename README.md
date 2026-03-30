# Image Segmentation & Fourier Boundary Analysis

A Java-based image processing pipeline built as part of M.Sc. Applied 
Computer Science coursework at Hochschule Schmalkalden.

## 🔍 What it does
- Threshold-based image segmentation
- Morphological erosion filtering (noise removal)
- Connected boundary cloud extraction (8-connectivity)
- Automatic seed point detection per image block
- Iterative region growing for full contour tracing
- Discrete Fourier Transform (DFT) shape descriptors
  with low-frequency reconstruction for smooth contours

## 🛠️ Tech Stack
- Java (Swing GUI)
- Custom DFT / Complex number implementation
- Maven build system

## ▶️ How to Run
1. Clone the repo
2. Open in NetBeans or IntelliJ
3. Run `Main.java` — the GUI launches automatically
4. Click **Start** to run the full pipeline

## 📸 Pipeline Stages
| Output | Description |
|--------|-------------|
| Output 0 | Original image |
| Output 1 | Segmented (binary) |
| Output 2 | Morphologically filtered |
| Output 3 | Boundary cloud + seed points |
| Output 4 | Fourier-reconstructed contour |
