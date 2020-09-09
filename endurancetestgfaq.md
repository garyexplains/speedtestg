# Endurance Test G FAQ

## Introduction
Endurance Test G is a companion test of Speed Test G. Before reading this FAQ you might want to read the [Speed Test G FAQ](https://github.com/garyexplains/speedtestg/blob/master/FAQ.md).

## 1. How does it work?
The concept is simple. I use a specially modified version of Speed Test G that runs in a loop. The 11 tests are run, ending with the Unreal test, and then the test is run again.
And again. And again. Until the battery goes flat.

For each iteration, the total time for running Speed Test G is noted. Afterwards, this data is collated and used to generate the graphs.

## 2. Can you record the temperature, that would be useful?
Unfrotnaly there is no standard way to measure the temperature of an Android device. There is an Android API to get the temperature but...
1) Implementations vary from device to device, meaning what temperature is reported is different on each d3evice. Could be the CPU temperature or the room temperature
or the temperature somewhere else in the device (but not near the CPU). 2) This API was deprecated in Android 4.0 (API Level 14).

## 3. Can't you use some other method to get the temperature?
Some devices allow the temperature to be read via the Linux kernel, however again this varies from device to device. As above there is no guarantee
about which temperature is being reported.

## 4. Can't you measure the temperature manually
Theoretically yes, but since these tests take several hours to run that would be a labor-intensive task. Ideally in a full lab set up there could be some automatic temperature
monitoring using an Arduino or Raspberry Pi, but I don't have a full lab setup.
