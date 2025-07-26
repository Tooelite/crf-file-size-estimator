# 🎥 CRF File Size Estimator 1.1

A simple web-based tool to help estimate the final file size of an H.264 or H.265 encode based on CRF value, preset, resolution, and optional audio configuration.

Perfect for users of **HandBrake**, **FFmpeg**, or anyone working with `x264` or `x265` encoders.

---

## 🔧 Features of initial release 1.0

- Estimate target file size in **MB/GB** based on CRF efficiency
- Choose between `x264` and `x265` codecs
- Supports `slow` preset (currently fixed)
- Resolution presets: **1080p (Blu-ray)** and **576p (DVD)**
- Optional audio calculation:
  - Stereo (2.0) or Surround (5.1)
  - Runtime-based bitrate estimation
- Language switcher: **English 🇬🇧 / Deutsch 🇩🇪**
- Clean, responsive UI with a **Reset button**

---

## ✨ New in Version 1.1

- 📂 **Drag & Drop support** for video files  
  → Automatically fills in the source file size based on the dropped file
- 🔁 **Improved Reset behavior**  
  → Drag & Drop area now resets to its initial state

---

## 🖼️ Screenshot

![Preview](preview.png)

---

## 🚀 Getting Started

Download the HTML-file from the repository or simply open the HTML file in your browser using this link:

👉 [Open CRF File Size Estimator](https://tooelite.github.io/crf-file-size-estimator/crf_file_size_estimator_v1.1.html)
