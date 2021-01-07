# Lung Inflammatory Disease Classification using X-Ray Images

## Data Source
<ul>
    <li> https://github.com/ieee8023/covid-chestxray-dataset  </li>
    <li> https://www.kaggle.com/praveengovi/coronahack-chest-xraydataset </li>
</ul>

## Data Exploration & Data Split

## Preprocessing
<ul>
    <li>Prepare the data</li>
    <li>Data split:</li>
    <ul>
        <li>Train data and test data are split in the image-dataset directory</li>
    </ul>
</ul>

        
## Methods

### Baseline CNN 
<ul>
    <li> Convolutional Nural Ntwork </li>
</ul>

### Transfer Learning
<ul>
    <li> RESNET34 </li>
    <li> RESNET50</li>
    <li> Vgg19_bn</li>
    <li> Alexnet </li>
    <li> Densenet201</li>
    <li> Mobilenet_v2
    <li> Squeezenet1_1 </li>
    <li> InceptionV3</li>
</ul>
 
 
## Model Evaluation
<ul>
    <li>Evaluate how accuarate the model performs with respect to the data in terms of prediction accuracy and other classifcation metrics </li>
    <li>Find the average error of your model (use testing data only) a.k.a model test/prediction evaluation</li>
</ul>


## Results


| | | | Model Accuracy | | | | 
|------|------|------|------|------|------|------|

|Resnet34|Resnet50|Vgg19|Alextnet|Densenet201|Mobilenet_v2|Squeezenet1_1|Cnn|
|------|------|------|------|------|------|------|------|
|0.836|0.849|0.830|0.828|0.864|0.849|0.829|0.778
