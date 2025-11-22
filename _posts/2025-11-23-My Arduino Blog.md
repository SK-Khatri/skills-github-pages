---
title: "My Arduino Blog"
date: 2025-11-23
---

# Arduino Beginner Guide (Draft)

This is a short draft blog about getting started with Arduino.

## What Is Arduino?

Arduino is an easy-to-use open-source electronics platform used for building simple to advanced projects.

## Requirements

- Arduino Uno
- USB cable
- Laptop
- Arduino IDE

## Arduino Uno

![Arduino Uno](https://upload.wikimedia.org/wikipedia/commons/3/38/Arduino_Uno_-_R3.jpg)

## Sample Code: Blink LED

```cpp
void setup() {
  pinMode(LED_BUILTIN, OUTPUT);
}

void loop() {
  digitalWrite(LED_BUILTIN, HIGH);
  delay(1000);
  digitalWrite(LED_BUILTIN, LOW);
  delay(1000);
}
