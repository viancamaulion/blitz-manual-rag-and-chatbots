# ⚡ Code Cuts Blitz Activity: Build an RAG Chat App

### 🧠 Theme
Build a real-time chat app that responds using AI and retrieves knowledge from a sample company database.

### 🎯 Objectives
- Learn how to stream LLM outputs using streamText()
- Utilize vector embeddings and vector store for similarity search
- Use RAG (Retrieval-Augmented Generation) with Supabase vector search

---

## 🧩 The Challenge

### Your mission:  
In **1 hour**, create a **minimum viable RAG chat app** with the following features:

#### ✅ Required Features
1. **Basic real-time chat UI**
   - Show a list of messages and a message input box
   - Responds using `streamText()`
2. Uses RAG to augment responses
   - Perform a vector search using a matcher function in Supabase using the sample embeddings
   - Stream the search result in the AI prompt
  
That’s it — no tools, no model switching, no complex setup.

#### 🔧 Bonus Features (Optional)
- A card component that displays companies
   <img width="791" height="615" alt="image" src="https://github.com/user-attachments/assets/02cbd7ba-2a35-4d07-b480-941165a83656" />


### 🚀 Get some quick head start!
#### ✅ Recommended: Clone the boilerplate

```bash
git clone git@github.com:viancamaulion/chatbot-rag-boilerplate.git
```
#### 🧩 Optional Path: Set Up Your Own Supabase Instance & Project (⚠️ Recommended Only if You Want Full Control — Setup Takes More Time)

```bash
npm install @ai-sdk/openai@^1.3.23 @ai-sdk/react@^1.2.12 @supabase/supabase-js@^2.50.5 ai@^4.3.17 dotenv@^17.2.0 lucide-react@^0.525.0 next@15.3.5 openai@^5.9.0 react@^19.0.0 react-dom@^19.0.0 react-markdown@^10.1.0 && npm install -D @eslint/eslintrc@^3 @tailwindcss/postcss@^4 @types/node@^20 @types/react@^19 @types/react-dom@^19 eslint@^9 eslint-config-next@15.3.5 tailwindcss@^4 tsx@^4.20.3 typescript@^5
```


---

## 🧪 Output

Submit one of the following in the `#code-cuts` announcement thread:
- Screenshot of your output (Loom, GIF, video, or image file)
- GitHub repo with `README.md` (optional but it would be great!)
- Live demo (e.g., Vercel, Netlify) (optional)

---

## 🕐 Event Flow

| Time          | Activity |
|---------------|----------|
| `T+0 min`     | Assembly & Kick-off – Host explains activity |
| `T+15 min`    | Check attendance, questions allowed |
| `T+30 min`    | Halftime Check-in – Organizers go around and check in |
| `T+60 min`    | End of activity – Host calls for submissions |
| `T+60–90 min` | Presentations & Feedback (Volunteers share their work) |

---

## 📋 Judging Criteria (Just for feedback, not ranking)

| Criteria | Description |
|----------|-------------|
| Creativity | Did the idea push beyond “just another chatbot”? |
| Completion | Did it meet the 3 required features? |
| Code clarity | Is it understandable and maintainable? |
| Presentation | Can they explain what they built and how? |
| Bonus features | Any extra wow factor or polish? |

---

## 📚 Reference Links
- [RAG | AI SDK Docs](https://ai-sdk.dev/cookbook/guides/rag-chatbot)
- [Embeddings | AI SDK Docs](https://ai-sdk.dev/docs/ai-sdk-core/embeddings)
- [streamText() | AI SDK Docs](https://ai-sdk.dev/docs/reference/ai-sdk-core/stream-text#streamtext)
- [streamObject() | AI SDK Docs](https://ai-sdk.dev/docs/reference/ai-sdk-core/stream-object)
- [useChat() | AI SDK Docs](https://ai-sdk.dev/docs/reference/ai-sdk-ui/use-chat)


---

🛎️ **Reminder:** Submit your work to `#code-cuts` even if it's incomplete.  
🎤 Be ready to present or explain what you tried.
