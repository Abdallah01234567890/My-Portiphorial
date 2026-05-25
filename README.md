Portfolio Backend API
Flask backend kwa portfolio website. Inahost kwenye Render.
Endpoints
Method	URL	Maelezo
GET	/	API status check
GET	/api/profile	Taarifa za kibinafsi
GET	/api/skills	Orodha ya skills
GET	/api/projects	Orodha ya projects
GET	/api/projects/<id>	Project moja

Jinsi ya Run Locally (kwenye kompyuta yako)
# 1. Install dependencies
pip install -r requirements.txt

# 2. Run server
python app.py

# 3. Fungua browser: http://localhost:5000
Deploy kwenye Render
    1. Push code hii GitHub
    2. Nenda render.com → New Web Service
    3. Connect GitHub repo yako
    4. Build Command: pip install -r requirements.txt
    5. Start Command: gunicorn app:app
    6. Bonyeza Deploy!
