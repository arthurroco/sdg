# AI Engineer position
## Technical assessment of Arthur Vieira
________________________
Document designated to guide the assessment of the technical skills for a candidate from different perspectives for the  role of AI Engineer within SDG Group’s Data Technologies practice.

# About the project
As the candidate haven't skills as an AI engineer, from the perspective of a data engineer, he proposed doing an ETL using Tableau Prep Builder and exposing the information in a dashboard.

# Technologies used
- Tableau Desktop
- Tableau Prep Builder (ETL Tool)
- MySQL
- Excel

# Procedures
1. Created database on MySQL
```sh
CREATE DATABASE `sdg` /*!40100 DEFAULT CHARACTER SET utf8mb4 COLLATE utf8mb4_0900_ai_ci */ /*!80016 DEFAULT ENCRYPTION='N' */;
```
2. Created table
```sh
CREATE TABLE `sales` (
  `date` date NOT NULL,
  `id_store` tinyint NOT NULL,
  `id_item` tinyint NOT NULL,
  `sales` int NOT NULL,
  PRIMARY KEY (`date`,`id_store`,`id_item`)
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_0900_ai_ci;
```
3. Created a new Excel File with the stores name;
4. Through Tableau Prep Builder, created the flows called stores and sales
5. Created Tableau Forecast Dashboard. To see click [here](https://public.tableau.com/app/profile/arthurroco/viz/SDG_16460832129040/Forecasting?publish=yes)

# Releases
| Version | About |
| ------ | ------ |
| 1.0 | Dashboard created using Kaggle Excel File as source |
| 2.0 | Created ETL, output to Tableau File (Hyper File) and changed dashboard sources | 

# Developers
| Developer | E-mail | Phone |
| --------- | ------ | ----- |
| Arthur de Oliveira R. Vieira | [arthurroco@gmail.com](mailto:arthurroco@gmail.com) | [+5511982900573](https://api.whatsapp.com/send?phone=5511982900573)