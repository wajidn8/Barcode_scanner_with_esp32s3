# Barcode_scanner_with_esp32s3
barcode scanner using esp32s3 and printing it in serial monitor (esp idf framework)


steps to compile and flash:
s1:open esp idf
s2:select target board (esp32s3)
s3:create project 
s4:build the project
s5:flash to esp32s3
s6:monitor 

o/p: gives the barcode decode o/p

esp32 s3:
gpio 19,20 connected to d+,d- of barcode scanner
vcc,gnd of barcode scanner is connected to external 5v supply

esp32s3 is connected to pc/lap.
