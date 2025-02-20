# Video to ASCII Converter 🎥➞🖦️

This Python script converts video frames into ASCII art and displays them in the terminal in real time. It uses OpenCV for video processing and ANSI escape codes for colored output.

## Features  
✅ Converts video frames into ASCII representation  
✅ Supports colored ASCII output in the terminal  
✅ Adjustable width for better readability  
✅ Customizable playback speed  

## Installation  

Make sure you have Python installed, then install the required dependencies:  

```bash
pip install opencv-python colorama
```

## Usage  

1. Replace `"vid.mp4"` in `main()` with the path to your own video file.  
2. Run the script:  

```bash
python video_to_ascii.py
```

### Customization  

You can modify the following parameters when initializing the `VideoToText` class:  

- `video_path`: Path to the video file (required).  
- `width`: Adjusts the width of the ASCII output (default: `100`).  
- `delay`: Controls playback speed (default: `0.03` seconds per frame).  

Example of customizing these values:  

```python
video_to_text = VideoToText(video_path="your_video.mp4", width=80, delay=0.05)
```

## Exit Instructions  

- Press `q` while the video is playing to exit the program.  
- The script will automatically loop when it reaches the end of the video.  

## License  

This project is open-source under the MIT License. Feel free to modify and improve it! 🚀  

---

🔹 **Contributions & Feedback**: If you have any improvements or suggestions, feel free to open an issue or create a pull request!  

