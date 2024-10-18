---
layout: single
title: baseOsc
permalink: /modules/baseOsc
---
<div style="text-align: center;">
    <img src="/assets/images/baseosc.png" alt="baseOsc Module" style="height: 65vh; max-width: 100%;"/>
</div>
## Overview

The baseOsc is a versatile oscillator for VCV Rack, designed to serve as the core of your sound design setup.

Drawing on robust code from the Mutable Instruments' Braids oscillator, it offers a range of audio output shapes including triangle, sawtooth, pulse (with PWM), sine, and square sub-oscillator.

With its wavetable capability, users can smoothly interpolate between samples and cycles, and control the wavetable index for dynamic sounds.

The baseOsc features unique noise options, including pitched noise and digital clocked noise with modifiable sample cycle length and quantization.

Pitch controls allow for precise adjustments via coarse and fine tuning, octave shifts, and frequency modulation.

FM CV input can be atttenuverted, and the reponse can be toggled between linear and exponential.

When in LFO mode, the module's LED indicators display output polarity, enhancing visual feedback.

The built-in quantizer supports 19 scales and allows you to choose root notes, with LEDs indicating the current scale + root configuration.

A global bit reduction parameter for oscillator output allows can be set from 1-bit to 16-bit resolution.

The baseOsc is ready to be an essential building block for shaping both musical and experimental sounds in your patches.

## Features

- Audio output shapes
  - Triangle
  - Sawtooth
  - Pulse with Pulse Width Modulation
  - Sine
  - Square Sub Oscillator
  - Wavetable, Linear, with smooth interpolation between the samples and cycles. Modulation of wavetable index/location.
  - Noise (unaffected by pitch or LFO settings)
  - Pitched noise
  - Digital clocked noise with modulation over sample cycle length and quantization amount
- Pitch controls
  - Coarse tune
  - Fine tune
  - Octave up and down buttons +/- 5 octaves
  - LEDs above coarse knob show the current octave range
  - Frequency Modulation with toggle between linear and exponential
  - FM CV input with attenuverter
  - LFO mode toggle
    - When LFO is active, LEDs above the coarse knob show the polarity of the output in use
  - Quantizer
    - Choose between Off or 19 scales
    - Choose root note
    - Quantizer LEDs light up to indicate current scale+root combination
    - Currently quantized note indicated in these LEDs
- Bit reduction setting
  - Choose between 1-bit to 16-bit oscillator generation resolution.
