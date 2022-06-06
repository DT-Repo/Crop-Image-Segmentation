# Crop-Image-Segmentation - 1st ACRE Cascade Competition
<img src="https://github.com/DT-Repo/Crop-Image-Segmentation/blob/master/Images/keras.png" width="600" height="250">
Crop-Image-Segmentation is developed to take part in the 1st ACRE Cascade Competition , whose details and rules are available at the challenge description page: https://competitions.codalab.org/competitions/27176#learn_the_details-data .

## Overview
>ACRE is the Agri-food Competition for Robot Evaluation, part of the METRICS project funded by the European Union’s Horizon 2020 research and innovation program >under grant agreement No 871252. Autonomous robots compete to demonstrate their ability to perform agricultural tasks (such as removing weeds or surveying >crops down to individual-plant resolution). At field campaigns, participants collect data that are then made available for online competitions (Cascade >Campaigns) like the one you are seeing. For more information about ACRE and METRICS visit the official website.
>
>After years of decline, the number of undernourished people began to slowly increase again in 2015. Food Security requires that everyone can have enough food >produced in a sustainable manner. The topic is increasingly gaining attention as food scarcity is worsened by a continuously growing population. Also, food >production is threatened by climate change. The topic is so relevant that is part of one of the 17 Sustainable Development Goals of the UN 2030 Agenda. In >particular, Food Security is a pillar of SDG number 2, Zero Hunger.
>
>In this context, the agricultural sector is going under a process of revolution by the introduction of digital technologies. The Digital Agricultural >Revolution can help to reduce the use of resources (water, fertilizers, and pesticides), thus diminishing the environmental contamination and the costs for the >farmers. Also, it could increase the climate resilience of crops and their productivity.
>
>Automatic crop and weed segmentation can be a driver of innovations to optimize the agricultural processes. Indeed, automatic weed detection can be exploited >by a ground robot for mechanical weeding. Thus, pesticides could even be completely avoided. By joining this challenge you can contribute to advance the >application of digital technologies in agriculture. We hope you will enjoy the competition :)

## Dataset Overview
>The dataset is composed of images captured by different sensors in different moments and are about two kinds of crops: haricot and maize. Data comes from the >2019 ROSE Challenge where four teams have competed with agricultural robots. Each team has collected images of the same two crops, but in different moments and >with different sensors (RGB cameras).
>
>Images in the dataset are divided into different folders based on the team that acquired the image, i.e., Bipbip, Pead, Roseau, Weedelec. For each team, we >have two different sub-folders named as the type of crop present in the images, i.e., Haricot and Mais. Finally, for each crop, we provide the captured RGB >images, in the Images folder, and the corresponding ground-truth segmentations, in the Masks folder. 


<img src="https://github.com/DT-Repo/Crop-Image-Segmentation/blob/master/Images/UNET.jpg" width="500" height="400">
