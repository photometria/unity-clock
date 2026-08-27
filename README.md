# unity-clock

A simple real-time analog clock made in Unity using C#. The clock uses the computer's system time and updates the clock hands to match the current time.

## Overview
This project renders an analog clock in Unity by mapping system time values to rotational transformations of clock hand objects. The clock updates continuously using Unity’s frame update loop.

## Implementation Details
- Gets the current time using `DateTime.Now.TimeOfDay`
- Converts the hours, minutes, and seconds into rotation angles
- Hand movement implemented using `Quaternion.Euler`
- Continuous updates handled in Unity `Update()` loop

## Time-to-Rotation Mappings
- Hours: 30° per hour
- Minutes: 6° per minute
- Seconds: 6° per second

## What Did I Learn?
- How Unity's Transform hierarchy works
- How to use Quaternions for object rotation
- How to get and use system time in C#
- How Unity's Update() loop can be used for real-time updates

## Demo
 ![f902saE](https://github.com/integerincrement/unity-clock/assets/87837473/4aef5eaa-ca45-4aed-bf89-215dad2bbe40)
