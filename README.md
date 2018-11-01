# Meridian Example Socket connection

### Prerequisites

- [nodejs 8 or later][nodejs]
- Meridian Location ID
- Meridian Map ID
- [Meridian Authentication Token](https://edit.meridianapps.com/api/tokens)


### Project Setup

After [`nodejs`][nodejs] has been installed run `npm install` in the directory of the project to install the necessary dependencies


### Example Usage

```sh
$ LOCATION_ID='5468665088573440'
$ MAP_ID='5653104741580800'
$ TOKEN='014a16eb151e577f17684346d798bad88ab58009'
$ node example.js --locationID "$LOCATION_ID" --mapID "$MAP_ID" --token "$TOKEN"
```


[nodejs]: https://nodejs.org/en/download "NodeJS Download Page"
