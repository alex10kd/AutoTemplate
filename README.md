Automatically finds all groups in the Grasshopper canvas and skips any whose names start with //.

Applies color coding to groups based on name prefixes: in (reddish), out (greenish), op (beige), and vis (light blue).

Processes group names by removing these prefixes for cleaner scribble labels (e.g., in Curves becomes Curves).

Searches for existing scribbles inside each group and updates them if update is set to true.

Creates new scribbles at the top-left corner of each group if none exist and update is true.

If update is false, no changes are made—only a report is generated showing what would happen.

Scribble font size is controlled by the size input, with a default layout and alignment for clarity.

Outputs a list of actions taken (or that would be taken) for each group, helping you keep track of changes.
