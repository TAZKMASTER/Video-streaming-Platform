📹 Streamlit Video Streaming App
A simple and interactive web application built with Streamlit for video streaming. This app lets users select from multiple videos and play them directly in the browser with a clean and responsive user interface.

📝 Features
🎥 Stream Multiple Videos: Watch videos with just a click.
🖼️ Dynamic UI: Responsive layout with buttons for each video.
🛠️ Custom Titles: Each video is accompanied by a title for better identification.
🗃️ Reusable Components: Modular code for easy scalability and maintenance.
📂 Folder Structure
bash
Copy code
.
├── app.py                # Main Streamlit app file
├── videos/
│   ├── 20770858-hd_1080_1920_30fps.mp4
│   ├── 20600550-hd_1920_1080_30fps.mp4
│   ├── 20576968-hd_1920_1080_25fps.mp4
│   ├── 15921892-hd_1920_1080_50fps.mp4
│   ├── 6060027-hd_1080_1920_25fps.mp4
└── README.md             # Project documentation
🚀 How to Run
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/video-streaming-app.git
cd video-streaming-app
Install the required dependencies:

bash
Copy code
pip install streamlit
Place your video files in the videos/ folder.

Run the Streamlit app:

bash:

streamlit run app.py
Open the app in your browser at http://localhost:8501.

🛠️ Customization
Adding New Videos:

Update the video_data list in app.py with the new video file name and title:
python

video_data = [
    {"filename": "new_video.mp4", "title": "New Video Title"}
]
UI Adjustments:

Modify the layout, styles, or titles in the main() or play_video() functions.
📜 License
This project is licensed under the MIT License. Feel free to use, modify, and distribute as needed.

🙌 Contributions
Contributions, issues, and feature requests are welcome! Feel free to fork the repository and submit a pull request.
