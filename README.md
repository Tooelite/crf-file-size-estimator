# 🎥 CRF File Size Estimator 1.0

A simple web-based tool to help estimate the final file size of an H.264 or H.265 encode based on CRF value, preset, resolution, and optional audio configuration.

Perfect for users of **HandBrake**, **FFmpeg**, or anyone working with `x264` or `x265` encoders.

---

## 🔧 Features

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

## 🖼️ Screenshot

![Preview](preview.png)

---

## 🚀 Getting Started

Simply open the HTML file in your browser:

```bash
# Open locally
open crf_file_size_estimator_v1.0.html
