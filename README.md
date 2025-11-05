<img alt="lucyra-logo" src="./assets/images/logo.png" style="margin-left:auto; margin-right:auto; display:block; width:200px;"/>

# Lucyra

**Lucyra** is a browser‑based image forensics flashlight that applies **177 pixel‑space effects** under your cursor to surface subtle artifacts and hidden structure — all locally in your browser.

[**View Live Demo**](https://nqrlabs.com/Lucyra/)

## Overview

Lucyra renders your image on an HTML5 Canvas and blends an *interactive circular spotlight* of the selected effect over the original image. You can cycle effects, resize the beam, and zoom/pan to inspect any region with precision. No uploads, no servers — everything runs client‑side.

## Features

- **177 effects** spanning brightness/contrast, channel isolation, LSB/bit‑plane views, XOR/masks, modulo/thresholding, gradients/edges, HSL components, posterization, gamma, temperature shifts, and more.
- **Flashlight workflow:** move to inspect, **Shift+Scroll** to change radius, **Ctrl+Scroll** to zoom, **Scroll/↑↓** to cycle effects, **drag** to pan.
- **Zero dependencies:** pure JavaScript + Canvas; no third‑party libraries.
- **Presets:** save/load four quick presets plus a full state snapshot.
- **Privacy:** all computation is local; images never leave your machine.

## Usage

1. Open *Lucyra* in your browser and click **Load Image**.
2. Move the cursor to sweep the effect over the region of interest.
3. Use **Scroll** or **↑/↓** to cycle effects; **Shift+Scroll** adjusts beam radius; **Ctrl+Scroll** zooms; **drag** pans.
4. Use **Save Current State** to capture parameters/preset buttons for fast recall.

## Effect Index Reference (1–177)

> Each entry lists the effect name and, succinctly, which steganographic signals it’s most effective at surfacing in practice.

1. **Brightness 0.50x** — Reveals: visibility, faint-watermarks/overlays.
2. **Brightness 0.75x** — Reveals: visibility, faint-watermarks/overlays.
3. **Brightness 1.00x** — Reveals: visibility, faint-watermarks/overlays.
4. **Brightness 1.25x** — Reveals: visibility, faint-watermarks/overlays.
5. **Brightness 1.50x** — Reveals: visibility, faint-watermarks/overlays.
6. **Brightness 1.75x** — Reveals: visibility, faint-watermarks/overlays.
7. **Brightness 2.00x** — Reveals: visibility, faint-watermarks/overlays.
8. **Brightness 2.25x** — Reveals: visibility, faint-watermarks/overlays.
9. **Brightness 2.50x** — Reveals: visibility, faint-watermarks/overlays.
10. **Brightness 2.75x** — Reveals: visibility, faint-watermarks/overlays.
11. **Brightness 3.00x** — Reveals: visibility, faint-watermarks/overlays.
12. **Contrast -4.0** — Reveals: visibility, faint-watermarks/overlays.
13. **Contrast -3.5** — Reveals: visibility, faint-watermarks/overlays.
14. **Contrast -3.0** — Reveals: visibility, faint-watermarks/overlays.
15. **Contrast -2.5** — Reveals: visibility, faint-watermarks/overlays.
16. **Contrast -2.0** — Reveals: visibility, faint-watermarks/overlays.
17. **Contrast -1.5** — Reveals: visibility, faint-watermarks/overlays.
18. **Contrast -1.0** — Reveals: visibility, faint-watermarks/overlays.
19. **Contrast -0.5** — Reveals: visibility, faint-watermarks/overlays.
20. **Contrast 0.0** — Reveals: visibility, faint-watermarks/overlays.
21. **Contrast 0.5** — Reveals: visibility, faint-watermarks/overlays.
22. **Contrast 1.0** — Reveals: visibility, faint-watermarks/overlays.
23. **Contrast 1.5** — Reveals: visibility, faint-watermarks/overlays.
24. **Contrast 2.0** — Reveals: visibility, faint-watermarks/overlays.
25. **Contrast 2.5** — Reveals: visibility, faint-watermarks/overlays.
26. **Contrast 3.0** — Reveals: visibility, faint-watermarks/overlays.
27. **Contrast 3.5** — Reveals: visibility, faint-watermarks/overlays.
28. **Contrast 4.0** — Reveals: visibility, faint-watermarks/overlays.
29. **Contrast 4.5** — Reveals: visibility, faint-watermarks/overlays.
30. **Contrast 5.0** — Reveals: visibility, faint-watermarks/overlays.
31. **Contrast 5.5** — Reveals: visibility, faint-watermarks/overlays.
32. **Contrast 6.0** — Reveals: visibility, faint-watermarks/overlays.
33. **Red x0.5** — Reveals: channel-LSB, single-channel hiding.
34. **Red x1.0** — Reveals: channel-LSB, single-channel hiding.
35. **Red x1.5** — Reveals: channel-LSB, single-channel hiding.
36. **Red x2.0** — Reveals: channel-LSB, single-channel hiding.
37. **Red x2.5** — Reveals: channel-LSB, single-channel hiding.
38. **Green x0.5** — Reveals: channel-LSB, single-channel hiding.
39. **Green x1.0** — Reveals: channel-LSB, single-channel hiding.
40. **Green x1.5** — Reveals: channel-LSB, single-channel hiding.
41. **Green x2.0** — Reveals: channel-LSB, single-channel hiding.
42. **Green x2.5** — Reveals: channel-LSB, single-channel hiding.
43. **Blue x0.5** — Reveals: channel-LSB, single-channel hiding.
44. **Blue x1.0** — Reveals: channel-LSB, single-channel hiding.
45. **Blue x1.5** — Reveals: channel-LSB, single-channel hiding.
46. **Blue x2.0** — Reveals: channel-LSB, single-channel hiding.
47. **Blue x2.5** — Reveals: channel-LSB, single-channel hiding.
48. **Red Only** — Reveals: channel-LSB, single-channel hiding.
49. **Green Only** — Reveals: channel-LSB, single-channel hiding.
50. **Blue Only** — Reveals: channel-LSB, single-channel hiding.
51. **Full Invert** — Reveals: general visibility.
52. **Invert Red** — Reveals: parity/LSB, watermarks.
53. **Invert Green** — Reveals: parity/LSB, watermarks.
54. **Invert Blue** — Reveals: parity/LSB, watermarks.
55. **Red Bit 0** — Reveals: LSB/bit-plane (incl. BPCS).
56. **Red Bit 1** — Reveals: LSB/bit-plane (incl. BPCS).
57. **Red Bit 2** — Reveals: LSB/bit-plane (incl. BPCS).
58. **Red Bit 3** — Reveals: LSB/bit-plane (incl. BPCS).
59. **Red Bit 4** — Reveals: LSB/bit-plane (incl. BPCS).
60. **Red Bit 5** — Reveals: LSB/bit-plane (incl. BPCS).
61. **Red Bit 6** — Reveals: LSB/bit-plane (incl. BPCS).
62. **Red Bit 7** — Reveals: LSB/bit-plane (incl. BPCS).
63. **Green Bit 0** — Reveals: LSB/bit-plane (incl. BPCS).
64. **Green Bit 1** — Reveals: LSB/bit-plane (incl. BPCS).
65. **Green Bit 2** — Reveals: LSB/bit-plane (incl. BPCS).
66. **Green Bit 3** — Reveals: LSB/bit-plane (incl. BPCS).
67. **Green Bit 4** — Reveals: LSB/bit-plane (incl. BPCS).
68. **Green Bit 5** — Reveals: LSB/bit-plane (incl. BPCS).
69. **Green Bit 6** — Reveals: LSB/bit-plane (incl. BPCS).
70. **Green Bit 7** — Reveals: LSB/bit-plane (incl. BPCS).
71. **Blue Bit 0** — Reveals: LSB/bit-plane (incl. BPCS).
72. **Blue Bit 1** — Reveals: LSB/bit-plane (incl. BPCS).
73. **Blue Bit 2** — Reveals: LSB/bit-plane (incl. BPCS).
74. **Blue Bit 3** — Reveals: LSB/bit-plane (incl. BPCS).
75. **Blue Bit 4** — Reveals: LSB/bit-plane (incl. BPCS).
76. **Blue Bit 5** — Reveals: LSB/bit-plane (incl. BPCS).
77. **Blue Bit 6** — Reveals: LSB/bit-plane (incl. BPCS).
78. **Blue Bit 7** — Reveals: LSB/bit-plane (incl. BPCS).
79. **R-G Diff x1** — Reveals: channel-correlation anomalies.
80. **R-G Diff x2** — Reveals: channel-correlation anomalies.
81. **R-G Diff x3** — Reveals: channel-correlation anomalies.
82. **R-G Diff x4** — Reveals: channel-correlation anomalies.
83. **R-G Diff x5** — Reveals: channel-correlation anomalies.
84. **R-B Diff x1** — Reveals: channel-correlation anomalies.
85. **R-B Diff x2** — Reveals: channel-correlation anomalies.
86. **R-B Diff x3** — Reveals: channel-correlation anomalies.
87. **R-B Diff x4** — Reveals: channel-correlation anomalies.
88. **R-B Diff x5** — Reveals: channel-correlation anomalies.
89. **G-B Diff x1** — Reveals: channel-correlation anomalies.
90. **G-B Diff x2** — Reveals: channel-correlation anomalies.
91. **G-B Diff x3** — Reveals: channel-correlation anomalies.
92. **G-B Diff x4** — Reveals: channel-correlation anomalies.
93. **G-B Diff x5** — Reveals: channel-correlation anomalies.
94. **H-Gradient** — Reveals: edge-adaptive embedding regions, sharp overlays.
95. **V-Gradient** — Reveals: edge-adaptive embedding regions, sharp overlays.
96. **All Gradients** — Reveals: edge-adaptive embedding regions, sharp overlays.
97. **Above Avg x2** — Reveals: blocky/binary overlays, statistical outliers.
98. **Above Avg x4** — Reveals: blocky/binary overlays, statistical outliers.
99. **Above Avg x6** — Reveals: blocky/binary overlays, statistical outliers.
100. **Above Avg x8** — Reveals: blocky/binary overlays, statistical outliers.
101. **Above Avg x10** — Reveals: blocky/binary overlays, statistical outliers.
102. **Above Avg x12** — Reveals: blocky/binary overlays, statistical outliers.
103. **Above Avg x14** — Reveals: blocky/binary overlays, statistical outliers.
104. **Above Avg x16** — Reveals: blocky/binary overlays, statistical outliers.
105. **Below Avg x2** — Reveals: blocky/binary overlays, statistical outliers.
106. **Below Avg x4** — Reveals: blocky/binary overlays, statistical outliers.
107. **Below Avg x6** — Reveals: blocky/binary overlays, statistical outliers.
108. **Below Avg x8** — Reveals: blocky/binary overlays, statistical outliers.
109. **Below Avg x10** — Reveals: blocky/binary overlays, statistical outliers.
110. **Below Avg x12** — Reveals: blocky/binary overlays, statistical outliers.
111. **Below Avg x14** — Reveals: blocky/binary overlays, statistical outliers.
112. **Below Avg x16** — Reveals: blocky/binary overlays, statistical outliers.
113. **Hue Only** — Reveals: color-plane anomalies, channel-LSB.
114. **Saturation Only** — Reveals: color-plane anomalies, channel-LSB.
115. **Luminance Only** — Reveals: color-plane anomalies, channel-LSB.
116. **Hue Amplified** — Reveals: color-plane anomalies, channel-LSB.
117. **Saturation Amplified** — Reveals: color-plane anomalies, channel-LSB.
118. **XOR 1** — Reveals: LSB/parity (StegSolve-style).
119. **XOR 3** — Reveals: LSB/parity (StegSolve-style).
120. **XOR 7** — Reveals: LSB/parity (StegSolve-style).
121. **XOR 15** — Reveals: LSB/parity (StegSolve-style).
122. **XOR 31** — Reveals: LSB/parity (StegSolve-style).
123. **XOR 63** — Reveals: LSB/parity (StegSolve-style).
124. **XOR 85** — Reveals: LSB/parity (StegSolve-style).
125. **XOR 127** — Reveals: LSB/parity (StegSolve-style).
126. **XOR 170** — Reveals: LSB/parity (StegSolve-style).
127. **XOR 255** — Reveals: LSB/parity (StegSolve-style).
128. **Edges Soft** — Reveals: edge-adaptive embedding regions, sharp overlays.
129. **Edges Normal** — Reveals: edge-adaptive embedding regions, sharp overlays.
130. **Edges Hard** — Reveals: edge-adaptive embedding regions, sharp overlays.
131. **Posterize 2** — Reveals: palette/indexed-color stego, quantization steps.
132. **Posterize 4** — Reveals: palette/indexed-color stego, quantization steps.
133. **Posterize 6** — Reveals: palette/indexed-color stego, quantization steps.
134. **Posterize 8** — Reveals: palette/indexed-color stego, quantization steps.
135. **Posterize 10** — Reveals: palette/indexed-color stego, quantization steps.
136. **Posterize 12** — Reveals: palette/indexed-color stego, quantization steps.
137. **Posterize 14** — Reveals: palette/indexed-color stego, quantization steps.
138. **Posterize 16** — Reveals: palette/indexed-color stego, quantization steps.
139. **Modulo 2** — Reveals: k-LSB/parity visualization.
140. **Modulo 4** — Reveals: k-LSB/parity visualization.
141. **Modulo 8** — Reveals: k-LSB/parity visualization.
142. **Modulo 16** — Reveals: k-LSB/parity visualization.
143. **Modulo 32** — Reveals: k-LSB/parity visualization.
144. **Modulo 64** — Reveals: k-LSB/parity visualization.
145. **Modulo 128** — Reveals: k-LSB/parity visualization.
146. **Threshold 32** — Reveals: binary overlays/QR/text.
147. **Threshold 64** — Reveals: binary overlays/QR/text.
148. **Threshold 96** — Reveals: binary overlays/QR/text.
149. **Threshold 128** — Reveals: binary overlays/QR/text.
150. **Threshold 160** — Reveals: binary overlays/QR/text.
151. **Threshold 192** — Reveals: binary overlays/QR/text.
152. **Threshold 224** — Reveals: binary overlays/QR/text.
153. **Gamma 0.3** — Reveals: visibility, faint-watermarks/overlays.
154. **Gamma 0.6** — Reveals: visibility, faint-watermarks/overlays.
155. **Gamma 0.9** — Reveals: visibility, faint-watermarks/overlays.
156. **Gamma 1.2** — Reveals: visibility, faint-watermarks/overlays.
157. **Gamma 1.5** — Reveals: visibility, faint-watermarks/overlays.
158. **Gamma 1.8** — Reveals: visibility, faint-watermarks/overlays.
159. **Gamma 2.1** — Reveals: visibility, faint-watermarks/overlays.
160. **Gamma 2.4** — Reveals: visibility, faint-watermarks/overlays.
161. **Gamma 2.7** — Reveals: visibility, faint-watermarks/overlays.
162. **Temp -100** — Reveals: visibility, faint-watermarks/overlays.
163. **Temp -80** — Reveals: visibility, faint-watermarks/overlays.
164. **Temp -60** — Reveals: visibility, faint-watermarks/overlays.
165. **Temp -40** — Reveals: visibility, faint-watermarks/overlays.
166. **Temp -20** — Reveals: visibility, faint-watermarks/overlays.
167. **Temp 0** — Reveals: visibility, faint-watermarks/overlays.
168. **Temp +20** — Reveals: visibility, faint-watermarks/overlays.
169. **Temp +40** — Reveals: visibility, faint-watermarks/overlays.
170. **Temp +60** — Reveals: visibility, faint-watermarks/overlays.
171. **Temp +80** — Reveals: visibility, faint-watermarks/overlays.
172. **Temp +100** — Reveals: visibility, faint-watermarks/overlays.
173. **Solarize 50** — Reveals: thresholded/contrast-coded overlays.
174. **Solarize 100** — Reveals: thresholded/contrast-coded overlays.
175. **Solarize 150** — Reveals: thresholded/contrast-coded overlays.
176. **Solarize 200** — Reveals: thresholded/contrast-coded overlays.
177. **Solarize 250** — Reveals: thresholded/contrast-coded overlays.

## Notes on Interpretation

- **Bit‑plane, modulo, and XOR masks** directly visualize LSB/k‑LSB structure and parity patterns (commonly used by spatial‑domain steganography).
- **Channel splits, differences, and HSL views** expose inter‑channel inconsistencies characteristic of single‑channel or color‑plane embedding.
- **Thresholding/posterization** make binary overlays (e.g., text, QR/barcodes, palette tricks) pop from backgrounds.
- **Gradients/edges** help localize edge‑adaptive embedding regions and faint, sharp overlays.
- **Global tone tools** (brightness/contrast/gamma/temperature) simply lift low‑contrast content that may include watermarks or blends.

## Technical Notes

Lucyra uses Canvas APIs (`getContext('2d')`, `getImageData/putImageData`) to compute effects and a radial blend around the cursor for a natural “flashlight” reveal.

## License

MIT License — free for modification and use. Attribution appreciated if used publicly.

## Credits

Created by **NQR** for analysts, ARG players, and curious technologists who enjoy illuminating the unseen. If you use *Lucyra* in a project or ARG, I'd love to hear about it.
