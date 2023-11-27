# DeepFake Face Swapping

Welcome to the DeepFake Face Swapping Project! This project focuses on implementing a face-swapping algorithm using deep learning techniques. The goal is to seamlessly replace faces in videos with the faces of other individuals, creating realistic and convincing deepfake videos.

## Features

1. Face swapping in videos with high realism.
2. Support for different face datasets.
3. Customizable model parameters for fine-tuning.
4. GPU acceleration for faster processing.

## Requirements

Make sure you have the following dependencies installed:

1. Python 3.x
2. TensorFlow
3. OpenCV
4. NumPy
5. Other dependencies (specified in requirements.txt)

## Usage

Start the program with arguments:

```
python run.py [options]

-h, --help                                                                 show this help message and exit
-s SOURCE_PATH, --source SOURCE_PATH                                       select an source image
-t TARGET_PATH, --target TARGET_PATH                                       select an target image or video
-o OUTPUT_PATH, --output OUTPUT_PATH                                       select output file or directory
--frame-processor FRAME_PROCESSOR [FRAME_PROCESSOR ...]                    frame processors (choices: face_swapper, face_enhancer, ...)
--keep-fps                                                                 keep target fps
--keep-frames                                                              keep temporary frames
--skip-audio                                                               skip target audio
--many-faces                                                               process every face
--reference-face-position REFERENCE_FACE_POSITION                          position of the reference face
--reference-frame-number REFERENCE_FRAME_NUMBER                            number of the reference frame
--similar-face-distance SIMILAR_FACE_DISTANCE                              face distance used for recognition
--temp-frame-format {jpg,png}                                              image format used for frame extraction
--temp-frame-quality [0-100]                                               image quality used for frame extraction
--output-video-encoder {libx264,libx265,libvpx-vp9,h264_nvenc,hevc_nvenc}  encoder used for the output video
--output-video-quality [0-100]                                             quality used for the output video
--max-memory MAX_MEMORY                                                    maximum amount of RAM in GB
--execution-provider {cpu} [{cpu} ...]                                     available execution provider (choices: cpu, ...)
--execution-threads EXECUTION_THREADS                                      number of execution threads
-v, --version                                                              show program's version number and exit
```
## Installation
<div id="badges">
  <a href="https://colab.research.google.com/drive/1Ni2ZXRnH02v-eTpabwfMhUk_ExjJc7Dx?usp=sharing">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Google Colab Badge"/>
  </a>
</div>

## Sample Output
![image](https://github.com/vclabs/Deepfake/assets/141710657/6166d17a-6958-401e-a37b-f069d06cbda5)


## License

This project is licensed under the MIT License. Feel free to use and modify the code as needed.

Thank you for using the DeepFake Face Swapping Project! If you have any questions or feedback, please don't hesitate to reach out.

Disclaimer: Be aware of the ethical considerations and legal implications associated with deepfake technology. Ensure that you have the right to use the images and videos in your datasets, and use the technology responsibly.
