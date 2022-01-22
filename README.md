# Merge Directories

```
dir1/
├─ file_a.txt
└─ file_b.txt

dir2/
├─ file_a.txt
└─ file_c.txt

result/
├─ file_a.txt
├─ file_b.txt
└─ file_c.txt
```

`dir1 + dir2 = result`

- `file_a` is overwritten
- `file_b` is not changed
- `file_c` is added

`dir1` is overwritten with the result.
