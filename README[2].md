# UNI Atlas Backend

This is a secure Node.js backend that connects your frontend AI search box to Google's Gemini 2.0 Flash model.

## How to Use

1. Install dependencies:
```bash
npm install
```

2. Add your Gemini API key to `.env`:
```
GEMINI_API_KEY=your-real-api-key
```

3. Start the server:
```bash
npm start
```

4. Send POST requests to:
```
http://localhost:3001/query-atlas
```
