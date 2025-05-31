<p align="center">
  <small>Best viewed in <a href="https://github.com/settings/appearance">Light Mode</a> and on a Desktop (Recommended)</small>
</p>

<div align="center">

# 🌴 AI RESUME ANALYZER 🌴

A Tool for Resume Analysis, Predictions, and Recommendations



</div>

---

## 📌 About the Project

<div align="center">
  <p align="justify">
    A tool that parses information from a resume using Natural Language Processing (NLP), extracts relevant keywords, clusters them by sectors, and provides recommendations, predictions, and analytics to the applicant or recruiter based on keyword matching.
  </p>
</div>

---

## 🎯 Scope

1. Convert resumes into structured tabular and CSV formats for analytics.
2. Provide resume improvement suggestions, predictions, and scores.
3. Increase traffic via a user-friendly interface and user engagement features.
4. Help colleges evaluate students' resumes before placements.
5. Offer analytics on trending job roles users seek.
6. Continuously improve the tool using user feedback.

---

## 🔧 Tech Stack

<details>
  <summary>Frontend</summary>
  <ul>
    <li><a href="https://streamlit.io/">Streamlit</a></li>
    <li><a href="https://developer.mozilla.org/en-US/docs/Learn/HTML">HTML</a></li>
    <li><a href="https://developer.mozilla.org/en-US/docs/Web/CSS">CSS</a></li>
    <li><a href="https://developer.mozilla.org/en-US/docs/Learn/JavaScript">JavaScript</a></li>
  </ul>
</details>

<details>
  <summary>Backend</summary>
  <ul>
    <li><a href="https://streamlit.io/">Streamlit</a></li>
    <li><a href="https://www.python.org/">Python</a></li>
  </ul>
</details>

<details>
  <summary>Database</summary>
  <ul>
    <li><a href="https://www.mysql.com/">MySQL</a></li>
  </ul>
</details>

<details>
  <summary>Python Modules</summary>
  <ul>
    <li><a href="https://pandas.pydata.org/">pandas</a></li>
    <li><a href="https://github.com/OmkarPathak/pyresparser">pyresparser</a></li>
    <li><a href="https://pypi.org/project/pdfminer3/">pdfminer3</a></li>
    <li><a href="https://plotly.com/">Plotly</a></li>
    <li><a href="https://www.nltk.org/">NLTK</a></li>
  </ul>
</details>

---

## 🚀 Features

### 🧑‍💻 Client

* Parse resume to extract:

  * Basic Information
  * Skills
  * Keywords
* Recommend:

  * Additional skills
  * Predicted job roles
  * Relevant courses and certificates
  * Resume tips
  * Videos for resume/interview tips
  * Overall resume score

### 👨‍💼 Admin

* View and export user data in CSV format.
* Access uploaded resumes.
* View feedback and ratings.
* Visual analytics through pie charts:

  * Ratings
  * Predicted roles
  * Experience levels
  * Resume scores
  * Geographic data (City, State, Country)

### 📝 Feedback

* Collect ratings (1–5) and comments via form.
* Show past feedback and overall rating analytics.

---

## 📦 Requirements

Make sure the following are installed:

1. Python 3.9.12: [Download](https://www.python.org/downloads/release/python-3912/)
2. MySQL: [Download](https://www.mysql.com/downloads/)
3. Visual Studio Code (Preferred): [Download](https://code.visualstudio.com/Download)
4. Visual Studio Build Tools for C++: [Download](https://aka.ms/vs/17/release/vs_BuildTools.exe)

---

## ⚙️ Setup & Installation

Follow these steps to run the project:

### 1. Clone the repository

```bash
git clone <repo-url>
```

### 2. Create and activate a virtual environment

```bash
python -m venv venvapp
cd venvapp/Scripts
activate
```

### 3. Install required packages

```bash
cd ../..
cd App
pip install -r requirements.txt
python -m spacy download en_core_web_sm
```

### 4. Set up the database

* Create a MySQL database named `cv`.
* Update the credentials in `App.py`.

### 5. Replace pyresparser script

Navigate to:

```
venvapp\Lib\site-packages\pyresparser
```

Replace `resume_parser.py` with the one provided in the `pyresparser` folder.

---

🎉 **Congratulations!** Your setup is complete.

Now, with your `venvapp` activated and working directory set to `App`, start the application:

```bash
streamlit run App.py
```

---

## ❗ Known Issues

* If you face a `GeocoderUnavailable` error, check your internet connection and speed.

---

## 🧪 Usage

* Upload a resume and watch the magic happen!
* Start testing with the sample resume in the `Uploaded_Resumes` folder.
* Admin credentials:

  * **Username**: `admin`
  * **Password**: `admin@resume-analyzer`



## 🛣️ Roadmap

* [x] Predict user experience level.
* [x] Add scoring criteria for skills and projects.
* [x] Recommendations for web, Android, iOS, and data science.
* [ ] Add roles and recommendations for other domains.
* [x] Extract more resume details.
* [ ] Add view for individual user details.

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you'd like to improve.

