### Patches to generate lists of values:
- gen-fun: generate from a function (expr)
- gen-rnd: generate at random
- fractal: generate fractal list from a function (expr)
- scale: get a scale in MIDI pitches

### Patches to get items from a list:
- list-next: get next item in sequence
- list-rnd: get one item at random
- list-rnr: get one item at random without repeating any
- list-item: wrapper to choose one of the above

### Patches to play MIDI:
- play: plays a single note
- play-lists: plays a sequence of notes. Consumes lists for channels, pitches, velocities and durations
- play-ctl: also consumes lists, but to play midi controllers

### Filters to apply to lists in order to get modified versions:
- sublist: get a fragment of an existing list
- list-prof-+: creates a profile of differences re. one of the elements
- list-prof-x: creates a profile of proportions re. one of the elements
- augment: expand individual values to several by using expr
- aug-prof-+: expand individual values by summing a profile
- aug-prof-x: expand individual values by multiplying a profile
- fit: make the values fit some boundaries (scale [+ transport])
- list-shuffle: shuffle items in a list
- list-shuffle-x: repeat a list shuffled differently every time

### Utility patches:
- add: adds values to an accumulated sum up to a limit
- count: counts messages up to a limit
- list-concat: concatenate items/lists into a bigger list
