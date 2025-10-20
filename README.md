#  Vehicle Detection and Counting using YOLOv8

##  Problem Statement
Traffic congestion is one of the most critical challenges in Pakistan’s urban areas, such as **Karachi, Lahore, Islamabad, and Rawalpindi**.  
Manual vehicle monitoring is inefficient and prone to human error, making it difficult for authorities to understand **real-time traffic flow**, **peak congestion hours**, and **road usage trends**.  
This leads to problems like:  
- Unpredictable travel times  
- Fuel wastage and pollution  
- Poor road infrastructure planning  
- Inefficient traffic signal timing  

---

##  Proposed Solution
This project presents an **AI-powered Vehicle Detection and Counting System** using the **YOLOv8 pre-trained model** implemented in **Google Colab**.  
The system automatically detects vehicles in uploaded traffic videos and counts them over time, generating insights that can be used for:  
- **Traffic flow analysis**  
- **Urban road planning**  
- **Smart traffic light systems**  
- **Environmental impact studies**

---

## Technology Stack
- **Programming Language:** Python  
- **Framework:** Google Colab  
- **Model:** YOLOv8 (Pre-trained from Ultralytics)  
- **Libraries Used:** OpenCV, Matplotlib, Ultralytics, NumPy  
- **Input:** Video uploaded via Google Drive  
- **Output:**  
  - Processed video with detected vehicles  
  - Vehicle count plotted over time  

---

##  How It Works
1. Mount Google Drive to access the uploaded traffic video.  
2. Load YOLOv8 pre-trained weights for object detection.  
3. Process each frame to detect and classify vehicles.  
4. Count vehicles and record counts over time.  
5. Plot the **vehicle count vs. time graph** using Matplotlib.  
6. Save the **resultant video** (with bounding boxes and detections) back to Google Drive.  

*(Full implementation is provided in the Google Colab notebook linked below.)*

---

##  Results
- The system successfully detects **multiple vehicles simultaneously** in real-time video.  
- Generates a **vehicle count graph** for visual analysis.  
- Detects cars, buses, trucks, and motorbikes with high accuracy using pre-trained YOLOv8.  

Example Insight:  
> Peak traffic hours between 8–9 AM showed the highest vehicle count — valuable data for traffic control departments.

---

##  Usefulness in Pakistan
- **Reduces manual traffic monitoring** and enables **automated data-driven decisions**.  
- Supports **CDA, LDA, and NHA** in identifying high-traffic areas for road expansions.  
- Helps in **smart city development**, **public transport route optimization**, and **pollution control**.  
- Enables **researchers** and **students** to extend this system for real-world traffic analytics.

---

##  Future Improvements
- Add **vehicle type classification** (Car, Truck, Bike, Bus).  
- Integrate **speed estimation** and **license plate recognition**.  
- Deploy as a **real-time web dashboard** for city authorities.  
- Use **YOLOv8n or YOLOv8s** for faster edge device deployment.

---

##  How to Run

###  Clone this Repository
```bash
git clone https://github.com/<your-username>/Vehicle-Detection-and-Counting-YOLOv8.git
cd Vehicle-Detection-and-Counting-YOLOv8
```

###  Run the Project in Google Colab
1. Open the Colab notebook provided in this repository.  
2. Mount your Google Drive.  
3. Upload your traffic video (e.g., `traffic.mp4`).  
4. Run all cells to generate detection results and vehicle count plots.  
5. The processed video and graph will be saved back to Drive automatically.

---

##  Learning Outcome
This project helps beginners in AI/ML to:
- Implement a real-world use case using a **pre-trained model**.  
- Understand **object detection and counting** concepts.  
- Gain hands-on experience with **OpenCV**, **YOLOv8**, and **data visualization**.

---
##  Results
<img width="1000" height="500" alt="vehicle_count_plot" src="https://github.com/user-attachments/assets/fead820f-b29c-4b22-8d74-0cf897584027" />

**<img width="1827" height="1002" alt="image" src="https://github.com/user-attachments/assets/65c7b430-1f9f-49e1-b392-0bdff1b05c3a" />



## Conclusion
The **Vehicle Detection and Counting System** provides a scalable and practical approach to analyzing traffic flow using AI.  
By applying it to real-world traffic videos, especially in congested cities of Pakistan, this system contributes to **smart urban mobility**, **road safety**, and **environmental improvement**.

---
### 🏷️ Made with Python 🐍 | Model: YOLOv8 🚀 | Author: Fatima Noor ✨
