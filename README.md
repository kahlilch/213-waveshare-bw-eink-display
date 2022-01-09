# 213-waveshare-bw-eink-display
Python display functions for the 2.13 Waveshare E-Ink Pico module

I've written this module because I was finding the provided WaveShare and similar user interfaces I could find to be inadequate. This provides the bufpixel method, allowing users to display individual pixels with x,y coords, on a horizontal orientation. As the Framebuf class doesn't allow rotation, this is calculated manually.

Uses modified printchar, printstring, and cmap values from derived from https://github.com/leswright1977/picofont. As well as the classes from Waveshare themselves, see the original and other info here: https://www.waveshare.com/wiki/2.13inch_e-Paper_HAT
