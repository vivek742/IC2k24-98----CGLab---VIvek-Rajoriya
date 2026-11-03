# DDA Line Drawing Algorithm

## 📌 Aim
Write a C++ program using the `graphics.h` library to draw a straight line between two given points using the Digital Differential Analyzer (DDA) line drawing algorithm.

## 🎯 Algorithm
1. Read the starting point `(x1, y1)` and ending point `(x2, y2)`.
2. Calculate `dx = x2 - x1` and `dy = y2 - y1`.
3. Calculate the number of steps using `max(abs(dx), abs(dy))`.
4. Calculate X and Y increments.
5. Start from the initial coordinates.
6. Plot pixels using `putpixel()` and update X and Y in each iteration.

## 💻 Input Points

**Starting Point:**
```text
(0, 0)
```

**Ending Point:**
```text
(100, 100)
```

## 🧮 Calculation

```text
x1 = 0, y1 = 0
x2 = 100, y2 = 100

dx = 100 - 0 = 100
dy = 100 - 0 = 100

steps = max(100, 100) = 100

X Increment = 100 / 100 = 1
Y Increment = 100 / 100 = 1
```

## ▶️ Sample Input
```text
Enter starting point (x1 y1): 0 0
Enter ending point (x2 y2): 100 100
```

## 📊 Output
- A graphics window of size 800 × 600.
- Black background.
- Cartesian coordinate axes.
- Yellow diagonal line connecting `(0,0)` and `(100,100)`.
- Scale factor of 2 to make the line visually larger.

## 📚 Functions Used

| Function | Description |
|---|---|
| `initwindow()` | Creates the graphics window |
| `setbkcolor()` | Sets background color |
| `cleardevice()` | Clears the graphics screen |
| `line()` | Draws coordinate axes |
| `putpixel()` | Plots individual pixels |
| `setcolor()` | Sets drawing color |
| `outtextxy()` | Displays text |
| `getch()` | Waits for keyboard input |
| `closegraph()` | Closes the graphics window |

## ⚙️ Compilation and Execution

**Compile:**
```bash
g++ DDA.cpp -o DDA.exe -lbgi -lgdi32 -lcomdlg32 -luuid -loleaut32 -lole32
```

**Run:**
```bash
./DDA.exe
```

## ✅ Result
Successfully implemented the Digital Differential Analyzer (DDA) line drawing algorithm to draw a straight line between the points `(0,0)` and `(100,100)`.

---

