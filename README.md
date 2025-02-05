
New York City experiences a high volume of motor vehicle collisions. This is a big data project leveraging NYC Open Data to analyze these collisions.
This project dives into three key datasets: collisions, vehicles, and people involved. By analyzing these interconnected datasets, we aim to gain insights into various aspects of NYC traffic accidents, including :


▪ Accident Patterns (Factors) : Highlighting trends in accident times, vehicle types involved, pre-accident actions, location of the victim, contributing factors, etc 

▪ Impact Analysis (Consequences): Understanding the types of public property damaged and harm to human life 

▪ Spatial Distribution (Location Clustering): Examining collision distribution across boroughs, identifying potential hotspots and assigning weights. 

▪ Predictive Modeling: Developing models to predict human life loss and injuries in high-risk areas. 

This project aims to provide valuable data-driven insights to improve road safety and inform traffic management strategies in New York City. 






NYC MOTOR VEHICLE COLLISION ANALYTICS AND PREDICTIVE MODELING Databricks notebooks
1. *Initial data cleaning and EDA* -     
https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/2223093725023385/3402554983214854/563989775462406/latest.html
2. *Data Wrangling* -    
https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/2223093725023385/1978338885242709/563989775462406/latest.html
3. *Data Cleaning for Spatial CLustering* -    
https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/2202773089231587/3270097802115930/6397218320977099/latest.html
4. ⁠⁠*Features and target variable for predictive modeling* -    
https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/2202773089231587/288185156849501/6397218320977099/latest.html
5. *Train Test Split and Join Data* -   
https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/2202773089231587/3538449047751016/6397218320977099/latest.html
6. *Model Training* -   
https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/2223093725023385/3086432350858478/563989775462406/latest.html






*NOTE* 


In the stages of preprocessing data, we had to displace our data from one user to the other, without getting rid of all the preprocessing as the joining and discretization were expensive operations. So, we utilized df.display() to get all the data and download it, transferred to another user and uploaded to their DBFS to continue with the subsequent steps in the preprocessing. Thus, at many points of our code, there have been calls to datasets other than the ones mentioned in our presentation.
           
![teamA-mv-collisions-images-0](https://github.com/user-attachments/assets/a491edbc-b4d7-4c65-85fa-2884ab2b7d95)


![teamA-mv-collisions-images-5](https://github.com/user-attachments/assets/0cd02302-9d71-49e5-8faa-1ce4c3275fcc)

![teamA-mv-collisions-images-9](https://github.com/user-attachments/assets/5fe7748d-6ddd-482a-aacd-8bebf840a08e)
![teamA-mv-collisions-images-11](https://github.com/user-attachments/assets/76bae72b-0708-4d45-aee1-2a381713438a)
![teamA-mv-collisions-images-12](https://github.com/user-attachments/assets/51695b8e-e27b-4220-a7b7-09cf0f24b3d0)
![teamA-mv-collisions-images-13](https://github.com/user-attachments/assets/00236edb-87f0-44d6-beaf-526b2bb33eae)
![teamA-mv-collisions-images-15](https://github.com/user-attachments/assets/37e6d1ba-6f8b-4e16-9b8f-cdc405524739)
![teamA-mv-collisions-images-16](https://github.com/user-attachments/assets/7fd35567-775f-40d9-8f70-85fa193ac5ee)

![teamA-mv-collisions-images-17](https://github.com/user-attachments/assets/eb819dd7-d771-4dd3-ad60-2faaef425245)
![teamA-mv-collisions-images-19](https://github.com/user-attachments/assets/2814491d-a540-4962-8dbb-0af76e1d66ae)


![teamA-mv-collisions-images-20](https://github.com/user-attachments/assets/77f24910-a717-45f5-80ff-6c01ffc3cd11)
![teamA-mv-collisions-images-22](https://github.com/user-attachments/assets/3c8ea63d-cfac-40a4-9a3d-585bcafbf36b)

![teamA-mv-collisions-images-24](https://github.com/user-attachments/assets/8ef10160-8a31-438d-9a8a-adea35019b67)


![teamA-mv-collisions-images-34](https://github.com/user-attachments/assets/c63ef08a-2063-4383-be84-c59719eb339f)

![teamA-mv-collisions-images-36](https://github.com/user-attachments/assets/8820e793-e7a5-4d8c-8e3b-b7e455bd5490)


![teamA-mv-collisions-images-39](https://github.com/user-attachments/assets/d601f74a-37f9-48a1-80aa-37a5650eff26)
![teamA-mv-collisions-images-40](https://github.com/user-attachments/assets/945285a2-a867-4603-be05-5fa5715a1633)
![teamA-mv-collisions-images-42](https://github.com/user-attachments/assets/44145134-ba97-40d0-af21-b05f3006efc4)

![teamA-mv-collisions-images-47](https://github.com/user-attachments/assets/fe628163-3442-4d89-9c09-509d8903817e)
![teamA-mv-collisions-images-48](https://github.com/user-attachments/assets/a101acfa-6369-47f0-bd90-36d7e4e6120b)
