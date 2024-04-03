---
layout: page
title: Reality Labs Research
permalink: /portfolio/reality-labs-research/
---

<center>
<b>Location:</b> Redmond, WA<br>
<b>Time Frame:</b> September 2021 - September 2023 
</center>

<div>
![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=csharp&logoColor=white) ![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Rust](https://img.shields.io/badge/rust-%23000000.svg?style=for-the-badge&logo=rust&logoColor=white)  
</div>

![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) ![Mercurial](https://img.shields.io/badge/mercurial-999999.svg?style=for-the-badge&logo=mercurial&logoColor=white) ![Perforce Helix](https://img.shields.io/badge/-PERFORCE%20HELIX-00AEEF?style=for-the-badge&logo=Perforce&logoColor=white)

![Rider](https://img.shields.io/badge/Rider-000000.svg?style=for-the-badge&logo=Rider&logoColor=white&color=black&labelColor=crimson) ![PyCharm](https://img.shields.io/badge/pycharm-143?style=for-the-badge&logo=pycharm&logoColor=black&color=black&labelColor=green) ![CLion](https://img.shields.io/badge/CLion-black?style=for-the-badge&logo=clion&logoColor=white) ![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white) ![Vim](https://img.shields.io/badge/VIM-%2311AB00.svg?style=for-the-badge&logo=vim&logoColor=white)

![Unity](https://img.shields.io/badge/unity-%23000000.svg?style=for-the-badge&logo=unity&logoColor=white) ![Unreal Engine](https://img.shields.io/badge/unrealengine-%23313131.svg?style=for-the-badge&logo=unrealengine&logoColor=white)

<p>The majority of my work done for RL-R is currently under NDA. As more publications, patents, and hardware is released, I'll be adding it to this portfolio. For the time being, the following is all I can share.</p>  

### Text Input Based Research

The majority of the work I contributed to at RL-R involved devices briefly discuss and showcased in [this](https://tech.facebook.com/reality-labs/2021/3/inside-facebook-reality-labs-wrist-based-interaction-for-the-next-computing-platform/) article. While I didn't work on the hardware itself, I utilized the data from the hardware to create a text-input system within the Unity3D engine. The system was first designed to be a one-off system used for a research study, however, upon working with three interns all needing similar functionality, it quickly evolved into an SDK.  

<iframe src="https://www.facebook.com/plugins/video.php?href=https%3A%2F%2Fwww.facebook.com%2FTechatMeta%2Fvideos%2F1146186389155473%2F%3Fref%3Dembed_video&show_text=0&width=560" width="700" height="394" style="border:none;overflow:hidden;display:block" scrolling="no" frameborder="1" allowfullscreen="true" allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share" allowFullScreen="true"></iframe>

The first of the papers published that utilized this text-input SDK can be found [here.](https://dl.acm.org/doi/10.1145/3581641.3584072) Support for various text-input methods including swipe-typing, single-character input, and predictive dictionary suggestions were provided. The text-input decoding used various methods and language libraries; each method also being an option within the SDK.

<link
      rel="alternate"
      type="application/json+oembed"
      href="https://iframe.videodelivery.net/oembed?url=https%3A%2F%2Fiframe.videodelivery.net%2FeyJraWQiOiI3YjgzNTg3NDZlNWJmNDM0MjY5YzEwZTYwMDg0ZjViYiIsImFsZyI6IlJTMjU2In0.eyJzdWIiOiI4MzkyZjNiODlkZmM2Zjk5MzQwMTljZDhmZGE5Yjg4ZCIsImV4cCI6MTcxMjEzMTY4NCwia2lkIjoiN2I4MzU4NzQ2ZTViZjQzNDI2OWMxMGU2MDA4NGY1YmIifQ.QrvFTLmpzgK1NRW7hoLphCS_bqwtH2Jurbk_e0W0G4-SmUhT-i2VO6reXaOcJ8whYAq3uIis9TJFWp-kUi-6GWT-ohuUbSMHLfjIQjwC63wcT76vnd69EdBY0EozthwKtcHQwz-cnk1QHi8qcsSaFeEAEhlU9_7e2-gWmQOmB-tNooQ7P08RoNL64a3eMLxBqWyUWrwnBC9KLI8MCZwfwim8Ptf7Pq2dqhAIAbDimCrTjzdnA2tmGrpUQ3J96fqNpDsoYeSIfhplyFcIf3QGVO_GEI8O-9xAC5FBmpQ-GX167P5YKr7DSBMt6R5IIvOUTwUV2wLtiHddV6IscwgOnA%3Fposter%3Dhttps%253A%252F%252Fvideodelivery.net%252FeyJraWQiOiI3YjgzNTg3NDZlNWJmNDM0MjY5YzEwZTYwMDg0ZjViYiIsImFsZyI6IlJTMjU2In0.eyJzdWIiOiI4MzkyZjNiODlkZmM2Zjk5MzQwMTljZDhmZGE5Yjg4ZCIsImV4cCI6MTcxMjEzMTY4NCwia2lkIjoiN2I4MzU4NzQ2ZTViZjQzNDI2OWMxMGU2MDA4NGY1YmIifQ.QrvFTLmpzgK1NRW7hoLphCS_bqwtH2Jurbk_e0W0G4-SmUhT-i2VO6reXaOcJ8whYAq3uIis9TJFWp-kUi-6GWT-ohuUbSMHLfjIQjwC63wcT76vnd69EdBY0EozthwKtcHQwz-cnk1QHi8qcsSaFeEAEhlU9_7e2-gWmQOmB-tNooQ7P08RoNL64a3eMLxBqWyUWrwnBC9KLI8MCZwfwim8Ptf7Pq2dqhAIAbDimCrTjzdnA2tmGrpUQ3J96fqNpDsoYeSIfhplyFcIf3QGVO_GEI8O-9xAC5FBmpQ-GX167P5YKr7DSBMt6R5IIvOUTwUV2wLtiHddV6IscwgOnA%252Fthumbnails%252Fthumbnail.jpg%253Ftime%253D10.0s"
    />
