Review checklist

Correctness:
- empty inputs
- min/max bounds
- duplicates (if relevant)
- termination conditions
- visited/seen correctness for graphs
- no hidden mutation bugs

Complexity:
- Big-O time + space correct
- no accidental quadratic loops

Implementation:
- off-by-one
- pointer movement consistency
- invariants stated + maintained

JS/TS specifics (frontend):
- closures capturing stale vars
- debounce/throttle: leading/trailing/cancel/flush behavior
- timers cleanup (clearTimeout/clearInterval)
- promises/async error handling
- event loop assumptions
