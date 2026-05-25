# unity-clock

A real-time analog clock built in Unity using C# that synchronizes with system time.

## Overview
This project renders an analog clock in Unity by mapping system time values to rotational transformations of clock hand objects. The clock updates continuously using Unity’s frame update loop.

## Implementation Details
- System time retrieved using `DateTime.Now.TimeOfDay`
- Time values converted into angular rotation
- Hand movement implemented using `Quaternion.Euler`
- Continuous updates handled in Unity `Update()` loop

## Time-to-Rotation Mappings
- Hours: 30° per hour
- Minutes: 6° per minute
- Seconds: 6° per second

## What Did I Learn?
- Unity Transform hierarchy
- Quaternion-based rotation in 2D space
- System time integration in C#

## Demo
 ![f902saE](https://github.com/integerincrement/unity-clock/assets/87837473/4aef5eaa-ca45-4aed-bf89-215dad2bbe40)
