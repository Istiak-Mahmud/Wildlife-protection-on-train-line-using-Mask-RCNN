# Wildlife-protection-on-train-line-using-Mask-RCNN

This is an implementation of the paper. The software files are attached in this repo. 

# Abstract

Train incidents with animals and even humans have gotten more attention in the past. Every year, thousands of animals are killed on train tracks, causing an imbalance in the ecosystem and significant delays in railway traffic. Similarly, sometimes train accident is prevalent at the rail gates, where motor vehicles are crossing the train line. All that happens due to the lack of detecting the objects correctly on the train line. Since the detection depends on the driver or human, there is a possibility of occasionally making an error in honking the horn at the right moment, leading to the accident. That’s why an automated solution for detecting objects on the train line and promptly notifying the driver is essential. In this research, we proposed a system that detects objects only on the train line. Sometimes, there is an object just beside the train line, which is at a safe distance. To eliminate this kind of wrong detection, we detected the train line first and then detected the objects on the detected train line. Here, we used the Mask R-CNN algorithm to detect the train line and things on the train line. A railway traffic dataset with an input size of 512×512 pixels was used to test the proposed methodology, which came up with results with a mean average precision of 0.9375 and a frame rate of 30 frames per second. According to the findings of the experiments, the suggested approach can apply to identify objects on railroads in the real world.

# Model Architecture

![image](https://github.com/Istiak-Mahmud/Wildlife-protection-on-train-line-using-Mask-RCNN/blob/main/block%20diagram.png)

# Keywords:

Train accidents, object detection, automated solution, mask R-CNN algorithm, railway
traffic dataset.

![ezgif com-video-to-gif](https://github.com/Istiak-Mahmud/Wildlife-protection-on-train-line-using-Mask-RCNN/assets/63910470/2d9dc6ae-ec84-4b34-8b0b-819fee316239)

Citation: 

I. Mahmud, M. M. Kabir, J. Shin, C. Mistry, Y. Tomioka and M. F. Mridha, "Advancing Wildlife Protection: Mask R-CNN for Rail Track Identification and Unwanted Object Detection," in IEEE Access, vol. 11, pp. 99519-99534, 2023, doi: 10.1109/ACCESS.2023.3313253.
