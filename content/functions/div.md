+++
name = "DIV"
syntax = "DIV( dividend <INTEGER | REAL>, divisor <INTEGER | REAL> )"
description = "Calculates the quotient of two values."
type = "arithmetical"
related = ["MUL", "ADD", "SUB"]
+++

#### Examples
- `DIV(sc-bytes, 1024) AS [KB Sent]`  
  Converts bytes sent from the server to the client to Kilobytes (KB).
- `DIV(DIV(sc-bytes, 1024), 1024) AS [MB Sent]`  
  Converts bytes sent from the server to the client to Megabytes (MB).
