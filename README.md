# Timezone Event Planner

This is a webpage I have made with the assistance of ChatGPT for the purpose of planning events across two separate timezones.

## Webpage (Deployment) Link

https://joshrissman.github.io/timezone-event-planner/

## How To Use

1. Select the applicable timezones from the drop-down boxes for Timezone A and Timezone B. NOTE: When changing Timezone B, the date and time will change according to the date and time listed for Timezone A.
2. Use the "Day of Week" slider to select a day of the week, starting on Sunday.
3. Use the "Time of Day" slider to select the time in hours and minutes (alternatively, you can use the time input box where the time (hh:mm) is shown).
4. Using the sliders for either timezone will move the time for the other timezone accordingly (i.e. moving the hour for Timezone A forward will move the hour for Timezone B ahead an equivalent amount).

## Technologies Used

- HTML
- JavaScript
- Luxon API
- Github Pages

## How It Works

When a slider, timezone selection, or time input box are changed, the applicable timezone at the given time are set as the current time and will update either the other timezone or itself accordingly. Examples include:
  - Editing the timezone of Timezone B will shift the date and time of Timezone B to be equivalent to the time given in Timezone A.
  - Pushing forward the time of Timezone A will push forward the time of Timezone B by the same amount.

## License

MIT License

Copyright (c) 2025 Joshua Rissman

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
