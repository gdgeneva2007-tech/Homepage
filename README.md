# 1.'z-30' only applies on elements which has 'position' (Relative, Absolute, Fixed, or Sticky)

# 2.You can use 'z-30' to handle overlap

# 3.You can use negative margin to create overlap (-ml-12)

# 4.In HTML, <i>,<span>,<a> are inline elements. Browsers cannot transform (scale/rotate) inline elements

# 5.In CSS, when you make a parent display: flex (or grid), its direct children stop being "inline" or "block." They become Flex Items.

The Rule: Flex Items always behave like blocks (technically "blockified"). They can have width, height, and transforms (like scale and rotate), even if they are <a> or <span> tags.

# 6.Use <br> to make a line break

# 7.If you want to make an image fill its container, you need to set 'w-full' and 'h-full' dimensions to the image and give it 'object-cover' attribute. If you only add 'w-full h-full' to its parent container, it won't work


