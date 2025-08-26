## Convolutional Neural network

### In this repo, I have trained CNN on 5 datasets--
 1. *Digit MNIST* 
 2. *Fashion MNIST* 
 3. *CIFAR_10*
 4. *Satellite-images-classification* 
 5. *Cat and dog image classification*                             --

### Not only trained on CNN but also fine-tuned on 4 different pre-trained models -- 
 1. *VGG16* 
 2. *ResNet50*
 3. *InceptionNetV3*
 4. *MobileNetV1*

### Here is the table of achieved validation accuracies:

<table style="width:100%; border-collapse: collapse; text-align: center; background-color: #090909ff">
    <thead>
        <tr>
            <th rowspan="2" style="border: 1px solid #ddd; padding: 8px; background-color: #090909ff; text-align: center;">Datasets</th>
            <th rowspan="2" style="border: 1px solid #ddd; padding: 8px; background-color: #090909ff; text-align: center;">No. of Epochs</th>
            <th colspan="5" style="border: 1px solid #ddd; padding: 8px; background-color: #090909ff; text-align: center;">Models</th>
        </tr>
        <tr>
            <th style="border: 1px solid #ddd; padding: 8px; background-color: #090909ff; text-align: center;">CNN</th>
            <th style="border: 1px solid #ddd; padding: 8px; background-color: #090909ff; text-align: center;">VGG16</th>
            <th style="border: 1px solid #ddd; padding: 8px; background-color: #090909ff; text-align: center;">ResNet50</th>
            <th style="border: 1px solid #ddd; padding: 8px; background-color: #090909ff; text-align: center;">InceptionNetV3</th>
            <th style="border: 1px solid #ddd; padding: 8px; background-color: #090909ff; text-align: center;">MobileNetV1</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="border: 1px solid #ddd; padding: 8px; text-align: left;">Digit MNIST</td>
            <td style="border: 1px solid #ddd; padding: 8px;">5</td>
            <td style="border: 1px solid #ddd; padding: 8px;">98.84</td>
            <td style="border: 1px solid #ddd; padding: 8px;">97.52</td>
            <td style="border: 1px solid #ddd; padding: 8px;">93.50</td>
            <td style="border: 1px solid #ddd; padding: 8px;">94.11</td>
            <td style="border: 1px solid #ddd; padding: 8px;">98.08</td>
        </tr>
        <tr>
            <td style="border: 1px solid #ddd; padding: 8px; text-align: left;">Fashion MNIST</td>
            <td style="border: 1px solid #ddd; padding: 8px;">5</td>
            <td style="border: 1px solid #ddd; padding: 8px;">88.11</td>
            <td style="border: 1px solid #ddd; padding: 8px;">87.20</td>
            <td style="border: 1px solid #ddd; padding: 8px;">77.60</td>
            <td style="border: 1px solid #ddd; padding: 8px;">84.77</td>
            <td style="border: 1px solid #ddd; padding: 8px;">90.45</td>
        </tr>
        <tr>
            <td style="border: 1px solid #ddd; padding: 8px; text-align: left;">CIFAR_10</td>
            <td style="border: 1px solid #ddd; padding: 8px;">10-20</td>
            <td style="border: 1px solid #ddd; padding: 8px;">71.70</td>
            <td style="border: 1px solid #ddd; padding: 8px;">59.80</td>
            <td style="border: 1px solid #ddd; padding: 8px;">61.64</td>
            <td style="border: 1px solid #ddd; padding: 8px;">40.38</td>
            <td style="border: 1px solid #ddd; padding: 8px;">50.47</td>
        </tr>
        <tr>
            <td style="border: 1px solid #ddd; padding: 8px; text-align: left;">Satellite-images-classification</td>
            <td style="border: 1px solid #ddd; padding: 8px;">5</td>
            <td style="border: 1px solid #ddd; padding: 8px;">84.88</td>
            <td style="border: 1px solid #ddd; padding: 8px;">25.55</td>
            <td style="border: 1px solid #ddd; padding: 8px;">49.07</td>
            <td style="border: 1px solid #ddd; padding: 8px;">97.16</td>
            <td style="border: 1px solid #ddd; padding: 8px;">98.85</td>
        </tr>
        <tr>
            <td style="border: 1px solid #ddd; padding: 8px; text-align: left;">Cat and dog image classification</td>
            <td style="border: 1px solid #ddd; padding: 8px;">5</td>
            <td style="border: 1px solid #ddd; padding: 8px;">67.86</td>
            <td style="border: 1px solid #ddd; padding: 8px;">processing...</td>
            <td style="border: 1px solid #ddd; padding: 8px;">processing...</td>
            <td style="border: 1px solid #ddd; padding: 8px;">processing...</td>
            <td style="border: 1px solid #ddd; padding: 8px;">processing...</td>
        </tr>
    </tbody>
</table>


