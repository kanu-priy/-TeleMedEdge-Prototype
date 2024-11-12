### TeleMedEdge - Deployment Instructions

#### Step 1: Clone the Repository
```bash
git clone https://github.com/yourusername/TeleMedEdge-Prototype.git
cd TeleMedEdge-Prototype

####Step 2: Set Up Environment Variables
PORT=5000
VULTR_API_KEY=your_vultr_api_key


Step 3: Run Backend
cd src/backend
npm install
npm start


Step 4: Run AI Diagnostic Model
cd src/ai-diagnosis
pip install flask
python diagnostic_model.py



Step 5: Run Frontend
cd src/frontend
npm install
npm start

