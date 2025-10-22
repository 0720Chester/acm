要判断节点 `x` 是否在路径 `s-t` 上，可通过以下两个条件组合判断：

- `deep[x] >= deep[LCA(s, t)]`
- `LCA(s, x) = x` 或 `LCA(t, x) = x`
