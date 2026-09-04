# EX.NO.7 – DEVELOP A PROMPT-BASED APPLICATION

## Date: 27.08.2026
## Register No.: 212223060107

## AIM

To develop a prompt-based application using ChatGPT that acts as a **Personal Productivity Assistant** for managing daily tasks, organizing schedules, setting reminders, providing wellness suggestions, and answering general queries using natural language.

---

## AI TOOL REQUIRED

* ChatGPT
* Large Language Model (LLM)
* Internet connection

---

## INTRODUCTION

A **prompt-based application** is an application that uses natural-language instructions called **prompts** to interact with a Large Language Model (LLM). The quality of the output depends on how clearly the prompt is designed.

In this experiment, ChatGPT is used to develop a **Personal Productivity Assistant**. The assistant understands natural-language instructions and generates useful responses based on the user's requirements.

The application is designed to perform the following activities:

1. Manage daily tasks.
2. Prioritize tasks based on importance.
3. Create daily schedules.
4. Suggest suitable reminders.
5. Provide basic wellness tips.
6. Answer general queries.
7. Adapt responses according to user preferences.

---

## OBJECTIVE OF THE APPLICATION

The main objective is to demonstrate how prompt engineering can be used to convert a general-purpose LLM into an application designed for a specific purpose.

Instead of asking ChatGPT unrelated questions, a specific role and set of responsibilities are provided through a carefully designed prompt.

For example:

**General Prompt:**

"Help me with my tasks."

This may produce a vague response.

**Improved Prompt:**

"You are a personal productivity assistant. Organize my tasks according to priority and deadline. Create a practical schedule, suggest reminders, and provide short wellness tips. Ask for clarification if important information is missing."

The second prompt provides clear instructions and therefore produces a more useful response.

---

# PROMPT ENGINEERING

Prompt engineering is the process of designing and improving instructions given to an LLM to obtain the desired output.

In this experiment, the prompt is developed progressively.

### Level 1 – Simple Prompt

**Prompt:**

"Help me manage my daily tasks."

**Expected Response:**

The assistant provides general suggestions for organizing tasks.

---

### Level 2 – Role-Based Prompt

**Prompt:**

"Act as a personal productivity assistant and help me manage my daily tasks."

This tells the LLM what role it should perform.

---

### Level 3 – Detailed Prompt

**Prompt:**

"You are a personal productivity assistant. Help me manage my daily tasks, organize them according to priority and deadline, create schedules, suggest reminders, and provide wellness tips."

This provides specific responsibilities to the assistant.

---

### Level 4 – Advanced Prompt

**Prompt:**

"You are a personal productivity assistant. Help me manage my daily activities using natural language. Accept tasks from the user, identify their deadlines, classify them as high, medium, or low priority, and create a practical schedule. Suggest reminders for important tasks and identify possible scheduling conflicts. Provide simple wellness tips such as hydration, exercise, breaks, and sleep recommendations. Adapt your responses according to the user's preferences and previous instructions. Keep responses clear, organized, and easy to follow."

This is the final prompt used for the application.

---

# PROCEDURE

### Step 1: Identify the Requirements

The requirements of the personal productivity assistant are identified.

The assistant should be able to:

* Accept tasks in natural language.
* Identify deadlines.
* Assign priority levels.
* Organize pending tasks.
* Create schedules.
* Suggest reminders.
* Provide wellness tips.
* Answer general questions.
* Adapt to user preferences.

### Step 2: Define the Role

The LLM is given the role of a **Personal Productivity Assistant**.

This helps the model understand the purpose of the application.

### Step 3: Create the Prompt

A detailed prompt is created containing the responsibilities and expected behavior of the assistant.

### Step 4: Provide User Input

The user enters instructions using normal conversational language.

For example:

"I have to complete my assignment by 5 PM and study Java for two hours tonight."

### Step 5: Process the Prompt

ChatGPT analyzes the user's request and identifies:

* Tasks
* Deadlines
* Priority
* Required time
* Suitable schedule

### Step 6: Generate the Response

The LLM generates an organized response based on the prompt and user input.

### Step 7: Provide Feedback

The user can provide additional instructions.

For example:

"I prefer studying after 8 PM."

The assistant can modify the schedule accordingly.

### Step 8: Evaluate the Output

The generated response is checked to determine whether it satisfies the user's requirements.

---

# MAIN FEATURES

## 1. DAILY TASK MANAGER

The assistant accepts tasks using natural language and organizes them based on priority and deadline.

### User Input

"I need to complete my project report by 5 PM, revise Java tonight, and buy groceries."

### Output

**Today's Tasks:**

| Task                    | Priority | Deadline |
| ----------------------- | -------- | -------- |
| Complete project report | High     | 5:00 PM  |
| Revise Java             | Medium   | Tonight  |
| Buy groceries           | Low      | Evening  |

The assistant helps the user understand which task should be completed first.

---

# 2. TASK PRIORITIZATION

The assistant can classify tasks into different priority levels.

### Priority Levels

* **High Priority:** Urgent and important tasks.
* **Medium Priority:** Important but not immediately urgent.
* **Low Priority:** Tasks that can be completed later.

### Example

**Input:**

"I have an assignment due today, an exam next week, and I need to clean my room."

**Output:**

1. **High Priority:** Complete assignment.
2. **Medium Priority:** Prepare for next week's exam.
3. **Low Priority:** Clean the room.

---

# 3. SMART SCHEDULER

The assistant can create a daily schedule based on the user's available time.

### Input

"Create a schedule for me. I have college from 9 AM to 3 PM. I need to study Java, complete my assignment, and exercise."

### Output

**Suggested Schedule:**

* 9:00 AM – 3:00 PM → College
* 3:00 PM – 4:00 PM → Lunch and Rest
* 4:00 PM – 6:00 PM → Complete Assignment
* 6:00 PM – 6:30 PM → Break
* 6:30 PM – 7:00 PM → Exercise
* 7:30 PM – 9:00 PM → Java Study
* 9:00 PM onwards → Dinner and Relaxation

The schedule is generated according to the user's available time.

---

# 4. REMINDER SUGGESTION

The assistant can identify important tasks and suggest suitable reminder times.

### Input

"Remind me to submit my assignment tomorrow morning."

### Output

"Suggested reminder: Tomorrow at 9:00 AM – Submit assignment."

The assistant can also identify tasks that may be forgotten and recommend reminders.

---

# 5. WELLNESS TIPS GENERATOR

The assistant can provide simple wellness suggestions while planning the user's activities.

### Input

"Give me wellness tips for a busy study day."

### Output

* Drink enough water throughout the day.
* Take short breaks between study sessions.
* Avoid sitting continuously for long periods.
* Do some light physical activity.
* Reduce screen time during breaks.
* Maintain a regular sleep schedule.

The suggestions can be adapted based on the user's preferences.

---

# 6. GENERAL QUERY ANSWERING

The application can also answer general questions.

### Input

"What is Artificial Intelligence?"

### Output

"Artificial Intelligence is a technology that enables computers to perform tasks that normally require human intelligence, such as learning, reasoning, understanding language, and solving problems."

---

# 7. PREFERENCE ADAPTATION

The assistant can modify its responses according to user preferences.

### Example

**User:**

"I prefer studying in the evening."

**Assistant:**

"Okay. I will prioritize your study activities during evening hours when creating schedules."

### Another Example

**User:**

"Keep my schedules short and simple."

**Assistant:**

The assistant will generate a simple schedule instead of a detailed timetable.

This demonstrates how prompts and user feedback can be used to make the interaction more personalized.

---

# SAMPLE INTERACTION

### User Input

"I have an online test tomorrow. I need to revise SQL and Java, complete my assignment, and get enough sleep. Create a schedule."

### Assistant Output

**Priority Tasks:**

1. Complete assignment – High Priority
2. Revise SQL – High Priority
3. Revise Java – Medium Priority
4. Sleep – Essential

**Suggested Schedule:**

* 5:00 PM – 6:30 PM → Complete assignment
* 6:30 PM – 7:00 PM → Break
* 7:00 PM – 8:30 PM → SQL revision
* 8:30 PM – 9:00 PM → Dinner
* 9:00 PM – 10:00 PM → Java revision
* 10:00 PM onwards → Relax and prepare for sleep

**Reminder Suggestions:**

* Complete assignment before 6:30 PM.
* Revise important SQL concepts.
* Prepare for the test before sleeping.

---

# ADVANTAGES

1. Easy to interact with using natural language.
2. Reduces the effort required for manual task organization.
3. Helps users prioritize important activities.
4. Provides personalized schedules.
5. Can provide reminders and suggestions.
6. Can answer general queries.
7. Can adapt according to user preferences.
8. Demonstrates the practical use of Generative AI and prompt engineering.

---

# LIMITATIONS

1. The assistant depends on the quality of the prompt.
2. Generated responses may not always be completely accurate.
3. Basic ChatGPT interaction does not automatically create real-world reminders unless connected to a reminder or calendar service.
4. User preferences may need to be explicitly provided.
5. The application requires an LLM to generate responses.

---

# EXPECTED OUTPUT

The developed prompt-based application should successfully:

* Accept daily tasks using natural language.
* Identify and organize tasks.
* Assign priority levels.
* Create suitable schedules.
* Suggest reminders.
* Provide wellness tips.
* Answer general queries.
* Understand user feedback.
* Adapt responses according to user preferences.

---

# RESULT

Thus, a **prompt-based Personal Productivity Assistant** was successfully developed using ChatGPT. The experiment demonstrated the use of **prompt engineering and Large Language Models** to create a practical application for daily task management, scheduling, reminder suggestions, wellness guidance, and general query answering.

The experiment also helped in understanding how simple prompts can be progressively improved into detailed prompts to obtain more accurate, useful, and personalized responses from an LLM.
