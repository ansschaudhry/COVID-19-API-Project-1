# COVID-19 API Project 1

### **Application Description:**

Tihs application will display a section where there will be a drop down menu where people can interact and choose a specific country bringing up all the stats for that specific selection. These stats will include genral country data and stats relating to COVID-19. The goal of this application is to aquire COVID-19 data for many countries from a public API and display it on the webpage in a visually pleasing way.

### **API:**

COVID-19 API : https://github.com/M-Media-Group/Covid-19-API/blob/master/README.md

### **API Snippet:**

<pre>https://covid-api.mmediagroup.fr/v1</pre>

<pre>GET /cases?country</span>=<span class="hljs-string">France</pre>

<pre>{
    "All": {
        "confirmed": 5357230,
        "recovered": 328718,
        "deaths": 101339,
        "country": "France",
        "population": 64979548,
        "sq_km_area": 551500,
        "life_expectancy": "78.8",
        "elevation_in_meters": 375,
        "continent": "Europe",
        "abbreviation": "FR",
        "location": "Western Europe",
        "iso": 250,
        "capital_city": "Paris",
        "lat": "46.2276",
        "long": "2.2137",
        "updated": "2021/04/20 11:20:59+00"
    },
    "French Guiana": {
        "lat": "4",
        "long": "-53",
        "confirmed": 18081,
        "recovered": 9995,
        "deaths": 95,
        "updated": "2021/04/20 11:20:59+00"
    },
    "French Polynesia": {
        "lat": "-17.6797",
        "long": "-149.4068",
        "confirmed": 18708,
        "recovered": 4842,
        "deaths": 141,
        "updated": "2021/04/20 11:20:59+00"
    },
    "Guadeloupe": {
        "lat": "16.265",
        "long": "-61.551",
        "confirmed": 12927,
        "recovered": 2242,
        "deaths": 194,
        "updated": "2021/04/20 11:20:59+00"
    },
    "Martinique": {
        "lat": "14.6415",
        "long": "-61.0242",
        "confirmed": 9758,
        "recovered": 98,
        "deaths": 66,
        "updated": "2021/04/20 11:20:59+00"
    },
    "Mayotte": {
        "lat": "-12.8275",
        "long": "45.166244",
        "confirmed": 19789,
        "recovered": 2964,
        "deaths": 168,
        "updated": "2021/04/20 11:20:59+00"
    },
    "New Caledonia": {
        "lat": "-20.904305",
        "long": "165.618042",
        "confirmed": 124,
        "recovered": 58,
        "deaths": 0,
        "updated": "2021/04/20 11:20:59+00"
    },
    "Reunion": {
        "lat": "-21.1151",
        "long": "55.5364",
        "confirmed": 18425,
        "recovered": 16794,
        "deaths": 135,
        "updated": "2021/04/20 11:20:59+00"
    },
    "Saint Barthelemy": {
        "lat": "17.9",
        "long": "-62.8333",
        "confirmed": 934,
        "recovered": 462,
        "deaths": 1,
        "updated": "2021/04/20 11:20:59+00"
    },
    "Saint Pierre and Miquelon": {
        "lat": "46.8852",
        "long": "-56.3159",
        "confirmed": 25,
        "recovered": 24,
        "deaths": 0,
        "updated": "2021/04/20 11:20:59+00"
    },
    "St Martin": {
        "lat": "18.0708",
        "long": "-63.0501",
        "confirmed": 1702,
        "recovered": 1399,
        "deaths": 12,
        "updated": "2021/04/20 11:20:59+00"
    },
    "Wallis and Futuna": {
        "lat": "-14.2938",
        "long": "-178.1165",
        "confirmed": 439,
        "recovered": 44,
        "deaths": 5,
        "updated": "2021/04/20 11:20:59+00"
    }
}</pre>

### **Wireframe:**

![image](https://user-images.githubusercontent.com/82814499/115401072-fc5d6b80-a1b7-11eb-83e3-b4a17501bb06.png)

### **MVP:**

- Allow a user to access specific country data using a dropdown menu selector
- Render country name, population data and number of covid cases
- Replace previous country search data when new search is made

### **Post-MVP:**

- Use media queries to help facilitate responsive desgin for a tablet (iPad 770px)
- Allow users to compare the stats of different countries
- Allow users to choose specific countries regions or continents through a drop down menu/input, render those stats
- Allow users to favorite countries so they remain on the screen
- Add a second API that includes country images to help fill the screen with visuals

### **Goals:**

|  Day | Deliverable | Status
|---|---| ---|
|April 16-18| Prompt / Wireframes / Priority Matrix / Timeframes | Complete
|April 19 All Day| Project Approval | Complete
|April 20 Morning| Project Approval | Complete
|April 20 Morning| Core Application Structure / HTML & JS| Complete
|April 20 Afternoon| Pseudocode / Debug any bugs in JS | Complete
|April 20 Night| Start on CSS | Complete
|April 21 Morning| Initial Clickable Model / Review with instructor  | Complete
|April 22 Afternoon| Review MVP and Post-MVP| Complete
|April 22 Night| Turn in | Complete

### **Priority Matrix:**

![image](https://user-images.githubusercontent.com/82814499/115259627-0d4aa600-a100-11eb-956d-08c0cda78fc9.png)

### **Timeframes:**

| Component | Priority | Estimated Time | Time Invested | Actual Time |
| --- | :---: |  :---: | :---: | :---: |
| Reworking My API Proposal | H | 3hrs| 2.5hrs | 2.5hrs |
| Making HTML base structure | H | 1hrs| .5hrs | .25hrs |
| Connecting Files to HTML| H | 1hrs| .5hrs | .5hrs |
| Create a dynamic dropdown menu | H | 1hrs| .5hrs | .5hrs |
| From option tags and assign values| H | 3hrs| 2.5hrs | 2.5hrs |
| Add Eventhandler | H | 1hrs| .5hrs | .5hrs |
| API request for data and create dynamic text | H | 3hrs| 4hrs | 4hrs |
| Code CSS | L | 3hrs| 1.5hrs | 1.5hrs |
| Add media queries | L | 1hrs| .25hrs | .25hrs |
