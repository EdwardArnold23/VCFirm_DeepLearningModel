# Venture Capital Firm Deep Learning Model Analysis
__________________________________________________
## Analysis includes:

### Preparing the Data for Use on a Neural Network Model 
 * train_test_split
 * StandardScaler
 * OneHotEndcoder

### Compilation and Evaluation a Binary Classification Model Using a Neural Network
  * TensorFlow Keras modeling
  * Dense
  * Sequential model
 
 ### Finally Optimizing of the Neural Network Model using an original and 2 optimized models
 * Original Model
   - Features = 116
   - Outputs nodes = 1
   - Hidden Layers = 2 (layer_1 = 24; layer_2 = 8)
   - Results: Loss: 0.5540555715560913, Accuracy: 0.7297959327697754
 
 * A1 Model
  - Features = 116
   - Outputs nodes = 1
   - Hidden Layers = 4 (layer_1 = 64;layer_2 = 32;layer_3 = 18;layer_4 = 6) 
   - Results: Loss: 0.5544037818908691, Accuracy: 0.7302623987197876
 
 * A2 Model
  - Features = 40
   - Outputs nodes = 1
   - Hidden Layers = 4 (layer_1 = 64;layer_2 = 32;layer_3 = 18;layer_4 = 9)
   - Results: Loss: 0.5731913447380066, Accuracy: 0.7237317562103271
    
* Results
  After several phases of testing the second model, A1 model, performed the best against the data. This model performed better than the original model with the same amount of features.

## Libraries & Dependencies:
  * TensorFlow 
  * Pathlib
  * SKLearn
  * Pandas

## Datasource:
  * applicants_data.csv
  * AlphabetSoup_Model_1.keras
  * AlphabetSoup_Model_A1.keras
  * AlphabetSoup_Model_A2.keras
  


