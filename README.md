# matlab-study
数字信号处理 
1.离散卷积的计算
x=[3,11,7,0,-1,4,2];
y=[2,3,0,-5,2,1];
z=conv(x,y);
subplot(2,2,1);//将图像进行分割
stem(x);//绘制火柴图
subplot(2,2,2);
stem(y);
subplot(2,2,3);
stem(z);
disp(z);//输出序列
2.
