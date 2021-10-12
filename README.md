# Tiles

To generate the tiles:

* Check out the [openmaptiles repo](https://github.com/openmaptiles)
* Enter the repo and run the script `./quickstart.sh berlin`

Currently, we have restricted the tiles to a small area and a particular zoom
level in order to have a more compact file for test purposes.

To adjust these, you need to tweek the `MIN_ZOOM`, `MAX_ZOOM` and `BBOX`
parameters in the `.env` file in the `openmaptiles` repo.
(When changing the `BBOX` for the first time, you may need to delete an
`<area>.box` file in `openmaptiles/data`.)
For further reference, check the [openmaptiles
QUICKSTART](https://github.com/openmaptiles/openmaptiles/blob/master/QUICKSTART.md).
