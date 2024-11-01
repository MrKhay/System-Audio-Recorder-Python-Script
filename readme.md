# How to Setup

## Setup Instructions

This guide explains how to set up and use this script to record system audio on your computer using a virtual audio device. This solution is cross-platform and works on macOS, Windows, and Linux, using commonly available virtual audio devices.

### 1. Create environment

```bash
python3 -m venv myenv
```

## 2. Activate Environment

- On windows

```bash
myenv\Scripts\activate 
```

- On mac

```bash
python3 -m venv myenv
```

## 3. Install Libraries

```bash
pip install sounddevice numpy

```

## 4. Running script

```bash
python audio_recorder.py

```
