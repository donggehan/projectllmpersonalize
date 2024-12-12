---
layout: default
css: /assets/css/custom.css
---

<div style="text-align: center; margin-top: 40px; max-width: 100%;">
    <h1 style="font-size: 2.0em; margin-bottom: 20px; padding-bottom: 0;">LLM-Personalize: Aligning LLM Planners with Human Preferences via Reinforced Self-Training for Housekeeping Robots</h1>
</div>

<div style="text-align: center; margin-top: 20px;">
    <a href="https://arxiv.org/abs/2404.14285" style="background-color: #4dabf7; color: white; padding: 10px 20px; text-align: center; text-decoration: none; display: inline-block; font-size: 1.2em; margin-right: 20px; height: 30px; border-radius: 20px;">Arxiv</a>
    <a href="https://github.com/gdg94/codellmpersonalize" style="background-color: #4dabf7; color: white; padding: 10px 20px; text-align: center; text-decoration: none; display: inline-block; font-size: 1.2em; margin-right: 20px; height: 30px; border-radius: 20px;">Code</a>
    <a href="https://youtu.be/kyzRrVfgxsI"  style="background-color: #4dabf7; color: white; padding: 10px 20px; text-align: center; text-decoration: none; display: inline-block; font-size: 1.2em; margin-right: 20px; height: 30px; border-radius: 20px;">Youtube</a>
</div>

<div style="text-align: center; font-size: 1.1em; font-family: 'Times New Roman', Times, serif; margin-top: 40px; max-width: 100%;">
    COLING 2025
</div>

<div style="text-align: center; font-size: 1.1em; font-family: 'Times New Roman', Times, serif; margin-top: 40px; max-width: 100%;">
    Dongge&nbsp;Han, Trevor&nbsp;McInroe, Adam&nbsp;Jelley, Stefano&nbsp;V.&nbsp;Albrecht, Peter&nbsp;Bell, Amos&nbsp;Storkey
    <div style="font-size: 1.0em;font-style: italic; font-family: 'Times New Roman', Times, serif;">School of Informatics, University of Edinburgh, Edinburgh, United Kingdom.</div>
</div>


<div style="text-align: center; margin-top: 60px;">
    <video controls style="width: 90%; max-width: 800px;">
        <source src="data/video/iros_demo_slow.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
</div>

<div style="margin: 30px auto; max-width: 800px; padding: 20px; border: 0px solid #ccc; text-align: left;">
    <h2 style="font-size: 1.5em; margin-bottom: 20px;">Abstract</h2>
    <p style="font-size: 1.0em;"> Large language models (LLMs) have shown significant potential for robotics applications, particularly task planning, by harnessing their language comprehension and text generation capabilities. However, in applications such as household robotics, a critical gap remains in the personalization of these models to individual user preferences. We introduce LLM-Personalize, a novel framework with an optimization pipeline designed to personalize LLM planners for household robotics. Our LLM-Personalize framework features an LLM planner that performs iterative planning in multi-room, partially-observable household scenarios, making use of a scene graph constructed with local observations. The generated plan consists of a sequence of high-level actions which are subsequently executed by a controller.
    Central to our approach is the optimization pipeline, which combines imitation learning and iterative self-training to personalize the LLM planner. In particular, the imitation learning phase performs initial LLM alignment from demonstrations, and bootstraps the model to facilitate effective iterative self-training, which further explores and aligns the model to user preferences. We evaluate LLM-Personalize on Housekeep, a challenging simulated real-world 3D benchmark for household rearrangements, and show that LLM-Personalize achieves more than a 30 percent increase in success rate over existing LLM planners, showcasing significantly improved alignment with human preferences.</p>
</div>

<div style="margin-top: 10px; max-width: 800px; ">
    <h2 style="font-size: 1.5em; margin-bottom: 20px;">Citing Our Work</h2>
    <p style="font-size: 1.0em;">Our paper is available on Arxiv. If you find our code useful, please consider citing us!</p>
    <pre style="background-color: #f4f4f4; border-radius: 5px; border: 1px solid #ccc; padding: 20px; font-size: 0.9em; text-align: left; box-sizing: border-box; width: 100%; white-space: pre-wrap; word-wrap: break-word;">
@misc{han2024llmpersonalize,
      title={LLM-Personalize: Aligning LLM Planners with Human Preferences via Reinforced Self-Training for Housekeeping Robots}, 
      author={Dongge Han and Trevor McInroe and Adam Jelley and Stefano V. Albrecht and Peter Bell and Amos Storkey},
      year={2024},
      eprint={2404.14285},
      archivePrefix={arXiv},
      primaryClass={cs.RO}
}
</pre>
    <h2 style="font-size: 1.5em; margin-top: 40px; margin-bottom: 20px;">Acknowledgements</h2>
    <p style="font-size: 1.0em;">
    The <a href="https://yashkant.github.io/housekeep/" style="text-decoration: none; color: #4dabf7;">housekeep benchmark</a> and the housekeep simulator code used in this work is developed by Kant et. al. for their paper: 
    <a href="https://arxiv.org/abs/2205.10712" style="text-decoration: none; color: #4dabf7;">Housekeep: Tidying Virtual Households using Commonsense Reasoning.</a> 
    The simulator is based on the 
    <a href="https://github.com/facebookresearch/habitat-sim" style="text-decoration: none; color: #4dabf7;">Habitat simulator</a> 
    introduced in the paper 
    <a href="https://arxiv.org/abs/2106.14405" style="text-decoration: none; color: #4dabf7;">Habitat 2.0: Training Home Assistants to Rearrange their Habitat</a>.
</p>

</div>


