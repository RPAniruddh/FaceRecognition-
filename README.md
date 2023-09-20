# Face Recognition Attendance System

This Python script uses face recognition to track attendance in real-time. It captures video from the default camera and identifies known faces based on pre-trained encodings.

## Usage

1. Install the necessary libraries:

```bash
pip install face_recognition opencv-python numpy
```

2. Run the script:

```bash
python attendance_system.py
```

3. Follow the on-screen instructions:

   - The system will use your default camera to capture video frames.
   - Known faces (defined in the script) will be recognized, and attendance will be recorded.

## Dependencies

- face_recognition
- opencv-python
- numpy
- csv (built-in)
- datetime (built-in)

## Known Faces

- Ensure that you have images of known faces in the "Faces" directory.
- Uncomment the lines for additional images and encodings if needed.

## Student List

- Provide the names of known faces in the `known_face_names` list.

## Output

- The attendance data will be saved in a CSV file named with the current date (e.g., `yy-mm-dd.csv`).

## Example

```plaintext
Known faces detected:
1. John Doe

Press 'q' to exit the program.

Attendance recorded for John Doe.
```

## Note

- Make sure you have Python installed on your system.
- Ensure that the "Faces" directory contains images of the known faces in the format "1.jpg", "2.jpg", etc.
- You can adjust the script to accommodate additional faces.

## Author

[Aniuddh R Panicker](https://github.com/RPAniruddh)

---
