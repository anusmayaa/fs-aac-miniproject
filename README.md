# Search Algorithms Visualizer

An interactive web-based visualizer for Linear Search and Binary Search algorithms, built with HTML, CSS, and vanilla JavaScript.

## Features

- **Linear Search** – Step-by-step visualization of sequential search
- **Binary Search** – Step-by-step visualization of divide & conquer search
- **Side-by-Side Comparison** – Watch both algorithms run simultaneously to see the speed difference

## How to Use

1. Open `main.html` in any browser
2. Navigate between sections using the top navbar

### Linear Search
- Enter a comma-separated array (e.g. `5,3,8,1,9`)
- Enter a target value
- Click **Search**, then **Next Step** to walk through each comparison

### Binary Search
- Enter a **sorted** comma-separated array (e.g. `1,2,3,5,8,9`)
- Enter a target value
- Click **Search**, then **Next Step** to walk through each step

### Compare Both
- Enter a **sorted** array and a target value
- Click **Compare**, then **Next Step** to see both algorithms progress simultaneously

## Color Guide

| Color | Meaning |
|-------|---------|
| Purple | Currently being checked |
| Green | Target found |
| Faded purple | Already checked / out of range |

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript (no libraries or frameworks)
