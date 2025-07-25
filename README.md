# 🤖 Evaluator-Optimizer Workflow

The **Evaluator-Optimizer** pattern utilizes two large language model (LLM) calls working together — one to generate content (the optimizer), and another to evaluate it (the evaluator). This iterative loop helps improve quality by generating feedback and refining the response based on it.

---
<div align="center">
  <img src="https://github.com/RishulGupta/Evaluator-optimizer/blob/429aa39d13e2b86fb2fe34e4bbf1bc89f87ff010/Screenshot%202025-07-24%20210918.png" width="600">
  <img src="https://github.com/RishulGupta/Evaluator-optimizer/blob/429aa39d13e2b86fb2fe34e4bbf1bc89f87ff010/Screenshot%202025-07-24%20210846.png" width="200">
</div>


## 🔄 How It Works

1. The **optimizer** LLM creates an initial draft or output.
2. The **evaluator** LLM assesses the output using defined criteria and offers feedback.
3. The optimizer uses the feedback to revise the output.
4. This loop continues until the result meets the desired  standard.

---

## ✅ When to Use

This approach is well-suited for scenarios where:

- Clear evaluation criteria are available
- Iterative refinement improves quality
- LLMs are capable of self-assessing or mimicking expert feedback

Examples include document writing, code generation, summarization, and explanation tasks.

---

## 🧠 Technologies Used

- LLMs (Large Language Models)
- Iterative refinement strategy
- Prompt design and evaluation logic

---

## ⬇️ How to Download / Clone

To get a local copy of this project, run the following command:

```bash
git clone https://github.com/RishulGupta/Evaluator-optimizer.git
