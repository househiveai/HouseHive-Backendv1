# 🏠 HouseHive Backend (FastAPI)

### 🚀 Quick Deploy on Render
1. Create a new **Web Service** on [Render.com](https://render.com)
2. Connect this GitHub repo or upload this ZIP.
3. Set environment:
   - `OPENAI_API_KEY` = your key
   - `SECRET_KEY` = anything you want
4. Set **Start Command**:
   ```
   uvicorn main:app --host 0.0.0.0 --port $PORT
   ```
5. Click **Deploy**.

### ✅ Health Check
After it’s live, test:
```
https://your-app-name.onrender.com/api/health
```
It should return:
```json
{"status": "ok"}
```

Then connect your frontend with:
```
NEXT_PUBLIC_API_URL=https://your-app-name.onrender.com
```
