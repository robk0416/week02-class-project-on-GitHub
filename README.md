# Ohm's Law Calculator

## Purpose
Reads a voltage (V) and a resistance (ohms) and prints the current I = V / R.

## Input format
Two numbers separated by a space: voltage then resistance, e.g. `12 4`.

## Build and run
```
g++ -std=c++17 -Wall -Wextra -pedantic src/main.cpp -o build/app
./build/app
```

## Run the tests
```
bash test.sh
```

## Example output
```
$ echo "12 4" | ./build/app
Current: 3 A
$ echo "12 0" | ./build/app
Invalid input
```

## Limitations
- Resistance must be positive; zero or negative prints "Invalid input".
- Extra input after the two numbers is ignored.
- Output uses default double formatting (no fixed decimal places).

## Debugging reflection
WRITE 2-3 SENTENCES HERE ABOUT WHAT WENT WRONG AND HOW YOU FIXED IT.
