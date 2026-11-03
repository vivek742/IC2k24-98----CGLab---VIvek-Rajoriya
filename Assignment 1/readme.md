# CGM Lab Assignment 1 – Basic Graphics Primitives

## 📌 Aim
Write a C++ program using the `graphics.h` library to draw four basic graphics primitives in a single graphics window.

## 🎯 Shapes Implemented
1. **Straight Line** – Draws a straight line using the `line()` function.
2. **Circle** – Draws a circle using the `circle()` function.
3. **Rectangle** – Draws a rectangle using the `rectangle()` function.
4. **Triangle** – Draws a triangle using three `line()` functions.

## 📂 Project Structure
```text
Assignment 1/
│
├── basicshapes.cpp
├── basicshapes.exe
├── README.md
└── output.png
```

## ▶️ Compilation and Execution

**Step 1: Compile the program**

```bash
g++ basicshapes.cpp -o basicshapes.exe -lbgi -lgdi32 -lcomdlg32 -luuid -loleaut32 -lole32
```

**Step 2: Run the program**

```bash
./basicshapes.exe
```

## 📚 Graphics Functions Used

| Function | Description |
|---|---|
| `initwindow()` | Creates the graphics window |
| `setbkcolor()` | Sets the background color |
| `cleardevice()` | Clears the graphics screen |
| `setcolor()` | Sets the drawing color |
| `line()` | Draws a straight line |
| `circle()` | Draws a circle |
| `rectangle()` | Draws a rectangle |
| `outtextxy()` | Displays text at specified coordinates |
| `getch()` | Waits for keyboard input |
| `closegraph()` | Closes the graphics window |

## 🎨 Output
The program displays all four basic graphics primitives in one 800 × 600 graphics window:

- Yellow straight line
- Green circle
- Cyan rectangle
- Red triangle

## ✅ Result
Successfully implemented and displayed four basic graphics primitives using C++ and the `graphics.h` library.

--