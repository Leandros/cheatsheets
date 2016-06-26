# GDB Cheatsheet

## Examine code

**List code around position:**
`list`
`list <lines>`

## Stepping

**Step over line:**
`next [count]`

**Step in functions:**
`step [count]`

**Step out:**
`finish`

**Continue execution:**
`c`

## Breakpoints / Watchpoints

**Set Breakpoint:**
`b <function>`
`b <filename>:<linenum>`

**Set Watchpoint:**
`watch <variable>`
`watch *(<type>*)<address>`

**List Breakpoint:**
`info break`

**Disable / Enable Breakpoint:**
`enable <id>`
`disable <id>`

**Remove Breakpoint by ID:**
`del <id>`

**Remove Breakpoint by File/Line:**
`clear <linenum>`
`clear <filename>:<linenum>`


## Custom

**Stepping:**
`stepo` (step over)
`stepi` (step in)
