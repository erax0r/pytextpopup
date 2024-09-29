
# pytextpopup ![PyPI](https://img.shields.io/pypi/v/pytextpopup) ![License](https://img.shields.io/pypi/l/pytextpopup)

**pytextpopup** is a simple yet powerful Python library that allows you to create customizable floating text popups at the cursor's position on your screen. It’s a fun way to display text with style, and you can easily tweak the font, color, and speed of scrolling. Whether you want to create desktop notifications, fun reminders, or artistic popups, pytextpopup is your go-to library!

## 🚀 Features

- **Customizable Floating Text**: Change the font, color, and scroll speed with ease.
- **Dynamic Window Sizing**: The window automatically adjusts to the text size and fits your screen.
- **Cross-Platform**: Works seamlessly across different monitors and screen setups.
- **Lightweight**: Uses minimal resources with the help of `tkinter`.
- **Monitor-Aware**: Detects the current cursor position and adjusts the popup location accordingly.

## 🎬 Quick Demo

```python
from pytextpopup import text_popup

# Display a simple popup at the cursor's position
text_popup("Hello, World!", fontname="Helvetica", color="blue", scrollspeed=3)
```

![Demo](https://media.giphy.com/media/JU8j5bvsM0mR8/giphy.gif)  <!-- Replace with your own GIF if you'd like -->

## 💻 Installation

Get started with just one command!

```bash
pip install pytextpopup
```

## 🛠 Usage

Here’s a quick breakdown of how to use `pytextpopup`. You can pass text, font name, color, and scroll speed as arguments to the `text_popup` function.

### Example 1: Simple Usage

```python
from pytextpopup import text_popup

# Basic usage
text_popup("Welcome to pytextpopup!")
```

### Example 2: Custom Fonts and Colors

```python
from pytextpopup import text_popup

# Use custom font and color
text_popup("This is a custom popup!", fontname="Comic Sans MS", color="green", scrollspeed=2)
```

### Example 3: Faster Scrolling

```python
from pytextpopup import text_popup

# Change scroll speed
text_popup("Zooming text!", scrollspeed=10)
```

### Example 4: Multi-line Text

```python
from pytextpopup import text_popup

# Display multi-line text
text_popup("Line 1\nLine 2\nLine 3", fontname="Courier", color="purple", scrollspeed=4)
```

## ⚙️ Parameters

- `text` (str): The text to display in the popup.
- `fontname` (str): The font family to use (default: "Arial").
- `color` (str): The color of the text (default: "white").
- `scrollspeed` (int): The speed of text scrolling, with lower numbers being slower (default: 5).

## 🎨 Customization

You have full control over the appearance and behavior of the text popup:

- **Font**: Choose any system-installed font.
- **Color**: Set any color using standard names like `red`, `blue`, or hex values like `#FF5733`.
- **Scroll Speed**: Adjust how fast or slow the text should scroll.

Want to experiment? Try out different values for an even more personalized popup.

```python
text_popup("Try Me!", fontname="Times New Roman", color="#FF0000", scrollspeed=1)
```

## 📦 Dependencies

- **tkinter**: Built-in with Python for GUI applications.
- **screeninfo**: To detect monitor setup and handle cursor positioning.

You can install `screeninfo` easily via pip:

```bash
pip install screeninfo
```

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
