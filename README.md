![demir](https://img.shields.io/badge/PyTorch-V1.2.0-red) ![licence](https://img.shields.io/badge/demir-ai-blueviolet) ![licence](https://img.shields.io/badge/Ahmet%20Furkan-DEM%C4%B0R-blue)



# Initialization Covid19

* Multi-class classification project on Covid 19 data set.

* We used the PyTorch module in the classification process. Since there are errors in the Initialization section of the PyTorch module, we wrote the function that will perform this function.

* To learn more about Initialization : https://github.com/AhmetFurkanDEMIR/Online-Istanbul-Applied-Data-Science-102-Bootcamp/tree/master/Lesson2/Notebook/Hafta%206


## Datasets

![0](https://user-images.githubusercontent.com/54184905/94127895-250bc580-fe62-11ea-9624-7583c668bce1.png) **(Covid19)**

![0](https://user-images.githubusercontent.com/54184905/94127921-2a691000-fe62-11ea-8bb4-c36d344e3eb6.png) **(Healthy)**

![0](https://user-images.githubusercontent.com/54184905/94127928-2e952d80-fe62-11ea-9a0b-e7cac4e34dbc.png) **(Others)**


* The dataset is from Harvard University : https://dataverse.harvard.edu/file.xhtml?persistentId=doi:10.7910/DVN/SZDUQX/RTVB06&version=1.0

* The data are Computed tomography data with .png extension.

* Covid : It is the computed tomography data of people with Covid 19 disease. (2167 items)

* Healthy : Computed tomography data of healthy people. (757 items)

* Others : Computed tomography data of patients who are sick but not caught with Covid 19. (1247 items)


## Model and Results

* **Layers and parameters :**

![Screenshot_2020-09-24_12-38-50](https://user-images.githubusercontent.com/54184905/94129080-98620700-fe63-11ea-8831-821c5006907a.png)

![Screenshot_2020-09-24_12-42-03](https://user-images.githubusercontent.com/54184905/94129082-98fa9d80-fe63-11ea-88f3-99fa24054a25.png)

* **The model was trained with Google Colab pro on tesla v100 GPU :**

![Screenshot_2020-09-24_12-48-14](https://user-images.githubusercontent.com/54184905/94129685-55ecfa00-fe64-11ea-937c-95ef96e26766.png)

* **Model performance and loss :**

![Screenshot_2020-09-24_12-47-21](https://user-images.githubusercontent.com/54184905/94129680-55546380-fe64-11ea-93a8-65fdd124eaae.png)
