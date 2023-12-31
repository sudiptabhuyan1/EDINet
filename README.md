# EDINet:Estimated depth based progressive interactive framework for RGB salient object detection in images
Use of depth information is often beneficial for salient object detection (SOD) in color images, and hence, RGB-D SOD has gained popularity. However, the availability of depth data related to a color image can not be assumed, which is when RGB SOD is needed. RGB SOD can still leverage the benefits of depth information if the depth is estimated from the RGB data and suitably employed. To this end, we propose a novel estimated depth based interactive (EDINet) framework that performs SOD in images using only RGB data as its input.
EDINet consists of a depth attentive feature extractor (DAFE) to capture features from depth-attentive regions and an RGB-estimated depth interaction module (RGB-EDI) that fuses hierarchical features from DAFE and the input RGB data. The salient object map is obtained after its progressive enhancement through its iterative use as a feedback into RGB-EDI. Quantitative and qualitative performance comparison with the state-of-the-art (SOTA) on benchmark RGB datasets shows the effectiveness of our framework. Considering RGB-D benchmark datasets and RGB-D SOD SOTA, the usefulness of EDINet in RGB-D SOD is also demonstrated by employing the actual depth instead of the estimated one.
* PROPOSED EDINet
![framework1_1_page-0001](https://github.com/sudiptabhuyan1/EDINet/assets/95354449/7cf13a25-4f2f-4977-bbc3-6bd179ecf6a3)
* Quantitative comparison with SOTA on RGB datasets 
![RGBresult](https://github.com/sudiptabhuyan1/EDINet/assets/95354449/8d7bf090-8d24-4e32-9d0d-cc9bbbab67d6)
* Quantitative comparison with SOTA on RGB-D datasets 
![RGBDresult](https://github.com/sudiptabhuyan1/EDINet/assets/95354449/e275e89b-1e8a-4aea-955f-86bbf0ed0b9b)
* Qualitative comparison with recent SOTA 
![Capture](https://github.com/sudiptabhuyan1/EDINet/assets/95354449/681ca355-ff20-456d-9b97-de6b0ee18fcb)
# Data and code will be available in due course...
# Contact
Sudipta Bhuyan: sudiptabhuyan1[at]gmail[dot]com
