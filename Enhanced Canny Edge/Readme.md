# Enhanced Canny Edge Detection

We are making use of a parameter named **sigma** that we can change easily to alter both upper and lower threshold required for Canny Edge to work.
We are keeping **sigma** to be **33%** which is for most past the optimal ratio but can be altered according to one's need and for experimental purposes.

## Using Argparse and Glob

### Argparse and Glob in combination makes it buttery smooth for our model to fetch the data from whatever directory using command line

```shell
python auto_canny.py --images images
```

hello