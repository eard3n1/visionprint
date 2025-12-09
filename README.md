# visionprint
A small Python utility library offering conditional styles for CLIs.

## Features
- Coherent printing style for different conditions
- Lightweight, easy to use
- No dependencies

## Installation
```bash
pip install visionprint
```

## Example
```python
from visionprint import success, info, note, warn, error

success("Success") # Green, bold, italic
info("Info")       # Blue, italic
note("Note")       # Faint
warn("Warn")       # Yellow, bold, underline
error("Error")     # Red, underline
```

## Reference
- <code>success(msg: str)</code><br>Green, bold, italic<br><br>
- <code>info(msg: str)</code><br>Blue, italic<br><br>
- <code>note(msg: str)</code><br>Faint<br><br>
- <code>warn(msg: str)</code><br>Yellow, bold, underline<br><br>
- <code>error(msg: str)</code><br>Red, underline<br><br>

## Note
Work in progress...

## License
MIT License
