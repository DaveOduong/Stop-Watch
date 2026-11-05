# STOPWATCH

## 1. Project Description
Stopwatch is a simple web application developed using HTML and JavaScript. It allows users to measure elapsed time in minutes and seconds using Start, Stop, and Reset controls.

## 2. Features
- **Start:** Starts the stopwatch and counts seconds automatically.
- **Stop:** Pauses the stopwatch without losing the elapsed time.
- **Reset:** Stops the stopwatch and returns the time to 00:00.
- Displays time in MM:SS format.
- Uses a two-digit format for minutes and seconds.

## 3. Technologies Used
- **HTML:** Creates the stopwatch display and control buttons.
- **JavaScript:** Handles time tracking, intervals, and button functionality.

## 4. Project Files
- `index.html` – Contains the webpage structure, timer display, and buttons.
- `script.js` – Contains the functions responsible for stopwatch operations.

## 5. How to Run
1. Save the HTML code as `index.html`.
2. Save the JavaScript code as `script.js`.
3. Place both files in the same folder.
4. Open `index.html` in a web browser.
5. Use the Start, Stop, and Reset buttons to operate the stopwatch.

## 6. JavaScript Functions

**padStart(value)**

Converts time values into two-digit strings by adding a leading zero when necessary.

**setTime()**

Calculates minutes and seconds and updates the stopwatch display.

**timer()**

Increases the elapsed time by one second and refreshes the display.

**startClock()**

Starts the stopwatch using `setInterval()` to execute the timer function every second.

**stopClock()**

Uses `clearInterval()` to stop the running interval.

**resetClock()**

Stops the stopwatch, resets elapsed seconds to zero, and updates the display.

## 7. JavaScript Concepts Demonstrated
- Variables and state management.
- Functions.
- DOM manipulation.
- `setInterval()` and `clearInterval()`.
- Mathematical operations (`Math.floor()` and modulo `%`).
- String conversion and `padStart()`.
- Event handling using `onclick`.

## 8. Conclusion
This project demonstrates how JavaScript can be used to create a functional stopwatch through time tracking, interval management, DOM manipulation, and user interaction.
