# GDB Cheatsheet

## Examine code

**List code around position:**<br>
`list`<br>
`list <lines>`

## Stepping

**Step over line:**<br>
`next [count]`

**Step in functions:**<br>
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


## Custom

**Stepping:**<br>
`stepo` (step over)<br>
`stepi` (step in)
