<h1 align="center">✨ mipnote ✨</h1>
<h3 align="center">A Simple CLI Note-Taking App, Based Around Git</h3>
<h4 align="center">Use in class, at work, or to keep track of ideas</h4>

*A work in progress*

### Installation:
```bash
git clone https://github.com/mipy1/mipnote.git # Clones this repo
cd mipnote # Enters working directory
./installer # Runs installer script
cd && rm -r mipnote # Removes redundant folder
```

### Usage:

To configure mipnote, edit the `mipnote.conf` file

To create a new note, or edit an existing one:
```bash
mipnote
```

To initialise a notes repository:
```bash
mipnote -i # OR --init
```

To get a preview of a note:
```bash
mipnote -p # OR --preview
```

To get help:
```bash
mipnote -h # OR --help
```

### Future Features / Ideas:
**May not be up-to-date; see TODO.md**

- Multiple notes topics (ideas, classes, or whatever)
    - directories, and ability to switch between??
    - different branches in same directory??
- Reading notes without editing
- Better method of checking default editor
- Settings
    - default editor (maybe even, god forbid, the use of a GUI one Crowd ghasps)
    - notes directory location
    - remote repository
- Somehow have images
- Search for different notes containing phrase

