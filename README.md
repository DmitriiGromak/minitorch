# minitorch
The full minitorch student suite. 


To access the autograder: 

* Module 0: https://classroom.github.com/a/qDYKZff9
* Module 1: https://classroom.github.com/a/6TiImUiy
* Module 2: https://classroom.github.com/a/0ZHJeTA0
* Module 3: https://classroom.github.com/a/U5CMJec1
* Module 4: https://classroom.github.com/a/04QA6HZK
* Quizzes: https://classroom.github.com/a/bGcGc12k

# Тесты для 3.3, 3.4
В Gitlab нет GPU, а для этих тестов он нужен, поэтому та их нельзя запустить. Я локально их прогнал, у меня прошли
=================================================================== test session starts ===================================================================
platform linux -- Python 3.10.21, pytest-7.1.2, pluggy-1.6.0
rootdir: /mnt/jack-7/dgromak/momo/minitorch, configfile: setup.cfg
plugins: hydra-core-1.3.2, env-0.6.2, hypothesis-6.54.0
collected 294 items / 237 deselected / 57 selected                                                                                                        

tests/test_tensor_general.py .........................................................                                                              [100%]

==================================================================== warnings summary =====================================================================
tests/test_tensor_general.py: 16 warnings
  /mnt/jack-1/dgromak/miniconda3/envs/minitorch/lib/python3.10/site-packages/numba/cuda/dispatcher.py:536: NumbaPerformanceWarning: Grid size 1 will likely result in GPU under-utilization due to low occupancy.
    warn(NumbaPerformanceWarning(msg))

tests/test_tensor_general.py: 4268 warnings
  /mnt/jack-1/dgromak/miniconda3/envs/minitorch/lib/python3.10/site-packages/numba/cuda/cudadrv/devicearray.py:888: NumbaPerformanceWarning: Host array used in CUDA kernel will incur copy overhead to/from device.
    warn(NumbaPerformanceWarning(msg))

tests/test_tensor_general.py: 11 warnings
  /mnt/jack-1/dgromak/miniconda3/envs/minitorch/lib/python3.10/site-packages/numba/cuda/dispatcher.py:536: NumbaPerformanceWarning: Grid size 2 will likely result in GPU under-utilization due to low occupancy.
    warn(NumbaPerformanceWarning(msg))

tests/test_tensor_general.py::test_one_args[cuda-fn5]
tests/test_tensor_general.py::test_one_derivative[cuda-fn0]
tests/test_tensor_general.py::test_one_derivative[cuda-fn3]
tests/test_tensor_general.py::test_one_derivative[cuda-fn10]
tests/test_tensor_general.py::test_sum_practice2
  /mnt/jack-1/dgromak/miniconda3/envs/minitorch/lib/python3.10/site-packages/numba/cuda/dispatcher.py:536: NumbaPerformanceWarning: Grid size 3 will likely result in GPU under-utilization due to low occupancy.
    warn(NumbaPerformanceWarning(msg))

tests/test_tensor_general.py::test_one_derivative[cuda-fn0]
  /mnt/jack-1/dgromak/miniconda3/envs/minitorch/lib/python3.10/site-packages/numba/cuda/dispatcher.py:536: NumbaPerformanceWarning: Grid size 6 will likely result in GPU under-utilization due to low occupancy.
    warn(NumbaPerformanceWarning(msg))

tests/test_tensor_general.py::test_one_derivative[cuda-fn0]
  /mnt/jack-1/dgromak/miniconda3/envs/minitorch/lib/python3.10/site-packages/numba/cuda/dispatcher.py:536: NumbaPerformanceWarning: Grid size 4 will likely result in GPU under-utilization due to low occupancy.
    warn(NumbaPerformanceWarning(msg))

tests/test_tensor_general.py::test_one_derivative[cuda-fn0]
  /mnt/jack-1/dgromak/miniconda3/envs/minitorch/lib/python3.10/site-packages/numba/cuda/dispatcher.py:536: NumbaPerformanceWarning: Grid size 8 will likely result in GPU under-utilization due to low occupancy.
    warn(NumbaPerformanceWarning(msg))

tests/test_tensor_general.py::test_one_derivative[cuda-fn1]
  /mnt/jack-1/dgromak/miniconda3/envs/minitorch/lib/python3.10/site-packages/numba/cuda/dispatcher.py:536: NumbaPerformanceWarning: Grid size 12 will likely result in GPU under-utilization due to low occupancy.
    warn(NumbaPerformanceWarning(msg))

tests/test_tensor_general.py::test_one_derivative[cuda-fn3]
  /mnt/jack-1/dgromak/miniconda3/envs/minitorch/lib/python3.10/site-packages/numba/cuda/dispatcher.py:536: NumbaPerformanceWarning: Grid size 9 will likely result in GPU under-utilization due to low occupancy.
    warn(NumbaPerformanceWarning(msg))

tests/test_tensor_general.py::test_one_derivative[cuda-fn3]
  /mnt/jack-1/dgromak/miniconda3/envs/minitorch/lib/python3.10/site-packages/numba/cuda/dispatcher.py:536: NumbaPerformanceWarning: Grid size 27 will likely result in GPU under-utilization due to low occupancy.
    warn(NumbaPerformanceWarning(msg))

tests/test_tensor_general.py::test_one_derivative[cuda-fn8]
  /mnt/jack-1/dgromak/miniconda3/envs/minitorch/lib/python3.10/site-packages/numba/cuda/dispatcher.py:536: NumbaPerformanceWarning: Grid size 18 will likely result in GPU under-utilization due to low occupancy.
    warn(NumbaPerformanceWarning(msg))

tests/test_tensor_general.py::test_sum_practice_other_dims
  /mnt/jack-1/dgromak/miniconda3/envs/minitorch/lib/python3.10/site-packages/numba/cuda/dispatcher.py:536: NumbaPerformanceWarning: Grid size 16 will likely result in GPU under-utilization due to low occupancy.
    warn(NumbaPerformanceWarning(msg))

-- Docs: https://docs.pytest.org/en/stable/how-to/capture-warnings.html
============================================== 57 passed, 237 deselected, 4308 warnings in 222.25s (0:03:42) ==============================================
=================================================================== test session starts ===================================================================
platform linux -- Python 3.10.21, pytest-7.1.2, pluggy-1.6.0
rootdir: /mnt/jack-7/dgromak/momo/minitorch, configfile: setup.cfg
plugins: hydra-core-1.3.2, env-0.6.2, hypothesis-6.54.0
collected 294 items / 287 deselected / 7 selected                                                                                                         

tests/test_tensor_general.py .......                                                                                                                [100%]

==================================================================== warnings summary =====================================================================
tests/test_tensor_general.py::test_mul_practice1
  /mnt/jack-1/dgromak/miniconda3/envs/minitorch/lib/python3.10/site-packages/numba/np/ufunc/parallel.py:371: NumbaWarning: The TBB threading layer requires TBB version 2021 update 6 or later i.e., TBB_INTERFACE_VERSION >= 12060. Found TBB_INTERFACE_VERSION = 12050. The TBB threading layer is disabled.
    warnings.warn(problem)

tests/test_tensor_general.py::test_mul_practice1
tests/test_tensor_general.py::test_mul_practice3
tests/test_tensor_general.py::test_mul_practice3
tests/test_tensor_general.py::test_bmm[cuda]
tests/test_tensor_general.py::test_bmm[cuda]
tests/test_tensor_general.py::test_bmm[cuda]
  /mnt/jack-1/dgromak/miniconda3/envs/minitorch/lib/python3.10/site-packages/numba/cuda/dispatcher.py:536: NumbaPerformanceWarning: Grid size 1 will likely result in GPU under-utilization due to low occupancy.
    warn(NumbaPerformanceWarning(msg))

tests/test_tensor_general.py: 111 warnings
  /mnt/jack-1/dgromak/miniconda3/envs/minitorch/lib/python3.10/site-packages/numba/cuda/cudadrv/devicearray.py:888: NumbaPerformanceWarning: Host array used in CUDA kernel will incur copy overhead to/from device.
    warn(NumbaPerformanceWarning(msg))

tests/test_tensor_general.py::test_mul_practice4
  /mnt/jack-1/dgromak/miniconda3/envs/minitorch/lib/python3.10/site-packages/numba/cuda/dispatcher.py:536: NumbaPerformanceWarning: Grid size 35 will likely result in GPU under-utilization due to low occupancy.
    warn(NumbaPerformanceWarning(msg))

tests/test_tensor_general.py::test_mul_practice4
tests/test_tensor_general.py::test_bmm[cuda]
tests/test_tensor_general.py::test_bmm[cuda]
  /mnt/jack-1/dgromak/miniconda3/envs/minitorch/lib/python3.10/site-packages/numba/cuda/dispatcher.py:536: NumbaPerformanceWarning: Grid size 4 will likely result in GPU under-utilization due to low occupancy.
    warn(NumbaPerformanceWarning(msg))

tests/test_tensor_general.py::test_mul_practice5
tests/test_tensor_general.py::test_bmm[cuda]
tests/test_tensor_general.py::test_bmm[cuda]
  /mnt/jack-1/dgromak/miniconda3/envs/minitorch/lib/python3.10/site-packages/numba/cuda/dispatcher.py:536: NumbaPerformanceWarning: Grid size 8 will likely result in GPU under-utilization due to low occupancy.
    warn(NumbaPerformanceWarning(msg))

tests/test_tensor_general.py::test_bmm[cuda]
tests/test_tensor_general.py::test_bmm[cuda]
tests/test_tensor_general.py::test_bmm[cuda]
  /mnt/jack-1/dgromak/miniconda3/envs/minitorch/lib/python3.10/site-packages/numba/cuda/dispatcher.py:536: NumbaPerformanceWarning: Grid size 2 will likely result in GPU under-utilization due to low occupancy.
    warn(NumbaPerformanceWarning(msg))

tests/test_tensor_general.py::test_bmm[cuda]
  /mnt/jack-1/dgromak/miniconda3/envs/minitorch/lib/python3.10/site-packages/numba/cuda/dispatcher.py:536: NumbaPerformanceWarning: Grid size 16 will likely result in GPU under-utilization due to low occupancy.
    warn(NumbaPerformanceWarning(msg))

tests/test_tensor_general.py::test_bmm[cuda]
  /mnt/jack-1/dgromak/miniconda3/envs/minitorch/lib/python3.10/site-packages/numba/cuda/dispatcher.py:536: NumbaPerformanceWarning: Grid size 24 will likely result in GPU under-utilization due to low occupancy.
    warn(NumbaPerformanceWarning(msg))

tests/test_tensor_general.py::test_bmm[cuda]
  /mnt/jack-1/dgromak/miniconda3/envs/minitorch/lib/python3.10/site-packages/numba/cuda/dispatcher.py:536: NumbaPerformanceWarning: Grid size 64 will likely result in GPU under-utilization due to low occupancy.
    warn(NumbaPerformanceWarning(msg))

tests/test_tensor_general.py::test_bmm[cuda]
  /mnt/jack-1/dgromak/miniconda3/envs/minitorch/lib/python3.10/site-packages/numba/cuda/dispatcher.py:536: NumbaPerformanceWarning: Grid size 6 will likely result in GPU under-utilization due to low occupancy.
    warn(NumbaPerformanceWarning(msg))

tests/test_tensor_general.py::test_bmm[cuda]
tests/test_tensor_general.py::test_bmm[cuda]
  /mnt/jack-1/dgromak/miniconda3/envs/minitorch/lib/python3.10/site-packages/numba/cuda/dispatcher.py:536: NumbaPerformanceWarning: Grid size 3 will likely result in GPU under-utilization due to low occupancy.
    warn(NumbaPerformanceWarning(msg))

tests/test_tensor_general.py::test_bmm[cuda]
  /mnt/jack-1/dgromak/miniconda3/envs/minitorch/lib/python3.10/site-packages/numba/cuda/dispatcher.py:536: NumbaPerformanceWarning: Grid size 48 will likely result in GPU under-utilization due to low occupancy.
    warn(NumbaPerformanceWarning(msg))

tests/test_tensor_general.py::test_bmm[cuda]
  /mnt/jack-1/dgromak/miniconda3/envs/minitorch/lib/python3.10/site-packages/numba/cuda/dispatcher.py:536: NumbaPerformanceWarning: Grid size 12 will likely result in GPU under-utilization due to low occupancy.
    warn(NumbaPerformanceWarning(msg))

tests/test_tensor_general.py::test_bmm[cuda]
  /mnt/jack-1/dgromak/miniconda3/envs/minitorch/lib/python3.10/site-packages/numba/cuda/dispatcher.py:536: NumbaPerformanceWarning: Grid size 18 will likely result in GPU under-utilization due to low occupancy.
    warn(NumbaPerformanceWarning(msg))

tests/test_tensor_general.py::test_bmm[cuda]
  /mnt/jack-1/dgromak/miniconda3/envs/minitorch/lib/python3.10/site-packages/numba/cuda/dispatcher.py:536: NumbaPerformanceWarning: Grid size 27 will likely result in GPU under-utilization due to low occupancy.
    warn(NumbaPerformanceWarning(msg))

tests/test_tensor_general.py::test_bmm[cuda]
  /mnt/jack-1/dgromak/miniconda3/envs/minitorch/lib/python3.10/site-packages/numba/cuda/dispatcher.py:536: NumbaPerformanceWarning: Grid size 36 will likely result in GPU under-utilization due to low occupancy.
    warn(NumbaPerformanceWarning(msg))

tests/test_tensor_general.py::test_bmm[cuda]
  /mnt/jack-1/dgromak/miniconda3/envs/minitorch/lib/python3.10/site-packages/numba/cuda/dispatcher.py:536: NumbaPerformanceWarning: Grid size 5 will likely result in GPU under-utilization due to low occupancy.
    warn(NumbaPerformanceWarning(msg))

tests/test_tensor_general.py::test_bmm[cuda]
  /mnt/jack-1/dgromak/miniconda3/envs/minitorch/lib/python3.10/site-packages/numba/cuda/dispatcher.py:536: NumbaPerformanceWarning: Grid size 32 will likely result in GPU under-utilization due to low occupancy.
    warn(NumbaPerformanceWarning(msg))

-- Docs: https://docs.pytest.org/en/stable/how-to/capture-warnings.html
==================================================== 7 passed, 287 deselected, 141 warnings in 11.13s =====================================================


# 1.5
## Simple
Epoch  10  loss  31.571232946376742 correct 29
Epoch  20  loss  24.972563519163824 correct 34
Epoch  30  loss  17.79310192658581 correct 40
Epoch  40  loss  13.993291252324322 correct 42
Epoch  50  loss  7.631355988899491 correct 47
Epoch  60  loss  7.383729413221 correct 46
Epoch  70  loss  10.989158448856102 correct 45
Epoch  80  loss  2.7298428035533973 correct 50
Epoch  90  loss  2.262397000487213 correct 50
Epoch  100  loss  1.9557525847536117 correct 50
Epoch  110  loss  1.7239233739509439 correct 50
Epoch  120  loss  1.5424905457442768 correct 50
Epoch  130  loss  1.3930152403194564 correct 50
Epoch  140  loss  1.2670084874353116 correct 50
Epoch  150  loss  1.1586465974524252 correct 50
Epoch  160  loss  1.0641453659763167 correct 50
Epoch  170  loss  0.981057773488088 correct 50
Epoch  180  loss  0.907414309371675 correct 50
Epoch  190  loss  0.8418282931466856 correct 50
Epoch  200  loss  0.7830778185602132 correct 50
Epoch  210  loss  0.7303227843519368 correct 50
Epoch  220  loss  0.6830106576756687 correct 50
Epoch  230  loss  0.6410276440105317 correct 50
Epoch  240  loss  0.6022486287637844 correct 50
Epoch  250  loss  0.567337409880453 correct 50
Epoch  260  loss  0.5354326277770111 correct 50
Epoch  270  loss  0.5062108303793236 correct 50
Epoch  280  loss  0.47941316257578404 correct 50
Epoch  290  loss  0.4547433758389084 correct 50
Epoch  300  loss  0.43205481051138456 correct 50
Epoch  310  loss  0.4110665083920356 correct 50
Epoch  320  loss  0.39133757394992263 correct 50
Epoch  330  loss  0.3733405336812407 correct 50
Epoch  340  loss  0.3565350697381283 correct 50
Epoch  350  loss  0.34083578508632384 correct 50
Epoch  360  loss  0.3263087135233627 correct 50
Epoch  370  loss  0.31273337220058856 correct 50
Epoch  380  loss  0.2998266486946038 correct 50
Epoch  390  loss  0.287879130769375 correct 50
Epoch  400  loss  0.2767096483048167 correct 50
Epoch  410  loss  0.2660549290103728 correct 50
Epoch  420  loss  0.2560515039418597 correct 50
Epoch  430  loss  0.24664277270448584 correct 50
Epoch  440  loss  0.23779037231782746 correct 50
Epoch  450  loss  0.22944366009847875 correct 50
Epoch  460  loss  0.22156666094476415 correct 50
Epoch  470  loss  0.21411848728811111 correct 50
Epoch  480  loss  0.20707123777327416 correct 50
Epoch  490  loss  0.20039846190520788 correct 50
Epoch  500  loss  0.19406872311822937 correct 50

## Diag
Epoch  10  loss  15.170302715455858 correct 45
Epoch  20  loss  14.50350570809956 correct 45
Epoch  30  loss  13.757702416280775 correct 45
Epoch  40  loss  12.791470056376879 correct 45
Epoch  50  loss  11.520841274336764 correct 45
Epoch  60  loss  9.989513404454765 correct 45
Epoch  70  loss  8.38520224935731 correct 45
Epoch  80  loss  6.967145525552402 correct 46
Epoch  90  loss  5.841559731315895 correct 48
Epoch  100  loss  4.967770933293595 correct 48
Epoch  110  loss  4.3079205461145635 correct 48
Epoch  120  loss  3.8026265488979867 correct 49
Epoch  130  loss  3.4085787445565128 correct 49
Epoch  140  loss  3.0946015133165186 correct 49
Epoch  150  loss  2.8389867931433463 correct 50
Epoch  160  loss  2.6263422049946787 correct 50
Epoch  170  loss  2.445899213337452 correct 50
Epoch  180  loss  2.2900711513366394 correct 50
Epoch  190  loss  2.153976934204333 correct 50
Epoch  200  loss  2.0342743129950467 correct 50
Epoch  210  loss  1.9296795456105458 correct 50
Epoch  220  loss  1.8465511085958792 correct 50
Epoch  230  loss  1.8551622501219702 correct 50
Epoch  240  loss  2.5411362656577645 correct 49
Epoch  250  loss  3.374519418147545 correct 49
Epoch  260  loss  2.5166632989892994 correct 49
Epoch  270  loss  1.990733655574308 correct 49
Epoch  280  loss  1.7711192630024182 correct 49
Epoch  290  loss  1.6931024910090005 correct 49
Epoch  300  loss  1.7015339076725517 correct 49
Epoch  310  loss  1.7854418260659066 correct 49
Epoch  320  loss  1.9047126615918488 correct 49
Epoch  330  loss  1.9474533505730778 correct 49
Epoch  340  loss  1.8304164857353542 correct 49
Epoch  350  loss  1.6511755344824603 correct 49
Epoch  360  loss  1.504677919654442 correct 49
Epoch  370  loss  1.4053567345986664 correct 50
Epoch  380  loss  1.3500881712940207 correct 50
Epoch  390  loss  1.3336731781923712 correct 50
Epoch  400  loss  1.3506521521803374 correct 50
Epoch  410  loss  1.4099998834936243 correct 49
Epoch  420  loss  1.4966364121571736 correct 49
Epoch  430  loss  1.5380989695434202 correct 49
Epoch  440  loss  1.4834070897536962 correct 49
Epoch  450  loss  1.3600706318734963 correct 49
Epoch  460  loss  1.2197661280406764 correct 50
Epoch  470  loss  1.1207987876312253 correct 50
Epoch  480  loss  1.0455602192316993 correct 50
Epoch  490  loss  1.0057593254222932 correct 50
Epoch  500  loss  0.9992115649264663 correct 50

## Circle
Epoch  10  loss  31.0795568253632 correct 31
Epoch  20  loss  29.27973725042576 correct 31
Epoch  30  loss  27.202225119262913 correct 32
Epoch  40  loss  25.48347200785652 correct 34
Epoch  50  loss  28.101453598504627 correct 35
Epoch  60  loss  25.858647785741518 correct 33
Epoch  70  loss  26.500864181004022 correct 36
Epoch  80  loss  22.769298800234655 correct 36
Epoch  90  loss  24.10139291126656 correct 37
Epoch  100  loss  22.72828975834346 correct 38
Epoch  110  loss  22.73958214542811 correct 39
Epoch  120  loss  19.62730949475978 correct 40
Epoch  130  loss  17.78386186504214 correct 41
Epoch  140  loss  16.95719837714439 correct 42
Epoch  150  loss  13.676738345001661 correct 43
Epoch  160  loss  13.619721418960209 correct 43
Epoch  170  loss  11.297408853624002 correct 45
Epoch  180  loss  10.744708158325267 correct 46
Epoch  190  loss  8.247702208424514 correct 48
Epoch  200  loss  13.178026547270253 correct 42
Epoch  210  loss  7.770176902782451 correct 49
Epoch  220  loss  5.541541753708121 correct 49
Epoch  230  loss  8.322829011384954 correct 46
Epoch  240  loss  6.165580025423082 correct 47
Epoch  250  loss  6.619776313416743 correct 47
Epoch  260  loss  6.278608621768907 correct 47
Epoch  270  loss  5.732722798801174 correct 47
Epoch  280  loss  5.556552722380198 correct 47
Epoch  290  loss  5.320128893551561 correct 48
Epoch  300  loss  5.158278474765547 correct 48
Epoch  310  loss  4.9679806546263725 correct 48
Epoch  320  loss  4.750769743600669 correct 48
Epoch  330  loss  4.619166941434797 correct 48
Epoch  340  loss  4.474189356878014 correct 49
Epoch  350  loss  4.251582385593522 correct 49
Epoch  360  loss  4.138770220648677 correct 49
Epoch  370  loss  4.066899623113882 correct 49
Epoch  380  loss  3.9548010434373824 correct 49
Epoch  390  loss  3.896667877861563 correct 49
Epoch  400  loss  3.7996761067965035 correct 49
Epoch  410  loss  3.6590830024492678 correct 49
Epoch  420  loss  3.620346246852068 correct 49
Epoch  430  loss  3.3018488329777504 correct 49
Epoch  440  loss  3.2056793614455126 correct 49
Epoch  450  loss  3.2273252913139325 correct 49
Epoch  460  loss  3.2389229120722405 correct 49
Epoch  470  loss  3.1039599010525962 correct 49
Epoch  480  loss  3.1125036322362543 correct 49
Epoch  490  loss  2.996841139969789 correct 49
Epoch  500  loss  3.042507160953477 correct 49

## Spiral
Epoch  10  loss  34.02272309064788 correct 28
Epoch  20  loss  33.805951048682566 correct 29
Epoch  30  loss  33.83970121013573 correct 28
Epoch  40  loss  33.792644553550545 correct 28
Epoch  50  loss  33.66382263624536 correct 28
Epoch  60  loss  33.64284658958133 correct 29
Epoch  70  loss  33.79588673928978 correct 28
Epoch  80  loss  33.81156393573948 correct 28
Epoch  90  loss  33.64394766257774 correct 29
Epoch  100  loss  33.71339806324503 correct 28
Epoch  110  loss  33.68081460005936 correct 29
Epoch  120  loss  33.64402035140953 correct 29
Epoch  130  loss  33.56010731570258 correct 29
Epoch  140  loss  33.54153775073259 correct 29
Epoch  150  loss  33.54236933196537 correct 29
Epoch  160  loss  33.59526423137204 correct 29
Epoch  170  loss  33.53718937222186 correct 29
Epoch  180  loss  33.519090048671025 correct 29
Epoch  190  loss  33.59739350167038 correct 30
Epoch  200  loss  33.62373101969532 correct 28
Epoch  210  loss  33.5210651367189 correct 29
Epoch  220  loss  33.50444627983136 correct 29
Epoch  230  loss  33.469589753828814 correct 29
Epoch  240  loss  33.4720959290298 correct 29
Epoch  250  loss  33.58962640098098 correct 29
Epoch  260  loss  33.48014230473017 correct 29
Epoch  270  loss  33.56859129105265 correct 29
Epoch  280  loss  33.537150297647734 correct 29
Epoch  290  loss  33.45728363512942 correct 29
Epoch  300  loss  33.45751344914966 correct 29
Epoch  310  loss  33.634117539789294 correct 28
Epoch  320  loss  33.54875571191589 correct 28
Epoch  330  loss  33.469364839939026 correct 30
Epoch  340  loss  33.5411034819773 correct 28
Epoch  350  loss  33.52047382168504 correct 28
Epoch  360  loss  33.41475330306955 correct 29
Epoch  370  loss  33.39352610922908 correct 29
Epoch  380  loss  33.3695348266467 correct 29
Epoch  390  loss  33.33511994646847 correct 29
Epoch  400  loss  33.308405386161965 correct 29
Epoch  410  loss  33.34096734935548 correct 29
Epoch  420  loss  33.36911323962985 correct 29
Epoch  430  loss  33.337252093645404 correct 29
Epoch  440  loss  33.25503513498239 correct 29
Epoch  450  loss  33.67470994450386 correct 28
Epoch  460  loss  33.38250011112084 correct 29
Epoch  470  loss  33.31341399084474 correct 29
Epoch  480  loss  33.26482015821735 correct 29
Epoch  490  loss  33.343080262254176 correct 29
Epoch  500  loss  33.53746985222207 correct 28

# 2.5
## Simple
Epoch  10  loss  29.079524902165396 correct 28  time/epoch 0.1504s
Epoch  20  loss  16.82184820726721 correct 45  time/epoch 0.1409s
Epoch  30  loss  8.084443464418118 correct 49  time/epoch 0.1899s
Epoch  40  loss  4.729599465038092 correct 50  time/epoch 0.1942s
Epoch  50  loss  3.2745795118421848 correct 50  time/epoch 0.1843s
Epoch  60  loss  2.4890515114854455 correct 50  time/epoch 0.1514s
Epoch  70  loss  2.0067600905887035 correct 50  time/epoch 0.1884s
Epoch  80  loss  1.6808732149523025 correct 50  time/epoch 0.1891s
Epoch  90  loss  1.443378964929799 correct 50  time/epoch 0.1867s
Epoch  100  loss  1.262297774404582 correct 50  time/epoch 0.1512s
Epoch  110  loss  1.1188767606086512 correct 50  time/epoch 0.1442s
Epoch  120  loss  1.0020620672089584 correct 50  time/epoch 0.1963s
Epoch  130  loss  0.9048812223963607 correct 50  time/epoch 0.1412s
Epoch  140  loss  0.8227654455257992 correct 50  time/epoch 0.1371s
Epoch  150  loss  0.7523862650075137 correct 50  time/epoch 0.1673s
Epoch  160  loss  0.6914221375370888 correct 50  time/epoch 0.1946s
Epoch  170  loss  0.6381451481587447 correct 50  time/epoch 0.1875s
Epoch  180  loss  0.5912373520766732 correct 50  time/epoch 0.1606s
Epoch  190  loss  0.5497705899851157 correct 50  time/epoch 0.1408s
Epoch  200  loss  0.5128618242065657 correct 50  time/epoch 0.1877s
Epoch  210  loss  0.47997236033243207 correct 50  time/epoch 0.1666s
Epoch  220  loss  0.45033219316310635 correct 50  time/epoch 0.1574s
Epoch  230  loss  0.42351740461925425 correct 50  time/epoch 0.1687s
Epoch  240  loss  0.3991742611522098 correct 50  time/epoch 0.1941s
Epoch  250  loss  0.37700393092050627 correct 50  time/epoch 0.1946s
Epoch  260  loss  0.3567520341101576 correct 50  time/epoch 0.1520s
Epoch  270  loss  0.3382007842079292 correct 50  time/epoch 0.1931s
Epoch  280  loss  0.3211629060611399 correct 50  time/epoch 0.1884s
Epoch  290  loss  0.30547609691648236 correct 50  time/epoch 0.1889s
Epoch  300  loss  0.2909994305926577 correct 50  time/epoch 0.1468s
Epoch  310  loss  0.2776099517975507 correct 50  time/epoch 0.1423s
Epoch  320  loss  0.2652001741920077 correct 50  time/epoch 0.1868s
Epoch  330  loss  0.2536752012918471 correct 50  time/epoch 0.1973s
Epoch  340  loss  0.2429515135358871 correct 50  time/epoch 0.1978s
Epoch  350  loss  0.23295526386419485 correct 50  time/epoch 0.1552s
Epoch  360  loss  0.22362092498735003 correct 50  time/epoch 0.1566s
Epoch  370  loss  0.21489019128379366 correct 50  time/epoch 0.1421s
Epoch  380  loss  0.206711046551366 correct 50  time/epoch 0.1879s
Epoch  390  loss  0.1990369693075225 correct 50  time/epoch 0.1883s
Epoch  400  loss  0.1918262527544299 correct 50  time/epoch 0.1500s
Epoch  410  loss  0.18504142078768054 correct 50  time/epoch 0.1436s
Epoch  420  loss  0.17864872480164112 correct 50  time/epoch 0.1345s
Epoch  430  loss  0.17261815374907544 correct 50  time/epoch 0.2145s
Epoch  440  loss  0.16693206478437578 correct 50  time/epoch 0.2111s
Epoch  450  loss  0.16155386638770824 correct 50  time/epoch 0.1780s
Epoch  460  loss  0.1564610300599438 correct 50  time/epoch 0.1434s
Epoch  470  loss  0.15163309475422063 correct 50  time/epoch 0.1932s
Epoch  480  loss  0.14705141765303958 correct 50  time/epoch 0.1625s
Epoch  490  loss  0.1426989896038799 correct 50  time/epoch 0.1393s
Epoch  500  loss  0.13856023412227883 correct 50  time/epoch 0.1537s

## Diag
Epoch  10  loss  10.302856720027696 correct 46  time/epoch 0.1742s
Epoch  20  loss  8.0472442372575 correct 46  time/epoch 0.1503s
Epoch  30  loss  6.200271114126988 correct 46  time/epoch 0.1966s
Epoch  40  loss  4.673220195469074 correct 48  time/epoch 0.1969s
Epoch  50  loss  3.6738004533371935 correct 49  time/epoch 0.1958s
Epoch  60  loss  3.0127229213507785 correct 49  time/epoch 0.1510s
Epoch  70  loss  2.557225066930167 correct 49  time/epoch 0.1896s
Epoch  80  loss  2.233213972055708 correct 49  time/epoch 0.1898s
Epoch  90  loss  1.996110920358825 correct 49  time/epoch 0.1746s
Epoch  100  loss  1.8166953750857566 correct 49  time/epoch 0.1510s
Epoch  110  loss  1.6756839051383936 correct 49  time/epoch 0.1393s
Epoch  120  loss  1.5623788102032599 correct 50  time/epoch 0.1902s
Epoch  130  loss  1.4688975019656902 correct 50  time/epoch 0.1955s
Epoch  140  loss  1.3902154728174816 correct 50  time/epoch 0.1975s
Epoch  150  loss  1.3229906093734476 correct 50  time/epoch 0.1528s
Epoch  160  loss  1.2646497092911702 correct 50  time/epoch 0.1603s
Epoch  170  loss  1.2136301588120175 correct 50  time/epoch 0.1482s
Epoch  180  loss  1.1700657297446728 correct 50  time/epoch 0.2001s
Epoch  190  loss  1.1314150054502479 correct 50  time/epoch 0.2052s
Epoch  200  loss  1.096255321081696 correct 50  time/epoch 0.1401s
Epoch  210  loss  1.0641116969570468 correct 50  time/epoch 0.1373s
Epoch  220  loss  1.0344562036775131 correct 50  time/epoch 0.1967s
Epoch  230  loss  1.006937392232715 correct 50  time/epoch 0.1841s
Epoch  240  loss  0.9812664746285793 correct 50  time/epoch 0.1706s
Epoch  250  loss  0.9571755582203747 correct 50  time/epoch 0.1451s
Epoch  260  loss  0.9344501522664632 correct 50  time/epoch 0.1610s
Epoch  270  loss  0.9129305632885909 correct 50  time/epoch 0.1825s
Epoch  280  loss  0.8924737457090599 correct 50  time/epoch 0.1429s
Epoch  290  loss  0.8729800647021468 correct 50  time/epoch 0.1510s
Epoch  300  loss  0.8543420966846798 correct 50  time/epoch 0.1964s
Epoch  310  loss  0.8364745903117061 correct 50  time/epoch 0.1979s
Epoch  320  loss  0.819307066162678 correct 50  time/epoch 0.1638s
Epoch  330  loss  0.8027863530471515 correct 50  time/epoch 0.1642s
Epoch  340  loss  0.7868501644136779 correct 50  time/epoch 0.1754s
Epoch  350  loss  0.7714495105389607 correct 50  time/epoch 0.1884s
Epoch  360  loss  0.7565430245361117 correct 50  time/epoch 0.2025s
Epoch  370  loss  0.7420942487824027 correct 50  time/epoch 0.1438s
Epoch  380  loss  0.7280709384167455 correct 50  time/epoch 0.1817s
Epoch  390  loss  0.7144444809191373 correct 50  time/epoch 0.1897s
Epoch  400  loss  0.7011894095312159 correct 50  time/epoch 0.1879s
Epoch  410  loss  0.6882829928814151 correct 50  time/epoch 0.1585s
Epoch  420  loss  0.6757048871424867 correct 50  time/epoch 0.1509s
Epoch  430  loss  0.6634368396758674 correct 50  time/epoch 0.2017s
Epoch  440  loss  0.6514653122901377 correct 50  time/epoch 0.1870s
Epoch  450  loss  0.639787043451168 correct 50  time/epoch 0.1752s
Epoch  460  loss  0.6283708993823856 correct 50  time/epoch 0.1376s
Epoch  470  loss  0.6172445762760662 correct 50  time/epoch 0.1885s
Epoch  480  loss  0.6064910981190318 correct 50  time/epoch 0.2061s
Epoch  490  loss  0.5959521579508162 correct 50  time/epoch 0.1999s
Epoch  500  loss  0.5856201201942628 correct 50  time/epoch 0.1491s

## Circle
Epoch  10  loss  31.565186203722906 correct 34  time/epoch 0.1552s
Epoch  20  loss  31.179149223673594 correct 34  time/epoch 0.1345s
Epoch  30  loss  30.820098559782224 correct 34  time/epoch 0.1967s
Epoch  40  loss  30.579519291121546 correct 34  time/epoch 0.1963s
Epoch  50  loss  30.345790883546815 correct 34  time/epoch 0.1958s
Epoch  60  loss  30.104886752083708 correct 34  time/epoch 0.1560s
Epoch  70  loss  29.840567284496146 correct 34  time/epoch 0.1843s
Epoch  80  loss  29.54720927362164 correct 34  time/epoch 0.2006s
Epoch  90  loss  29.23496234393731 correct 34  time/epoch 0.1516s
Epoch  100  loss  28.935541292725198 correct 34  time/epoch 0.1388s
Epoch  110  loss  28.630692115498146 correct 34  time/epoch 0.1343s
Epoch  120  loss  28.31521316859655 correct 34  time/epoch 0.1963s
Epoch  130  loss  28.03133479129014 correct 34  time/epoch 0.1886s
Epoch  140  loss  27.73857608522489 correct 34  time/epoch 0.2188s
Epoch  150  loss  27.40030578942862 correct 34  time/epoch 0.1345s
Epoch  160  loss  27.08108488330072 correct 34  time/epoch 0.1370s
Epoch  170  loss  26.785986509021683 correct 34  time/epoch 0.1856s
Epoch  180  loss  26.476595169420342 correct 34  time/epoch 0.1929s
Epoch  190  loss  26.113774531467094 correct 34  time/epoch 0.1469s
Epoch  200  loss  25.78607829593411 correct 34  time/epoch 0.1940s
Epoch  210  loss  25.391231806802594 correct 34  time/epoch 0.1878s
Epoch  220  loss  25.049876148354148 correct 34  time/epoch 0.1898s
Epoch  230  loss  24.58099088236507 correct 34  time/epoch 0.1893s
Epoch  240  loss  24.233503380902093 correct 34  time/epoch 0.1869s
Epoch  250  loss  23.881950875265712 correct 34  time/epoch 0.1547s
Epoch  260  loss  23.4453614356195 correct 36  time/epoch 0.1806s
Epoch  270  loss  23.099979389375402 correct 38  time/epoch 0.1574s
Epoch  280  loss  22.759154764352264 correct 37  time/epoch 0.1425s
Epoch  290  loss  22.452420825621925 correct 37  time/epoch 0.1619s
Epoch  300  loss  22.056759687073495 correct 38  time/epoch 0.1398s
Epoch  310  loss  21.632061919498828 correct 38  time/epoch 0.1861s
Epoch  320  loss  21.20235765821481 correct 38  time/epoch 0.1561s
Epoch  330  loss  20.761001165613624 correct 38  time/epoch 0.1565s
Epoch  340  loss  20.489827723896965 correct 39  time/epoch 0.1442s
Epoch  350  loss  20.180873921925976 correct 39  time/epoch 0.1893s
Epoch  360  loss  19.82109821606553 correct 39  time/epoch 0.1557s
Epoch  370  loss  19.456278025004504 correct 39  time/epoch 0.1411s
Epoch  380  loss  19.221575036139296 correct 40  time/epoch 0.1369s
Epoch  390  loss  18.805528354806892 correct 39  time/epoch 0.1422s
Epoch  400  loss  18.563202604626003 correct 40  time/epoch 0.1950s
Epoch  410  loss  18.08688277763429 correct 41  time/epoch 0.1756s
Epoch  420  loss  17.733334392174505 correct 41  time/epoch 0.1807s
Epoch  430  loss  18.630504163192374 correct 38  time/epoch 0.1503s
Epoch  440  loss  17.150102855378428 correct 40  time/epoch 0.1963s
Epoch  450  loss  15.335282244801272 correct 41  time/epoch 0.1867s
Epoch  460  loss  14.341347028259266 correct 43  time/epoch 0.1653s
Epoch  470  loss  13.571740115280498 correct 44  time/epoch 0.1443s
Epoch  480  loss  13.845135877869772 correct 44  time/epoch 0.1474s
Epoch  490  loss  12.232960691737631 correct 45  time/epoch 0.1973s
Epoch  500  loss  11.506613797569193 correct 46  time/epoch 0.2015s

## Spiral
Epoch  10  loss  34.12439914195035 correct 29  time/epoch 0.1986s
Epoch  20  loss  34.03929565437552 correct 29  time/epoch 0.1966s
Epoch  30  loss  33.95479686367036 correct 29  time/epoch 0.2017s
Epoch  40  loss  33.883183887278015 correct 29  time/epoch 0.1934s
Epoch  50  loss  33.82676929522586 correct 29  time/epoch 0.1896s
Epoch  60  loss  33.78397495022837 correct 29  time/epoch 0.1858s
Epoch  70  loss  33.75321089969158 correct 30  time/epoch 0.1755s
Epoch  80  loss  33.733285665931604 correct 30  time/epoch 0.1469s
Epoch  90  loss  33.72098209317253 correct 30  time/epoch 0.1521s
Epoch  100  loss  33.71145901156481 correct 29  time/epoch 0.1952s
Epoch  110  loss  33.70550019780929 correct 29  time/epoch 0.2035s
Epoch  120  loss  33.70079001882435 correct 29  time/epoch 0.1638s
Epoch  130  loss  33.697113050943955 correct 28  time/epoch 0.1443s
Epoch  140  loss  33.69375433714595 correct 28  time/epoch 0.1873s
Epoch  150  loss  33.690433892803334 correct 28  time/epoch 0.1579s
Epoch  160  loss  33.68712705967776 correct 28  time/epoch 0.1425s
Epoch  170  loss  33.683770976963714 correct 28  time/epoch 0.1361s
Epoch  180  loss  33.68023203247739 correct 28  time/epoch 0.1490s
Epoch  190  loss  33.67667156996816 correct 28  time/epoch 0.1997s
Epoch  200  loss  33.673156088590424 correct 28  time/epoch 0.1954s
Epoch  210  loss  33.669821184974886 correct 29  time/epoch 0.1658s
Epoch  220  loss  33.66649139120325 correct 29  time/epoch 0.1868s
Epoch  230  loss  33.662917924423155 correct 29  time/epoch 0.1950s
Epoch  240  loss  33.65932970997462 correct 29  time/epoch 0.1966s
Epoch  250  loss  33.65560756640404 correct 29  time/epoch 0.1449s
Epoch  260  loss  33.6517457574358 correct 29  time/epoch 0.1439s
Epoch  270  loss  33.64757549576146 correct 29  time/epoch 0.1855s
Epoch  280  loss  33.64364474124175 correct 29  time/epoch 0.1894s
Epoch  290  loss  33.63964644472122 correct 29  time/epoch 0.1972s
Epoch  300  loss  33.635044125671705 correct 29  time/epoch 0.1415s
Epoch  310  loss  33.63071388477643 correct 29  time/epoch 0.1417s
Epoch  320  loss  33.62585755409258 correct 29  time/epoch 0.1934s
Epoch  330  loss  33.62123368157937 correct 29  time/epoch 0.1921s
Epoch  340  loss  33.61603062196389 correct 30  time/epoch 0.1944s
Epoch  350  loss  33.611095672907965 correct 30  time/epoch 0.1529s
Epoch  360  loss  33.60592718600935 correct 30  time/epoch 0.1875s
Epoch  370  loss  33.60046594822174 correct 30  time/epoch 0.1517s
Epoch  380  loss  33.594859032658206 correct 30  time/epoch 0.1553s
Epoch  390  loss  33.588995706408866 correct 30  time/epoch 0.1877s
Epoch  400  loss  33.5827448327696 correct 30  time/epoch 0.1882s
Epoch  410  loss  33.5762532019393 correct 30  time/epoch 0.1625s
Epoch  420  loss  33.57029531942172 correct 30  time/epoch 0.1514s
Epoch  430  loss  33.563152024668014 correct 30  time/epoch 0.1980s
Epoch  440  loss  33.539419529187 correct 30  time/epoch 0.1970s
Epoch  450  loss  33.510473122255775 correct 29  time/epoch 0.1530s
Epoch  460  loss  33.49006972593137 correct 29  time/epoch 0.1962s
Epoch  470  loss  33.47373998959947 correct 29  time/epoch 0.1953s
Epoch  480  loss  33.45245826642381 correct 29  time/epoch 0.1634s
Epoch  490  loss  33.43227267498851 correct 29  time/epoch 0.1448s
Epoch  500  loss  33.41307242315701 correct 29  time/epoch 0.1830s

# 3.5
## Split
### CPU
Epoch  0  loss  6.191452629696352 correct 36  time/epoch 11.8765s
Epoch  10  loss  5.3861280486214325 correct 38  time/epoch 0.1540s
Epoch  20  loss  3.1280900559055147 correct 40  time/epoch 0.1984s
Epoch  30  loss  2.9304296765000104 correct 43  time/epoch 0.1545s
Epoch  40  loss  2.683659534734801 correct 46  time/epoch 0.1526s
Epoch  50  loss  2.236716614533773 correct 47  time/epoch 0.1514s
Epoch  60  loss  1.6572397643286971 correct 48  time/epoch 0.1499s
Epoch  70  loss  4.090730472774073 correct 42  time/epoch 0.1578s
Epoch  80  loss  3.0303513463885245 correct 45  time/epoch 0.1504s
Epoch  90  loss  1.8811993139890186 correct 48  time/epoch 0.1581s
Epoch  100  loss  1.3307831462673225 correct 48  time/epoch 0.1988s
Epoch  110  loss  2.713057958337076 correct 49  time/epoch 0.1625s
Epoch  120  loss  2.793691626634266 correct 48  time/epoch 0.1666s
Epoch  130  loss  0.9657052817818665 correct 48  time/epoch 0.1563s
Epoch  140  loss  2.364342083706039 correct 48  time/epoch 0.1684s
Epoch  150  loss  0.9668940057944595 correct 49  time/epoch 0.1626s
Epoch  160  loss  1.0970838633050586 correct 48  time/epoch 0.1619s
Epoch  170  loss  0.7396490062655384 correct 49  time/epoch 0.1497s
Epoch  180  loss  1.6678952881776832 correct 47  time/epoch 0.1949s
Epoch  190  loss  0.6023316520246135 correct 47  time/epoch 0.1760s
Epoch  200  loss  1.6286505639235511 correct 48  time/epoch 0.1507s
Epoch  210  loss  1.3330069427576943 correct 45  time/epoch 0.1619s
Epoch  220  loss  0.6643579312061 correct 50  time/epoch 0.1591s
Epoch  230  loss  0.41127729573381766 correct 49  time/epoch 0.1594s
Epoch  240  loss  0.9155397960483747 correct 48  time/epoch 0.1527s
Epoch  250  loss  1.4735387757885972 correct 48  time/epoch 0.1685s
Epoch  260  loss  0.4915870312410176 correct 50  time/epoch 0.1910s
Epoch  270  loss  1.0600053135189924 correct 45  time/epoch 0.1833s
Epoch  280  loss  2.9541763158622123 correct 45  time/epoch 0.1513s
Epoch  290  loss  0.3053363273311168 correct 50  time/epoch 0.1513s
Epoch  300  loss  0.43469645054861933 correct 49  time/epoch 0.1525s
Epoch  310  loss  0.6536023682759694 correct 49  time/epoch 0.1525s
Epoch  320  loss  0.10139733157657818 correct 49  time/epoch 0.1534s
Epoch  330  loss  0.49694548274846156 correct 50  time/epoch 0.1548s
Epoch  340  loss  0.610286544813474 correct 50  time/epoch 0.2106s
Epoch  350  loss  0.46332614693892665 correct 48  time/epoch 0.1510s
Epoch  360  loss  0.40000601648284867 correct 49  time/epoch 0.1508s
Epoch  370  loss  1.4058242141394386 correct 46  time/epoch 0.1560s
Epoch  380  loss  0.9051601845780314 correct 48  time/epoch 0.1504s
Epoch  390  loss  0.087726126633732 correct 49  time/epoch 0.1540s
Epoch  400  loss  0.8537460331575203 correct 50  time/epoch 0.1513s
Epoch  410  loss  0.09574594280708708 correct 50  time/epoch 0.1478s
Epoch  420  loss  0.009688061955070318 correct 50  time/epoch 0.1963s
Epoch  430  loss  0.2149266649222972 correct 48  time/epoch 0.1498s
Epoch  440  loss  0.3248939145289328 correct 50  time/epoch 0.1568s
Epoch  450  loss  0.021578313933258753 correct 50  time/epoch 0.1480s
Epoch  460  loss  0.3311412236256379 correct 49  time/epoch 0.1498s
Epoch  470  loss  0.045223792051689644 correct 50  time/epoch 0.1504s
Epoch  480  loss  2.715428186502709 correct 47  time/epoch 0.1492s
Epoch  490  loss  0.3462008122087764 correct 49  time/epoch 0.1505s
### GPU
Epoch  0  loss  7.008294925000246 correct 28  time/epoch 4.5087s
Epoch  10  loss  6.787605865393115 correct 38  time/epoch 1.4396s
Epoch  20  loss  5.4052757532333295 correct 42  time/epoch 1.8501s
Epoch  30  loss  6.129383787163302 correct 42  time/epoch 1.7001s
Epoch  40  loss  4.659374234062835 correct 43  time/epoch 1.2916s
Epoch  50  loss  4.284730537663202 correct 46  time/epoch 1.2505s
Epoch  60  loss  3.766697046715651 correct 45  time/epoch 1.2812s
Epoch  70  loss  5.2078801841352815 correct 38  time/epoch 1.2284s
Epoch  80  loss  2.4653098535700444 correct 49  time/epoch 1.2557s
Epoch  90  loss  2.458692059996065 correct 49  time/epoch 1.2388s
Epoch  100  loss  0.9860646448717766 correct 49  time/epoch 1.2607s
Epoch  110  loss  3.7884211737005073 correct 43  time/epoch 1.2333s
Epoch  120  loss  4.388877063215378 correct 41  time/epoch 1.2616s
Epoch  130  loss  1.5801466059768658 correct 48  time/epoch 1.2656s
Epoch  140  loss  2.3116491080597603 correct 49  time/epoch 1.7471s
Epoch  150  loss  2.1196395435938107 correct 49  time/epoch 1.8076s
Epoch  160  loss  0.49758872451785313 correct 49  time/epoch 1.8223s
Epoch  170  loss  0.44907481783169223 correct 49  time/epoch 1.3835s
Epoch  180  loss  0.8196397538881212 correct 48  time/epoch 1.2735s
Epoch  190  loss  2.6871311405187934 correct 46  time/epoch 1.2873s
Epoch  200  loss  0.4439580719817492 correct 48  time/epoch 1.3216s
Epoch  210  loss  0.9746118518189956 correct 48  time/epoch 1.2506s
Epoch  220  loss  1.4182382779045926 correct 49  time/epoch 1.2205s
Epoch  230  loss  0.2054101075825296 correct 49  time/epoch 1.2399s
Epoch  240  loss  2.160158198868813 correct 48  time/epoch 1.2621s
Epoch  250  loss  0.38926115960799423 correct 49  time/epoch 1.2815s
Epoch  260  loss  1.2065306097669937 correct 49  time/epoch 1.3509s
Epoch  270  loss  0.7213348820603541 correct 49  time/epoch 1.9151s
Epoch  280  loss  2.6552650026143962 correct 47  time/epoch 1.4227s
Epoch  290  loss  1.0569287645049004 correct 49  time/epoch 1.2552s
Epoch  300  loss  0.8328175015861895 correct 49  time/epoch 1.2752s
Epoch  310  loss  1.1449164237168319 correct 49  time/epoch 1.2815s
Epoch  320  loss  1.6643958608859097 correct 49  time/epoch 1.2553s
Epoch  330  loss  1.013419072721816 correct 50  time/epoch 1.2609s
Epoch  340  loss  0.9267438995033289 correct 48  time/epoch 1.2397s
Epoch  350  loss  0.9199868980005748 correct 50  time/epoch 1.2717s
Epoch  360  loss  0.20729533168398914 correct 49  time/epoch 1.2511s
Epoch  370  loss  1.3472371783302195 correct 49  time/epoch 1.4963s
Epoch  380  loss  0.9370157057264632 correct 49  time/epoch 1.8625s
Epoch  390  loss  0.3208085520655022 correct 50  time/epoch 1.6506s
Epoch  400  loss  0.1675228135819735 correct 46  time/epoch 1.2833s
Epoch  410  loss  1.1407921280199411 correct 49  time/epoch 1.2414s
Epoch  420  loss  0.1496502423838907 correct 49  time/epoch 1.2570s
Epoch  430  loss  1.6573114458370815 correct 47  time/epoch 1.2637s
Epoch  440  loss  2.056681898890667 correct 49  time/epoch 1.2935s
Epoch  450  loss  2.7583163253997425 correct 48  time/epoch 1.2507s
Epoch  460  loss  0.10996215397868404 correct 47  time/epoch 1.2848s
Epoch  470  loss  0.07432053984065194 correct 49  time/epoch 1.2878s
Epoch  480  loss  1.0711009133975529 correct 50  time/epoch 1.3116s
Epoch  490  loss  0.366896310522684 correct 50  time/epoch 1.2882s
## Simple
### CPU
Epoch  0  loss  4.254983574487291 correct 44  time/epoch 10.2292s
Epoch  10  loss  0.9917067760371571 correct 50  time/epoch 0.1384s
Epoch  20  loss  0.6649264031013403 correct 50  time/epoch 0.1333s
Epoch  30  loss  0.8508371229323203 correct 50  time/epoch 0.1361s
Epoch  40  loss  0.11678608513558979 correct 50  time/epoch 0.1665s
Epoch  50  loss  0.2914586652271779 correct 50  time/epoch 0.1628s
Epoch  60  loss  0.29165551352047814 correct 50  time/epoch 0.1350s
Epoch  70  loss  0.1700992392245205 correct 50  time/epoch 0.1399s
Epoch  80  loss  0.07468299573618321 correct 50  time/epoch 0.1342s
Epoch  90  loss  0.04845006214865642 correct 50  time/epoch 0.1319s
Epoch  100  loss  0.16183084296091738 correct 50  time/epoch 0.1451s
Epoch  110  loss  0.16187472929332453 correct 50  time/epoch 0.1336s
Epoch  120  loss  0.06349093543527272 correct 50  time/epoch 0.1312s
Epoch  130  loss  0.04823723082651852 correct 50  time/epoch 0.1639s
Epoch  140  loss  0.022963825117819716 correct 50  time/epoch 0.1710s
Epoch  150  loss  0.010826977511234707 correct 50  time/epoch 0.1341s
Epoch  160  loss  0.18772257265250197 correct 50  time/epoch 0.1333s
Epoch  170  loss  0.11420754862288018 correct 50  time/epoch 0.1301s
Epoch  180  loss  0.10393227099647294 correct 50  time/epoch 0.1319s
Epoch  190  loss  0.02192408313567616 correct 50  time/epoch 0.1622s
Epoch  200  loss  0.01013810991887745 correct 50  time/epoch 0.1307s
Epoch  210  loss  0.07148568992446681 correct 50  time/epoch 0.1300s
Epoch  220  loss  0.09464977327085132 correct 50  time/epoch 0.1709s
Epoch  230  loss  0.007589747151095524 correct 50  time/epoch 0.1625s
Epoch  240  loss  0.13311224170666403 correct 50  time/epoch 0.1432s
Epoch  250  loss  0.1362033014512737 correct 50  time/epoch 0.1321s
Epoch  260  loss  0.0051054313198007125 correct 50  time/epoch 0.1326s
Epoch  270  loss  0.07671065626122257 correct 50  time/epoch 0.1329s
Epoch  280  loss  0.060638633248812336 correct 50  time/epoch 0.1316s
Epoch  290  loss  0.01025001940448339 correct 50  time/epoch 0.1342s
Epoch  300  loss  0.015171003614164097 correct 50  time/epoch 0.1385s
Epoch  310  loss  0.09463414935565567 correct 50  time/epoch 0.1605s
Epoch  320  loss  0.05667249059246192 correct 50  time/epoch 0.1721s
Epoch  330  loss  0.05483508306830016 correct 50  time/epoch 0.1358s
Epoch  340  loss  0.017529923178913283 correct 50  time/epoch 0.1358s
Epoch  350  loss  0.08168844899718265 correct 50  time/epoch 0.1421s
Epoch  360  loss  0.009393196030830579 correct 50  time/epoch 0.1335s
Epoch  370  loss  0.0017286398220769494 correct 50  time/epoch 0.1473s
Epoch  380  loss  0.03732249033985099 correct 50  time/epoch 0.1410s
Epoch  390  loss  0.03596721082483075 correct 50  time/epoch 0.1356s
Epoch  400  loss  0.08786976535798077 correct 50  time/epoch 0.1553s
Epoch  410  loss  0.0025047819379270687 correct 50  time/epoch 0.1561s
Epoch  420  loss  0.003437360062227477 correct 50  time/epoch 0.1381s
Epoch  430  loss  0.07111587058596987 correct 50  time/epoch 0.1399s
Epoch  440  loss  0.03900671447843008 correct 50  time/epoch 0.1340s
Epoch  450  loss  0.045590223316084186 correct 50  time/epoch 0.1323s
Epoch  460  loss  0.030778293119685537 correct 50  time/epoch 0.1299s
Epoch  470  loss  0.00901171124381398 correct 50  time/epoch 0.1310s
Epoch  480  loss  0.030260251483918327 correct 50  time/epoch 0.1311s
Epoch  490  loss  0.001177575545641689 correct 50  time/epoch 0.1593s
### GPU
Epoch  0  loss  5.408035248252185 correct 33  time/epoch 4.2733s
Epoch  10  loss  2.509417672095368 correct 47  time/epoch 1.3198s
Epoch  20  loss  1.1829656722562714 correct 48  time/epoch 1.2453s
Epoch  30  loss  1.0941526973075009 correct 48  time/epoch 1.4829s
Epoch  40  loss  0.9028638843665739 correct 47  time/epoch 1.8987s
Epoch  50  loss  2.519696640933296 correct 49  time/epoch 1.6745s
Epoch  60  loss  0.666810220208248 correct 49  time/epoch 1.4479s
Epoch  70  loss  0.43791304653442487 correct 48  time/epoch 1.3017s
Epoch  80  loss  0.06828266572432665 correct 49  time/epoch 1.2187s
Epoch  90  loss  0.7390758164626445 correct 48  time/epoch 1.1984s
Epoch  100  loss  1.8812503460244738 correct 49  time/epoch 1.2038s
Epoch  110  loss  0.2523827625268157 correct 49  time/epoch 1.2004s
Epoch  120  loss  1.4036467765218033 correct 49  time/epoch 1.1907s
Epoch  130  loss  0.6524136726395238 correct 49  time/epoch 1.2010s
Epoch  140  loss  0.04029371677903062 correct 49  time/epoch 1.1879s
Epoch  150  loss  0.9418616984956707 correct 50  time/epoch 1.2036s
Epoch  160  loss  0.8733063379516125 correct 49  time/epoch 1.2132s
Epoch  170  loss  0.8983205693927425 correct 49  time/epoch 1.2120s
Epoch  180  loss  0.8863211591386186 correct 48  time/epoch 1.1949s
Epoch  190  loss  0.9552759776915494 correct 48  time/epoch 1.2897s
Epoch  200  loss  0.029620015587187496 correct 48  time/epoch 1.2962s
Epoch  210  loss  1.0972122562301245 correct 49  time/epoch 1.2385s
Epoch  220  loss  1.057562839902198 correct 48  time/epoch 1.2087s
Epoch  230  loss  0.6116174310521431 correct 50  time/epoch 1.2002s
Epoch  240  loss  0.5447864526652997 correct 50  time/epoch 1.2068s
Epoch  250  loss  0.7100163440517279 correct 50  time/epoch 1.2053s
Epoch  260  loss  0.08234481601863453 correct 50  time/epoch 1.2413s
Epoch  270  loss  0.0226248023055688 correct 50  time/epoch 1.5064s
Epoch  280  loss  1.520259975467885 correct 48  time/epoch 1.6134s
Epoch  290  loss  0.5537909519978206 correct 50  time/epoch 1.7684s
Epoch  300  loss  0.06160940283076394 correct 50  time/epoch 1.7245s
Epoch  310  loss  0.4347679491691838 correct 50  time/epoch 1.5205s
Epoch  320  loss  0.3737733663869953 correct 48  time/epoch 1.2173s
Epoch  330  loss  0.3277907342028984 correct 48  time/epoch 1.2249s
Epoch  340  loss  1.2320428861148027 correct 48  time/epoch 1.2277s
Epoch  350  loss  1.3485437894973802 correct 49  time/epoch 1.2115s
Epoch  360  loss  0.06862582812029124 correct 48  time/epoch 1.2144s
Epoch  370  loss  0.035587109678340646 correct 49  time/epoch 1.2210s
Epoch  380  loss  0.08023784281947086 correct 48  time/epoch 1.2251s
Epoch  390  loss  0.40663493976945664 correct 49  time/epoch 1.2070s
Epoch  400  loss  1.5710529393011368 correct 48  time/epoch 1.2098s
Epoch  410  loss  0.017331424927337927 correct 50  time/epoch 1.2183s
Epoch  420  loss  0.7177492991665415 correct 49  time/epoch 1.2172s
Epoch  430  loss  0.9259538600239486 correct 50  time/epoch 1.2143s
Epoch  440  loss  0.49484682040676325 correct 50  time/epoch 1.2366s
Epoch  450  loss  0.0056135320680869615 correct 49  time/epoch 1.2154s
Epoch  460  loss  0.6665450235846213 correct 50  time/epoch 1.2276s
Epoch  470  loss  0.0035081633362975123 correct 49  time/epoch 1.2077s
Epoch  480  loss  0.7373222214800891 correct 50  time/epoch 1.2117s
Epoch  490  loss  0.055981511861829675 correct 49  time/epoch 1.4940s
## Xor
### CPU
Epoch  0  loss  5.632198311577527 correct 28  time/epoch 11.6261s
Epoch  10  loss  5.577337465623728 correct 45  time/epoch 0.1510s
Epoch  20  loss  3.9377463036475655 correct 45  time/epoch 0.1590s
Epoch  30  loss  4.451347123032196 correct 44  time/epoch 0.1647s
Epoch  40  loss  3.85193207499115 correct 47  time/epoch 0.1530s
Epoch  50  loss  4.843737664716958 correct 46  time/epoch 0.1500s
Epoch  60  loss  2.657792559018892 correct 46  time/epoch 0.2014s
Epoch  70  loss  3.0259944723908125 correct 45  time/epoch 0.1523s
Epoch  80  loss  2.756155667629834 correct 47  time/epoch 0.1587s
Epoch  90  loss  0.9294146521394904 correct 48  time/epoch 0.1521s
Epoch  100  loss  1.3678170516882782 correct 47  time/epoch 0.1659s
Epoch  110  loss  0.5476422311680175 correct 48  time/epoch 0.1507s
Epoch  120  loss  2.1587702125550394 correct 47  time/epoch 0.1625s
Epoch  130  loss  0.6367703050397259 correct 47  time/epoch 0.1516s
Epoch  140  loss  2.1646033848991904 correct 49  time/epoch 0.2021s
Epoch  150  loss  1.4772835985525248 correct 46  time/epoch 0.1616s
Epoch  160  loss  2.0874785768704305 correct 47  time/epoch 0.1513s
Epoch  170  loss  1.0446328317124556 correct 49  time/epoch 0.1607s
Epoch  180  loss  1.4734369668242804 correct 48  time/epoch 0.1528s
Epoch  190  loss  0.8024262869369049 correct 49  time/epoch 0.1619s
Epoch  200  loss  1.4239587583959754 correct 49  time/epoch 0.1602s
Epoch  210  loss  1.40598500522831 correct 49  time/epoch 0.1633s
Epoch  220  loss  1.5159858961289723 correct 49  time/epoch 0.2000s
Epoch  230  loss  0.5005647581788272 correct 49  time/epoch 0.1499s
Epoch  240  loss  1.2158297353463525 correct 50  time/epoch 0.1613s
Epoch  250  loss  1.4575837421932842 correct 49  time/epoch 0.1534s
Epoch  260  loss  0.2645149100017482 correct 50  time/epoch 0.1589s
Epoch  270  loss  0.429964706586727 correct 50  time/epoch 0.1550s
Epoch  280  loss  1.2520162835159039 correct 48  time/epoch 0.1510s
Epoch  290  loss  0.40939901449290933 correct 50  time/epoch 0.1539s
Epoch  300  loss  1.7769663690344923 correct 50  time/epoch 0.1985s
Epoch  310  loss  0.5130492992480468 correct 49  time/epoch 0.1617s
Epoch  320  loss  0.29464914440777246 correct 50  time/epoch 0.1614s
Epoch  330  loss  0.4298838004011164 correct 50  time/epoch 0.1512s
Epoch  340  loss  1.015602021301686 correct 50  time/epoch 0.1540s
Epoch  350  loss  0.21620210781216978 correct 50  time/epoch 0.1619s
Epoch  360  loss  0.37141727106773786 correct 50  time/epoch 0.1602s
Epoch  370  loss  1.3705521003890988 correct 50  time/epoch 0.1765s
Epoch  380  loss  1.0530149795379278 correct 50  time/epoch 0.2011s
Epoch  390  loss  1.3400486154811337 correct 50  time/epoch 0.1650s
Epoch  400  loss  0.7915629481914983 correct 49  time/epoch 0.1524s
Epoch  410  loss  0.24883140344785393 correct 50  time/epoch 0.1638s
Epoch  420  loss  0.9430648651953928 correct 50  time/epoch 0.1562s
Epoch  430  loss  1.0367686072853126 correct 50  time/epoch 0.1631s
Epoch  440  loss  0.5361052702274323 correct 50  time/epoch 0.1535s
Epoch  450  loss  0.7804415894698769 correct 50  time/epoch 0.2046s
Epoch  460  loss  0.036920653950503805 correct 50  time/epoch 0.2107s
Epoch  470  loss  1.253694463189519 correct 50  time/epoch 0.1524s
Epoch  480  loss  0.5147624753725196 correct 50  time/epoch 0.1516s
Epoch  490  loss  0.3673221417126996 correct 50  time/epoch 0.1526s
### GPU
Epoch  0  loss  7.99053571030123 correct 26  time/epoch 4.4140s
Epoch  10  loss  5.958247407694234 correct 37  time/epoch 1.1774s
Epoch  20  loss  6.065593642465989 correct 39  time/epoch 1.2109s
Epoch  30  loss  5.679386388649455 correct 40  time/epoch 1.2265s
Epoch  40  loss  3.2465173459747785 correct 44  time/epoch 1.3049s
Epoch  50  loss  3.8814131700921526 correct 46  time/epoch 1.2352s
Epoch  60  loss  3.0774158919146295 correct 45  time/epoch 1.1953s
Epoch  70  loss  3.3017119661304544 correct 46  time/epoch 1.2020s
Epoch  80  loss  2.584481128559376 correct 47  time/epoch 1.2122s
Epoch  90  loss  2.2197569023704387 correct 45  time/epoch 1.2944s
Epoch  100  loss  2.1800547350046906 correct 47  time/epoch 1.3019s
Epoch  110  loss  1.9242236801716628 correct 47  time/epoch 1.2566s
Epoch  120  loss  1.0454736430074147 correct 49  time/epoch 1.2267s
Epoch  130  loss  2.577260601274203 correct 48  time/epoch 1.2295s
Epoch  140  loss  1.3769526069659381 correct 49  time/epoch 1.2087s
Epoch  150  loss  0.9851188884832158 correct 48  time/epoch 1.2124s
Epoch  160  loss  2.3115747674697236 correct 48  time/epoch 1.2638s
Epoch  170  loss  1.3578640388594128 correct 49  time/epoch 1.4861s
Epoch  180  loss  0.7406450591596503 correct 50  time/epoch 1.7681s
Epoch  190  loss  1.5771742483077633 correct 50  time/epoch 1.7515s
Epoch  200  loss  1.0751822687392303 correct 49  time/epoch 1.6032s
Epoch  210  loss  0.3237001886084511 correct 50  time/epoch 1.3013s
Epoch  220  loss  0.834696762538115 correct 50  time/epoch 1.2033s
Epoch  230  loss  1.349109330389667 correct 48  time/epoch 1.2125s
Epoch  240  loss  0.8927578757230705 correct 50  time/epoch 1.2045s
Epoch  250  loss  2.1700002918425048 correct 50  time/epoch 1.2597s
Epoch  260  loss  0.9049979491532313 correct 50  time/epoch 1.1982s
Epoch  270  loss  0.3292748595895108 correct 50  time/epoch 1.2061s
Epoch  280  loss  0.5027334050384052 correct 50  time/epoch 1.2127s
Epoch  290  loss  0.5700314803700363 correct 50  time/epoch 1.3197s
Epoch  300  loss  0.7937924440081189 correct 50  time/epoch 1.2235s
Epoch  310  loss  0.7048681000571875 correct 50  time/epoch 1.1847s
Epoch  320  loss  0.15490602681411234 correct 50  time/epoch 1.2160s
Epoch  330  loss  1.1299286500494123 correct 50  time/epoch 1.2008s
Epoch  340  loss  0.5536286891836519 correct 49  time/epoch 1.2217s
Epoch  350  loss  0.26909291485284004 correct 50  time/epoch 1.2365s
Epoch  360  loss  0.2016917311232677 correct 50  time/epoch 1.2341s
Epoch  370  loss  1.213824117662587 correct 50  time/epoch 1.2092s
Epoch  380  loss  1.823112586371997 correct 49  time/epoch 1.3836s
Epoch  390  loss  2.0898395644357977 correct 50  time/epoch 1.5361s
Epoch  400  loss  0.450256519934089 correct 50  time/epoch 1.7223s
Epoch  410  loss  0.9996348605812796 correct 50  time/epoch 1.8008s
Epoch  420  loss  0.39086753000432306 correct 50  time/epoch 1.6589s
Epoch  430  loss  0.5053060159608025 correct 50  time/epoch 1.5050s
Epoch  440  loss  0.5152186887967279 correct 50  time/epoch 1.2318s
Epoch  450  loss  0.2667577626875104 correct 50  time/epoch 1.2724s
Epoch  460  loss  0.37690710158880236 correct 50  time/epoch 1.1972s
Epoch  470  loss  0.3361868548654978 correct 50  time/epoch 1.1975s
Epoch  480  loss  0.8755478338184659 correct 50  time/epoch 1.1898s
Epoch  490  loss  0.983752875023729 correct 50  time/epoch 1.1970s