.. include:: ./links.inc

Arduino to Parallel Port converter
==================================

Parallel ports are less and less common on computers, and are not supported by macOS.
Instead, the `Human Neuroscience Platform <fcbg hnp_>`_ developed a USB to parallel port
converter using an arduino.

The details can be found on this repository:
https://github.com/fcbg-hnp-meeg/arduino-trigger

.. warning::

    On Linux, the arduino to parallel-port converter works reliably for ~10 minutes
    after which some sort of overflow occurs and impacts negatively the timing of the
    triggers. Use at your own discretion.
