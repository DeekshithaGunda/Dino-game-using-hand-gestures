### Aim of the Project

The aim of this project is to develop an interactive version of the classic Dino game, where players control the in-game character using hand gestures instead of traditional keyboard or touchscreen inputs.

### Explanation

#### Implementation Details:

**Gesture Detection:**  
Use libraries like MediaPipe Hands or OpenCV to detect gestures such as:  
- **Jump Gesture:** A raised hand or fist.  
- **Duck Gesture:** A flat hand or lowered hand.

**Video Input Processing:**  
Capture real-time video from a webcam, process each frame to detect and classify gestures.

**Game Integration:**  
Convert gestures into in-game actions by simulating keyboard events like spacebar for jump and down arrow for duck.

**Tools & Libraries:**  
- **MediaPipe Hands:** Real-time hand tracking and gesture detection.  
- **OpenCV:** Computer vision techniques for detecting hand shapes and movements.  
- **TensorFlow.js:** Train models to classify gestures from video input.

![image](https://github.com/user-attachments/assets/df815094-71d3-4ec8-9072-3410c1363303)

### Conclusion

In conclusion, this project successfully integrates hand gesture recognition with the classic Dino game, transforming the traditional gameplay into an interactive, hands-free experience. By leveraging computer vision and machine learning, we developed a system that accurately detects and interprets real-time hand gestures, providing seamless control over in-game actions like jumping and ducking.

