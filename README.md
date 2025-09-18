# Back-Tracking-Sudoku-Solver---Hard
This Sudoku solver uses backtracking. It checks each empty cell (.) and tries placing digits 1–9. For each placement, it verifies if it’s safe (row, column, and 3×3 subgrid constraints). If valid, it proceeds recursively; if stuck, it backtracks by resetting the cell. The recursion ends successfully once all rows are filled.
