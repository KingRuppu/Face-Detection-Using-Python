# Face Detection

Simple OpenCV webcam face enrollment and recognition for Aniruddha Dutta.

## Setup

```powershell
pip install -r requirements.txt
```

## Usage

Enroll new samples:

```powershell
python ProjectWork enroll
```

Train from saved samples:

```powershell
python ProjectWork train
```

Run recognition:

```powershell
python ProjectWork recognize
```

If your webcam is not camera `0`, try:

```powershell
python ProjectWork recognize --camera 1
```

Training images and generated models are intentionally ignored by Git because they contain private biometric data.
