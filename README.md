# DaikinCon
Daikin Online/Mobile Controller Wire Harness

Daikin Online Controller (Europe) or Daikin Mobile Controller (Asia) uses to add WiFi interface to Daikin devices. It helps to bridge Daikin devices to home automation system. Some Daikin devices have pre-installed wire harness to directly plug a controller in but some devices need wire harness or extra interface adapter to connect with. So a controller has different models depends on including wire harness and interface adapter.

BRP069A41 -> Controller Only

BRP069A42/BRP069A43/BRP069A44/BRP069A45/BRP069A81 -> BRP069A41 controller with differenct wire harness and interface adapter.

*Also applied to BRP069B41 (Europe), BRP072A42/BRP072B42/BRP072C42 (Asia)

![BRP072A42](https://i1.wp.com/www.penair.com.au/wp-content/uploads/2018/06/IMG_20150130_093631-e1432621757523.jpg)

It is possible to build wire harness in case that some controller models are not available in your country or if you want to swap controller between different Daikin devices. Also, BRPxxxx41 controller only model price is about of half of other models.

## 42 Model
For Daikin wall type devices that have S21 socket on control board but not have pre-installed wire harness.

## 81 Model
For Daikin Sky Air cassette type, duct type, floor standing type devices. It uses X50 socket on control board.

Original A81 wire harness
![original_a81_wire_harness](https://user-images.githubusercontent.com/44964969/62939548-c1f4d600-bdfb-11e9-95c8-4628c0121dcd.jpg)

Cable and header pin
![cable_header_pin_mapping](https://user-images.githubusercontent.com/44964969/62939571-d1741f00-bdfb-11e9-96ac-6f0fe0eacfc7.jpg)

JST Connector part number
![jst_part_number](https://user-images.githubusercontent.com/44964969/62939597-d9cc5a00-bdfb-11e9-9e97-085322eea2e1.jpg)

## Instruction
1. Find a model your need for your device by reading Installation Manual from http://www.onlinecontroller.daikineurope.com/ and compare to your actual device. Also open your Daikin unit and check for actual socket on control board.
2. Order JST connectors parts. I use https://lcsc.com/ .
3. Find JST crimp tool. I recommend one that has multiple sizes like 0.25mm/0.5mm/1.0mm since each header in wire harness has different size.
4. If control board of your device doesn't have socket but has circuit at that position, it MIGHT be possible to soldering socket onto board. For example, I soldered X50A socket on my old Daikin Sky Air model and used BRP069A41 with hand made wire harness. However, you need surface mounted soldering tool.

![x50a_socket_position](https://user-images.githubusercontent.com/44964969/62941229-c4f1c580-bdff-11e9-98b8-2ec45b25d760.jpg)

## More Information
I don't have access to all Daikin wire harness types. If you have information please tell me so I can link back to your repository.
