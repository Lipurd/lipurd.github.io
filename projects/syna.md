---
layout: page
title: syna
permalink: /syna/
description: >-
  Display menu items on SSD1306 Displays for ESP32 or ESP8266
categories: [project,]
---

### Features
* pagination with automatic page breaks according to screen height
* display of headlines
* automatic back and forth cycle while going up and down through the pages

### Usage
```python
items = ['Test 1', 'Test 2', 'Test 3', 'Test 4', 'Test 5', 'Test 6']
menu = syna.Syna(oled, items, 'Testdevice')

menu.show()
```

Navigation via `menu.up()` and `menu.down()`
### References
* [GitHub](https://github.com/Lipurd/syna)

