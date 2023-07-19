# QGIS_PostgreSQL
![image](https://user-images.githubusercontent.com/119863892/235365495-7e5728f1-b9af-4681-8f23-17e2863e7615.png)


# Final Project 
## Update of The Database

- Connection between QGIS and Postgres

  <img width="215" alt="image" src="https://github.com/GMT-352/final-project-individual-sudeyaprak/assets/119863892/f0ca8f13-0c6b-48cd-99c2-5ec0cd2a6ae9">
 
- A road was found that is not in the database, resulting in the long way being taken to the destination.
  - The road is between Tunçalp Özgen Culture Congress Hall and Amphitheatre 

  ![image](https://github.com/GMT-352/final-project-individual-sudeyaprak/assets/119863892/30cdce12-d6d1-49f1-a208-7c20495606b7)
  
- The nodes are connected with snapping tools.
 
  <img width="287" alt="image" src="https://github.com/GMT-352/final-project-individual-sudeyaprak/assets/119863892/d0f10169-c98c-4327-88ba-acbefd8f144b">

- The road information has been added.

  <img width="236" alt="image" src="https://github.com/GMT-352/final-project-individual-sudeyaprak/assets/119863892/96e2fdd8-07a0-4afa-a656-78a3149e5dce">
  
  ![image](https://github.com/GMT-352/final-project-individual-sudeyaprak/assets/119863892/6e36150e-6495-4810-8b9d-6f2d1e6aba36)

- The final version of the road has been drawn in QGIS.

  <img width="960" alt="image" src="https://github.com/GMT-352/final-project-individual-sudeyaprak/assets/119863892/b77eac26-2f22-4dbd-8ce9-02611b7c18e9">

- The changes in QGIS were saved and updated. PgAdmin was refreshed, and the data of the road was checked through a query.

  ![image](https://github.com/GMT-352/final-project-individual-sudeyaprak/assets/119863892/419d4bdb-5dab-4c59-b85a-cf44edea3989)

- A terminal was opened in Visual Studio Code, and the following codes were executed in sequence for the server.

```javascript
cd server
npm install
npm run start
```
- A new terminal was opened, and the following codes were executed sequentially for the client, resulting in the interface being launched..

```javascript
cd client
npm install
npm run start
```
### Before
![image](https://github.com/GMT-352/final-project-individual-sudeyaprak/assets/119863892/222aaf10-d33a-49b2-8237-f44554984817)

### After
![image](https://github.com/GMT-352/final-project-individual-sudeyaprak/assets/119863892/743e0a7e-bc9a-481a-b4ed-b515a9318c74)


## Smart Campus

### Location-based services on a smart campus: A system and a study 

This paper introduces a framework for location-based services (LBS) in smart campus environments, leveraging existing infrastructure. The framework consists of three user facing components: an Android application for end users to access services based on their location, a web application for users to search for campus-wide services, and a web application for administrators to manage services and service areas. The framework's back-end utilizes a PostgreSQL database to store information about available services and their spatial scope. Localization accuracy is evaluated as a critical factor for effective LBS delivery. The framework addresses challenges in large-scale environments by utilizing data from various sources such as GPS, Wi-Fi fingerprinting, and accelerometers. The paper highlights the framework's functionality, including notification services and information services. The Android application operates in passive and active states to update the user's location. The framework's use-case involves users on campus accessing services in designated areas. Detailed descriptions of each component are provided. Overall, the framework aims to enhance location-based service delivery in smart campus environments.

![image](https://github.com/GMT-352/final-project-individual-sudeyaprak/assets/119863892/59e050e4-e00f-41e2-8c02-9cefb94281f3)

A. Petcovici and E. Stroulia, "Location-based services on a smart campus: A system and a study," 2016 IEEE 3rd World Forum on Internet of Things (WF-IoT), Reston, VA, USA, 2016, pp. 94-99, doi: 10.1109/WF-IoT.2016.7845406.

https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7845406&isnumber=7845389
