![ESP-8266](Photo.jpg)

# ESP-8266 Blink

This example shows the simplest thing you can do with an ESP-8266 to see physical output: it blinks the on-board LED. We use the ESP-8266 D1 Mini by WeMos.

```
/*
 * Copyright 2017 Richard Ng-Jobidon
 *
 * Licensed under the Apache License, Version 2.0 (the "License");
 * you may not use this file except in compliance with the License.
 * You may obtain a copy of the License at
 *
 *     http://www.apache.org/licenses/LICENSE-2.0
 *
 * Unless required by applicable law or agreed to in writing, software
 * distributed under the License is distributed on an "AS IS" BASIS,
 * WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 * See the License for the specific language governing permissions and
 * limitations under the License.
 */
 
void setup() 
{
  pinMode(BUILTIN_LED, OUTPUT);
}

void loop() 
{
  digitalWrite(BUILTIN_LED, HIGH);
  delay(1000);
  digitalWrite(BUILTIN_LED, LOW);
  delay(1000);
}
```
