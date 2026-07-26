A simple calculator built as a first-year project, later redesigned with a focus on visual design and UX.

Before: Basic calculator with keyboard input support, but no backspace (only full clear) and no visual design(default styling, single-line display).

After: Added a backspace key, a two-line display (expression + result), divide-by-zero handling(replaced the raw Infinity result with a clear error message), and a full UI redesign with its own color palette. Also replaced eval() with a self-written expression parser (tokenize → shunting-yard → RPN) as a best practice.

Built with HTML, CSS, and vanilla JS(no frameworks).
