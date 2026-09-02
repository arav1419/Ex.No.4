# Ex.No.4-EXP 4 Generate the Prompt and evaluate that for following prompt patterns - Zero-shot Prompting.•	Few-shot Prompting - Chain of Thought -	Persona Pattern - Reverse Prompting - Graph Prompting - Active Prompting

### DATE:  2/9/26  

### REGISTER NUMBER : 212224060023

### Aim: To write the prompt for the following prompt types and compare that with different AI tools and evaluate that using any one evaluation method (Ex. 
Rubrics). Zero-shot Prompting.•	Few-shot Prompting - Chain of Thought -	Persona Pattern - Reverse Prompting - Graph Prompting - Active Prompting 


# Use Case : 

## Drone Navigation using AI and Computer Vision

### Scenario

Autonomous drones are increasingly used for surveillance, agriculture, disaster management, and package delivery. AI enables drones to detect obstacles, plan safe routes, and reach destinations efficiently using sensors, GPS, and computer vision.

### Target Audience

- AI engineers
- Robotics students
- Drone developers
- Researchers
- Automation companies

### Main Objectives

- Improve navigation accuracy.
- Avoid obstacles automatically.
- Minimize travel time.
- Optimize battery consumption.
- Ensure safe autonomous flight.

---

# Prompt Design and Evaluation

## 1. Zero-shot Prompting

### Prompt

> Explain how an AI-powered drone navigates autonomously while avoiding obstacles.

### Expected AI Response

The AI drone uses GPS, cameras, LiDAR, and sensors to identify its surroundings. It processes real-time data using machine learning algorithms to detect obstacles, plan the safest route, and adjust its flight path automatically until it reaches the destination.

### Observation

The model generates a complete response without being provided with any examples.

---

## 2. Few-shot Prompting

### Prompt

**Example 1**

**Input:** Detect a tree in front of the drone.  
**Output:** Change direction to avoid collision.

**Example 2**

**Input:** Low battery detected.  
**Output:** Return to the home location automatically.

**Now Answer**

**Input:** Strong wind detected during flight.

### Expected AI Response

Reduce speed, stabilize flight using onboard sensors, and if conditions become unsafe, return safely to the launch point.

### Observation

Providing examples helps the AI understand the expected response format and improves consistency.

---

## 3. Chain of Thought Prompting

### Prompt

> A drone must deliver medicine to a village. Explain step by step how it plans the safest route while avoiding obstacles and minimizing battery usage.

### Expected AI Response

1. Receive destination coordinates.
2. Collect GPS and sensor information.
3. Detect nearby obstacles.
4. Calculate multiple possible paths.
5. Select the shortest safe route.
6. Monitor battery continuously.
7. Adjust the route if new obstacles appear.
8. Reach the destination safely.

### Observation

The response follows a logical sequence, making the reasoning process easier to understand.

---

## 4. Persona Pattern

### Prompt

> You are an experienced drone navigation engineer. Explain how AI improves autonomous drone navigation.

### Expected AI Response

As a drone engineer, I use AI algorithms to combine GPS, camera, and sensor data. The system predicts obstacles, selects efficient flight paths, reduces energy consumption, and continuously adapts to environmental changes for safe navigation.

### Observation

The response reflects the perspective and expertise of a drone navigation professional.

---

## 5. Reverse Prompting

### Prompt

> A drone successfully avoided birds, reached its destination, and returned safely with minimum battery consumption. What prompt could have generated this response?

### Expected AI Response

Design an AI-based drone navigation system that avoids moving obstacles such as birds, optimizes battery usage, selects the safest route, and returns safely after completing its mission.

### Observation

The AI infers the original prompt from the desired output.

---

## 6. Graph Prompting

### Prompt

> Represent the workflow of an AI-powered drone navigation system as a flow diagram.

### Expected AI Response

```text
Start
   ↓
Receive Destination
   ↓
Collect GPS & Sensor Data
   ↓
Detect Obstacles
   ↓
Plan Safe Route
   ↓
Navigate
   ↓
Monitor Battery
   ↓
Reach Destination
   ↓
Mission Complete
```

### Observation

Graph prompting organizes the information visually, making workflows easier to understand.

---

## 7. Active Prompting

### Prompt

> Analyze whether the drone should continue flying if heavy rain begins during navigation. If additional information is required, ask follow-up questions before giving the final recommendation.

### Expected AI Response

The AI first asks questions such as:

- What is the drone's waterproof rating?
- How much battery remains?
- How severe is the rainfall?
- How far is the destination?

After receiving the information, it recommends either continuing the mission or returning safely based on the risk assessment.

### Observation

The AI actively gathers missing information before making a decision, improving accuracy.

---

# Outputs for Each Prompting Technique

## 1. Zero-shot Prompting

### Prompt
Explain how an AI-powered drone navigates autonomously while avoiding obstacles.

### AI Output

An AI-powered drone uses GPS, cameras, LiDAR, and ultrasonic sensors to understand its surroundings. It continuously collects real-time environmental data and processes it using AI algorithms. The system detects obstacles such as trees, buildings, and power lines, then calculates the safest flight path. During the flight, the drone automatically changes its direction or altitude whenever a new obstacle is detected, ensuring safe and efficient navigation until it reaches its destination.

---

## 2. Few-shot Prompting

### Prompt

Example 1

Input: Detect a tree in front of the drone.

Output: Turn right by 30° and continue flying.

Example 2

Input: Battery level drops below 20%.

Output: Return to the home location automatically.

Now answer:

Input: Heavy fog detected during flight.

### AI Output

Output: Reduce flight speed, activate obstacle avoidance sensors, switch to safe navigation mode, and return to the home location if visibility becomes critically low.

---

## 3. Chain of Thought Prompting

### Prompt

A drone must deliver medicine to a remote village. Explain step by step how it plans the safest route while avoiding obstacles and minimizing battery usage.

### AI Output

Step 1: Receive the destination coordinates.

Step 2: Load the digital map of the area.

Step 3: Collect GPS, camera, and LiDAR sensor data.

Step 4: Detect obstacles such as buildings, trees, birds, and power lines.

Step 5: Generate multiple possible routes.

Step 6: Compare routes based on safety, travel distance, and battery consumption.

Step 7: Select the optimal route.

Step 8: Monitor weather conditions continuously.

Step 9: Modify the flight path if new obstacles appear.

Step 10: Reach the destination safely and return if required.

---

## 4. Persona Pattern

### Prompt

You are an experienced drone navigation engineer. Explain how AI improves autonomous drone navigation.

### AI Output

As a drone navigation engineer, I rely on AI to improve both safety and efficiency. The AI system combines information from GPS, cameras, LiDAR, and onboard sensors to create a real-time understanding of the environment. It predicts possible obstacles before they become dangerous, calculates the safest route, and continuously updates the flight path. This significantly reduces human intervention, improves navigation accuracy, and extends battery life during autonomous missions.

---

## 5. Reverse Prompting

### Prompt

A drone successfully avoided birds, reached its destination safely, minimized battery consumption, and returned to its launch point. Generate the prompt that could have produced this response.

### AI Output

Design an AI-powered drone navigation system that uses GPS, computer vision, and obstacle detection to safely avoid moving obstacles such as birds, optimize battery usage, calculate the shortest safe route, complete the delivery mission, and return automatically to the launch point.

---

## 6. Graph Prompting

### Prompt

Represent the workflow of an AI-powered drone navigation system as a flow diagram.

### AI Output

```text
Start
   │
   ▼
Receive Destination
   │
   ▼
Collect GPS & Sensor Data
   │
   ▼
Detect Obstacles
   │
   ▼
Analyze Environment
   │
   ▼
Plan Safe Route
   │
   ▼
Navigate Drone
   │
   ▼
Monitor Battery & Weather
   │
   ▼
Update Route if Needed
   │
   ▼
Reach Destination
   │
   ▼
Mission Complete
```

---

## 7. Active Prompting

### Prompt

Determine whether the drone should continue flying if heavy rain starts during navigation. Ask for any missing information before making a recommendation.

### AI Output

Before making a decision, I need the following information:

1. What is the drone's battery level?
2. Is the drone waterproof?
3. How heavy is the rainfall?
4. How far is the destination?
5. Is there a safe landing location nearby?

Based on the answers:

- If the drone is waterproof, battery level is above 60%, and rainfall is light, continue the mission while reducing speed.
- If rainfall is heavy or battery is low, return to the launch point or land safely at the nearest secure location.

# Comparison with Different AI Tools

| Prompt Type | ChatGPT | Google Gemini | Microsoft Copilot |
|-------------|----------|---------------|-------------------|
| Zero-shot Prompting | Detailed and accurate | Clear explanation | Moderate detail |
| Few-shot Prompting | Learns examples effectively | Good consistency | Adequate |
| Chain of Thought | Well-structured reasoning | Logical explanation | Basic reasoning |
| Persona Pattern | Natural expert response | Professional style | Brief |
| Reverse Prompting | Highly accurate prompt generation | Good | Moderate |
| Graph Prompting | Clear workflow representation | Good flow | Simple diagram |
| Active Prompting | Excellent follow-up questioning | Good clarification | Limited questions |

---

# Evaluation Method – Rubrics

## Evaluation Criteria

| Criteria | Excellent (5) | Good (4) | Average (3) |
|----------|---------------|----------|-------------|
| Reasoning | Logical and complete | Mostly logical | Basic reasoning |
| Correctness | Highly accurate | Minor errors | Some inaccuracies |
| Token Usage | Efficient and concise | Moderate | Slightly verbose |

---

## Rubrics Scores

| AI Tool | Reasoning | Correctness | Token Usage | Total / 15 |
|----------|-----------|-------------|-------------|------------|
| ChatGPT | 5 | 5 | 5 | **15** |
| Google Gemini | 4 | 5 | 4 | **13** |
| Microsoft Copilot | 4 | 4 | 4 | **12** |

---

# Result Analysis

- **ChatGPT** generated the most logical, accurate, and concise responses across all prompting techniques.
- **Google Gemini** produced technically correct responses with good reasoning but occasionally used more tokens.
- **Microsoft Copilot** provided shorter responses suitable for quick understanding but with less detailed reasoning.

---

# Conclusion

This experiment successfully demonstrated the use of advanced prompting techniques for an AI-based Drone Navigation System. Zero-shot prompting generated responses without examples, few-shot prompting improved consistency using sample inputs, chain-of-thought prompting enhanced logical reasoning, persona prompting produced expert-level explanations, reverse prompting inferred the original query from the output, graph prompting presented workflow visually, and active prompting improved decision-making through follow-up questions. Based on the evaluation using reasoning, correctness, and token usage, ChatGPT achieved the highest overall score due to its clear reasoning, high accuracy, and efficient response generation.

---

# Result

Thus, the advanced prompting techniques were implemented successfully, compared across different AI tools, and evaluated using a rubric-based method. The Drone Navigation case study demonstrated that selecting the appropriate prompting technique significantly improves AI reasoning, correctness, and response efficiency for engineering applications. Thus, the experiment successfully achieved its objective of understanding and evaluating advanced prompt engineering techniques for real-world engineering scenarios.
