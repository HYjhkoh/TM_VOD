# TM-VOD
Pytorch implementation of the paper
* **Title**: Joint Representation of Temporal Image Sequences and Object Motion for Video Object Detection
* **Author**: Junho Koh*, Jaekyum Kim*, Younji Shin, Byeongwon Lee, Seungji Yang, Jun Won Choi (* indicates equal contributions)
* **Conference**:  IEEE International Conference on Robotics and Automation (ICRA), 2021.
* **More deteails**: [[homepage]](https://sites.google.com/view/junhokoh/icra2021?authuser=0) [[paper]](https://ieeexplore.ieee.org/document/9561778)
## Abstract
In this paper, we propose a new video object detection (VoD) method, referred to as temporal feature aggregation and motion-aware VoD (TM-VoD), that produces a joint representation of temporal image sequences and object motion. The TM-VoD generates strong spatiotemporal features for VOD by temporally redundant information in an image sequence and the motion context. These are produced at the feature level in the region proposal stage and at the instance level in the refinement stage. In the region proposal stage, visual features are temporally fused with appropriate weights at the pixel level via gated attention model. Furthermore, pixel level motion features are obtained by capturing the changes between adjacent visual feature maps. In the refinement stage, the visual features are aligned and aggregated at the instance level. We propose a novel feature alignment method, which uses the initial region proposals as anchors to predict the box coordinates for all video frames. Moreover, the instance level motion features are obtained by applying the region of interest (RoI) pooling to the pixel level motion features and by encoding the sequential changes in the box coordinates. Finally, all these instance level features are concatenated to produce a joint representation of the objects. Experiments on the ImageNet VID dataset demonstrate that the proposed method significantly outperforms existing VoDs and achieves performance comparable with that of state-of-the-art VoDs. 

Coming soon...
