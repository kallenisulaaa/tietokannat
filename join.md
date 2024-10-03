### Tehtävä 1
SELECT country.name AS "country_name", airport.name AS "airport_name"
FROM airport
INNER JOIN country ON country.iso_country = airport.iso_country
WHERE country.name = 'Finland' AND airport.scheduled_service = 'yes';

![image](https://github.com/user-attachments/assets/85fcd871-a0ee-457b-baa7-e25ac87bf90a)

### Tehtävä 2
SELECT game.screen_name, airport.name
FROM game
INNER JOIN airport ON game.location = airport.ident;

![image](https://github.com/user-attachments/assets/4ced22ee-eb74-4be1-bfaf-25a002ba4111)

### Tehtävä 3
SELECT game.screen_name, country.name
FROM game
JOIN airport ON game.location = airport.ident
JOIN country ON airport.iso_country = country.iso_country;

![image](https://github.com/user-attachments/assets/74c94a7c-4bdf-4ec1-b5f9-864ddb1c11a4)

### Tehtävä 4
SELECT airport.name, game.screen_name
FROM airport
LEFT JOIN game ON airport.ident = game.location
WHERE airport.name LIKE '%Hels%'
ORDER BY game.screen_name DESC;

![image](https://github.com/user-attachments/assets/0a6d9fce-ce70-4717-a02a-12b2d5426d93)

### Tehtävä 5
SELECT goal.name, game.screen_name
FROM goal
LEFT JOIN goal_reached ON goal.id = goal_reached.goal_id
LEFT JOIN game ON goal_reached.game_id = game.id;

![image](https://github.com/user-attachments/assets/e87fc933-7195-4a34-8cd5-421e262d670a)
