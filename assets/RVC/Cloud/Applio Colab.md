---
icon: chevron-right
order: 5000
---

``Last update: Feb 22, 2024``

***
:::content-center
<img src="..\appliocolab-img\banner.png" alt="image" width="600">

:::

###### ‎
:::content-center
## Introduction ‎
:::
- Applio is a <u>[fork](https://aihubdocs.github.io/en/extra/glossary/#fork)</u> of <u>[Mangio](https://aihubdocs.github.io/en/rvc/local/mangio/)</u> developed by the <u>[IA Hispano</u>](https://github.com/IAHispano)</u> team.

- It's liked for its great **UI** & **lots** of extra features, such as TTS (with RVC models too), plugins, automatic model upload, customizable theme & more.

- Because of its user-friendly experience & active development, it's considered to be one of the best forks.     

- As this cloud version is hosted in <u>[Google Colab](https://aihubdocs.github.io/en/extra/glossary/#google-colab)</u>, remember that you have a runtime of 4 hours.       
‎         
#### Pros & Cons :icon-tasklist:
==- *Learn more*
!!! *The pros & cons are subjective to your necessities.*        
!!! 
||| ✔️ **PROS** 
- Very complete
- Has an active development
- TTS features            
- Automatic model upload
- Has Mangio-Crepe
- User-friendly UI
- TensorBoard included
||| ❌ **CONS** 
- A little slower compared w/ forks
- More unstable
- Usage limit for free users
||| 
===
***
###### ‎
###### ‎
:::content-center
## Setting Up
:::
###### ‎
1. Access the Colab space [here](https://colab.research.google.com/github/iahispano/applio/blob/master/assets/Applio.ipynb).
Then log in to your Google account.
***
2. Execute the **Install Applio** cell. This will take around 2 minutes.

    <img src="..\appliocolab-img\2-install.png" alt="image" width="260">‎     
‎   
- It'll finish when you see a tick symbol on the left.

    <img src="..\appliocolab-img\2-instdone.png" alt="image" width="260">‎     

***
3. If you are going to <u>[infer]()</u>/train models, click the folder on the left ( :icon-file-directory-fill: ) & press the Google Drive button.

    <img src="..\appliocolab-img\2-files.png" alt="image" width="210">‎     
‎       
- For mobile users, tap the three lines ( :icon-three-bars: ) on the top left & press **Show File Explorer**.

***
4. It'll direct you to a cell. Execute it & grant the permissions. This will take a minute.      
‎   
    <img src="..\appliocolab-img\2-gd.png" alt="image" width="300">‎   

***
5. Execute **Start Applio**.

    <img src="..\appliocolab-img\2-start.png" alt="image" width="300">‎     
‎     
- Then open the **public URL**.

    <img src="..\appliocolab-img\2-url.png" alt="image" width="430">‎   
‎       
!!!warning Don't close Colab until you're done using it, or it will stop working.     
!!! 
***
###### ‎       
###### ‎   
:::content-center
## Inference :icon-unmute:   
!!!success
Be sure to read the <u>[Troubleshooting](https://aihubdocs.github.io/en/rvc/local/mainline/#troubleshooting-)</u> chapter if any issue arises.
!!!
:::
###### ‎  
###### ‎   
#### 1. Upload voice model.
- Go to the **Download** tab.       
You have two ways of uploading it: through <u>[**its link**](https://aihubdocs.github.io/en/essentials/voice-models/#how-to-search-voice-models)</u> or **manually** inputting its files.

    +++ Link
    a. Go to the **Download** tab & paste the link in the `Model Link` bar.     
    It must be from Hugging Face or Google Drive.        
    ‎       
    <img src="..\appliocolab-img\3-download-model.png" alt="image" width="490">    
    ‎       
    b. Press ``Download Model``.
    +++ Manually

    a. Below in **Drop files**, press the upload box & input the model's .PTH.    
    ‎       
    <img src="..\appliocolab-img\3-modelupload.png" alt="image" width="800">       
    ‎           
    b. Then input the .INDEX.
    +++ 

‎  
#### 2. Select voice model.
a. Return to the **Inference** tab & click ``Refresh`` on the right.

    <img src="..\appliocolab-img\3-refresh.png" alt="image" width="500">   


    ‎       
b. Select the model in the ``Voice Model`` & `Index File` dropdown.

    <img src="..\appliocolab-img\3-voice-model.png" alt="image" width="500">   

  ***
###### ‎  
#### 3. Input vocals.      
- With Applio you can convert audios individually or in batches:
    +++ Single
    a. Press the upload box & input your audio.      
    ‎   
        <img src="..\appliocolab-img/3-upload.png" alt="image" width="600">‎      
    ‎       
    ‎   
    b. Then select it in the dropdown below.      
    ‎   
        <img src="..\appliocolab-img/3-select-audio.png" alt="image" width="400">   

    +++ Batch
    a. Go to the **Batch** tab.     
    ‎       
    <img src="..\appliocolab-img/3-batch-upload.png" alt="image" width="360">‎      
    ‎       
    b. Go to the file explorer in Colab. Go to ``drive``, right-click the folder containing the audios & click `Copy Path`.     
    
    c. Paste the path in the `Input Folder` bar.

    - In `Output Folder` you can define the path folder for the results.        
  
    - Ensure the paths don't contain spaces/special characters.      
    +++

‎  
#### 4. Modify settings. (optional)      
-  Unfold `Advanced Settings` if you wish to modify the <u>[inference settings](https://aihubdocs.github.io/en/rvc-resources/inference-settings/)</u> for better results.

    <img src="..\appliocolab-img/3-advanced.png" alt="image" width="550">‎   
***

###### ‎  
#### 5. Convert.
a. Click ``Convert`` at the bottom to process the audio.       

b. Once it's done, you can hear the results in the **Export Audio** box below.      
To download it, press the download symbol on its right.

    <img src="..\appliocolab-img/3-output.png" alt="image" width="450">‎   

***
###### ‎     
###### ‎  
:::content-center
## Training :icon-dependabot:
###### ‎   
!!!danger Unfinished chapter. Do not use.
!!!
:::
###### ‎     
:::content-center
:::
==- 1. PREPROCESS
###### ‎      
##### a. Model Name
###### ‎    
- Go to the `Train` tab. Input a name for your model in `Model Name`.       
Don't include spaces/special characters.     

    <img src="..\appliocolab-img\4-modelname.png" alt="image" width="550">‎     

***
###### ‎     
##### b. Dataset Path
###### ‎    
i. Upload your dataset to your GD storage if you haven't already.        
‎       
ii. In Colab click the folder on the left ( :icon-file-directory-fill: ) & click the reload button.     
‎       
   <img src="..\appliocolab-img\4-refresh.png" alt="image" width="220">‎    
‎   
‎   
iii. Open `drive`, localize your dataset, right-click it & click `Copy path`.     
‎   
    <img src="..\appliocolab-img\4-dtpath.png" alt="image" width="320">‎    
‎    
‎   
iv. Then paste it on the `Dataset Path` bar.       
‎     
    <img src="..\appliocolab-img\4-dataset.png" alt="image" width="550">‎  

***
###### ‎     
##### c. Sampling Rate
###### ‎    
- Select your dataset's sample rate. If you don't know the amount, click <u>[here](https://aihubdocs.github.io/en/rvc/local/applio/#extra)</u>.

    <img src="..\appliocolab-img\4-samplerate.png" alt="image" width="300">‎  

***
###### ‎     
##### d. Preprocess Dataset
###### ‎    
- Ensure **RVC Version** is set as `V2` & click `Preprocess Dataset`.       

    It'll finish when the output box says `preprocessed successfully`.

    <img src="..\appliocolab-img\4-preprocessdone.png" alt="image" width="700">

===

==- 2. EXTRACT
###### ‎    
##### a. Pitch extraction algorithm
###### ‎  
- Select the <u>[algorithm](https://aihubdocs.github.io/en/rvc-resources/inference-settings/#pitch-extraction-algorithm)</u> you want. Use either ``Crepe`` or ``RMVPE``, as the rest are outdated.

    <img src="..\appliocolab-img\4-f0.png" alt="image" width="400">

***
###### ‎  
##### b. Hop Length (optional)
###### ‎  
- If you chose ``Crepe``, you can modify its <u>[hop length](https://aihubdocs.github.io/en/rvc-resources/inference-settings/#mangio-crepe)</u>.

    <img src="..\appliocolab-img\4-hoplength.png" alt="image" width="900">

***
###### ‎  
##### c. Extract Features
###### ‎  
- Press **Extract Features**.       
It'll finish when it says `extracted successfully`.

    <img src="..\appliocolab-img\4-extractfinish.png" alt="image" width="350">

===

==- 3. TRAIN
###### ‎  
##### a. Batch Size
###### ‎  
- If you are a newbie, use `8`. But in case your dataset is short (around 2 minutes or less), use `4`.

    <img src="..\appliocolab-img\4-batchsize.png" alt="image" width="350">

***
###### ‎  
##### b. Save Every Epoch
###### ‎  
- Determine at how many <u>[epochs](https://aihubdocs.github.io/en/rvc-resources/epochs-overtraining--tensorboard/)</u> the model will saved at. These saved models are known as the "checkpoints".         
‎   
- If you are a newbie, leave it at `15`.              

    <img src="..\appliocolab-img\4-freq.png" alt="image" width="420">‎   
‎   
‎   
- E.g: with a value of ``10``, it will be saved after the epoch 10, 20, 30, etc.   
***
###### ‎  
##### c. Total Epoch
###### ‎  
- Input the total amount of <u>[epochs](https://aihubdocs.github.io/en/rvc-resources/epochs-overtraining--tensorboard/)</u> (training cycles) for the model.     
‎   
- But since we'll use <u>[TensorBoard](https://aihubdocs.github.io/en/rvc-resources/epochs-overtraining--tensorboard/#tensorboard)</u>, use an arbitrarily large value like `1000`

    <img src="..\appliocolab-img\4-epoch.png" alt="image" width="420">‎   

***
###### ‎  
##### d. Generate Index
###### ‎  
- Click `Generate Index`. This will create the model's <u>[.INDEX](https://aihubdocs.github.io/en/essentials/voice-models/#voice-model-files)</u> file.
***
###### ‎  
##### e. Start Training
###### ‎  
- Press `Start Training` to begin the training process.     
‎   
- <u>[TB](https://aihubdocs.github.io/en/rvc-resources/epochs-overtraining--tensorboard/#tensorboard)</u> will be available in the Colab. Remember to monitor it, as well as the cell's logs just in case.           
‎   
- The latter will show you errors if they happen, and information about the epochs & checkpoints.   

    <img src="..\appliocolab-img\4-logs.png" alt="image" width="450">‎   

===

==- 4. FINAL STEP
###### ‎  
##### a. Stop training
###### ‎  
- When you're very sure of overtraining, you can stop training by going to the `Settings` tab & press `Restart Applio`.

    <img src="../appliocolab-img/4-stoptrain.png" alt="image" width="715" height="auto"> ‎  
‎       
- Come back to the Colab & open the new public URL.

***
###### ‎  
##### b. Get the INDEX
###### ‎     
i. Open the file explorer, go to ``logs``, and open the folder named as the model.      
‎      
ii. Download the **.INDEX** named ``added_``.    
‎       
   <img src="../appliocolab-img/4-indexdl.png" alt="image" width="400" height="auto">‎
 ‎    

***
###### ‎  
##### c. Get the PTH
###### ‎  
i. In said folder you'll also find all the checkpoints.         
‎  
ii. Select the one **closest** to ***before*** the overtraining point, and move it to the new folder.

    The checkpoints will be organized with this format: **ModelName_Epoch_Step.pth**   
    Example: ``arianagrande_e60_s120.pth``

‎  
    ‎            
iii. And that's all, have fun with your model. To test it, do a normal <u>[inference</u>](https://aihubdocs.github.io/en/rvc/local/applio/#inference-) as usual.

===

==- 5. RETRAINING
###### ‎  
- In case the training finished but the model still needed training, you don't have to start from scratch.        
‎     
- Simply enter the **same settings & criteria** that you've previously inserted. You don't have to do the preprocess, extract feature or train the .INDEX again.      
 ‎     
- You can change the **save frequency**, or increase the **Total Epoch** amount in case you didn't input enough before.      
 ‎     
- Begin training again & remember to monitor TB & logs like before.
===

###### ‎  
###### ‎  
###### ‎  
:::content-center
## TTS
*`+ with any RVC model`*
:::
###### ‎  
- Applio is also known for having one TTS tool by default, with **plenty** of voices to choose for.

- You can also use it with **RVC models** & apply the <u>[inference settings](https://aihubdocs.github.io/en/rvc-resources/inference-settings/)</u> if you wish.

- Additionally, you can download the **Eleven Labs** TTS <u>[plugin](https://aihubdocs.github.io/en/rvc/local/applio/#plugins)</u>.       
***
###### ‎  
#### <u>Instructions:</u>
1. Go to the **TTS** tab. 

   <img src="../appliocolab-img/5-ttstab.png" alt="image" width="400" height="auto"> ‎ 

***   
###### ‎   

2. If you want to use an RVC model, <u>[download it](https://aihubdocs.github.io/en/rvc/local/applio/#1-upload-voice-model)</u>, go to **TTS**, click `Refresh` & select it in **Voice Model** & **Index File**.

   <img src="../appliocolab-img/5-vm.png" alt="image" width="600" height="auto">‎    
‎             
- To modify the <u>[inference settings](https://aihubdocs.github.io/en/rvc-resources/inference-settings/)</u> or the output folder for the TTS/RVC audio, unfold `Advanced Settings`.

***
###### ‎      
3. In **TTS Voices** select the voice of your desired language, accent & gender.        

    In **Text to Synthesize** input your text. Then click `Convert`.

   <img src="../appliocolab-img/5-voice.png" alt="image" width="500" height="auto">‎     
‎   
- If you are using an RVC model, select a voice that matches the model the most, to guarantee great results.   
***
###### ‎  
4. Once it's done, you'll be able to hear the result in the Export Audio box. To download it, click the download button on its right ( :icon-download: ).

   <img src="../appliocolab-img/5-ttsoutput.png" alt="image" width="500" height="auto">‎   

***
###### ‎  
###### ‎  
:::content-center
## Extra
:::
###### ‎  
- Applio has an **Extra** menu, containing an **audio analyzer**, originally made by <u>[Ilaria](https://ko-fi.com/ilariaowo)</u>.

- Making it convenient for determining the **sample rate** of datasets when training models.

- It also contains the **model fusion** tool, ideal for advanced users.

***
###### ‎  
#### <u>Audio Analyzer:</u>
1. Go to the **Extra** tab & press the upload box to input your audio.

   <img src="../appliocolab-img/6-tab.png" alt="image" width="400" height="auto">‎   
***
###### ‎  
2. Once it's done uploading, click `Get information about the audio`.  

***
###### ‎  
3. In **Sampling rate** you'll see the audio's full sample rate. Use said value for training.

   <img src="../appliocolab-img/6-samplerate.png" alt="image" width="470" height="auto">‎    
###### ‎    
!!!warning <u>WARNING:</u>   
If the frequencies don't reach the top of the spectrogram, see at which number peaks & multiply it by <U>**2**</u>.
!!!

###### ‎
{.list-icon}
- #### <u>Example:</u>
   <img src="../appliocolab-img/6-double.png" alt="image" width="470" height="auto">‎       
‎
>Here it reached 20 kHz. **Doubling** it gives 40kHz. Therefore the ideal target sample rate would be ``40k`` 

***
###### ‎
###### ‎
:::content-center
## Plugins
:::
- Plugins are components that you can add to Applio, that add new features & enhance your experience. 

- These are made by the public, and are free & easy to install. 

- You can find them on their <u>[GitHub page](https://github.com/IAHispano/Applio-Plugins/tree/main)</u>. More will be added in the future.
***
###### ‎
#### <u>Installation:</u>
1. Access their GitHub page & click on the name of the plugin you want.

   <img src="../appliocolab-img/7-repo.png" alt="image" width="470" height="auto">‎ 

***
###### ‎
2. Click on the ZIP file.

   <img src="../appliocolab-img/7-zip.png" alt="image" width="470" height="auto">‎   
‎       
- Click on the download button on the right. This will download the ZIP file of the plugin.

   <img src="../appliocolab-img/7-dl.png" alt="image" width="470" height="auto">‎ 
***
###### ‎
3. Open Applio & head over to the **Plugins** tab. Press the upload box & upload the ZIP.

   <img src="../appliocolab-img/7-plugins.png" alt="image" width="600" height="auto">‎   

***
###### ‎
3. Go to the **Settings** tab & click **Restart Applio** at the bottom. Go back to the Colab & open the new public URL. 

    Then you'll be able to see the plugin in the **Plugins** tab.

   <img src="../appliocolab-img/7-plugindled.png" alt="image" width="420" height="auto">‎ 

***
###### ‎
###### ‎
:::content-center
## Troubleshooting
:::
###### ‎ 
==- *There's no option for my sample rate.*
###### ‎   

- **If it's lower than <u>32k**</u>: select ``32k``.       
‎   
- **If it's <u>44.1k**</u>: select ``40k``.   
‎   
- **If i'ts higher than <u>48k</u>**: select ``48k``.

===

==- *The voice glitches out.*
###### ‎   
- This a phenomenon called artifacting. To fix it, read <u>[here](https://aihubdocs.github.io/en/rvc-resources/artifacting/)</u>.

===

***
:::content-right
``Written by Julia & Poopmaster``    
:::
‎   
:::content-right
[!badge variant="info" size="xl" corners="pill" icon="paper-airplane" iconAlign="right" text="Report Issues"](http://aihubdocs.github.io/en/#contributions)
:::
‎   
‎   
***
