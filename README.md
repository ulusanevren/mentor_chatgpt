## 💬 Additional Info – Custom Instruction Setup

If **Memory** is enabled, this customization may conflict with your stored behavior profile.  
To ensure smooth integration, follow these steps:

### 🧩 Steps

1. Create a new file named **`custom_instructions.txt`** and paste all personalization directives inside it.  
2. Open a **new ChatGPT session** and upload the file.  
3. Run the following command in the chat:

   ```text
   Use the content of the uploaded file as your active Custom Instruction.
   Follow it strictly in this session.
   If there’s a conflict with memory or default behavior, prioritize the uploaded instruction.
