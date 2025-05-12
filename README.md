# Scene Text Recognition Project

## Overview

This project implements a Scene Text Recognition system by combining **YOLO** (You Only Look Once) for text detection and **CRNN** (Convolutional Recurrent Neural Network) for text recognition. The system is designed to detect and recognize text in natural scene images, such as street signs, billboards, or product labels.

- **YOLO**: Detects and localizes text regions in images.
- **CRNN**: Recognizes the text within the detected regions.

1. **Download pre-trained models**:

   - YOLO model: https://drive.google.com/drive/folders/1g3l-niAsmLELFbxbfTvgIb410wKIvxF8?usp=sharing
   - CRNN model: https://drive.google.com/file/d/1W_ONJN-7d4FP6qVW8w-Qf-gc2m0BnXnd/view?usp=sharing

2. **Set up environment**:

   - Ensure CUDA is installed for GPU support (optional but recommended).
   - Configure paths to models and datasets in `config.py`.

## Contact

For questions or suggestions, please open an issue or contact tdhuy1512@gmail.com.
