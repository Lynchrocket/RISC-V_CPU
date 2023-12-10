# RISC-V_CPU
一个简单的单周期RISC-V CPU设计，支持RV32I指令集的几乎全部指令，有小小的瑕疵。未来可能会增加流水线和冒险优化，以及增加更多的指令支持。

感谢 @Shennoter 的帮助，他为本项目提供了仿真测试，并协助修改了许多CPU设计上的bug。

本项目使用 Jupiter 或者 [venus](http://venus.cs61c.org/) 将RISC-V汇编源码转成十六进制码。
