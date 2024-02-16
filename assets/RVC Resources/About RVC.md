---
icon: chevron-right
order: 5000
visibility: private
---

``Last update: Feb 14, 2024``

‎
:   ‎

## Introduction :icon-book:
***
- RVC (Retrieval-Based Voice Conversion) is an advanced AI voice cloning software, considered the best one to date. Developed by the <u>[RVC-Project team](https://github.com/RVC-Project/Retrieval-based-Voice-Conversion-WebUI)</u>.

- It was designed for desktop, requiring great specs to run it effectively, specially GPU for training models (specifically NVIDIA).

- Though it can be executed through the <u>[cloud](https://aihubdocs.github.io/en/other/glossary/#cloud-based)</u> & be used in any device, in case you don't meet the previous requirement.        
‎       
‎       
***
## Forks :icon-repo-forked:
***

RVC has quite a few <U>[forks](https://aihubdocs.github.io/en/other/glossary/#fork)</u> made by the public, each one meeting different needs for the user, and with its pros & cons.     

These are the main ones, along with their cloud-based versions:       

{.list-icon}
- #### :icon-chevron-right: <u>[Mainline](https://github.com/RVC-Project/Retrieval-based-Voice-Conversion-WebUI)</u> (Original RVC)
###### ‎    
{.list-icon}
- #### :icon-chevron-down: <u>[Applio](https://applio.org/)</u>
    - #### :icon-chevron-right: <u>[Applio Colab](https://colab.research.google.com/github/iahispano/applio/blob/master/assets/Applio.ipynb)</u>
###### ‎   
{.list-icon}
- #### :icon-chevron-down: <u>[Mangio](https://github.com/Mangio621/Mangio-RVC-Fork)</u>
    - ##### :icon-chevron-right: <u>[RVC Disconnected]()</u>
    - ##### :icon-chevron-right: <u>[Ilaria RVC]()</u>
###### ‎  
{.list-icon} 
- #### :icon-chevron-down: <u>[AICoverGen](https://github.com/SociallyIneptWeeb/AICoverGen)</u>     
    - ##### :icon-chevron-right: <u>[AICoverGen NO UI](https://colab.research.google.com/drive/1u1brjK8IZt647UsbZuGYfW29oFM2I4tk?usp%3Dsharing&sa=D&source=editors&ust=1704303145687891&usg=AOvVaw3M9tmokG80RXF-GD1LJqCL)</u>
    - ##### :icon-chevron-right: <u>[AICoverGen UI]()</u>

###### ‎   
!!!success
For a usage guide, check their respective pages on this website.
!!!
###### ‎       


***
## FAQ :icon-question:
***

==- ***What's the best fork?***
###### ‎       
- As explained before, it depends on your needs.        
- It's best to try them yourself. <u>[Mainline](https://aihubdocs.github.io/en/rvc/local/mainline/)</u> is a great starting point for newbies.
===

==- ***What are the requirements for RVC locally?***
###### ‎      
- The **recommended** minimum specs vary depending if it's for training models or <u>[inference](https://aihubdocs.github.io/en/other/glossary/#inference)</u>.
+++ For Training
**SPEC** | **REQUIREMENT** | 
:---: | :---: | :---: |
Operating System | Windows 10 or 11 | 
GPU | NVIDIA RTX 2060ti | 
RAM | 16GB
STORAGE | 30 GB

+++ For Inference
**SPEC** | **REQUIREMENT** | 
:---: | :---: | :---: |
Operating System | Windows 10 or 11 | 
GPU | NVIDIA GTX 1050ti | 
RAM | 8GB
STORAGE | 6 GB
+++
###### ‎    
!!! <u>NOTES:</u>
- If you don't meet these requirements, it's more convenient to use RVC through the <u>[cloud](https://aihubdocs.github.io/en/other/glossary/#cloud-based)</u>.
- Regarding GPUs, RVC is only compatible with NVIDIA. Learn below why.
!!!

=== 

==- ***Can I use it on my Intel/AMD GPU?***
###### ‎  
- You can, but it's not recommended, as these GPUs aren't compatible with AI software.
- Therefore RVC will be more prone to errors & will rely on your CPU, slowing down the speed significantly.
- So it's more convenient using RVC through the <u>[cloud](https://aihubdocs.github.io/en/other/glossary/#cloud-based)</u>.
=== 

==- ***How long does it take to train?***
###### ‎      
- The total time depends on a lot of factors, like dataset length, batch size, pretrains, specs, etc.

- A 10 min <u>[dataset](https://aihubdocs.github.io/en/vocal-isolation--datasets/datasets/)</u> with <u>[RMVPE](https://aihubdocs.github.io/en/rvc-resources/inference-settings/#pitch-extraction-algorithm)</u> may take you around 1 to 2 hours.
=== 

==- ***Can I run it on a Mac?***
###### ‎      
===

==- ***Do I need internet to use it?***
###### ‎      
- If you are using RVC locally, no.
- If you are using it through the cloud, then yes.
===

***
:::content-right
`Written by Julia`
:::
‎    
:::content-right
[!button variant="primary" corners="pill" icon="feed-discussion" iconAlign="right" text="Send Suggestions"](http://aihubdocs.github.io/en/#contributions)
:::
‎  
‎      
***