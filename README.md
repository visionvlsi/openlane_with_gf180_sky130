# openlane_with_gf180_sky130

# To install gf180 with openlane follow the below steps:
<ol>
git clone https://github.com/The-OpenROAD-Project/OpenLane.git
cd OpenLane
export PDK_FAMILY=gf180mcu
export PDK=gf180mcuC
make
make test
</ol><br/>

# To install sky130 with openlane follow the below steps:
<ol>
git clone https://github.com/The-OpenROAD-Project/OpenLane.git
cd OpenLane
make
make test
</ol><br/>
# To install gf180 and sky130 together with openlane follow the below steps:

First step do the following:<br/>
<ol>
git clone https://github.com/The-OpenROAD-Project/OpenLane.git
cd OpenLane
export PDK_FAMILY=gf180mcu
export PDK=gf180mcuC
make
make test
</ol><br/>
Second step do the following:
<ol>
exit
cd OpenLane
make
make test
</ol>
