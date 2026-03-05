<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

Uses digital logic with a simple Verilog ROM to display a bouncing logo on a VGA display.

## How to test

Provide a 25MHz clock and assert reset, then observe the output via a Tiny VGA adapter connected to `uo_out`!

## External hardware

Tiny VGA adapter connected to a VGA monitor (or, say, a VGA=>HDMI converter).
