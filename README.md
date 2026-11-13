# YOLO Density-Aware Traffic Light System

An AI-powered web application that detects real-time vehicle density at intersections using a YOLO deep learning model and adjusts traffic signal timing based on vehicle count and emergency vehicle presence.

Built as my M.Sc. Computer Science final-year project.

## Features

- Real-time vehicle detection using a YOLO model and OpenCV
- Adaptive signal control: signal durations change with the number of vehicles detected
- Emergency vehicle priority in the signal logic
- User authentication
- Video upload with live detection output
- Analytics dashboard
- SQLite database for detection history and signal logs
- Automated PDF report generation

## Tech Stack

Python, YOLO (Ultralytics), OpenCV, Streamlit, SQLite

## Project Files

| File | Purpose |
|---|---|
| `app.py` | Main Streamlit application |
| `requirements.txt` | Python dependencies |
| `*.pt` | Trained YOLO model weights |

## Models

- `best.pt`: [FILL IN: what this model detects, e.g. vehicles]
- `amb.pt`: [FILL IN: what this model detects, e.g. emergency vehicles]
- `amb1.pt`: [FILL IN, or delete this line if the file is removed]

## How to Run

Python 3.11 is recommended.

```bash
git clone https://github.com/iamthowfeek-coder/yolo-traffic-light-system.git
cd yolo-traffic-light-system
python -m venv venv
venv\Scripts\activate        # Windows (on Linux/Mac: source venv/bin/activate)
pip install -r requirements.txt
streamlit run app.py
```

If the `streamlit` command is not found, use `python -m streamlit run app.py`.

## Notes

- Database files and sample videos are not included in this repository. Use your own traffic video to try the detection.

<!--
## Screenshots
Add screenshots to a docs/ folder, then remove the comment marks around this section:
![Login](docs/login.png)
![Detection](docs/detection.png)
![Dashboard](docs/dashboard.png)
-->

## Author

J. Kother Thowfeek
[GitHub](https://github.com/iamthowfeek-coder) | [LinkedIn](https://www.linkedin.com/in/kother-thowfeek-1739b22b1)
