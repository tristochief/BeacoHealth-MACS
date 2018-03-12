# BeacoHealth-MACS
The Moment Annotation and Capturing Software (MACS) is a tool that allows users to capture data on a realsense RGB/Depth camera and also annotate it for either image recognition or object detection.

# Motivation
The realsense devices provide a great solution to many computer vision related applications. Though what's missing from the realsense sdk is an easy way to 
annotate and label the data it captures for machine learning software. This tool is an extension to the realsense viewer, that allows you to
annotate videos for object detection, and label an image for image recognition

# Principles of the App:
1. Annotating at a fast pace is a massive priority. The tool must provide fast annotation and labelling tools
2. Annotations must be powerful. A wide range of options for how you can annotate must be available
3. Compatibility with other well known machine learning algorithms must be provided. A wide range of formats to save annotations and labelling information must be kept
4. Code is elegant.
5. Code is reusable.
6. Code is concise.
7. Code is well described and maintainable.

# Features
1. All features are done on the keyboard only for speed

## Annotation for Object Detection
2. Changing between frames on loaded images by arrow keys
3. Scaling, positioning of bounding boxes by keys only
4. Multiple bounding boxes in 1 frame key selection
5. Save to formats available for theano, tensorflow, and other popular libraries
6. labels for bounding boxes can be selected quickly

## Annotations for Image Recognition
7. Selection of image label can be done quickly
8. Image selection by pressing arrow keys
9. Can save both image and label data to a wide variety of formats specifically for deep learning frameworks


