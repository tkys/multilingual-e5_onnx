# multilingual-e5_onnx

ノーマルmultilingual-e5-smallと量子最適化された.onnxモデルでの推論の速度比較

.onnxモデルはHFリポジトリ内で提供されているモデルをそのまま使う


## Result

multi-e5.onnx is  **x2 faster** than normal multi-e5.bin @googlecolab/cpu
 

![plot](https://github.com/tkys/multilingual-e5_onnx/assets/24400946/2257ed3f-b36d-4cc7-872e-0ac778a90b26)


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
onnx_time_total	14.439099999999998
onnx_token_total	13279
onnx_speed	920 token/sec


norm_time_total	28.244899999999998
norm_token_total	13279
norm_speed	470 token/sec

```

