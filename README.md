# sl-satfinder


`sl-satfinder` is a Python app I made to find the best direction to point your dish.  You will know if you need this, if you are wondering why you need it you don't have the challange.

## Basic features

- Figures out where to point your dishy for the best connection
- Gives you the average azimuth and elevation of the satellites (as in "which way to point")
- Shows you a bunch of details about starlink satellite positions if you're into that
- Works with UK postcodes (sorry, solved my itch - but open to adding geos!)

## How does it do its magic?

1. Asks you for your postcode to query the API
2. Grabs your location details
3. Fetches the latest Starlink satellite positions
4. Does some maths to figure out where most satellites are, this reminded me of school maths.
5. Tells you where to point your dish

## Current limitations (aka "features to be added later")

- Only works for UK postcodes right now
- Needs internet to work (ironic for a tool to help with internet, I know)

## Future plans (maybe, if I'm not too lazy)

- Make it work worldwide
- Add some cool visuals (probably a site map or similar?)
- Fix things that are broken (for those "I have no internet to figure out how to get internet" moments)

## How to use it

It's super simple:

```
./sl-satfinder SW1A 1AA
```

Just replace `SW1A 1AA` with your actual postcode.

## A word of caution

This is just a side project, if you end up pointing your dish at a passing pigeon instead of a satellite, okay?

## Want to help?

Found a bug? Got an idea to make this even cooler? Feel free to jump in! pr's and issues welcome, sans SLA's.

## License

This project is licensed under the MIT License - see the MIT-LICENSE.txt file for details. Basically, do whatever you want with it, but you are on your own.

