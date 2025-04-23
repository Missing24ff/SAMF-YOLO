# SAMF-YOLO

SAMF-YOLO is an advanced object detection model based on YOLOv11, incorporating SAM (Segment Anything Model) features for enhanced detection capabilities.

## Features

- Based on YOLOv11 architecture
- Integration with SAM (Segment Anything Model)
- High-performance object detection
- Support for various datasets
- Comprehensive training and evaluation tools

## Project Structure

```
SAMF-YOLO/
├── dataset/          # Dataset directory
├── ultralytics/      # Core YOLO implementation
├── tests/            # Test files
├── docs/             # Documentation
└── runs/             # Training and inference results
```

## Requirements

- Python 3.8+
- PyTorch
- OpenCV
- NumPy
- Other dependencies listed in requirements.txt

## Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/SAMF-YOLO.git
cd SAMF-YOLO
```

2. Install the required packages:
```bash
pip install -r requirements.txt
```

## Usage

### Training

```bash
python train.py --data your_dataset.yaml --weights yolov11.pt
```

### Inference

```bash
python detect.py --source your_image.jpg --weights best.pt
```

## Dataset Preparation

Place your dataset in the `dataset` directory following the standard YOLO format:
- images/
- labels/
- train.txt
- val.txt

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- YOLOv11
- SAM (Segment Anything Model)
- Ultralytics 