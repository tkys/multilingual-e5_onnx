# multilingual-e5_onnx

ノーマルmultilingual-e5-smallと量子最適化された.onnxモデルでの推論の速度比較

.onnxモデルはHFリポジトリ内で提供されているモデルをそのまま使う


## Result

multi-e5.ONNX is   ~~**x7.83 faster**~~ than normal multi-e5. 

---
## Benchmark 

```
@googlecolab/cpu

# Normal
# multilingual-e5-small.bin

encode_time.sum:5.049156904220581
encode_token_len_sum:1001
encode speed (token/sec):198.25091970567718

# ONNX
# multilingual-e5-small.onnx

encode_time_sum:0.6443085670471191
encode_token_len_sum:1001
encode speed (token/sec):1553.6034303992042
```
