# Chapter 5: Evaluation

## 🎯 Core Goal
To rigorously and objectively prove that your artifact achieves its stated goals and effectively answers your research questions, using the methodology defined in Chapter 3.

---

## ✅ Content Checklist (from `module_guidance_paper-structure-v2.md`)
- [ ] **Evaluation Setup:** Restate the evaluation goals and hypotheses.
- [ ] **Metrics:** Clearly define the quantitative metrics you measured.
- [ ] **Baselines:** Describe the implementation of the baseline/control group systems.
- [ ] **Environment:** Detail the experimental environment (hardware, software, network conditions).
- [ ] **Results Presentation:** Present the collected data objectively using clear tables and figures.
- [ ] **Statistical Analysis:** Report the results of any statistical tests performed (e.g., ANOVA, t-test).
- [ ] **Analysis of Results:** Analyze the data, explain the observed phenomena, and state whether the results support your hypotheses.

---

## ✍️ Suggested Sentence Starters (Academic Phrasebank)

**To set up the evaluation:**
*   `To evaluate the effectiveness of our proposed protocol, we conducted a comparative experiment.`
*   `Our evaluation is designed to test the following three hypotheses (H1-H3): ...`
*   `We compare our artifact against two baselines: a fully centralized API gateway (Baseline A) and a purely on-chain registry (Baseline B).`

**To present results:**
*   `The results of the experiment are summarized in Table [X].`
*   `Figure [Y] illustrates the query latency under different network loads.`
*   `As shown in the data, our hybrid protocol consistently outperforms the on-chain baseline in terms of...`

**To analyze results:**
*   `A one-way ANOVA was conducted to compare the effect of the three protocols on query latency. The result revealed a significant effect, F(2, N-3) = [...], p < .001.`
*   `These results support H1, demonstrating that our approach significantly reduces...`
*   `An interesting observation is the performance degradation of Baseline B as the registry size increases, which is likely due to...`

---

## 🔗 Logical Flow & Writing Tips
*   **Structure:** A good structure is: 1. State your goals/hypotheses. 2. Describe your method (setup, metrics, baselines). 3. Present the results objectively (the "what"). 4. Analyze the results (the "so what").
*   **Objectivity First:** In the results presentation part, just state the facts and describe what the charts show. Save the deeper interpretation and discussion of *why* for the analysis part and for Chapter 6.
*   **Link Back to RQs:** Explicitly state how your findings relate to the research questions you set out in the Introduction.
*   **Transition to Chapter 6:** The end of this chapter should summarize the key findings and set the stage for a broader discussion. Example: `In summary, our evaluation demonstrates that the proposed artifact successfully achieves a superior balance between decentralization and performance. The broader implications of these findings will be discussed in the next chapter.`
