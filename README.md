# RAK831-LoRaGateway-RPi
ttn_gateway based on the latest SX1301 driver [lora_gateway](https://github.com/Lora-net/lora_gateway) v5.0.1 and semtech [packet_forwarder](https://github.com/Lora-net/packet_forwarder) v4.0.1  


##	Installation procedure

step1 : Download and install [Raspbian Stretch LITE](https://www.raspberrypi.org/downloads/raspbian/) 


step2 : Clone the installer and start the installation

      $ git clone https://github.com/RAKWireless/RAK831-LoRaGateway-RPi.git ~/rak831-loragateway
      $ cd ~/rak831-loragateway
      $ sudo ./install.sh

step3 : Next you will see some messages as follow. Just hit the Enter key to keep default or enter your information if you want.

      Host name [ttn-gateway]:
      Descriptive name [ttn-rak831]:
      Latitude [0]: 
      Longitude [0]: 
      Altitude [0]: 

step4 : Runing the gateway after the rpi restarted automatically. 
    
      $ cd ~/rak831-loragateway/packet_forwarder/lora_pkt_fwd/
      $ sudo ./start.sh
      
Now your gateway should working!
