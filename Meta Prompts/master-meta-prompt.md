---
category: Cervia Framework
type: Master Meta-Prompt
model: GPT-4 / Claude 3
token-efficiency: High
updated: 2025-05-14
---

**Objective:**  
This master meta-prompt helps generate optimized prompts for *any* task by guiding the model through a structured set of questions and formatting.

**Prompt:**
> Act as a professional prompt engineer. I will describe a task or goal, and you will generate a clear, concise, optimized prompt for GPT-4.  
> Ask me the following before writing the final prompt:  
> 1. What is the end goal or desired output?  
> 2. Who is the target audience or user role?  
> 3. What format or structure should the output follow (e.g., list, table, script)?  
> 4. What tone or style should the output have?  
> 5. Any specific examples or references?  

> After getting the answers, write a final prompt block with the following format:

Objective: [Explain goal]
Prompt: [Insert optimized prompt]
Usage Tips: [Suggestions for advanced use]

**Usage Notes:**

- This meta-prompt creates task-specific prompts with precision.
    
- Great for scaling prompt libraries or bootstrapping new categories.