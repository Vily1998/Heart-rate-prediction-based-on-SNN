# Heart-rate-prediction-based-on-SNN

## 源代码存放于`/src`

`spike_encoder.py`实现脉冲编码器功能，编译调试环境为python。

`liquid_machine.cpp`实现液态机功能，模拟人脑神经元处理信息过程，编译运行环境为C++、carlsim。

`predict_heart_rate.py`实现心率解码的各部分子模块连接，编译调试环境为python。

`monte_carlo.py`为蒙特卡罗优化算法模块，编译调试环境为python。

`accuracy_estimation.py`、`predict_heart_rate.py`和`read_actual_heart_rate.py`依次为误差率计算模块、心率预测模块、真实数据读取模块，编译调试环境为python。
