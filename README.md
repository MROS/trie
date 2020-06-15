## merkle patricia trie benchmark

fork 自 [paritytech/trie](https://github.com/paritytech/trie)。

僅修改檔案 `trie-db/benches/bench.rs` ，請自行研究 rust 的 benchmark 機制，以及用 `git diff` 來觀察修改的痕跡。

### 跑 benchmark

```
cargo bench -- trie_proof_verification
```