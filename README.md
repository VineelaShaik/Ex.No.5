# EXP 5: COMPARATIVE ANALYSIS OF DIFFERENT TYPES OF PROMPTING PATTERNS AND EXPLAIN WITH VARIOUS TEST SCENARIOS
# AIM:
To test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios. Analyze the quality, accuracy, and depth of the generated responses.

# AI Tools Required:
CHATGPT
# Explanation:
Define the Two Prompt Types:
# Prompt 1: Write a short paragraph on the importance of teamwork.
<img width="1000" height="799" alt="image" src="https://github.com/user-attachments/assets/21375236-2259-4755-86d7-ca29b6c19184" />

# Prompt 2 : Explain Ohm’s Law in simple words.
<img width="265" height="190" alt="image" src="https://github.com/user-attachments/assets/66fadc90-9397-49b7-ac32-85cdadb26d46" />

# OUTPUT
Zero-Shot Prompting
# Definition:
Zero-shot prompting means giving the model a task with no prior examples.You only give a clear instruction, and the model uses its own knowledge to answer.It tests how well ChatGPT can perform a new task from just one prompt.

# Prompt 1 :
You are a communication coach. Explain the importance of teamwork in a simple paragraph for students.

# Output :
Teamwork is important because it helps people share ideas, divide tasks, and reach goals together. When team members communicate and support each other, they can solve problems more easily and build trust. Working as a team makes success easier and more enjoyable.

# Prompt 2:
You are a science teacher. Explain Ohm’s Law in simple words so that a beginner can understand it.

# Output :
Ohm’s Law says that the current in a circuit depends on voltage and resistance. When voltage increases, current increases; when resistance increases, current decreases. It helps us understand how electricity flows in wires and electronic devices.

Few-Shot Prompting
# Definition:
Few-shot prompting means giving two or more examples of input-output pairs before the actual question.This helps ChatGPT learn the style, tone, and structure you want from examples.

# Prompt 1:
# Example 1:
Input: Write a short paragraph on the importance of honesty.
Output: Honesty is important because it builds trust between people. When we are honest, others believe in us and respect us.

# Example 2:
Input: Write a short paragraph on the importance of time management.
Output: Time management helps us stay organized and complete tasks on time. It reduces stress and improves success.

Input:
Write a short paragraph on the importance of teamwork.

# Output:
Teamwork is important because it helps people share ideas, divide tasks, and reach goals together. When team members communicate and support one another, they can complete work more efficiently and develop trust. Working as a team leads to success and unity.

# Prompt 2:
# Example 1:
Input: Explain Newton’s First Law in simple words. 
Output: Newton’s First Law says that an object will stay at rest or keep moving unless an outside force acts on it.

# Example 2:
Input: Explain Hooke’s Law in simple words.
Output: Hooke’s Law says that the more you stretch a spring, the more it pulls back.

# Input:
Explain Ohm’s Law in simple words.

# Output:
Ohm’s Law explains the relationship between voltage, current, and resistance.When voltage increases, current increases.When resistance increases, current decreases.It helps us understand how electricity flows in wires and devices.

# Chain-of-Thought Prompting
# Definition:
Chain-of-thought prompting asks ChatGPT to explain its thinking process step-by-step before presenting the final answer. This improves the logic, detail, and clarity of the response.

# Prompt:
Think step-by-step and explain:
What does teamwork mean?
Why is teamwork important?
What are its main benefits?

# Output:
Step 1: Teamwork means people working together to achieve a shared goal.
Step 2: It is important because it helps combine different ideas and skills to complete tasks efficiently.
Step 3: The main benefits include better communication, faster problem-solving, and stronger relationships.
Step 4: For example, a group of students working on a project succeed when they divide work equally and support each other.
Final Answer: Teamwork builds cooperation, trust, and helps people achieve goals more effectively.

# Evaluation Table:

<img width="1301" height="553" alt="image" src="https://github.com/user-attachments/assets/09662d7b-ec9b-4c5c-a5ff-b182796ea6d1" />

# Analysis
1.Quality:

Basic prompts produce better structured, more fluent, and readable answers.
Naïve prompts give short, rough responses that may lack clarity.

2.Accuracy:

Both Naïve and Basic prompts are mostly correct, but Basic prompts add more context, reducing chances of vague or incomplete answers.

3.Depth:

Basic prompts encourage explanations, reasoning, and examples.
Naïve prompts often stay at the definition level, giving less insight.

4.Consistency:

Basic prompts consistently score higher in all three categories.
Naïve prompts may work only for very common knowledge, but not for detailed or complex tasks.
# RESULT:
The prompt for the above said problem executed successfully

