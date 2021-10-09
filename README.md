# Analysis of accommodation and tourist locations 
# 01 Brief & Tool Introduction

- This tool is used to study the relationship between accommodation locations and tourist attractions.
- Hoping this tool can give visitors some advice on identifying where is the nearest place to live base on their personalities.
- People can choose different colored layers to view depending on their preference for different types of attractions.
- Currently, there are several categories regarding people's preferences, as shown below.

### Specify Feature List

*PS： You can add or subtract options by your preferences.*

**Accommodation**

apartment, hostel, hotel

**Basic attractions and leisure**

attraction
parks: dog park, golf course, nature reserve, park, water park

**Family （with children）**

park, playground, resort, water park, campsite, picnic site, theme park, zoo

**Religious**

place of worship, cathedral, chapel, church, mosque, temple.

**Culture & art**

college, library, university, artwork, gallery, museum.

**Music**

the arts center, amenity, music school, theatre, shop = music, shop= music instrument.

**Shopping**

marketplace, gift, mall, supermarket

**Bar**

bar, pub, nightclub

# 02 Element

![intro4](https://user-images.githubusercontent.com/88767205/134797787-16cc7e2e-d137-41b8-a6d6-0eae20044dde.jpg)


- A general classification of places to visit 【blue groups】
- point-line / grid-field 【light green / dark green groups】
- Adjusts the display color of points or lines【red groups】


### Point - Line
Use point and line analysis to identify tourist attractions within 1500m of a residential location. This distance is adjustable as required.


**Apartment**（suitable for family travel）⇥⇥⇥ Basic & Family 

**Hotel** (for the wealthy) ⇥⇥⇥ Basic & Shopping & Bar

**Hostel** (for young people or tourists who don't have enough money to travel) ⇥⇥⇥ Special tour

### Grid
In the position of the accommodation, the grid expands outwards. Facilitates the identification of accommodation in the area on the map.

### Field
Mark the parks and green Spaces on the map. You can intuitively understand the greening rate of the city.

# 03 How to use
1. Use your own openstreet map. 
2. The expanded part of the grid shows the place of accommodation.
3. The different colored dots and lines represent the connection between different types of tourist attractions and living places.
4. Identify the grid expansion with or without the connecting lines of favored attractions to find a suitable place to live.
5. When the grid is expanded and there are many scenic spots connected, it is most likely to be a popular place for tourists to stay.

## Example & Display

[Pretoria]

![0021ee1528067a49650a4ce17c4e568](https://user-images.githubusercontent.com/88767205/134798916-2e700217-eb8e-4e94-9892-283d114c8021.png)



- red-dots → accommodation
- pink-dots → basic attractions
- blue-dots → culture & religion & art & music
- yellow-dots →shopping & bar

Point-to-point lines represent the distance between each type of attraction and the place of accommodation.

## Change over time

**Main slider: 0-24 (one day)**

Look into the changes in attraction recommendations over the day (24 hours) because many attractions have fixed opening hours.
The current time setting for the opening of the attraction is general. Further, by adjusting the Threshold can also be used to show the popular times of attractions.

**Example【Pretoria】**



https://user-images.githubusercontent.com/88767205/134799168-d6681766-57ef-436e-a11c-02e6188c1544.mp4



- Attractions 【Threshold = 8 (8am) / 18 (6pm)】

                           Grey dots→ Pink dots →Grey dots

- Theme park & zoo 【Threshold = 9 (9am) / 17 (5pm)】

                          Grey dots→ Red dots →Grey dots

- Art centre & theater & gallery & museum 【Threshold = 9 (9am) / 17 (5pm)】

                          Grey dots→ Blue dots →Grey dots

- Bars 【Threshold =  18 (6pm) / 2 (2am)】

                          Disappeared → Light blue dots

## Charts

These charts show the different proportions of three types of accommodations and the number of various tourist attractions in the city.




