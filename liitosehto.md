### Tehtävä 1
SELECT c.name AS "country name", a.name AS "airport name" FROM country c JOIN airport a ON c.iso_country = a.iso_country WHERE c.name = "Iceland";
![image](https://github.com/user-attachments/assets/266045e3-e435-4c12-8482-97d00c5603e0)

### Tehtävä 2
SELECT name AS "airport name" FROM airport WHERE iso_country = 'FR' AND type = 'large_airport';
![image](https://github.com/user-attachments/assets/7ec5f148-63a7-46a3-8636-e02ad2193d55)

### Tehtävä 3

### Tehtävä 4
SELECT airport.elevation_ft FROM game JOIN airport ON game.location = airport.ident WHERE game.screen_name = 'Heini';
![image](https://github.com/user-attachments/assets/a95b103e-a26a-4838-b280-298d3f04a9fc)

### Tehtävä 5
SELECT airport.elevation_ft * 0.3048 AS elevation_m FROM game JOIN airport ON game.location = airport.ident WHERE game.screen_name = 'Heini';
![image](https://github.com/user-attachments/assets/bf5812ea-b98e-4e45-97dd-a6cf3e0c15be)

### Tehtävä 6
SELECT airport.name FROM game JOIN airport ON game.location = airport.ident WHERE game.screen_name = 'Ilkka';
![image](https://github.com/user-attachments/assets/fba2ca3c-8fc7-4723-b370-eb14220c422d)

### Tehtävä 7

### Tehtävä 8
SELECT g.name FROM goal g JOIN goal_reached gr ON g.id = gr.goal_id JOIN game ga ON ga.id = gr.game_id WHERE ga.screen_name = 'Heini' AND g.id (4, 7);
![image](https://github.com/user-attachments/assets/1f338a8b-5c0b-4b2e-9872-73456c7842db)

### Tehtävä 9

### Tehtävä 10
