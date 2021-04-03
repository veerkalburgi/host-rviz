# host-rviz
## To use Rviz visulization tool in host pc.
---


   1. Go to hosts directory and open it.
   
   > _sudo vi /etc/hosts_
   
   2. In the hosts file add the clinet IP address.
   > _192.168.1.174_ #clinet jetson board or intel nuc board IP address.
   
   3. Go to .bashrc and add the clinet ROS and host IP.
   
   > _vi ~/.bashrc_
   
   > _export ROS_MASTER_URI=http://192.168.1.174:11311/_
   
   > export ROS_IP=192.168.1.208
   
   4. update the .bashrc file
   
   > _source ~/.bashrc_
   
   5. Check the ROSMASTER_URI and ROS_IP
    
   > _echo $ROS_MASTER_URI_
   
   > _echo $ROS_IP_
   
   ---
   
   ### Now it's ready, enjoy it ;)
