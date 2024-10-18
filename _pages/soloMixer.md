---
layout: single
title: soloMixer
permalink: /modules/soloMixer
---
<div style="text-align: center;">
    <img src="/assets/images/solomixer.png" alt="soloMixer Module" style="height: 65vh; max-width: 100%;"/>
</div>
## Overview

The soloMixer is a versatile mixer for VCV Rack, designed to give you precise control over three input channels—Red, Green, and Blue.
Each channel features a logarithmic level control and is normalled to the channel below it. If there isn’t a cable plugged into a channel's input, it receives the signal from the channel above, prior to any attenuation. The top channel, R, has a +5V signal by default, which allows the module to be used as a CV offset.
The module offers visual feedback through color-coded LEDs that indicate attenuation levels and the final mix output. With bipolar and unipolar options, along with soft-clipping on each output, the soloMixer is perfect for shaping sounds.
The soloMixer also features a unique solo functionality, providing two states of solo configurations. This makes it easy to quickly toggle between two sets of output mixes, which lends itself well to performance or quick comparisons. The individual outputs on each channel are not affected by the solo status, providing additional flexibility in routing your signals.

## Features

- 3 inputs: Red, Green, and Blue channels
- Logarithmic level control for each input
- Inputs normalled to the channel below for easy chaining
- Color-coded LED indicates attenuation level for each channel
- Final mix output can be inverted on the +/- output or unipolar on the + output
- Final mix output LED color based on the sum of the 3 channels
- Soft-clipping overdrive on each output
- +5V on the top channel (Channel R) when nothing is plugged in, allowing for CV offset output. This cascades via the normalization configuration.
- Solo functionality for R, G, and B channels; multiple channels can be active
- Two solo states (1 and 2) toggleable via a button next to the mix knob, with corresponding LEDs for each channel's solo state
