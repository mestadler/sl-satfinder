# sl-satfinder


`sl-satfinder` app to find the best direction to point starlink dish.  You will know if you need this, will be of no interest if you don't.

## Basic features

- Figures out where to point your dish for the best connection
- Gives you the average azimuth and elevation of the satellites (as in "which way to point")
- Shows you a bunch of details about starlink satellite positions if you're into that
- Works with UK postcodes.

## How

1. Asks you for your postcode to query the API
2. Fetches the latest Starlink satellite positions
4. Does some maths to figure out positions and density of starlink satelites.
5. provides direction and elecation to point your dish

## Current limitations

- Only works for UK postcodes right now
- Needs internet to work (ironic for a tool to help with internet, I know)

## Future (nmaybe)

- Add flag to use lat/long/elev

## How to use it

```
./sl-satfinder SW1A 1AA
```

Just replace `SW1A 1AA` with your actual postcode.

## License

This project is licensed under the MIT License, essentially, do whatever you want with it,

