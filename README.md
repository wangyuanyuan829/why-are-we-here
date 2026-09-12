**Why Do Designers Still Need to Learn Programming When AI Excels at "Doing"? A Practical Reflection Based on AI E-Commerce Video Creation**

---

### I. Introduction: Framing the Problem

In 2026, artificial intelligence is capable of generating executable code from a single natural language instruction in English. In the realm of visual media, AI can seamlessly generate posters, advertisements, short-form videos, subtitles, and voiceover audio. This gives rise to a pressing practical question: If machines are becoming increasingly proficient at executing specific technical tasks, why do designers still need to learn programming? During my internship at ByteDance TikTok Shop, I participated in exploring AI-generated e-commerce videos. Through repeated experiments, I found that although AI significantly accelerated content production, it also introduced new challenges, including unpredictable outputs, inconsistent visual details, and difficulties in controlling generation results.

Rather than naively asserting that programming skills will never be rendered obsolete, this paper examines the evolving value of programming education in the age of generative AI, drawing upon my hands-on experience in generating e-commerce promotional videos with AI. The core thesis of this paper is that the significance of learning to program is shifting from "personally writing every line of code" toward "comprehending systems, establishing rules, validating outcomes, and assuming accountability."

---

### II. From Vague Description to Granular Control

Recent studies show that video-language models may produce visually plausible but factually inconsistent outputs, including temporal distortions and fabricated content [^3]. In AI-assisted video production, entering a prompt such as "generate a high-end product advertisement" rarely yields an output that meets professional requirements. This experience revealed that prompt engineering is not equivalent to controlling AI. Instead, prompts only influence the probability of certain outcomes without guaranteeing specific results. Models frequently distort product geometry, generate erroneous packaging text, or produce erratic character movements and incoherent camera logic. Consequently, designers must translate qualitative aesthetic goals into discrete, actionable conditions, including product color fidelity, shot sequencing, character kinematics, voiceover scripts, and brand compliance constraints.

This translation process mirrors the problem decomposition and logical structuring inherent to programming. While prompt engineering itself is not strictly equivalent to coding, crafting effective prompts demands the ability to convert ambiguous human intentions into explicit rules and systemic constraints.

---

### III. The "Gacha" Mechanism and Model Hallucinations

AI video generation possesses inherent stochasticity; Generative AI systems do not directly execute user intentions; instead, they sample outputs from learned probability distributions, resulting in variations even under identical conditions [^1]. During my AIGC e-commerce video production experience, I gradually realized that AI generation behaves more like a "gacha mechanism" rather than a traditional design tool. Even with carefully designed prompts, the model does not directly execute instructions but samples possible outputs based on learned patterns. Visual artifacts frequently arise—such as deformed hands, compromised product structural integrity, and broken temporal continuity between shots. For example, when generating product advertisements, some outputs correctly preserved product appearance, while others changed product structures, distorted materials, or produced unrealistic movements. These differences occurred even under similar prompt conditions. Voiceovers are similarly prone to phonetic garbling, incomplete semantics, or outright "gibberish" (phonemic hallucinations). More insidiously, flawed outputs often mask their errors behind realistic visual styling, appearing plausible while embedding deceptive or inaccurate information. Prompting provides a mechanism to guide model behavior, but it does not guarantee deterministic or controllable outputs [^2]. Therefore, designers need programming-based verification systems rather than relying solely on visual judgment.

As a result, designers can no longer merely serve as content generators; they must establish rigorous verification workflows to audit the alignment among product metadata, subtitles, voiceovers, and visual frames.

---

### IV. The Practical Value of Programming Education

Programming empowers designers to modularize the AI-driven creative workflow into discrete stages—scripting, storyboarding, generation, filtering, auditing, and post-production—while leveraging automation to enhance overall pipeline efficiency. In my internship, the workflow was not simply "prompt → generate → publish". Instead, it required continuous testing, filtering, evaluation, and optimization. This process is closer to system design than traditional visual creation. In the future, designers may no longer primarily focus on manually crafting individual frames; instead, their role will evolve toward designing generative systems, managing variables, handling edge-case exceptions, and evaluating output quality.

---

### V. Conclusion

While AI will undoubtedly automate repetitive tasks within both programming and design, it cannot autonomously define problem scope, exercise aesthetic judgment, or shoulder responsibility for the final outcome. For designers, learning to program is not about competing with AI in execution speed; rather, it is about maintaining the ability to understand, evaluate, and control AI systems when unexpected outputs occur.
[/] Markdown

# References

[^1]: Holtzman, A., et al. (2020).  
  [The Curious Case of Neural Text Degeneration](https://arxiv.org/abs/1904.09751).

[^2]: Liu, P., et al. (2023).  
  [Pre-train, Prompt, and Predict](https://doi.org/10.1145/3560815).

[^3]: Huang, Y., et al. (2026).  
  Distorted or Fabricated? A Survey on Hallucination in Video LLMs.
