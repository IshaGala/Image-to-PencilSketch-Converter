This Python script converts a color image into a pencil sketch using various image processing techniques. It performs the following steps:
1.Read an Image: The script uses the imageio library to read an image file (e.g., rainbow.jpg).
2.Convert to Grayscale: It transforms the RGB image into a grayscale format using a weighted sum of the RGB channels.
3.Invert Grayscale Image: The grayscale image is inverted to highlight darker areas.
4.Apply Gaussian Blur: A Gaussian filter is applied to the inverted image to create a soft blur effect.
5.Dodge Function: The dodge function combines the blurred and original grayscale images to create the final sketch effect. Areas in the blurred image lighten the corresponding areas in the grayscale image.
6.Save Result: The resulting pencil sketch is saved as a PNG file (rainbow-sketch.png).
This script effectively simulates a pencil drawing by emphasizing outlines and shading based on the original image's features.
