This project leverages the YOLOv8 object detection model to monitor traffic in video footage. It detects vehicles, tracks their movement, calculates their speed, and annotates the video with relevant information. Additionally, it integrates custom audio into the video to highlight specific events, such as speeding violations.

**Features**
Vehicle Detection: Detects vehicles using YOLOv8.
Tracking: Tracks detected vehicles across frames to maintain consistent identification.
Speed Calculation: Measures the speed of vehicles based on frame-by-frame analysis.
Video Annotation: Adds bounding boxes, speed labels, and directional lines to the video.
Audio Alerts: Integrates audio cues at specific times in the video - when speed violations are detected.
Logging Speeding Tickets: Output information about vehicles that exceed the speed limit.

**How It Works**
Detection: The YOLOv8 model detects vehicles in each video frame.
Tracking: A custom tracking algorithm follows the detected vehicles across frames, ensuring each vehicle is consistently identified.
Speed Measurement: The script calculates vehicle speed based on their movement between frames and known time intervals.
Annotation and Audio: The video is annotated with bounding boxes, vehicle speeds, and custom audio cues inserted at specific times.
