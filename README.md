# Expression Tree Studio

An interactive expression tree debugger for understanding how binary tree structure changes arithmetic meaning.

**Version:** 3.4 · **Format:** static HTML/CSS/JavaScript · **Course context:** CS102

## Explore

- Edit an infix expression and watch the spatial tree update live.
- Orbit, zoom, and reset the 3D-style tree visualization.
- Inspect and directly edit numeric or operator nodes.
- Rotate valid subtrees, compare their structure, and undo or redo changes.
- Run preorder, inorder, or postorder traversal with synchronized Java-style trace and recursive call stack.
- Observe why raw inorder output can lose parentheses and change an expression's value.

**Try:** `8 - (3 - 1)` evaluates to `6`, while `(8 - 3) - 1` evaluates to `4`, although their raw inorder tokens are the same.

## Open locally

Open `index.html` directly in a modern browser. It contains all required CSS and JavaScript; no package installation or build step is necessary.

## Public deployment

A Render **Static Site** can serve this repository from `main` with:

- Build command: `echo ready`
- Publish directory: `.`
- Auto deploy: enabled

Alternatively, enable GitHub Pages from `main` and `/ (root)`.

## Feedback

Feedback on visual clarity, ease of manipulating the tree, and whether the execution trace makes recursion easier to understand is welcome.

## Notes

This is an educational visualization, not a Java virtual machine. The 2.5D call stack and heap relationships illustrate conceptual program state. Arithmetic inputs are deliberately restricted to the editor's supported grammar.

