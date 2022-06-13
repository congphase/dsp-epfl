# 1.1.3.b. The Karplus-Strong algorithm

## Building blocks
### Adder
![](../docs/adder_building_block.png)

### Multiplier
![](../docs/multiplier_bb.png)

### Unit delay
![](../docs/unit_delay_bb.png)

### Arbitrary delay
![](../docs/arbitrary_delay_bb.png)

## Moving average
![](../docs/2_point_moving_average.png)

### Moving average on act
- Delta:

![](../docs/sample_moving_average.png)
- Notice how $ y[0] $ and $ y[1] $ got averaged out. But not $ y[2] $ (The right-handed graph is the graph of the output, don't confuse)

- Sinusoidal:

![](../docs/averaging_of_sinusoidal_signal.png)


## A recursion
![](../docs/the_reverse.png)

- An initial condition of 0 for each memory cell ($ z^{-1} $) must be set.


## Make some music
### Some bullets 

![](../docs/make_music_1.png)

### A simple example

![](../docs/make_music_2.png)

- If we play that with the sampling frequency of 48KHz, the pattern will repeat every 100 samples

- Some realism

![](../docs/realism.png)

- The Karplus-Strong algorithm
![](../docs/karplus_strong_algo.png)