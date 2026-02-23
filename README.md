# Advanced Lane Detection

![Udacity](https://img.shields.io/badge/Udacity-02B3E4?style=flat-square&logo=udacity&logoColor=white)
![Self-Driving Car](https://img.shields.io/badge/Nanodegree-Self--Driving_Car-02B3E4?style=flat-square)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

> **Udacity Self-Driving Car Engineer Nanodegree** -- Advanced Lane Finding

Advanced lane line detection using camera calibration, gradient thresholds, color space transforms, perspective warping, and sliding window polynomial fitting.

---

## Pipeline

1. Camera calibration (distortion correction)
2. Gradient thresholds (Sobel, magnitude, direction)
3. Color space transforms (HLS S-channel)
4. Perspective transform (bird's eye view)
5. Sliding window lane pixel detection
6. Polynomial fit and curvature calculation
7. Lane overlay on original frame

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Language | Python |
| Vision | OpenCV |
| Notebooks | Jupyter |

---

## Getting Started

```bash
jupyter notebook advanced_lane_lines.ipynb
```

---

## License

MIT
