## 📬 Postman Dump (API Testing)

You can test the Together AI API used in this project using Postman:

1. Import the collection:  
   `postman/postman_collection.json`

2. (Optional) Import the environment:  
   `postman/postman_environment.json`

3. In Postman, go to the top-right environment dropdown → select `Together-env`.

4. Replace `TOGETHER_API_KEY` with your real Together API key.

5. Use the request to test the LLM with inputs like:

```json
{
  "model": "meta-llama/Llama-3-70b-chat-hf",
  "messages": [
    { "role": "user", "content": "Explain photosynthesis" }
  ]
}
```

📡 Endpoint used:  
`https://api.together.xyz/v1/chat/completions`