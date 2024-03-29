# MGJSON (Motion Graphics JSON)

This repository contains documentation on the mgJSON format and demo files that can be imported in Adobe After Effects to read external dynamic and static data.

## Example files

- **demo**.mgjson: Minimal working example. A static text a static nubmer and a dynamic stream with three samples (keyframes of sorts)
- **gopro**.mgjson: Comprehensive file with many data streams. Created with [GoPro Telemetry](https://goprotelemetryextractor.com/free)
- **dji**.mgjson: File with flight data from a Mavic Pro drone. Created with [DJI SRT Viewer](https://djitelemetryoverlay.com/srt-viewer)
- **from-csv**.mgjson: File with numeric data originally in CSV format. Created with [To mgJSON](https://goprotelemetryextractor.com/csv-gpx-to-mgjson/)
- **from-gpx**.mgjson: File with gps path data originally in GPX format. Created with [To mgJSON](https://goprotelemetryextractor.com/csv-gpx-to-mgjson/)

The underlying JSON schema is available for download under [Adobe's SensorManager SDK Package](https://console.adobe.io/downloads/ae).

## Software that supports mgJSON

Convert other file formats to mgJSON (CSV, GPX...):

- [To mgJSON](https://goprotelemetryextractor.com/csv-gpx-to-mgjson/)

These apps can output mgJSON files:

- [GoPro Telemetry Extractor](https://goprotelemetryextractor.com)
- [DJI Telemetry Overlay](https://djitelemetryoverlay.com)

## Sample projects

You can find sample projects that use mgJSON files on the [GoPro Telemetry Extractor page](https://goprotelemetryextractor.com). Look for the **Lite templates**.

## Videos made with mgJSON

- [mgJSON playlist on YouTube](https://youtu.be/TAdxsTv4hPU?list=PLgoeWSWqXedI7FbZccAEudt2_t8qPX0Px)

If you create something with mgJSON, let me know and I'll add it to the list.

## Tutorial

- HKChad created a [tutorial explaining the basics of displaying mgJSON data in After Effects](https://youtu.be/btY0NNFDOUs). Much more complex things are possible, but it's a great way to get started.

## Code implementations

These repositories convert other formats to mgJSON:

- [tomgjson](https://github.com/JuanIrache/tomgjson) (Go)
- [gopro-telemetry](https://github.com/JuanIrache/gopro-telemetry/blob/master/code/toMgjson.js) (JavaScript)
- [DJI_SRT_Parser](https://github.com/JuanIrache/DJI_SRT_Parser/blob/master/modules/toMGJSON.js) (JavaScript)

## Notes

Real world files filled with data from different sources can have different structures and data types than the examples here, but since online documentation is very scarce, I thought these demos were worth posting.

For instructions on how to use the imported data, see [Work with Data-driven animation](https://helpx.adobe.com/after-effects/using/data-driven-animations.html)

Feel free to submit your own samples if you think they can be useful for the community.

Note that the code has some typos, like _frequecy_ instead of _frequency_. These are necessary for the files to load in some After Effects versions.
