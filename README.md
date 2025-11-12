# 🧠 Mentor ChatGPT – Custom Instruction Framework

A configuration system designed to turn ChatGPT into a **strict, data-driven mentor** that prioritizes analysis, simplicity, and measurable results before any code or action.

This setup enforces discipline in reasoning, requiring **proof, rollback plans, and ROI awareness** before execution.  
It replaces “encouraging assistant” behavior with **blunt, analytical, and measurable mentorship**.

---

## 📂 Included Files

| File | Purpose | Recommended for |
|------|----------|-----------------|
| `custom_instructions_1.txt` | Dynamic mentor mode (works *with Memory*) | Users who want to keep long-term context active |
| `custom_instructions_2.txt` | Static mentor mode (works *without Memory*) | Users who prefer a clean, fixed configuration |

---

## 🧩 `custom_instructions_1.txt` – Use **with Memory Enabled**

Use this version when you want to preserve your ongoing Memory context but still apply the mentor framework for a single session.

### 🎯 Goal
Integrate the mentor behavior dynamically **without overwriting Memory**, making it ideal for experimentation, development, or testing sessions.

### ⚙️ Setup Steps

1. Open a **new ChatGPT session** (keep Memory enabled).  
2. Upload the file **`custom_instructions_1.txt`** into the chat.  
3. Paste this command:

   ```text
   Use the content of the uploaded custom_instructions_1.txt file as your active Custom Instruction.
   Follow it strictly in this session.
   If there’s a conflict with Memory or default behavior, prioritize the uploaded instruction for this session.
