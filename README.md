# Exno.7-Develop a prompt-based application tailored to their personal needs, fostering creativity and practical problem-solving skills while leveraging the capabilities of large language models.

# Date:23.10.2025
# Register no. 212222050011
# Aim: To develop a prompt-based application using ChatGPT - To demonstrate how to create a prompt-based application to organize daily tasks, showing the progression from simple to more advanced prompt designs and their corresponding outputs.

#AI Tools Required: 
ChatGPT
Lovable AI


# Explanation: 
Prompt:
"Design a personal productivity assistant that can help manage daily tasks, schedule reminders, suggest wellness tips, and answer general queries. The assistant should interact using natural language and be adaptable to the user’s changing preferences over time."
Procedure:
1. Define the core requirements of a personal productivity assistant.
2. Identify and construct appropriate prompts for each task using an LLM (e.g., ChatGPT).
3. Simulate natural user interaction through a simple interface or command-line system.
4. Collect feedback or inputs from users and adapt responses accordingly.
5. (Optional) Integrate basic memory to simulate preference adaptation.
EXPECTED OUTPUT: - (attached the drive link)
Output (Example Response by LLM):
Personal Productivity Assistant Features:
1. Daily Task Manager:
o Accept tasks via natural language (e.g., "Remind me to call mom at 6 PM").
o Organize tasks by priority and deadline.
o Provide daily summaries and pending items.
2. Smart Scheduler:
o Schedule events and set reminders using contextual understanding.
o Notify user of overlapping appointments or free time slots.
3. Wellness Tips Generator:
o Suggest daily wellness advice (hydration, exercise, screen-time breaks).
o Adapt suggestions based on past user preferences and responses.
**Experiment:**

## **Prompt:**

"Design a personal productivity assistant that can help manage daily tasks, schedule reminders, suggest wellness tips, and answer general queries. The assistant should interact using natural language and be adaptable to the user’s changing preferences over time."

## **Procedure**

### **Step 1: Define Core Requirements**

A **Personal Productivity Assistant** should be able to:

1. **Understand natural language** to communicate intuitively.
2. **Manage daily tasks** such as adding, deleting, updating, and listing tasks.
3. **Schedule reminders** with contextual time-based alerts.
4. **Provide wellness tips** (hydration, meditation, screen breaks, etc.) tailored to user behavior.
5. **Answer general knowledge queries** (e.g., “What’s the weather today?” or “Give me a motivational quote”).
6. **Adapt to user preferences** over time (e.g., noticing preferred tip types or productivity styles).


### **Step 2: Identify and Construct LLM Prompts**

Below are sample prompt designs to be used with an LLM such as ChatGPT:

| **Function**             | **Prompt Example**                                          | **Expected LLM Response**                                                   |
| ------------------------ | ----------------------------------------------------------- | --------------------------------------------------------------------------- |
| **Add a Task**           | “Add a new task to my list: Finish project report by 5 PM.” | “Got it! Task ‘Finish project report’ added and set for 5 PM.”              |
| **Check Tasks**          | “What are my pending tasks for today?”                      | “Here’s your list: 1) Finish project report, 2) Buy groceries.”             |
| **Set Reminder**         | “Remind me to attend the meeting at 3 PM.”                  | “Reminder set for 3 PM — Meeting.”                                          |
| **Suggest Wellness Tip** | “Give me a wellness tip for today.”                         | “Stay hydrated! Aim to drink 8 glasses of water today.”                     |
| **General Query**        | “What’s a motivational quote for the day?”                  | “Quote: ‘Success is not final; failure is not fatal.’ — Winston Churchill.” |
| **Adaptation Prompt**    | “I prefer short wellness tips.”                             | “Understood. I’ll keep future wellness tips brief and to the point.”        |



---

### **Step 3: Simulate Natural User Interaction (Command-Line Example)**

**Example Python pseudocode for simulation:**

```python
print("👋 Welcome to Your Personal Productivity Assistant!")
while True:
    user_input = input("You: ")
    if "add task" in user_input.lower():
        print("Assistant: Task added successfully!")
    elif "remind" in user_input.lower():
        print("Assistant: Reminder set!")
    elif "wellness" in user_input.lower():
        print("Assistant: Remember to take a 5-minute break and stretch.")
    elif "exit" in user_input.lower():
        print("Assistant: Goodbye! Stay productive 😊")
        break
    else:
        print("Assistant: Let me think about that... Here's a general tip: Stay focused!")
```

This can simulate **text-based interaction** through a simple interface.

---

### **Step 4: Feedback & Adaptation**

* The assistant stores user preferences like:

  * Preferred task style (short or detailed)
  * Active hours for reminders
  * Type of wellness tips (physical, mental, motivational)

**Example Adaptation Flow:**

* User frequently ignores “exercise” tips → Assistant switches to “hydration” or “mental wellness” tips.
* User prefers morning notifications → Assistant shifts daily summaries to 8 AM.

---

### **Step 5: (Optional) Integrate Memory for Preference Adaptation**

**Example Implementation:**
Store user preferences in a simple JSON file:

```json
{
  "preferred_wellness_type": "hydration",
  "reminder_time": "morning",
  "task_priority_style": "deadline-based"
}
```

When the assistant interacts again, it refers to these saved preferences to personalize responses.

---

## ✅ **Expected Output (Example Response by LLM)**

### **Personal Productivity Assistant Features**

#### 🗓️ **Daily Task Manager**

* Accepts tasks via natural language (e.g., “Remind me to call mom at 6 PM”).
* Organizes tasks by **priority** and **deadline**.
* Provides **daily summaries** and lists pending tasks.

#### ⏰ **Smart Scheduler**

* Schedules events and sets reminders contextually.
* Notifies users of **overlaps** and **free time slots**.
* Suggests best times for meetings based on previous data.

#### 💧 **Wellness Tips Generator**

* Suggests **daily health tips** (hydration, posture, eye breaks, etc.).
* Tracks user engagement and adapts suggestions over time.
* Encourages short physical activities during idle periods.

#### 💬 **General Query Responder**

* Answers simple factual, motivational, and time-based questions.
* Can provide quotes, news headlines, or weather updates.

#### 🧩 **Adaptive Learning**

* Adjusts tone, timing, and content based on user interactions.
* Learns preferred reminder styles (text, summary, detailed).
* Stores frequently used commands for faster responses.

---

### **Example Conversation:**

**User:** “Add a task to submit my report by 5 PM.”
**Assistant:** “✅ Task ‘Submit report’ added! I’ll remind you at 4:45 PM.”

**User:** “Give me a wellness tip.”
**Assistant:** “💧 Don’t forget to hydrate! Drink a glass of water now.”

**User:** “I prefer evening tips.”
**Assistant:** “Got it! I’ll start sending your wellness tips at 6 PM from tomorrow.”

“To-Do List for a Day” — from morning to evening — designed to keep you productive while maintaining a good balance between study/work and personal wellness 👇
<img width="1024" height="1536" alt="ChatGPT Image Oct 23, 2025, 09_07_03 AM" src="https://github.com/user-attachments/assets/ed1ed481-503e-4b06-84f3-bb307a631d87" />


# Result: 
The lab exercise resulted in the creation of a prototype concept for a personal assistant powered by large language models. Students were able to:
 Understand how to tailor LLM prompts to real-life applications.
 Foster creativity by designing features suited to their personal or academic lives.
 Learn prompt engineering techniques for optimal interaction with AI tools.
 Experience the versatility and utility of generative AI in solving everyday problems.
