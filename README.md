# findhydrant_takashimacity

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A web application that displays the locations of fire hydrants, fire cisterns, and other firefighting water sources in Takashima City, Shiga, Japan. It utilizes open data published by the city.

## Demo

https://code4fukui.github.io/findhydrant_takashimacity/

## Features

-   Plots various firefighting water sources (hydrants, cisterns, pools, etc.) on an interactive map.
-   Uses distinct icons to differentiate between water source types.
-   Finds the nearest water source to the user's current GPS location.
-   Displays details for each location, such as type, address, and capacity.
-   The map interface is powered by Leaflet using map tiles from the Geospatial Information Authority of Japan (GSI).

## Data Source

This application uses the "Takashima City Fire Hydrant Information" (高島市 消火栓情報) open dataset, available on the [BODIK.jp platform](https://data.bodik.jp/dataset/252123_fire_hydrant_format).

The data is provided as several CSV files (one for each area of the city) which are included in this repository.

## Getting Started

No build process or installation is required.

1.  Clone this repository.
2.  Open the `index.html` file in a modern web browser.

*Note: For the best experience, especially for GPS functionality, serve the files from a local web server.*

## Attribution

This project is based on the work of Taisuke Fukuno. The original source includes the attribution: `(c)taisukef CC BY http://fukuno.jig.jp/`.

## License

MIT License — see [LICENSE](LICENSE).