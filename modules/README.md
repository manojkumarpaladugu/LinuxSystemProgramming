<h1>Load kernel module</h1>
sudo insmod Hello.ko  
<h1>Check status of kernel module</h1>
sudo lsmod | grep Hello  
<h1>Check info of kernel module</h1>
sudo modinfo Hello.ko
<h1>Unload kernel module</h1>
sudo rmmod Hello  
