1.对.zip文件的ＩＯ操作，ｚｌｉｂ函数库的IO操作。

    （zlib是一种函数库，用来压缩和解压缩用的）

 

      lines file(s)
      4299 code/qcommon/unzip.c
        4546 libs/pak/unzip.cpp

2.MD4消息加密算法：

 

      lines file(s)
         299  code/qcommon/md4.c
        277  common/md4.c

3.标准c库的代替:

       hecksums are used to validate pak files

        standard C library replacement routines
         -----------------------------------------------------------------------------
         l ines file(s)
        1324 code/game/bg_lib.c

4.ADPCM 编码和解码：

        -----------------------------------------------------------------------------
         lines file(s)
        330  code/client/snd_adpcm.c
          Copyright 1992 by Stichting Mathematisch Centrum, Amsterdam, The
         Netherlands.

 

5.JPEG library
-----------------------------------------------------------------------------
code/jpeg-6
libs/jpeg6
Copyright (C) 1991-1995, Thomas G. Lane

 

6.大体说明

 

GENERAL NOTES
=============

A short summary of the file layout:

code/        Quake III Arena source code ( renderer, game code, OS layer etc. )
code/bspc    机器人算法的源代码

lcc/    c编译器的重定向 produces assembly to be turned into qvm bytecode by q3asm
q3asm/     assembly to qvm bytecode compiler
q3map/   地图编译器  map compiler ( .map -> .bsp ) - this is the version that comes with Q3Radiant 200f
q3radiant/    Q3Radiant map editor build 200f ( common/ and libs/ are support dirs for radiant )

q3辐射地图编辑器
————————————————
版权声明：本文为CSDN博主「daojin505」的原创文章，遵循CC 4.0 BY-SA版权协议，转载请附上原文出处链接及本声明。
原文链接：https://blog.csdn.net/daojin505/article/details/76807358