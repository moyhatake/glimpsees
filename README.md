# Glimpsees
Glimpsees is Python application that extracts individual faces from videos, saving them as images. You can also compile these extracted faces into an animated GIF.

*Glimpsees is designed for Google Colab, but you can run it on your local machine, just comment out the following lines:*
* ***App** section: Lines 5 and 108*
* ***GIF** section: Line 37*

## Usage
1. **Upload Your Video File**: Begin by uploading your video (MP4 and AVI formats are currently supported) to your project directory.

2. **Install Libraries**: Run the Libs command to ensure all necessary dependencies are installed.

3. **Configure File Name**: In the Pre-config section, update the file_name variable to match the exact filename of your uploaded video (e.g., `my_example_video.mp4`). This name will be used for your output files (e.g., `faces_my_example_video.zip`, `faces_my_example_video.gif`).

4. **Set Custom FPS (Optional)**: If you wish to extract faces at a different frame rate than the original video, you can set a custom value for FPS. Leave this setting unchanged to use the video's original frames per second.

5. **Run the Application**: Execute the App script. Glimpsees will then process your video, detect first face (you can change it on line 65), and save each detected face per frame as a separate image.

6. **Generate GIF (Optional)**: After the App script completes, you can run the GIF script to compile all the extracted face images into an animated GIF.

## Open Source
Glimpsees is an open-source project. Feel free to fork the repository, explore the code, and contribute to its development!

## License
This project is licensed under the [MIT License](LICENSE) – see the [LICENSE file](LICENSE) for details.
