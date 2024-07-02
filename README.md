Overview

This script processes video files and manages related data by:

Uploading frames and locations to a MongoDB database.
Converting frame numbers to timecodes.
Generating and storing processed video clips.
Outputting data to an Excel file with embedded thumbnails.
Uploading video clips to Frame.io.
Key Features

Command-line Argument Parsing: Flexible input handling.
Video Processing with ffmpeg: Efficient and reliable video manipulation.
MongoDB Integration: Robust data storage and retrieval.
Automated Excel Report Generation: Create detailed reports with embedded thumbnails using pandas.
Frame.io Integration: Seamlessly upload video clips to Frame.io.


Usage -

Clone the repository and run the script with appropriate arguments:
python your_script.py --baselight <path_to_baselight_file> --xytech <path_to_xytech_file> --process <path_to_video_file> --output <output_excel_file>

Installation -

Install the required Python packages:
pip install -r requirements.txt
