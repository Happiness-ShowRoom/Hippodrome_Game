# Hippodrome_Game

IDE console horse racing simulator. Make your bets on one of the horses(Artax, Ruffian or Frankel), run the program and enjoy the race. Good luck! 

## Installation

Download and install [Node.js](https://nodejs.org/en/download/) to run the Undervalued_RE.
To install all the required npm modules, on the command line, in the root directory of the framework module, run:


```bash
npm install
```

## Usage
After all the node modules have been downloaded, navigate to "TestData" folder, open the "SearchCriteria.json" file and specify the criteria for your query.   

```
"appData":{
        "city": "Arlington, TX",
        "propertyType": "house+townhouse",
        "minPrice": "400k",
        "maxPrice": "500k",
        "minBeds" : "2",
        "maxBeds" : "5",
        "maxDaysOnMarket" : "30",
        "hasGarage" : "has-garage",
        "status" : "active"
    }
```
Navigate to "Configuration" folder and run:

```bash
protractor conf.js
```

Results will be outputted to "Results.xlsx" once the execution has finished, showing only those properties listed for less than an estimated market value.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.


## License
[MIT](https://choosealicense.com/licenses/mit/)
