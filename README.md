# mbed exam1
setup:
![](https://i.imgur.com/TWMlw0W.jpg)

compile main.cpp:
sudo mbed compile --source . --source ~/ee2405/mbed-os-build/ -m B_L4S5I_IOT01A -t GCC_ARM -f

compile FFT.py:
sudo python3 FFT.py

results:

select 1, measured by picoscope
![](https://i.imgur.com/0gRYMrB.png)
select 1/2, measured by picoscope
![](https://i.imgur.com/z0Wy0Jg.png)
select 1/4, measured by picoscope
![](https://i.imgur.com/m11WX4P.png)
select 1/8, measured by picoscope
![](https://i.imgur.com/6djqDne.png)

select 1 and do fourier transform
![](https://i.imgur.com/7UbjwIg.png)
select 1/2 and do fourier transform
![](https://i.imgur.com/vW53lrA.png)
select 1/4 and do fourier transform
![](https://i.imgur.com/g3pjyry.png)
select 1/8 and do fourier transform
![](https://i.imgur.com/epLaER8.png)

