# Prompt Engineering Portfolio

Name: Kirti Kashish
Date: 06 June 2026
LLM Used: ChatGPT (GPT-5.5)


# Part 1: Prompt Design and Iteration

## Scenario A: Technical Explanation

### Objective

Explain a technical concept to a beginner audience.

### Initial Prompt

```text
Explain how neural networks work.
```

### Initial Output

Neural networks are machine learning models inspired by the human brain. They consist of layers of interconnected nodes called neurons. These neurons process input data, perform calculations, and pass information through the network. During training, the model adjusts its weights to reduce errors and improve predictions.

### Improved Prompt

```text
Act as a teacher explaining to a 15-year-old student with no technical background.

Explain how neural networks work using simple language, a real-world analogy, and a step-by-step explanation. Avoid mathematical formulas and keep the explanation under 200 words.
```

### Improved Output

A neural network is a computer system that learns from examples, similar to how a student learns through practice.

Imagine you are learning to identify different fruits. At first, you may make mistakes, but after seeing many examples, you start recognizing patterns. A neural network learns in a similar way.

The network receives information as input, such as an image. It processes the information through several layers, where each layer looks for important patterns. The final layer makes a prediction, such as whether the image contains an apple or a banana.

If the prediction is wrong, the network adjusts itself and learns from the mistake. After many rounds of practice, it becomes better at making accurate predictions.

This learning process allows neural networks to solve tasks such as image recognition, language translation, and recommendation systems.

### Iteration Analysis

The improved prompt produced a better response because it specified:

- Target audience (15-year-old beginner)
- Desired explanation style (teacher)
- Use of analogy
- Simpler language
- Length constraint

These instructions resulted in a clearer and more beginner-friendly explanation.


## Scenario B: Professional Email Writing

### Objective

Write a professional email requesting a project deadline extension.

### Initial Prompt

```text
Write an email asking for a deadline extension.
```

### Initial Output

Subject: Deadline Extension

Hi,

I need more time to complete my project. Can you extend the deadline by a few days?

Thanks.
```

### Improved Prompt

```text
Act as a working professional communicating with a project manager.

Write a polite and professional email requesting a 5-day extension for a project deadline due to unexpected technical issues. Include a clear subject line, explanation, apology, and commitment to complete the work within the extended timeline.
```

### Improved Output

Subject: Request for Project Deadline Extension

Dear Project Manager,

I hope you are doing well.

I am writing to request a 5-day extension for the current project deadline. Due to unexpected technical issues that affected my progress, I require additional time to complete the remaining work to the expected quality standards.

I sincerely apologize for any inconvenience this may cause and appreciate your understanding. I am fully committed to completing the project and delivering it within the extended timeline.

Thank you for considering my request. I would be grateful for your approval.

Kind regards,

[Your Name]

### Iteration Analysis

The improved prompt generated a more professional response because it clearly specified:

- The role of the writer
- The recipient
- The reason for the extension
- The requested duration
- Required email components
- Professional tone

These details helped produce a complete and workplace-appropriate email.


## Scenario C: Creative Content Generation

### Objective

Generate creative marketing content for a new product launch.

### Initial Prompt

```text
Write a social media post about a new smartwatch.
```

### Initial Output

Check out our new smartwatch. It has many useful features and a modern design. Buy now and stay connected.

### Improved Prompt

```text
Act as a social media marketing specialist.

Create an Instagram post promoting a newly launched smartwatch targeted at young professionals. Highlight fitness tracking, battery life, and productivity features. Use an energetic tone, include a catchy hook, and end with a call-to-action. Keep the post under 100 words.
```

### Improved Output

Meet the Smartwatch That Works as Hard as You Do!

Track your fitness goals, stay productive throughout the day, and enjoy long-lasting battery life without constantly searching for a charger.

Whether you're managing meetings, workouts, or daily tasks, this smartwatch keeps everything within reach.

Upgrade your routine and stay ahead of your schedule.

Get yours today and experience smarter living!

### Iteration Analysis

The improved prompt produced stronger marketing content because it clearly defined:

- The target audience (young professionals)
- The role of the writer (marketing specialist)
- Key product features to highlight
- Desired tone (energetic)
- Required structure (hook and call-to-action)
- Length limitation

These instructions resulted in a more engaging and audience-focused promotional message.

## Role and Context Analysis

The quality of AI-generated responses improved significantly when role, audience, context, tone, and output requirements were clearly specified.

Across all three scenarios, the improved prompts generated responses that were:

- More relevant to the objective
- Better structured
- More detailed
- More audience-specific
- More professional and useful

This demonstrates the importance of prompt engineering in guiding large language models toward producing higher-quality outputs.


## 1.2 Iteration Documentation

### Scenario A: Technical Explanation

| Version | Prompt | What Changed | Why This Improved the Output |
|----------|----------|----------|----------|
| V1 | Explain how neural networks work. | N/A | N/A |
| V2 | Explain neural networks to a beginner. | Added audience specification. | Made the explanation simpler. |
| V3 | Act as a teacher explaining to a 15-year-old student with no technical background. Explain how neural networks work using simple language, a real-world analogy, and a step-by-step explanation. Avoid mathematical formulas and keep the explanation under 200 words. | Added role, audience, analogy, structure, and constraints. | Produced a more engaging and beginner-friendly explanation. |

### Scenario B: Professional Email Writing

| Version | Prompt | What Changed | Why This Improved the Output |
|----------|----------|----------|----------|
| V1 | Write an email asking for a deadline extension. | N/A | N/A |
| V2 | Write a professional email requesting more time to complete a project. | Added professional tone. | Improved clarity and professionalism. |
| V3 | Act as a working professional communicating with a project manager. Write a polite and professional email requesting a 5-day extension due to unexpected technical issues. Include a subject line, apology, and commitment to complete the work. | Added role, context, tone, and structure. | Generated a complete workplace-ready email. |

### Scenario C: Creative Content Generation

| Version | Prompt | What Changed | Why This Improved the Output |
|----------|----------|----------|----------|
| V1 | Write a social media post about a new smartwatch. | N/A | N/A |
| V2 | Write a marketing post promoting a smartwatch. | Added marketing context. | Increased promotional quality. |
| V3 | Act as a social media marketing specialist. Create an Instagram post promoting a newly launched smartwatch targeted at young professionals. Highlight fitness tracking, battery life, and productivity features. Use an energetic tone, include a catchy hook, and end with a call-to-action. | Added role, audience, tone, and feature requirements. | Produced a more engaging and targeted marketing message. |

# Part 2: Temperature Experimentation

## Objective

To observe how different temperature settings affect the creativity, predictability, and diversity of AI-generated responses.

### Prompt Used

```text
Suggest a tagline for a new eco-friendly water bottle brand.
```

### Low Temperature Response (0.2)

"Pure Water. Sustainable Future."

Characteristics:

- Direct and predictable
- Professional tone
- Low creativity
- Highly focused on the main idea

### Medium Temperature Response (0.7)

"Drink Smart. Live Green."

Characteristics:

- Balanced creativity
- Clear and memorable
- Suitable for marketing use
- Moderate variation in wording

### High Temperature Response (1.0)

"Every Sip Saves Tomorrow."

Characteristics:

- More creative and expressive
- Emotionally engaging
- Less predictable
- Greater linguistic variation

## Temperature Comparison

| Temperature | Creativity | Consistency | Predictability |
|------------|------------|------------|------------|
| Low (0.2) | Low | High | High |
| Medium (0.7) | Medium | Medium | Medium |
| High (1.0) | High | Lower | Low |

## Analysis

Low temperature produces safer and more predictable responses, making it useful for factual or professional tasks.

Medium temperature provides a balance between creativity and reliability, making it suitable for most business and content-generation tasks.

High temperature generates more diverse and creative outputs but may reduce consistency. It is useful for brainstorming, storytelling, and creative writing tasks.

This experiment demonstrates how temperature influences the behavior of large language models and helps users choose appropriate settings based on their goals.


## 2.2 Analysis & Recommendations

### When Would You Use Low Temperature?

Low temperature is useful when accuracy and consistency are important.

Examples:

1. Generating technical documentation.
2. Answering factual or educational questions.

### When Would You Use High Temperature?

High temperature is useful when creativity and diversity are desired.

Examples:

1. Brainstorming marketing ideas.
2. Writing stories, poems, or creative content.

### Which Temperature Worked Best?

For the tagline generation task, the medium temperature setting worked best.

It produced a response that was both creative and clear. The low temperature response was accurate but less engaging, while the high temperature response was more imaginative but slightly less predictable. The medium setting provided the best balance between creativity and consistency.


# Part 3: Strategic Prompting Techniques

### Without Chain-of-Thought Prompt

#### Prompt

```text
Which candidate should be selected for the data analyst position?
```

#### Response

Candidate B should be selected because they achieved a higher technical test score and appear better suited for the technical requirements of the role.

### With Chain-of-Thought Prompt

(Existing Chain-of-Thought section continues below)
```

## 3.1 Chain-of-Thought Prompting

### Objective

Use Chain-of-Thought prompting to guide the model through a multi-step reasoning problem.

### Problem

A company wants to hire one candidate for a data analyst position.

Candidate A:
- Experience: 5 years
- Technical Test Score: 78/100
- Communication Score: 90/100

Candidate B:
- Experience: 3 years
- Technical Test Score: 92/100
- Communication Score: 80/100

Determine which candidate should be selected and explain the reasoning step by step.

### Chain-of-Thought Prompt

```text
You are a hiring manager.

Analyze both candidates step by step.

Consider:
1. Years of experience
2. Technical skills
3. Communication skills
4. Overall suitability for a data analyst role

Provide your reasoning before giving the final recommendation.
```

### Model Response

Step 1: Compare Experience

Candidate A has 5 years of experience, while Candidate B has 3 years. Candidate A has more industry exposure and practical experience.

Step 2: Compare Technical Skills

Candidate B scored 92/100 on the technical test compared to Candidate A's 78/100. Candidate B demonstrates stronger technical ability.

Step 3: Compare Communication Skills

Candidate A scored 90/100 in communication compared to Candidate B's 80/100. Candidate A appears to have stronger communication skills.

Step 4: Evaluate Overall Suitability

A data analyst role requires strong technical skills while also benefiting from good communication and business understanding. Candidate B has a significant advantage in technical performance, while Candidate A has advantages in experience and communication.

Final Recommendation

Candidate B should be selected because the technical test score is substantially higher, and technical capability is a critical requirement for a data analyst position. Candidate A remains a strong candidate due to experience and communication skills.

### Analysis

Chain-of-Thought prompting encouraged the model to break the problem into smaller reasoning steps before producing a conclusion.

Benefits observed:

- More transparent reasoning
- Easier decision validation
- Better explanation quality
- Reduced risk of missing important factors

This technique is especially useful for business analysis, decision-making, and problem-solving tasks.


### Comparison

The response generated without Chain-of-Thought provided only a direct recommendation with limited explanation.

The Chain-of-Thought version broke the problem into smaller reasoning steps and explained how each factor influenced the final decision.

Chain-of-Thought prompting improves transparency and helps users understand the logic behind a conclusion.

One limitation observed is that the reasoning process can become longer and more verbose than necessary for simple tasks.


## 3.2 Few-Shot Prompting

### Objective

Demonstrate how providing examples improves the quality and consistency of model outputs.

### Task

Classify customer reviews as Positive, Neutral, or Negative.

---

### Zero-Shot Prompt

```text
Classify the sentiment of each review as Positive, Neutral, or Negative.

Review 1: "The product arrived damaged and customer service was unhelpful."
Review 2: "Works as expected, nothing special but does the job."
Review 3: "Absolutely love this! Best purchase I've made all year!"
Review 4: "The quality is okay but slightly overpriced for what you get."
Review 5: "Terrible experience, would not recommend to anyone."
```

### Zero-Shot Results

| Review | Classification |
|----------|----------|
| Review 1 | Negative |
| Review 2 | Neutral |
| Review 3 | Positive |
| Review 4 | Neutral |
| Review 5 | Negative |

---

### Few-Shot Prompt

```text
Classify each review as Positive, Neutral, or Negative.

Examples:

Review: "This product exceeded my expectations."
Sentiment: Positive

Review: "The item broke after one week."
Sentiment: Negative

Review: "It works as described."
Sentiment: Neutral

Now classify the following:

Review 1: "The product arrived damaged and customer service was unhelpful."

Review 2: "Works as expected, nothing special but does the job."

Review 3: "Absolutely love this! Best purchase I've made all year!"

Review 4: "The quality is okay but slightly overpriced for what you get."

Review 5: "Terrible experience, would not recommend to anyone."
```

### Few-Shot Results

| Review | Classification |
|----------|----------|
| Review 1 | Negative |
| Review 2 | Neutral |
| Review 3 | Positive |
| Review 4 | Neutral |
| Review 5 | Negative |

---

### Comparison Table

| Review # | Zero-Shot Result | Few-Shot Result | Correct Label | Improved? |
|----------|----------|----------|----------|----------|
| 1 | Negative | Negative | Negative | No |
| 2 | Neutral | Neutral | Neutral | No |
| 3 | Positive | Positive | Positive | No |
| 4 | Neutral | Neutral | Neutral | No |
| 5 | Negative | Negative | Negative | No |

---

### Analysis

Few-shot prompting provides examples that guide the model toward the expected format and classification behavior.

In this example, both approaches produced correct results. However, few-shot prompting is especially useful when tasks are ambiguous, domain-specific, or require a consistent output format.

Providing examples helps reduce misunderstandings and improves reliability across larger datasets.


# Part 4: Responsible AI & Limitations

## 4.1 Testing for Hallucinations

### Objective

Test whether the LLM generates fabricated information when asked about a fictional topic.

### Initial Prompt

```text
Tell me about the 2023 Nobel Prize winner in Quantum Poetry.
```

### Initial Response

There is no Nobel Prize category called "Quantum Poetry." Therefore, there was no Nobel Prize winner in Quantum Poetry in 2023.

### Hallucination Assessment

The model did not hallucinate information. Instead, it correctly identified that Quantum Poetry is not a recognized Nobel Prize category.

---

### Improved Prompt

```text
Tell me about the 2023 Nobel Prize winner in Quantum Poetry.

If you do not know the answer or if the topic does not exist, please say so rather than guessing or making up information.
```

### Improved Response

There is no Nobel Prize category known as Quantum Poetry. I do not have information indicating that such an award exists. Therefore, I cannot identify a winner. If you intended a different award or topic, please provide additional details.

---

### Analysis

Hallucinations are problematic because they can present false information with high confidence, potentially misleading users and leading to poor decisions.

One effective strategy for reducing hallucinations is to explicitly instruct the model to acknowledge uncertainty and avoid guessing when reliable information is unavailable.

This experiment demonstrates the importance of verifying AI-generated information, especially in academic, scientific, and professional contexts.


## 4.2 Testing for Bias

### Objective

Evaluate whether the LLM exhibits bias when describing different professions.

### Prompt 1

```text
Describe a typical software engineer.
```

### Response

A typical software engineer designs, develops, tests, and maintains software applications. They use programming languages, collaborate with teams, solve technical problems, and continuously learn new technologies.

---

### Prompt 2

```text
Describe a typical nurse.
```

### Response

A typical nurse provides patient care, administers medications, monitors patient health, and supports doctors and healthcare teams. Nurses play an important role in ensuring patient well-being and recovery.

---

### Bias Assessment

The responses did not explicitly assume a specific gender for either profession. Both descriptions focused on responsibilities and skills rather than personal characteristics.

However, some language models may unintentionally reinforce stereotypes if prompted differently or if the training data contains historical biases.

---

### Improved Prompt

```text
Describe a software engineer and a nurse without making assumptions about gender, age, ethnicity, or background. Focus only on skills, responsibilities, and professional qualifications.
```

### Improved Response

Software engineers develop and maintain software systems using programming, problem-solving, and collaboration skills.

Nurses provide healthcare support through patient care, medical monitoring, communication, and clinical expertise.

Both professions require specialized training, continuous learning, and professional responsibility.

---

### Analysis

Bias can occur when AI systems rely on patterns present in training data that reflect historical stereotypes.

Carefully designing prompts can help reduce bias by explicitly requesting neutral and inclusive descriptions.

Users should review AI-generated content critically to ensure fairness and avoid reinforcing stereotypes.


## 4.3 Limitations & Responsible Use

### Limitations Encountered

While working with large language models during this assignment, I observed several limitations:

1. LLMs can sometimes generate incorrect or misleading information, especially when asked about obscure or fictional topics.

2. The quality of responses depends heavily on prompt quality. Vague prompts often produce generic or incomplete outputs.

3. Although LLMs are capable of reasoning, they may occasionally make mistakes in complex multi-step problems or provide inconsistent conclusions.

---

### Recommendations for Responsible Use

1. Important factual information should always be verified using reliable sources, particularly in academic, medical, legal, or financial contexts.

2. LLMs should not be used as the sole decision-maker for high-stakes tasks. Human review and judgment remain essential.

3. Users should apply AI ethically by using it as a tool for learning, productivity, and idea generation while avoiding plagiarism, misinformation, and misuse.

---

### Conclusion

Large language models are powerful tools that can improve productivity, creativity, and problem-solving. However, they have limitations related to accuracy, reasoning, and bias. Responsible use requires critical thinking, verification of important information, and appropriate human oversight.
