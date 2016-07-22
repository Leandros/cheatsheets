# GDB Cheatsheet

## Examine code

**List code around position:**<br>
`list`<br>
`list <lines>`

## Stepping

**Step over line:**<br>
`next [count]`

**Step over instruction:**<br>
`stepi [count]` (short: `si`)
`nexti [count]` (steps over functions) (short: `ni`)

**Step over source line:**<br>
`step [count]`

**Step out:**<br>
`finish`

**Continue execution:**<br>
`c`

**One-Time breakpoint:**<br>
`until <linenum>`

## Breakpoints / Watchpoints

**Set Breakpoint:**<br>
`b <function>`<br>
`b <filename>:<linenum>`

**Set Watchpoint:**<br>
`watch <variable>`<br>
`watch *(<type>*)<address>`

**List Breakpoint:**<br>
`info break`

**Disable / Enable Breakpoint:**<br>
`enable <id>`<br>
`disable <id>`

**Remove Breakpoint by ID:**<br>
`del <id>`

**Remove Breakpoint by File/Line:**<br>
`clear <linenum>`<br>
`clear <filename>:<linenum>`

## Automatic Display

**Display expr each time gdb stops:**<br>
`display <expr>` (example: `display/i $pc` to display current assembly line)

**Show all current displays:**<br>
`info display`

**Modify displays:**<br>
`delete display <dnum>`
`disable display <dnum>`
`enable display <dnum>`
`display` (show all, same as stopping)

## Custom

**Stepping:**<br>
`stepo` (step over)<br>
`stepi` (step in)
