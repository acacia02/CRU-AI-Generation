# CRU Kitchen Visualizer

This project generates realistic kitchen image previews based on customer-uploaded photos. It allows users to see how different cabinet styles would look in their own space before committing to a purchase.

## Features

- Upload a kitchen photo
- Select cabinet style
- AI-powered image generation using ControlNet and Stable Diffusion
- Displays a modified image with updated cabinet styling

## How It Works

1. User uploads a kitchen photo.
2. The image is processed using edge detection.
3. ControlNet applies the chosen cabinet style to the detected cabinet regions.
4. A new image is generated and displayed for the user.

## Tech Stack

- Python
- Stable Diffusion v1.5 with ControlNet (Canny)
- Hugging Face Diffusers
- Google Colab (development/testing)
- OpenCV and PIL for image handling

## Status

- Image upload and processing: complete
- Prompt-based cabinet restyling: in progress
- Output generation: not complete
- Web integration: not complete

## Future Plans

- Streamlit or Flask interface
- Predefined style selection options
- Integration with CRU website and customer tools
- Support for multiple angles and lighting conditions
