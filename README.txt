JarpySDR - A Tayloe Detector board for Software Defined Radio.

This is a simple SDR frontend using all through-hole components.

It requires an off-board square-wave oscillator/clock running at F*4, where F is the radio frequency to be recieved. The design is pin compatible with WA6UFQ's Si570 oscillator card, and provides an I2C pass-through header with which to program the Si570.

You don't have to use the Si570 board however. You can clock it with any square-wave source you have handy.

The design is derived from the G0NQE Acorn SDR receiver.

Links:
  Si570 oscillator board
  http://home.roadrunner.com/~wa6ufq/universal_vfo_controller.html

  G0NQE Acorn SDR
  http://www.g0nqe.co.uk/projects/g0nqe-acorn_sdr_receiver
