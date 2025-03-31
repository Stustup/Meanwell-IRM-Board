# Meanwell IRM 20/30 Board

Simple board to quickly use the great Meanwell AC/DC power supply modules either in parallel or serien for a simple bipolar power supply. 

![3D  Viel from the side of the meanwell board](./Hardware/doc/Meanwell%20IRM%20Board%20Side.png)

You can connect your project to the JST EH connectors or solder wires directly to the board. The footprint for the IRM Board is a combination of 
20W and 30W modules, so you can use both. For example, you could use two 48V PSUs for a 96V power supply to power low voltage tube amps, or use 
two IRM-20-15 in series with GND connected to the "Voltage Conenct" header to get a great, simple and cheap biplar power supply for headphone 
amps and such.

![Top view of the meanwell board](./Hardware/doc/Meanwell%20IRM%20Board%20Top.png)

## Caution!

Always use an offboard switch and fuse in combination with these boards. There are many combined plug/switch/fuse boards like 
[these](https://www.mouser.de/ProductDetail/Qualtek/764-00-002?qs=uN5Dye%252BOwiXfVfVI0dfkHA%3D%3D) (there are always cheaper ones).

## TODO

- Place the AC connectors a little bit more intelligently. Now they almost touch the irm modules
- Place a shared 3 pin connector for directly accessing the bipolar psu
- power LEDs
- Power switch (maybe with relays and an optional bypass header)