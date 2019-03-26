Mainly the same as https://github.com/AlexeyAB/darknet

**Additional Feature**
1. Update CMakeLists.txt to find desirable OpenCV version
2. Change saved prediction result filename and path (also works for multiple image input using data/test.txt)
    - /home/darknet/predictions.jpg => /home/darknet/detected/<original-filename>.jpg
3. Add ROI for detection inside ROI only (yolo_console_dll.cpp only)
4. Add several additional cfg, txt, and `process.py` to split training and testing set
