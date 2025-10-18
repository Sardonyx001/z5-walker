# z5-walker

Generate colorful images via random walk in Z5 (Hue, Saturation, Value, X, Y).

## Usage

Go to [sardonyx001.github.io/z5-walker](https://sardonyx001.github.io/z5-walker/) or open `index.html` in a browser.

- **Generate**: Create a new random walk image (up to 50M steps)
- **Download**: Save the generated image as PNG

## How it works

A random walk in 5-dimensional integer space where:

- **H, S, V**: Color space (Hue, Saturation, Value)
- **X, Y**: Canvas coordinates (256×256)

Each step randomly increments or decrements one dimension, coloring pixels as the walker visits them.

## Stats

- Coverage: Percentage of pixels visited
- Steps: Total random walk iterations

## Requirements

Modern web browser with HTML5 Canvas support.
