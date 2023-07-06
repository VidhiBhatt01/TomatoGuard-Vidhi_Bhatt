# Tomato Guard

## Inspiration 💡

Tomato is my one of my favorite vegetable. I planted a tomato plant in my home garden but the plant was not growing as it should be. I investigated this deeper and it turns out that my plant was suffering from the Target Spot Disease. To ensure that such situation does not occur again, I started looking for probable solutions. While doing so, I landed up on a datset on Kaggle and then made this project!


<img src=" ">

### Target spot: 
Target spot, caused by the fungus Corynespora cassiicola, leads to circular, target-like lesions on leaves, stems, and fruits. It spreads through wind and rain. Managing target spot involves removing infected plant debris, good air circulation, and applying fungicides.

### Bacterial spot:
Bacterial spot is a disease caused by the bacteria Xanthomonas vesicatoria or Xanthomonas euvesicatoria. It leads to dark, water-soaked lesions on leaves, stems, and fruits. It thrives in warm and humid conditions, and can be managed through crop rotation, using disease-free seeds, and applying copper-based sprays.

### Early blight: 
Early blight, caused by the fungus Alternaria solani, affects leaves, stems, and fruits. It causes dark, concentric lesions on lower leaves, which can spread and cause defoliation. Proper spacing, removing infected plant debris, and applying fungicides can help manage early blight.

### Late blight: 
Late blight, caused by the oomycete Phytophthora infestans, is a devastating disease. It affects leaves, stems, and fruits, causing dark lesions with a white mold on the undersides. It spreads rapidly in cool and humid conditions. Proper monitoring, resistant varieties, fungicides, and timely harvest are crucial for managing late blight.

## Dataset Distribution

This dataset is a modified version/subset of the Plant Village Dataset available on Kaggle.

| No |  Disease Type | No. of Images |
|:-:|:-:|:-:|
| 01 | Target Spot | 1404 |
| 02 | Bacterial Spot | 1773 |
| 03 | Early Blight | 1000 |
| 04 | Healthy | 1591 |
| 05 | Late Blight | 1586 |

## What's next for the project? 📈
- Improving the model performance and accuracy. Currently even if the supplied image is not a plant leaf, the model still classifies it into one of the classes. A possible solution could be building a two stage classification model where first model classifies if an image is tomato plant or not and then the second model will classify the actual disease.

<br>
<p align="center">
 © 2023 | ALL RIGHTS RESERVED
</p>