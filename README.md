# EasyAnimator
Java program that reads in specially formatted text and creates the corresponding frame-by-frame animation. The user can choose to create the animation as plain text, a visual representation, or SVG-formatted text.

The visual representation uses Java Swing to display animations.

**Note:** Code must be kept private per course restrictions. If you would like to view it, please email me at eng.m@husky.neu.edu

## Features

**Views:**
- Text
- Visual (non-interactive)
- SVG
- Hybrid visual (interactive)

**Shapes**:
- Rectangle
- Oval

**Animations:**
- Color change
- Scale
- Translation

## Usage

```java -jar EasyAnimator.jar -if <input_file> -iv <view_mode> -o <output_file> -speed <speed>```

**Text view** assembles an easy-to-read log of each event that comprises the animation and outputs it to the specified <output_file>

**Visual** view displays a smooth playback of the animation from start to finish. This mode is not interactive.

**SVG** mode builds an event log similar to Text view, but in SVG format. It outputs it to the specified <output_file>

**Hybrid visual** mode gives the user control of when/how the animation is displayed. They can start/stop, restart, toggle automatic loopback, increment/decrement speed (ticks per second), or export the animation as SVG at any time via keyboard inputs. A real-time log of each action performed by the user is displayed under the animation.

## Hybrid Visual Mode Example
![alt text](https://i.imgur.com/wdIcfa0.png)

