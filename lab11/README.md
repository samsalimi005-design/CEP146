# Lab 11 – AI Bias and Transparency

## Exercise 1: Resume Screening AI Bias Analysis

### Step 1: Basic Statistics

**Interview Rate (AI Decision)**

- Male candidates: 46 out of 50 = 92%
- Female candidates: 24 out of 50 = 48%

**Actual Qualification Rate**

- Male candidates: 38 out of 50 = 76%
- Female candidates: 35 out of 50 = 70%

### Step 2: Bias Analysis

**AI Accuracy by Group**

The exact accuracy cannot be calculated because the dataset does not identify which individual candidates are actually qualified.

- Male AI accuracy: Cannot be determined exactly.
- Female AI accuracy: Cannot be determined exactly.

**False Negatives**

- Males: Between 0 and 4 qualified candidates were rejected.
- Females: Between 11 and 26 qualified candidates were rejected.

The exact numbers require more information about each candidate's qualifications.

### Step 3: Impact Assessment

Total interview invitations: 46 + 24 = 70

If TechCorp hires 20 people in proportion to the AI recommendations:

- Males: 46 / 70 × 20 = approximately 13
- Females: 24 / 70 × 20 = approximately 7

This is not proportional to the actual qualification rates. Male and female candidates have similar qualification rates, but male candidates receive significantly more interview invitations.

### Step 4: Reflection Questions

**What evidence of bias do you see?**

The AI gives male candidates a 92% interview rate and female candidates a 48% interview rate. However, the actual qualification rates differ by only 6 percentage points. This suggests possible gender bias in the AI system.

**How might this bias have developed?**

The AI may have been trained using historical hiring data that favoured male candidates. It may have learned unfair patterns from previous hiring decisions.

**What would you recommend to fix this system?**

I would use balanced training data, remove unnecessary gender-related information, and regularly test the system for bias. Human experts should also review AI decisions to make sure qualified candidates are treated fairly.

## Exercise 2: AI Decision Transparency Testing

### Round 1: Black Box AI System

The AI denied Sarah's scholarship without explaining the reason.

The system did not provide information about the selection criteria, improvements, fairness, or the appeal process.

This type of interaction could make a user feel confused and frustrated because they cannot understand the decision or improve their application.

### Round 2: Transparent AI System

The AI explained the following factors:

- GPA: 76/100
- Standardized test scores: 45/100
- Volunteer work: 85/100
- Leadership experience: 20/100
- Overall score: Approximately 61/100
- Required score: 75/100

Sarah could improve her chances by submitting SAT scores and gaining leadership experience.

The explanation makes the decision easier to understand. However, transparency alone does not prove that the decision was fair. The appeal process is also not provided.

### Round 3: Medical AI Diagnosis Assistant

**How certain is the diagnosis?**

The AI estimates a 78% probability of Type 2 Diabetes. This is not a confirmed diagnosis.

**What factors led to this conclusion?**

High blood glucose, BMI, age, family history, low physical activity, and reported symptoms contributed to the result.

**What should the patient do next?**

The patient should consult a doctor for additional medical tests and professional advice.

**Could the AI be wrong?**

Yes. AI systems can make mistakes or use incomplete information.

**What would happen if the patient changed their lifestyle?**

Healthy lifestyle changes may help reduce health risks, but the patient should still consult a doctor.

## Reflection Worksheet

### Emotional Impact

Round 1 could make a user feel frustrated because the AI does not explain its decision. Round 2 feels more understandable because the AI provides specific reasons.

The transparent system feels fairer because users can understand how their information affects the result.

### Understanding

The transparent scholarship and medical AI systems provide better explanations. The most helpful information is the individual factors, their scores, and how they influence the final decision.

### Trust

I would trust the transparent AI system more because it explains its decisions. However, explanations should also be accurate, and important decisions should include human review.

### Actionability

In Rounds 2 and 3, users can take specific actions. Sarah can improve her scholarship application, and the patient can consult a doctor.

This is important because AI should help people understand their options instead of simply giving them a decision.

### Programming Implications

Programmers should build explainable AI because users deserve to understand important decisions that affect their lives.

Some AI models are complex, which makes their decisions difficult to explain. Programmers must also protect private information and ensure explanations are accurate.

A lack of transparency can become an ethical problem because unfair decisions may go unnoticed, and users may not have a way to challenge them.

## Group Discussion Questions

**Should all AI systems be required to explain their decisions?**

AI systems should provide explanations, especially when decisions affect employment, education, healthcare, or finances.

**Are there situations where transparency might be harmful?**

Yes. Sharing too much information could expose private data or allow people to manipulate security systems.

**How detailed should explanations be?**

The level of detail should depend on the importance of the decision. High-risk decisions should have more detailed explanations, while simple decisions may only need a short explanation.
