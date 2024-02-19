# Tiny Language Model (TLM)

1) Is it possible use [Abstract Syntax Tree (AST)](https://en.wikipedia.org/wiki/Abstract_syntax_tree) (AST-like) instead of using [regex](https://en.wikipedia.org/wiki/Regular_expression)?

2) Can develop a tiny language model (TLM), character-based?

Based on this method that has some similarities with n-grams?

`The quick brown fox jumps over the lazy dog.`

⬇️ ⬆️ 

`the, quick, brown, fox, jumps, over, the, lazy, dog` --> word 9-gram or 9-wgram

⬇️ ⬆️ 

`t, h, e = t + h + e = the` --> char 3-gram or word 1-gram (3-cgram or 1-wgram)

`q, u, i, c, k = q + u + i + c + k = quick` --> char 5-gram or word 1-gram (5-cgram or 1-wgram)

...

⬇️ ⬆️ 

`a, b, c, d, e, f, g, h, i, j, k, l, m, n, o, p, q, r, s, t, u, v, w, x, y, z` --> char 1-gram or 1-cgram

