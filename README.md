# multilingual-e5_onnx

ノーマルmultilingual-e5-smallと量子最適化された.onnxモデルでの推論の速度比較

.onnxモデルはHFリポジトリ内で提供されているモデルをそのまま使う


## Result

multi-e5.onnx is  **x 2.5 faster** than normal multi-e5.bin @googlecolab/cpu
 

---
## Benchmark 



```
## Benchmark ##

Trail:0 Done
Trail:1 Done
Trail:2 Done
Trail:3 Done
Trail:4 Done
Trail:5 Done
Trail:6 Done
Trail:7 Done
Trail:8 Done
Trail:9 Done


## Result ##

Trail_Count:10

onnx_time_total	12.115
onnx_token_total	13291
onnx_speed	1097 token/sec


norm_time_total	32.376
norm_token_total	13291
norm_speed	411 token/sec
```
