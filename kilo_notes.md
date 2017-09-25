  * Quick command to convert hex number to binary (but the reverse doesn't work, why?)
      `echo 'ibase=16; obase=2;70' | bc`
  * Pressing CTRL with a character, strips bits 5 & 6 from character and send that. 
  * Set and clear bit 5 to switch between lowercase and uppercase
  * `\x1b = 27` is the the escape character. Escape sequences always start with `27` followed by `[`. Look at [VT100 User Guide](http://vt100.net/docs/vt100-ug/chapter3.html) for other codes.
  * Place the curser at a position using: `<esc>[12;40H`
  * Skipped Step 30
  * `snprintf`: print string to buffer, can be used to change size of strings
  * How are the other values set? Auto increment.

  enum editorKey {
    ARROW_LEFT = 1000,
    ARROW_RIGHT,
    ARROW_UP,
    ARROW_DOWN
}



