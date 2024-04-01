---
layout: default
css: /assets/css/custom.css
---

<div style="text-align: center; margin-top: 40px; max-width: 100%;">
    <h1 style="font-size: 2.0em; margin-bottom: 20px; padding-bottom: 0;">Aligning LLM Planners with Human Preferences via Reinforced Self-Training for Housekeeping Robots</h1>
    <p style="font-size: 1.3em;">*Under submission to IROS 2024*</p>
</div>

<div style="text-align: center; margin-top: 20px;">
    <a href="https://arxiv.org/abs/YOUR_ARXIV_ID" style="background-color: #4dabf7; color: white; padding: 10px 20px; text-align: center; text-decoration: none; display: inline-block; font-size: 1.2em; margin-right: 20px; height: 30px; border-radius: 20px;">Arxiv Link</a>
    <button style="background-color: grey; color: white; padding: 10px 20px; text-align: center; border: none; font-size: 1.2em; width: auto; min-width: 160px; height: 50px; border-radius: 20px;">Code: To be released</button>

</div>

<div style="text-align: center; font-size: 1.1em; margin-top: 40px; max-width: 100%;">
    Dongge&nbsp;Han, Trevor&nbsp;McInroe, Adam&nbsp;Jelley, Stefano&nbsp;V.&nbsp;Albrecht, Peter&nbsp;Bell, Amos&nbsp;Storkey
    <p style="font-size: 1.0em;">School of Informatics, University of Edinburgh, Edinburgh, United Kingdom.</p>
</div>


<div style="text-align: center; margin-top: 60px;">
    <video controls style="width: 90%; max-width: 800px;">
        <source src="data/video/iros_demo_slow.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
</div>

<div style="margin: 60px auto; max-width: 800px; padding: 20px; border: 0px solid #ccc; text-align: left;">
    <p style="font-size: 1.0em;"><strong>Abstract:</strong> Large language models (LLMs) have shown significant potential for robotics applications, particularly task planning, by harnessing their language comprehension and text generation capabilities. However, in applications such as household robotics, a critical gap remains in the personalization of these models to individual user preferences. We introduce LLM-Personalize, a novel framework with an optimization pipeline designed to personalize LLM planners for household robotics. Our LLM-Personalize framework features an LLM planner that performs iterative planning in multi-room, partially-observable household scenarios, making use of a scene graph constructed with local observations. The generated plan consists of a sequence of high-level actions which are subsequently executed by a controller.
    Central to our approach is the optimization pipeline, which combines imitation learning and iterative self-training to personalize the LLM planner. In particular, the imitation learning phase performs initial LLM alignment from demonstrations, and bootstraps the model to facilitate effective iterative self-training, which further explores and aligns the model to user preferences. We evaluate LLM-Personalize on Housekeep, a challenging simulated real-world 3D benchmark for household rearrangements, and show that LLM-Personalize achieves more than a 30 percent increase in success rate over existing LLM planners, showcasing significantly improved alignment with human preferences.</p>
</div>
