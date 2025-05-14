---
category: Code Generation
type: Tool Generator
model: GPT-4
token-efficiency: High
updated: 2025-05-13
---

# 🔧 Prompt – AI Tool Generator (Python CLI/Web App)

## 🧠 Goal  
Generate a working script or starter code for a productivity tool, CLI utility, or simple web app.

## 🏗️ Cervia Prompt Blueprint

**Prompt:**

> You are an expert Python developer. Generate a working prototype for a [tool type] that [main function].  
>  
> Requirements:  
> - Use only Python and standard libraries  
> - Provide complete code  
> - Add comments and usage examples

## 🔄 Optional Variables  
- Tool type: Text summarizer | Currency converter | Email parser  
- Interface: CLI | Web (Flask) | Desktop (Tkinter)  
- Output format: JSON | Markdown | Plain text  

## 🧪 Sample Use  
**Tool:** "Text-to-Checklist Generator"  
**Function:** Converts paragraph into an actionable checklist  
**Interface:** CLI  

Run
python checklist.py "Plan the launch. Send emails. Post on Twitter."
## 🧠 Sample Output


- [ ] Plan the launch  
- [ ] Send emails  
- [ ] Post on Twitter
