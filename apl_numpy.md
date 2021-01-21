# Apl operator vs numpy functions

| Apl operator | Monadic/unary equivalent | Dyalic/binary equivalent |
| ------------- | ------------- | ----|
| `+` | `positive` | `add` |
| `-` | `negative` | `subtract` |
| `×` | `sign` | `multiply` |
| `÷` | `reciprocal` | `divide` |
| `⌈` | `ceil` | `maximum` |
| `⌊` | `floor` | `minimum` |
| `*` | `exp` | `power` |
| `⍟` | `log` | `lambda x, y: divide(log(x), log(y))` |
| `○` | `lambda x: multiply(pi, x)` | Many trigonometric related functions |
| `|` | `absolute` | ~`mod` |
| `!` | Element wise factorial | Element wise combination |
| `>` | N/A | `greater` |
| `<` | N/A | `less` |
| `≥` | N/A | `greater_equal` |
| `≤` | N/A | `less_equal` |
| `=` | N/A | `equal` |
| `≠` | N/A | `not_equal` |
| `∧` | N/A | `logical_and` |
| `∨` | N/A | `logical_or` |
| `⍲` | N/A | Element wise logical_nand |
| `⍱` | N/A | Element wise logical_nor |
| `~` | `logical_not` | N/A |
| `+/` | `sum` | N/A |
| `×/` | `prod` | N/A |
| `∧/` | `all` | N/A |
| `∨/` | `any` | N/A |
| `⌈/` | `amax` | N/A |
| `⌊/` | `amin` | N/A |
| `⍴` | `ndarray.shape` | `reshape` |






