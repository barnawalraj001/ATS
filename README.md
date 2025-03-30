# **ATS Resume Expert**  

A **Streamlit** web application that analyzes resumes using **Google Gemini AI** and evaluates them against a job description. The tool extracts key insights and provides ATS-based percentage matching.  

## **🚀 Features**  

✅ Upload a **PDF resume**  
✅ Extract text & analyze resume using **Gemini AI**  
✅ Compare the resume with a **job description**  
✅ Provide **professional evaluation** of the resume  
✅ Generate **percentage match** with missing keywords  

---

## **🛠 Installation**  

### **1️⃣ Clone the Repository**  
```bash
git clone https://github.com/barnawalraj001/ATS.git
cd ats-resume-expert
```

### **2️⃣ Create a Virtual Environment**  
```bash
python -m venv myenv
```
Activate it:  
- **Windows:**  
  ```bash
  myenv\Scripts\activate
  ```
- **Linux/macOS:**  
  ```bash
  source myenv/bin/activate
  ```

### **3️⃣ Install Dependencies**  
```bash
pip install -r requirements.txt
```

### **4️⃣ Set Up API Key**  
Create a **.env** file in the project directory and add your **Google Gemini API key**:  
```
GOOGLE_API_KEY=your_google_api_key_here
```

---

## **📌 Usage**  

Run the Streamlit application:  
```bash
streamlit run app.py
```
Then, open the provided **localhost URL** in your browser.

---

## **📂 Project Structure**  
```
📦 ats-resume-expert
│── app.py               # Main Streamlit application
│── requirements.txt      # List of dependencies
│── .env                  # API key (Not shared in Git)
│── README.md             # Documentation
└── myenv/                # Virtual Environment (Generated)
```

---

## **🔧 Dependencies**  

Ensure you have the following installed:  
```bash
pip install streamlit python-dotenv pymupdf google-generativeai
```

---

## **🔹 How It Works?**  
1️⃣ Upload a **PDF Resume**  
2️⃣ Enter the **Job Description**  
3️⃣ Click **"Tell Me About the Resume"** to get a professional review  
4️⃣ Click **"Percentage Match"** to compare skills and get missing keywords  

---

## **👨‍💻 Author**  
Developed by **Raj Barnawal**  
