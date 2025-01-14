---
title: dfr arg-min
categories: |
  dataframe
version: 0.84.0
dataframe: |
  Return index for min value in series.
usage: |
  Return index for min value in series.
---

# <code>{{ $frontmatter.title }}</code> for dataframe

<div class='command-title'>{{ $frontmatter.dataframe }}</div>

## Signature

```> dfr arg-min ```


## Input/output types:

| input | output |
| ----- | ------ |
| any   | any    |

## Examples

Returns index for min value
```shell
> [1 3 2] | dfr into-df | dfr arg-min
╭───┬─────────╮
│ # │ arg_min │
├───┼─────────┤
│ 0 │       0 │
╰───┴─────────╯

```


**Tips:** Dataframe commands were not shipped in the official binaries by default, you have to build it with `--features=dataframe` flag