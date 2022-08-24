# Struct_dq

结构体对齐说明：

1.对齐系数，#pragma pack(n) ,n改变系数

2.有效对齐值：给定值和结构体中最长数据类型长度中的较小的那个是 对齐单位

3.结构体中第一个成员的偏移量为0，以后每个成员的offset都是成员大小与对齐单位中较小那个的整数倍

4.结构体的总大小为有效对齐的整数倍，如果有需要在最末一个成员之后加上填充字节
