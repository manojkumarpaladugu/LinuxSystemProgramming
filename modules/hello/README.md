<h1>Load kernel module</h1>
sudo insmod hello.ko  
<h1>Check status of kernel module</h1>
sudo lsmod | grep hello  
<h1>Check info of kernel module</h1>
sudo modinfo hello.ko
<h1>Unload kernel module</h1>
sudo rmmod hello  
