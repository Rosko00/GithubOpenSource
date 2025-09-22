- nainštaluj si Poetry - na správu Python závislostí
- naclonuj si projekt
- brew install postgresql
- brew services start postgresql
- createdb bracket

Backend (FastAPI)
- cd backend
- poetry install
- poetry run alembic upgrade head
- poetry run uvicorn app.main:app --reload
- Ip servera: http://127.0.0.1:8000

Frontend (Next.js)
- cd ../frontend
- npm install
- npm run dev
- Ip servera: http://localhost:3000

  Je to stiahnute z githubu. Je to opensource takže  to môžeš mať ako inšpiráciu pre tvoj projekt su tam pekné šablóny :-)
