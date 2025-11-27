Health Insights API with all biomarkers

This repository contains the FastAPI-based backend for the Health Insights System.

##  Getting Started

Follow these steps to get a local copy up and running.

📋 Prerequisites

Make sure you have the following installed:
- Python 3.9+
- pip (Python package manager)

Installation
1. Clone the Repository
git clone https://github.com/ranaidrees184/LLMSallBiomarkerwithoutRefTable.git

2. cd llmsmedicalinsightswithallBms

3. Create a Virtual Environment (Recommended)
   
   python -m venv venv
      
   source venv/bin/activate       # On Windows: venv\Scripts\activate

4. Install Dependencies

   pip install -r requirements.txt

5. Run the Application

   python -m uvicorn app:app --reload --host 0.0.0.0 --port 8000


The API will start locally at:
👉 http://127.0.0.1:8000

Interactive API docs are available at:
👉 http://127.0.0.1:8000/docs  

Deployment (General Instructions)

This API can run on any system that supports Python.
To deploy it:

Copy all project files to your server or environment.

Install dependencies with pip install -r requirements.txt.

Start the FastAPI app:

uvicorn app:app --host 0.0.0.0 --port 8000

Ensure port 8000 (or your chosen port) is open for access.

No additional setup, keys, or dependencies are required.

Testing the API

Once running, test endpoints via:

Browser Swagger UI: http://127.0.0.1:8000/docs

Curl/Postman: Send requests manually for validation.


Input Style is As Follow:

{
  "age": 52,
  
  "gender": "female",
  
  "height": 165,
  
  "weight": 70,
  
  "urea": 30,
  
  "creatinine": 1,
  
  "uric_acid": 5,
  
  "calcium": 9.5,
  
  "phosphorus": 3.5,
  
  "sodium": 140,
  
  "potassium": 4.2,
  
  "chloride": 102,
  
  "amylase": 70,
  
  "lipase": 35,
  
  "bicarbonate": 24,
  
  "egfr": 100,
  
  "serum_osmolality": 290,
  
  "ionized_calcium": 1.25,
  
  "wbc": 6,
  
  "hemoglobin": 14,
  
  "mcv": 90,
  
  "rdw": 13.5,
  
  "lymphocytes": 30,
  
  "fasting_blood_sugar": 85,
  
  "hb1ac": 5.4,
  
  "insulin": 10,
  
  "c_peptide": 1.2,
  
  "homa_ir": 1.2,
  
  "total_cholesterol": 180,
  
  "ldl": 90,
  
  "hdl": 50,
  
  "cholesterol_hdl_ratio": 3,
  
  "triglycerides": 120,
  
  "apo_a1": 140,
  
  "apo_b": 70,
  
  "apo_ratio": 0.5,
  
  "albumin": 4.2,
  
  "total_protein": 7,
  
  "alt": 25,
  
  "ast": 24,
  
  "alp": 120,
  
  "ggt": 20,
  
  "ld": 180,
  
  "globulin": 3,
  
  "albumin_globulin_ratio": 1.4,
  
  "magnesium": 2,
  
  "total_bilirubin": 0.7,
  
  "direct_bilirubin": 0.3,
  
  "indirect_bilirubin": 0.4,
  
  "ammonia": 35,
  
  "hs_crp": 1,
  
  "ck": 150,
  
  "ck_mb": 20,
  
  "homocysteine": 10,
  
  "zinc": 90,
  
  "copper": 100,
  
  "selenium": 120,
  
  "iron": 100,
  
  "tibc": 300,
  
  "transferrin": 250,
  
  "vitamin_d": 35,
  
  "vitamin_b12": 500,
  
  "total_testosterone": 450,
  
  "free_testosterone": 15,
  
  "estrogen": 60,
  
  "progesterone": 1,
  
  "dhea_s": 250,
  
  "shbg": 40,
  
  "lh": 5,
  
  "fsh": 6,
  
  "tsh": 2,
  
  "free_t3": 3.2,
  
  "free_t4": 1.2,
  
  "total_t3": 120,
  
  "total_t4": 8,
  
  "reverse_t3": 15,
  
  "tpo_ab": 5,
  
  "tg_ab": 3,
  
  "cortisol": 12,
  
  "acth": 25,
  
  "igf1": 200,
  
  "leptin": 10,
  
  "adiponectin": 10,
  
  "ca125": 20,
  
  "ca15_3": 25,
  
  "ca19_9": 30,
  
  "psa": 1,
  
  "cea": 2,
  
  "calcitonin": 5,
  
  "afp": 5,
  
  "tnf": 2,
  
  "ana": 0.5,
  
  "ige": 100,
  
  "igg": 1200,
  
  "anti_ccp": 10,
  
  "dsdna": 0.5,
  
  "ssa_ssb": 5,
  
  "rnp": 1,
  
  "sm_antibodies": 0.5,
  
  "anca": 0.5,
  
  "anti_ena": 0.5,
  
  "il6": 3,
  
  "allergy_panel": 10
  
}


“You can verify the request by pasting it directly into the Swagger interface and testing it there.”
