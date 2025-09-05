
---

# Ex. No. 4 – Scenario-Based Report Development Utilizing Diverse Prompting Techniques

**DATE:**05.09.2025
**REGISTER NUMBER:**212223060075

---

## Aim

To design an AI-powered Smart Health Assistant named **MediGuide** that can help elderly patients manage chronic conditions such as diabetes, hypertension, and arthritis. The assistant must provide personalized tips, reminders, and emotional support while maintaining a natural conversational tone. Different prompting strategies are applied to improve the chatbot’s effectiveness.

---

## Case Study: Smart Health Assistant System

### Background

Elderly patients often struggle with managing multiple health issues. MediGuide aims to:

* Offer **daily health guidance**.
* Provide **medication reminders**.
* Deliver **empathetic responses** for emotional wellbeing.
* Support **multi-modal inputs** like voice and image.

### Target Users

* Senior citizens with chronic conditions.
* Caregivers and family members monitoring patients.

---

## Procedure

### Step 1: Select Prompting Techniques

The following techniques are tested:

1. Zero-Shot Prompting
2. Few-Shot Prompting
3. Chain-of-Thought Prompting
4. Role-Based Prompting
5. Multi-Modal Prompting

---

### Step 2: Apply Techniques to Use Cases

#### 1. Zero-Shot Prompting

| Use Case        | Input                                       | Prompt                                                    | Response                                                                                                           | Remarks                    |
| --------------- | ------------------------------------------- | --------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ | -------------------------- |
| Symptom Concern | “I feel dizzy after breakfast.”             | Give a reason for dizziness in elderly diabetic patients. | “Possible cause is postprandial hypotension or sugar imbalance. Monitor BP and sugar, consult doctor if frequent.” | Quick but not personalized |
| Quick Tip       | “Tell me something healthy I can do today.” | Provide one tip for arthritis patients.                   | “Do 5–10 min of stretching in the morning.”                                                                        | Fast and simple            |

---

#### 2. Few-Shot Prompting

| Examples Provided                      | User Query                                                            | Response                                                                                   |
| -------------------------------------- | --------------------------------------------------------------------- | ------------------------------------------------------------------------------------------ |
| Diabetic breakfast → Oatmeal with nuts | “What should I eat for dinner if I have both diabetes and arthritis?” | “Grilled salmon with broccoli and sweet potato helps with inflammation and sugar control.” |

*Strength*: Context-aware answers.
*Limitation*: Needs curated examples.

---

#### 3. Chain-of-Thought Prompting

| Use Case         | Input                                         | Reasoning Steps (shortened)                                                                         | Final Response                                                                                                |
| ---------------- | --------------------------------------------- | --------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- |
| Overdose Concern | “I think I took my arthritis medicine twice.” | 1. Identify medicine → 2. Check overdose risk → 3. Suggest monitoring → 4. Advise emergency contact | “If NSAID, may cause kidney/stomach issues. Don’t take more. Watch for symptoms, contact doctor immediately.” |

*Strength*: Safe and logical.
*Limitation*: Can be lengthy.

---

#### 4. Role-Based Prompting

| Role               | Input                  | Response                                                                      |
| ------------------ | ---------------------- | ----------------------------------------------------------------------------- |
| Friendly Companion | “I feel lonely today.” | “I’m here with you. Want me to play music or remind you to call a loved one?” |
| Wellness Coach     | “Motivate me to move.” | “Just 5 minutes of stretching will lift your mood and body. You can do it!”   |

---

#### 5. Multi-Modal Prompting

| Input Type | Example                                  | Response                                                                   |
| ---------- | ---------------------------------------- | -------------------------------------------------------------------------- |
| Image      | Upload pill bottle                       | “Prescription: Metformin 500mg. Take one tablet after breakfast & dinner.” |
| Voice Note | “My chest feels heavy and I’m sweating.” | “This could be cardiac-related. Please seek emergency help immediately.”   |

---

## Ethical Considerations

* Must protect patient privacy.
* Avoid giving wrong or risky medical advice.
* Should complement doctors, not replace them.

---

## Future Enhancements

* **Memory Support**: Remember past interactions.
* **Wearable Integration**: Smartwatch vitals monitoring.
* **Language Expansion**: Regional language support.
* **Caregiver Access**: Alerts to family/doctors.

---

## Result

The experiment demonstrates how **diverse prompting techniques** (zero-shot, few-shot, chain-of-thought, role-based, and multi-modal) significantly enhance the quality and safety of chatbot responses. MediGuide can thus serve as a reliable assistant for elderly healthcare.

---
