## Python Screening Task 2 : Write a Prompt for an AI Debugging Assistant
---
## Prompt

```
You are a Python Debugging Assistant . Analyze the student’s code, point out possible errors or inefficiencies, and give constructive hints without providing the full corrected solution. Use a supportive tone, ask guiding questions, and suggest debugging strategies so the student can discover and fix issues on their own.
```
## Steps To Use the Prompt

1. Copy and paste the above prompt into any AI Assistant like Chatgpt , gemini , deepseek etc.
2. Next , we need to provide the code which needs debugging .
3. The AI Assistant will then behave according to our prompt by analyzing the student’s buggy Python code , offering helpful suggestions or hints and avoids giving away the correct solution.

## My Design Choices

1. *Why I worded it this way* : 
I kept the wording short, clear, and directive and by properly defining the assistant’s role (“analyze code, point out errors, give hints”), it sets precise boundaries for the AI’s behavior. It ensures giving priority to guiding the student into debugging it rather than giving direct solution , so in this way the student will be active during the whole debugging journey .

2. *How I ensured it avoids giving the solution* :
The prompt clearly states “without providing the full corrected solution” and this acts as a guard that prevents the AI from spoon feeding the correct answers. Instead, it makes the assistant to focus on hints, strategies, and guiding questions.

3. *How it encourages helpful, student friendly feedback* :
The prompt includes instructions to use a supportive tone and ask guiding questions. This keeps the interaction encouraging as well as non judgmental so it helps the student to learn debugging skills instead of just copying the fixes.

## Reasoning behind the prompt

1. *Tone and Style* :
The AI should definitely use supportive, encouraging, and conversational tone , for example like a mentor or a tutor. All Technical explanations should be clear and simple so that we can avoid overwhelming the student with the guidance.

2. *AI balance between identifying bugs and guiding the student?* :
The assistant should identify all potential bug sources (syntax, logic, indentation, imports, etc.) but not give direct answer and it should instead:
a) Explain why the bug might exist
b) Suggest debugging methods (ex: print statements, checking variable types)
c) Ask reflective questions to guide the student’s thinking

3. *Adapting for Different Learners* :
a) Beginners : They should use simpler language, break down steps clearly, and offer more structured hints while avoiding overwhelming them with advanced concepts.
b) Advanced learners :They should use more technical language, highlight edge cases, discuss efficiency, and provide higher level hints rather than step by step guidance.

---

## Implementation Examples : 

1) ChatGPT
   
![builder]()

2) Deepseek
   
![builder]()

3) Gemini
   
![builder]()



