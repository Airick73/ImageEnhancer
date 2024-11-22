# ImageEnhancer
Windows desktop apploication build using Qt for enchancing images 

# Key Features

## User Interface:
- **Image Loader**: Users can open and display images from their local system.
- **Real-time Preview**: Display the original and processed images side by side or allow toggling between them.
- **Responsive UI**: Use QML for a fluid and modern user interface.

## Image Processing Functions:
- **Basic Adjustments**: Brightness, contrast, saturation, and sharpness controls.
- **Denoising Filters**: Implement basic denoising algorithms to reduce image noise.
- **Sharpening Filters**: Enhance edges and details in the image.
- **Upscaling**: Integrate an open-source upscaling algorithm to improve image resolution.
- **Batch Processing (Optional)**: Allow users to apply the same enhancements to multiple images at once.

## Technical Stack:
- **Qt (C++ and QML)**: For building the desktop application's UI and handling user interactions.
- **OpenCV**: Utilize this library for image processing capabilities.
- **Optional AI Integration**: If time permits, integrate a pre-trained AI model (like ESRGAN) for advanced upscaling or denoising.
