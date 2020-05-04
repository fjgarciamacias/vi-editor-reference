# Basic
## Insert
* `Shift` + `a`: Insert at the end
* `Shift` + `i`: Insert at the beginning
* `a`: insert at the next position
* `i`: insert at the current position

## Motion
* `h`: Left

* `j`: Down

* `k`: Up

* `l`: Right

### Left-right motions
* `N` + `|`: go to the column N
* `0`: go to the beginning of the line
* `$`: go to the end of the line
* `N` + `l`: jump N characters to the right
* `N` + `h`: jump N characters to the left
* `N` + `f` + `{char}`: jump to the Nth ocurrence {char} in the current line ('**f**ind' right)
* `N` + `F` + `{char}`: jump to the Nth ocurrence {char} in the current line ('**F**ind' left)
* `N` + `t` + `{char}`: jump till before the Nth ocurrence {char} in the current line ('**t**ill' right)
* `N` + `T` + `{char}`: jump till before the Nth ocurrence {char} in the current line ('**T**ill' left)
* `N` + `;`: repeat the last command N times
* `N` + `,`: repeat the last command N times in the opposite direction

### Up-down motions
* `N` + `k`: up N lines
* `N` + `j`: down N lines
* `N` + `g` + `g`: go to the line N
* `N` + `-`: up N lines
* `N` + `+`: down N lines
* `N` + `%`: goto line N percentage down in the file

### Text motions
#### Basic
* `N` + `Shift` + `w`: N words forward
* `N` + `Shift` + `e`: N words forward to the end
* `N` + `Shift` + `b`: N words backward
#### Blocks of text
* `N` + `}`: N paragraphs forward
* `N` + `{`: N paragraphs backward
* `N` + `)`: N sentences forward
* `N` + `(`: N sentences backward
#### Blocks of code
**Note**: `[` is for backward and `]` is for forward 
* `N` + `[` + `m`: N times back to unclosed '{'
* `N` + `]` + `m`: N times forward to unclosed '{'
* `N` + `[` + `M`: N times back to unclosed '}'
* `N` + `]` + `M`: N times forward to unclosed '}'
* `N` + `[` + `(`: N times back to unclosed '('
* `N` + `]` + `)`: N times back to unclosed ')'
