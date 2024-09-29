### Tehtävä 1
SELECT * FROM goal;
![image](https://github.com/user-attachments/assets/ddc0bc98-03de-4b0e-8a2e-6f2a9bda8574)
### Tehtävä 2
SELECT type, name FROM airport WHERE iso_country = "FI";
![image](https://github.com/user-attachments/assets/71ab4192-3dcb-4b60-a407-87d2372dcead)
### Tehtävä 3
SELECT name FROM airport WHERE iso_country = "FI" ORDER BY name;
![image](https://github.com/user-attachments/assets/ac1e8040-b78c-4297-bedc-6fa68d0a3738)
### Tehtävä 4
SELECT name, type FROM airport WHERE iso_country = "FI" ORDER BY type, name;
![image](https://github.com/user-attachments/assets/65202b90-0121-4671-91b7-9ebccc1472b3)
### Tehtävä 5
SELECT name FROM country WHERE name LIKE 'F%' ORDER BY name;
![image](https://github.com/user-attachments/assets/1fee2b5b-2048-4d9a-a3a3-901e11c5dde1)
### Tehtävä 6
SELECT name FROM country WHERE name LIKE '%F%';
![image](https://github.com/user-attachments/assets/8480b8ea-e0ef-4849-bd40-29542a53f75c)
### Tehtävä 7
SELECT location FROM game WHERE screen_name = 'Vesa';
![image](https://github.com/user-attachments/assets/56aafa4d-b555-4745-9016-7fab39f049d6)
### Tehtävä 8
SELECT co2_consumed FROM game WHERE screen_name = 'Ilkka';
![image](https://github.com/user-attachments/assets/b286c761-f165-4d85-9e00-3fde993d3969)
### Tehtävä 9
SELECT DISTINCT co2_budget FROM game;
![image](https://github.com/user-attachments/assets/24ee5b59-fb00-4de5-a54a-ea1b08279457)
