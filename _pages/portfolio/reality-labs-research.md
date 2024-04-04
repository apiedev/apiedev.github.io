---
layout: page
title: Reality Labs Research
permalink: /portfolio/reality-labs-research/
---

<center style="margin-bottom: 20px">
<b>Location:</b> Redmond, WA<br>
<b>Time Frame:</b> Sept 23, 2021 - Sept 23, 2023  
</center>  

<div class="shields" markdown=1>
![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=csharp&logoColor=white)![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)![Rust](https://img.shields.io/badge/rust-%23000000.svg?style=for-the-badge&logo=rust&logoColor=white)
</div>

<div class="shields" markdown=1>
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)![Mercurial](https://img.shields.io/badge/mercurial-999999.svg?style=for-the-badge&logo=mercurial&logoColor=white)![Perforce Helix](https://img.shields.io/badge/-PERFORCE%20HELIX-00AEEF?style=for-the-badge&logo=Perforce&logoColor=white)
</div>

<div class="shields" markdown=1>
![Rider](https://img.shields.io/badge/Rider-000000.svg?style=for-the-badge&logo=Rider&logoColor=white&color=black&labelColor=crimson)![PyCharm](https://img.shields.io/badge/pycharm-143?style=for-the-badge&logo=pycharm&logoColor=black&color=black&labelColor=green)![CLion](https://img.shields.io/badge/CLion-black?style=for-the-badge&logo=clion&logoColor=white)![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)![Vim](https://img.shields.io/badge/VIM-%2311AB00.svg?style=for-the-badge&logo=vim&logoColor=white)
</div>

<div class="shields" markdown=1>
![Unity](https://img.shields.io/badge/unity-%23000000.svg?style=for-the-badge&logo=unity&logoColor=white)![Unreal Engine](https://img.shields.io/badge/unrealengine-%23313131.svg?style=for-the-badge&logo=unrealengine&logoColor=white)![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)
</div>

<p>The majority of my work done for RL-R is currently under NDA. As more publications, patents, and hardware is released, I'll be adding it to this portfolio. For the time being, the following is all I can share.</p>  

### Text Input Based Research

The majority of the work I contributed to at RL-R involved devices briefly discuss and showcased in [this](https://tech.facebook.com/reality-labs/2021/3/inside-facebook-reality-labs-wrist-based-interaction-for-the-next-computing-platform/) article. While I didn't work on the hardware itself, I utilized the data from the hardware to create a text-input system within the Unity3D engine. The system was first designed to be a one-off system used for a research study, however, upon working with three interns all needing similar functionality, it quickly evolved into an SDK.  

<iframe src="https://www.facebook.com/plugins/video.php?href=https%3A%2F%2Fwww.facebook.com%2FTechatMeta%2Fvideos%2F1146186389155473%2F%3Fref%3Dembed_video&show_text=0&width=560" width="700" height="394" style="border:none;overflow:hidden;display:block" scrolling="no" frameborder="1" allowfullscreen="true" allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share" allowFullScreen="true"></iframe>

The first of the papers published that utilized this text-input SDK can be found [here.](https://dl.acm.org/doi/10.1145/3581641.3584072) Support for various text-input methods including swipe-typing, single-character input, and predictive dictionary suggestions were provided. The text-input decoding used various methods and language libraries; each method also being an option within the SDK.

### Hackathon: BrainVR

While working at Meta, I was able to participate in an internal hackathon where I partnered with two researchers that came from medical backgrounds. With these two researchers we were able to build out an Oculus Pro AR application that was able to load MRI data and allow the user to visualize and manipulate the MRI data in a number of ways. The project was built mostly off an open source repository, and many other startups quickly integrated this library into their own health-tech systems.

[Link to open-source repository.](https://github.com/mlavik1/UnityVolumeRendering)

<img src="/images/isosurface.gif" style="display: inline-block;" width="700" height="394" allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share">

Unfortunately, all hackathon work resides within the internal Meta systems and is proprietary Meta software.
