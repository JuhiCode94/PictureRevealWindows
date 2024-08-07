# PictureRevealWindows
Author - Juhi

## Overview

Picture Reveal is a simple PyQt6-based application that presents a question and allows users to reveal an image by clicking a button.

## Features

- Neat and user-friendly interface.
- Click the button to reveal an image.
- Stylish button design with hover and pressed effects.

## Dependencies

- Python 3.11.4
- PyQt6 library

## How to Use

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/picture-reveal-app.git
    ```

2. Create a virtual environment and activate it:

    ```
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:

    ```
    pip install -r requirements.txt
    ```

4. Click the "Click me :)" button to reveal the picture.

## Styles

The application features a sleek and modern design:

- Label font: Segoe UI, size 25pt
- Button font: Segoe UI, bold, 16pt
- Button color:
  - Default: RGB(63, 0, 95)
  - Hover: RGB(107, 0, 161)
  - Pressed: RGB(198, 0, 0)
- Button border-radius: 30px

## File Structure

- `picture_reveal_app.py`: The main application file.
- `rings.png`: Sample image file. Replace with your desired image.

## How to Customize

1. Replace the `rings.png` file with your image.
2. Modify the styles in the `picture_reveal_app.py` file to match your preferences.
