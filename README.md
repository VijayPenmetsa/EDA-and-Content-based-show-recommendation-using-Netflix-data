# EDA-and-Content-based-show-recommendation-using-Netflix-data

## Introduction 

In this project, we perform **Exploratory Data Analysis** on the netlfix dataset, and provide **Content based User Recommendations.**

## Files

**netflix.ipynb** containts code all the necessary code.
**netlfix_titles.csv** contatins the raw data.

## Dataset

- The dataset contains 7787 rows of netflix data from 2008-01-01 to 2021-01-16.
- The shows were released from 1925 to 2021.
- We split the dataset based on the content type (TV Shows and Movies).

### Filling the Missing Values with NA

<img width="1151" alt="Screen Shot 2022-04-15 at 10 53 33 AM" src="https://user-images.githubusercontent.com/50517893/163585764-a6f8ecad-892c-4405-91f1-462c8ee5e43d.png">
<img width="1152" alt="Screen Shot 2022-04-15 at 10 53 42 AM" src="https://user-images.githubusercontent.com/50517893/163585781-9c52e141-3b72-46dc-b44f-dd9a593a8b06.png">

**Central Tendency**

<img width="738" alt="Screen Shot 2022-04-15 at 10 54 11 AM" src="https://user-images.githubusercontent.com/50517893/163585844-b6171d84-8b30-4aa7-96a8-1fe15b675674.png">

## Data Analysis

<img width="447" alt="Screen Shot 2022-04-15 at 10 54 47 AM" src="https://user-images.githubusercontent.com/50517893/163585936-6897dcaa-518b-4e7e-b875-2a18c9061093.png">

### Popular actors

<img width="888" alt="Screen Shot 2022-04-15 at 10 55 09 AM" src="https://user-images.githubusercontent.com/50517893/163585988-167246b4-2164-483c-bbfd-03de857cad24.png">


<img width="883" alt="Screen Shot 2022-04-15 at 10 55 48 AM" src="https://user-images.githubusercontent.com/50517893/163586060-0b9407e4-da24-454e-95c4-0179f5b1e498.png">


<img width="886" alt="Screen Shot 2022-04-15 at 10 56 29 AM" src="https://user-images.githubusercontent.com/50517893/163586132-448b06c6-72f3-4a65-be8c-594cdf7f873f.png">

### Popular directors

<img width="883" alt="Screen Shot 2022-04-15 at 10 57 24 AM" src="https://user-images.githubusercontent.com/50517893/163586225-2125acd0-fcd0-487b-8f92-b0853b860997.png">

<img width="885" alt="Screen Shot 2022-04-15 at 10 57 42 AM" src="https://user-images.githubusercontent.com/50517893/163586265-6de0e651-7449-4d8a-9042-dcf959eadbd8.png">

<img width="882" alt="Screen Shot 2022-04-15 at 10 57 55 AM" src="https://user-images.githubusercontent.com/50517893/163586298-0e1f9df8-67c9-4817-a20d-cbb3816fd037.png">

### Popular Genres

<img width="894" alt="Screen Shot 2022-04-15 at 10 58 18 AM" src="https://user-images.githubusercontent.com/50517893/163586352-f3fa747a-e2ab-43d9-bd86-8676a20b247f.png">

<img width="894" alt="Screen Shot 2022-04-15 at 10 58 32 AM" src="https://user-images.githubusercontent.com/50517893/163586379-15953a5f-5828-489b-99d7-8aabc68fa65d.png">

<img width="887" alt="Screen Shot 2022-04-15 at 10 58 41 AM" src="https://user-images.githubusercontent.com/50517893/163586395-78b3f978-d459-4ed8-bf0f-29980805b30e.png">

### Popular times for adding content

<img width="394" alt="Screen Shot 2022-04-15 at 10 59 15 AM" src="https://user-images.githubusercontent.com/50517893/163586463-5896966a-cfe7-4b75-af36-f4cfc54b4582.png">

<img width="423" alt="Screen Shot 2022-04-15 at 10 59 44 AM" src="https://user-images.githubusercontent.com/50517893/163586521-6502a497-3383-48be-937d-59c63585ce20.png">

### Visualizing content release location

<img width="1149" alt="Screen Shot 2022-04-15 at 11 00 19 AM" src="https://user-images.githubusercontent.com/50517893/163586601-38a89532-288b-4240-9de2-0308e0bc9c32.png">

### Most popular Release years

<img width="363" alt="Screen Shot 2022-04-15 at 11 00 56 AM" src="https://user-images.githubusercontent.com/50517893/163586674-878ed43d-9906-413b-bd5f-92dfca40f860.png">

### Popular rating types

<img width="895" alt="Screen Shot 2022-04-15 at 11 01 25 AM" src="https://user-images.githubusercontent.com/50517893/163586736-820016d6-d861-47d6-9748-82a43e3c7045.png">

<img width="894" alt="Screen Shot 2022-04-15 at 11 01 48 AM" src="https://user-images.githubusercontent.com/50517893/163586783-d6f5feb0-2d82-47b2-ad9a-3a7b40ae4ac0.png">

<img width="893" alt="Screen Shot 2022-04-15 at 11 02 00 AM" src="https://user-images.githubusercontent.com/50517893/163586801-f79d2d78-8d9f-495a-9f50-3292ac86cdea.png">

### Content duration trends

<img width="364" alt="Screen Shot 2022-04-15 at 11 02 29 AM" src="https://user-images.githubusercontent.com/50517893/163586862-306e6fff-c394-43eb-b487-ec7e91271cbd.png">

## Recommendation System (content based)

These recommendations are provided based on the actors, directors, description, and genre.

<img width="614" alt="Screen Shot 2022-04-15 at 11 03 41 AM" src="https://user-images.githubusercontent.com/50517893/163586978-82ab4cde-c326-44cf-a8c0-779be40ad399.png">





