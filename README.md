# Feature Matching in Computer Vision (Technical Presentation)

An interactive, 9-slide Apple Keynote-style technical presentation on **Feature Matching in Computer Vision: Unlocking Spatial Intelligence Across Multiple Views**.

Delivered by a 3-member presentation team:
- **Speaker 1**: Pavan Kumar S (Foundations & Detection, Slides 1–3)
- **Speaker 2**: Keerthana (Descriptors & Matching Algorithms, Slides 4–6)
- **Speaker 3**: Thanushree (Deep Learning & Applications, Slides 7–9)

Adhering to Apple Human Interface Guidelines (HIG), Human Resources presentation standards, SF Pro typography, and an uncluttered white canvas aesthetic.

---

## Live Presentation
- **Live Interactive Presentation**: [https://hrlpavan.github.io/feature-matching-presentation/](https://hrlpavan.github.io/feature-matching-presentation/)
- **Download Full PDF Deck**: [Feature_Matching_In_Computer_Vision_Presentation.pdf](Feature_Matching_In_Computer_Vision_Presentation.pdf)
- **Official Company Portal**: [https://hrlpavan.github.io/hrl-international-website-/](https://hrlpavan.github.io/hrl-international-website-/)

---

## Presentation Structure

### Part 1: Foundations & Detection (Speaker 1 &middot; Pavan Kumar S)
- **Slide 1: Title Slide** &mdash; Spatial Intelligence & Multiple-View Geometry: From Fundamental Geometry to AI-Powered Alignment.
- **Slide 2: Introduction & The Core Problem** &mdash; 3D spatial correspondences, perspective shearing, illumination shifts, scale variances, and the canonical 4-stage pipeline.
- **Slide 3: Feature Detection (Keypoint Extraction)** &mdash; Corners (Harris / Shi-Tomasi), Blobs (DoG / Hessian scale space), and FAST Bresenham circular segment thresholding.

### Part 2: Descriptors & Matching Algorithms (Speaker 2 &middot; Keerthana)
- **Slide 4: Feature Descriptors (Visual Fingerprints)** &mdash; 128-D continuous float vectors (SIFT) vs. 256-bit binary bitstrings (ORB / BRIEF) with hardware POPCNT acceleration.
- **Slide 5: Matching Mechanics & Distance Metrics** &mdash; Euclidean $L_2$ vs. Hamming distance, Brute-Force vs. FLANN randomized KD-trees, and David Lowe's Ratio Test ($d_1 / d_2 \le 0.75$).
- **Slide 6: Outlier Rejection & Geometrical Verification** &mdash; RANSAC iterative consensus loop, Homography planar transformations ($x' \sim Hx$), and Fundamental/Essential epipolar geometry ($x'^T F x = 0$).

### Part 3: Deep Learning, Applications & Future Directions (Speaker 3 &middot; Thanushree)
- **Slide 7: Modern Era &mdash; Learned Matching Architectures** &mdash; SuperPoint joint convolutional extraction (detector + descriptor heads) and SuperGlue attentional GNN with Sinkhorn optimal transport.
- **Slide 8: Algorithm Selection & Benchmark Guide** &mdash; Comprehensive latency, scale robustness, and hardware budget decision matrix (SIFT vs. ORB vs. SuperPoint/SuperGlue).
- **Slide 9: Real-World Applications & Conclusion** &mdash; 4-quadrant overview: Panoramic Image Stitching, Visual SLAM for robotics, 3D Structure from Motion (SfM) Digital Twins, and Augmented Reality spatial anchors.

---

## Interactive Presentation Controls

- **Next Slide**: Press `Right Arrow`, `Space`, or `PageDown`.
- **Previous Slide**: Press `Left Arrow` or `PageUp`.
- **Direct Jump**: Press keys `1` through `9`.
- **Speaker Delivery Script**: Press `N` or click the notes button to toggle the real-time speaker script drawer.
- **Full-Screen**: Press `F` for borderless presentation mode.

---

## Design System Specifications
- **Canvas Backdrop**: Apple Canvas White (`#FBFBFD`)
- **Slide Surfaces**: Pure Optical White (`#FFFFFF`) with subtle hairline border (`rgba(0, 0, 0, 0.08)`)
- **Typography**: `-apple-system, BlinkMacSystemFont, "SF Pro Display", "SF Pro Text", sans-serif`
- **Color Accents**: Obsidian Charcoal (`#1D1D1F`), Precision Emerald (`#059669`), Slate Navy (`#1E293B`)
- **Visual Policy**: 100% zero-emoji professional standard.

---

## Repository
Maintained by **Pavan Kumar Sadashiv (HRL)**, Founder & Managing Director, HRL International Private Limited.
