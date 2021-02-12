
<b>USE THIS!</b><br>
<br>
clear<br>
nvcc -I. ATen/native/cuda/ForeachBinaryOpScalar.cu -o test --expt-relaxed-constexpr<br>
./test