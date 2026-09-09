# CS895 - Foundation Models for Data Science - 2026
## Practical Session - Talking to Foundation Models: Closed APIs vs. Open Weights

This hands-on session compares two fundamentally different approaches to getting a large language model to perform work:

*   **Closed-Source API:** Sending requests to Google Gemini over the internet.
*   **Open-Weight Local Model:** Running Google Gemma 3 directly on local GPU hardware.

By evaluating both approaches with the exact same prompt, you can directly compare their generation speed, setup effort, cost, and data privacy implications.

## Running the Notebook

This notebook is intended to run on **Google Colab** using a **GPU (T4)** hardware accelerator. To complete the session, students will need to configure free accounts for both Google AI Studio and Hugging Face.

## Learning Outcomes

By the end of this practical, you will be able to:

*   Authenticate and send requests to a closed-source foundation model using the Gemini API.
*   Download and run an open-weight large language model locally.
*   Structure conversational prompts using chat templates for instruction-tuned models.
*   Evaluate the technical trade-offs between utilizing an API endpoint versus self-hosting model weights.

<br>

---

Instructor: [Rochana R. Obadage](https://rochanaro.github.io/)<br>
Last Updated: _08th September 2026_
