# Predicting-lung-function
predict the lung function of pulmonary fibrosis patients using pre diagnostic CT scan and longitudenal data of spirometer readings

# Overall Pipeline:

1. Extracting demographic information
2. Handcrafting features using clinical information
3. Generating features from a deep neural network 
4. Combining all the three types of features and building a regression model
5. Testing and Evalaution 

![image](https://user-images.githubusercontent.com/117613924/201547438-a5d9c256-6851-4d63-8fe4-5a4e6487b5c9.png)

# Results

Segmentation pipline to extact lungs from CT scan and extracting Textural GLCM features :

![image](https://user-images.githubusercontent.com/117613924/201547566-c666c74a-0247-4a1d-bd0e-ed25ad60f36a.png)

Extracting latent features from neural network and visualzing the gradients - to underastand what the latent features represent :

![image](https://user-images.githubusercontent.com/117613924/201547595-e58c9472-37a0-4709-b348-ff92aa0a25c5.png)

# Evalation:

Regression evaluation:
![image](https://user-images.githubusercontent.com/117613924/201547609-aa92d81b-ea7b-4043-9fc4-d52c8ac27021.png)

Model performance - demonstracted on two patients with different rate of decline:


![image](https://user-images.githubusercontent.com/117613924/201547634-a924047a-1545-45f9-b223-8c0c3a07a503.png)
