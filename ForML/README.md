# For Michael Lang 
 
To allow v0.9e to work with the RPi 3b+ you need to copy 2 files into /opt/picochess/etc
  
Log onto your RPi with a console and enter these commands:

cd  
sudo git clone https://github.com/ScallyBag/AlsPicoEngines  
cd AlsPicoEngines/ForMLang  
sudo cp dgt* -r /opt/picochess/etc  
cd  
sudo rm -rf AlsPicoEngines  
 
  
Al
