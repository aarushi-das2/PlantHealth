# AI-Based Non-Destructive Plant Health Assessment for Sustainable Agriculture
This project aims to develop an AI-based system for non-destructive assessment of plant health by predicting chlorophyll content from leaf images. Chlorophyll concentration is an important indicator of plant health, photosynthetic activity, and nutrient status. Traditional chlorophyll estimation methods require destructive sampling and laboratory analysis. This study explores the use of image processing and ML to provide a low-cost and sustainable alternative.

Primary SDG:
SDG 2 – Zero Hunger

Secondary SDG:
SDG 15 – Life on Land

## Expected Impact:
• Early plant stress detection
• Sustainable crop monitoring
• Reduced dependence on laboratory testing
• Improved agricultural decision making

## Features Used
• RGB statistics
• ExG
• NGRDI
• VARI
• Intensity
• Texture features

## Dataset
The complete dataset used for model development is available on Kaggle and consists of leaf images from five plant species along with experimentally measured chlorophyll values. Representative sample images are included in this repository.
Kaggle: https://www.kaggle.com/datasets/paradiseflycatcher/plant-health

## Results
### Validation Performance
LOOCV R²: 0.017
LOOCV Error: 53.97%

### Independent Test Performance
Test R²: 0.801
Test RMSE: 0.029
Test MAE: 0.027
Average Error: 10.30%

