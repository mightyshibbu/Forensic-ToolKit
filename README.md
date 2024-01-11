# 🕵️‍♂️ Forensic Tool Kit

Detect and uncover image forgeries with this powerful Python forgery detection project! 📸🔍

## Features

1. **Double JPEG Compression Detection** 📷🔄
    - Identify whether an image has undergone multiple JPEG compressions.

2. **Metadata Analysis Detection** 📅📷
    - Analyze and display Exif data to understand the image's metadata.

3. **Noise Variance Inconsistency Detection** 🎛️📊
    - Detect inconsistencies in noise variance to unveil potential forgeries.

4. **Copy-Move Detection** 🖼️🔍
    - Use advanced techniques, including SIFT detection, to locate and visualize copy-move forgeries.

## How to Use

### Prerequisites

- Python 3.x
- OpenCV (`pip install opencv-python`)
- PIL (`pip install Pillow`)

### Usage

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/forgery-detection.git
    ```

2. Navigate to the project directory:

    ```bash
    cd forgery-detection
    ```

3. Run the main script:

    ```bash
    python main.py <image_filename> [options]
    ```

    Options:
    - `--imauto`: Automatically search identical regions. (Default: 1)
    - `--imblev`: Blur level for degrading image details. (Default: 8)
    - `--impalred`: Image palette reduction factor. (Default: 15)
    - ... (other options)

4. Explore the results and enjoy uncovering image forgeries! 🔍🕶️

## Contributing

Feel free to contribute by opening issues or submitting pull requests. Your feedback is highly appreciated!
