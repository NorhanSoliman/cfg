CSCE 428/828 Project 2: Context Free Grammars
Team Members:
Norhan Alatyr
Nazrin Nazarudin
-----------------------------------------------------------------------
How the CFG Works:

- Red Background: CF::Background = [hue 352 sat 1]: Sets the background color with a hue of 352, saturation of 1, and default brightness.

- Startshape CHRISTMAS: Specifies the initial shape to be used, named "CHRISTMAS."

- shape CHRISTMAS{ ... }: Defines the rules for the "CHRISTMAS" shape. It consists of three components:

1. TREE[s 10 hue 120 sat 1 b 0.5]: Represents a tree with specific parameters for scale, hue, saturation, and brightness.

shape TREE{ ... }: Defines the "TREE" shape using recursive triangles, creating a fractal tree structure. Each level of recursion (TREE [y 0.2 s 0.9]) adds a smaller triangle, creating the appearance of a tree with branches.

2. STEM[s 11 hue 30 sat 1 b 0.3 y -4]: Represents a stem (trunk) with specified parameters.

shape STEM{ ... }: Defines the "STEM" shape, which is a square rotated 90 degrees. This represents the trunk of the tree.

3. STAR[s 0.3 y 20.7]: Represents a star with specific parameters and position.

shape STAR{ ... }: Defines the "STAR" shape, which consists of four triangles arranged to resemble a star. The triangles have specific parameters for scale, hue, saturation, and brightness.

------------------------------------------------------------------------------




