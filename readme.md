# MGJSON format example

This repository contains demo files that can be imported in Adobe After Effects to read external dynamic and static data.

- **demo**.mgjson: Minimal working example. A static text and a stream with three samples (keyframes of sorts)
- **gopro**.mgjson: Comprehensive file with many data streams. Created with [GoPro Telemetry](https://tailorandwayne.com/gopro-telemetry-extractor/)
- **AESpeedometer**.zip: Template demonstrating how to use mgJSON files in After Effects

The underlying JSON schema is available for download under [Adobe's SensorManager SDK Package](https://console.adobe.io/downloads/ae).

Actual files filled with data will have to change a lot depending on the contained data, but since online documentation is extremely scarce, I thought this demo was worth posting.

For instructions on how to use the imported data, see [Work with Data-driven animation](https://helpx.adobe.com/after-effects/using/data-driven-animations.html)

Feel free to submit your own samples if you think they can be useful for the community.

Note that the code has some typos, like _frequecy_ instead of _frequency_. These are necessary for the files to load in some After Effects versions.
