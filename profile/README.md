## formalsketch

Browser-based tools for formal languages and automata. No accounts, no backend, no install.

### FSM Studio

[Live demo](https://formalsketch.github.io) · [Repo](https://github.com/formalsketch/formalsketch.github.io)

![FSM Studio](https://github.com/formalsketch/formalsketch.github.io/raw/main/docs/screenshot.png)

A finite state machine designer that runs in the browser.

**Editor**
- Canvas drawing: double-click to add a state, shift-drag to add a transition, drag to move, Delete to remove
- Multi-FSM workspace with a sidebar; everything persists in localStorage
- Undo / redo, light / dark / system themes
- Touch support, responsive canvas, keyboard-only operation

**Algorithms**
- Step-by-step NFA simulator with state highlighting
- Regex to NFA (Thompson's construction)
- NFA to DFA (subset construction)
- DFA minimization (partition refinement)
- Auto-layout for generated diagrams
- Lint: missing start state, nondeterminism, missing transitions, unreachable states

**Export and share**
- PNG, SVG, LaTeX (TikZ, with standalone or snippet mode)
- Versioned JSON import / export
- Share by URL (state encoded in the hash)
- Natural-language generation: describe an FSM, get the diagram
