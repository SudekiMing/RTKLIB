# RTKLIB
RTKLIB开源库有着强大的GPS数据实时和后处理功能，由于笔者的毕业设计中需要对GPS载波相位观测量进行RTK解算，故而，对RTKLIB开源库进行了学习与研究。  RTKLIB提供了很多底层的函数，笔者准备直接对源码进行编译输出标准DLL的方式供C#调用。所用的VS平台是VS2012（其它VS版本类似），RTKLIB库用的是网上使用的最多，相对稳定的rtklib_2.4.2版本，编译的项目采用“相对路径”，即工程可移植到任何地方，方便以后使用。
RTKLIB简介（rtklib_2.4.2版本）
RTKLIB是全球导航卫星系统GNSS(global navigation satellite system)的标准&精密定位开源程序包，RTKLIB由日本东京海洋大学（Tokyo Universityof Marine Science and Technology）的高须知二（Tomoji Takasu）开发。RTKLIB由一个便携式程序库和多个AP（应用程序）工具库组成。

RTKLIB的主要功能有：

（1）支持多个GNSS系统的标准和精密定位算法，包括GPS，GLONASS，Beidou，Galileo，QZSS和SBAS

（2）支持多种GNSS实时和后处理定位模式：单点定位、DGPS/DGNSS,动态RTK、静态RTK、移动基站、PPP

（3）支持多种GNSS标准格式和协议：RINEX2.10、RINEX2.11、RINEX2.12、RINEX3.00、RINEX3.01、RINEX3.02、RTCM2.3、RTCM3.1、RTCM3.2、BINEX、NTRIP、NMEA0183、SP3、ANTEX1.4、IONEX1.0、NGS PCV、EMS 2.0

（4）支持多种GNSS接收机专有数据协议格式：NovAtel:OEM4/V/6，OEM3, OEMStar、Superstar II、 Hemisphere、Crescent、u‐blox:LEA-4T/5T/6T、SkyTraq、JAVAD 、GW10-II/III和NVS

（5）支持外部通信：Serial、TCP/IP、NTRIP、本地日志文件(记录和播发)和FTP/HTTP

（6）提供许多函数库和API（application program interfaces）：卫星和导航系统函数、矩阵和向量函数，时间和字符串函数、坐标的转换，输入和输出函数、调试跟踪函数、平台依赖函数、定位模型、大气模型、天线模型、地球潮汐模型、大地水准面模型、基准转换、RINEX函数、星历和时钟函数、精密星历和时钟、接收机原始数据函数、RTCM函数，解算函数、谷歌地球KML转换、SBAS函数、选项（option）函数、流数据输入和输出函数、整周模糊度解算、标准定位、精密定位、后处理定位（解算）、流服务器函数、RTK服务器函数、下载函数。
--------------------- 
作者：SudekiMing 
来源：CSDN 
原文：https://blog.csdn.net/WalterBrien/article/details/80754215 
版权声明：本文为博主原创文章，转载请附上博文链接！
