# demo/yolov3

Image processing demo for Titan.

## Requirements

- Python 3.7+

## Installation

Clone repository:
```bash
git clone https://github.com/Akoios/demo-yolov3.git
```

Install dependencies:
```bash
pip install -r requirements.txt
```

Clone `yolov3` locally:
```bash
git clone https://github.com/ultralytics/yolov3.git
```

## Usage

Edit the notebook in Jupyter Lab:
```bash
jupyter lab
```

Run image detection:
```bash
cd yolov3 && python detect.py --source "https://i.postimg.cc/rF3W27kn/https-bucketeer-e05bbc84-baa3-437e-9518-adb32be77984-s3-amazon.png"
```

## Deployment

Deploy with Titan:
```bash
titan deploy imageprocess.ipynb
```

Test the API:
```bash
https://services.demo.akoios.com/imageprocess/detect?param=https://i.postimg.cc/rF3W27kn/https-bucketeer-e05bbc84-baa3-437e-9518-adb32be77984-s3-amazon.png
```

