# 耳机模拟立体声音箱算法
通过模拟立体声音箱串扰、模拟房间反射声实现固定角度的模拟立体声音箱效果，用于优化耳机的空间印象

用法：  
1、安装Equalizer APO  
2、将2个txt文件复制到：根目录\EqualizerAPO\config，并且使用Equalizer APO加载  
3、使用Equalizer APO加载混响插件，并按图设置参数  
注意事项：  
1、注意旧文件备份，注意旧文件备份，注意旧文件备份。  
2、你可以用include功能手动加载“模拟音箱串扰.txt”、“模拟房间反射.txt”两个文件，也可以将下面3行参数复制粘贴到Equalizer APO主界面  
Preamp: 0.6 dB  
Include: 模拟音箱串扰.txt  
Include: 模拟房间反射.txt  
3、32位系统可直接用Equalizer APO加载“顶级混响D.dll”，如果是64位系统，则需要通过jBridge进行桥接。方法：①安装jBridge；②将“顶级混响D.64.dll”和“顶级混响D.dll”放在同一个文件夹内；③用Equalizer APO加载“顶级混响D.64.dll”；④按图设置参数  
4、检查Equalizer APO是否正常运作，如果加载参数之后声音没有任何变化，大致有以下几种原因：  
①、大概率是声卡驱动问题，卸载声卡驱动让它自动按装初始版本，或者手动安装早期版本驱动  
②、设备属性里需要勾选“启用音频增强”  
③、apo里需要选择对应的输出设备  
④、播放器的输出模式选择directsound（ds），不能选asio或者wasapi  
