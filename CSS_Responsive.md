# CSS Responsiveness

## Layouts the Easy Way

These are the tips from [5 simple tips to making responsive layouts the easy way](https://youtu.be/VQraviuwbzU) by [Kevin Powell](https://www.youtube.com/channel/UCJZv4d5rbIKd4QHMPkcABCw)

### 1 Start with Global Styling

***"Start with the things that kill the most birds with one stone. Dont worry about layout and smaller things."***

- Colours
  - Global Palette with variables
- Backgrounds
  - Root
  - Tags
  - Image Sizing (to adapt to their containers)
- Typography
  - Font
    - Face
    - Weight by selectors
    - Colours from palette
    - Margins
    - Padding

***"At this stage it doesn't look pretty, But it isn't broken"***

### 2 Avoid fixed sizes

***"Setting things in a fixed [*size*] is only going to cause you problems"***

Try to avoid using units of fixed measurements such as "width: 100px", "height 100px" or whatever

Avoid:

- Points (pt)
- Pixels (px)

Try and use maximums and measure in rems/ems and percentages to prevent content overflowing elements
