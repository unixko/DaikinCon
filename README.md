# DaikinCon
Daikin Online/Mobile Controller Wire Harness

Daikin Online Controller (Europe) or Daikin Mobile Controller (Asia) is an adapter to bridge Daikin device to WiFi/Internet. It consists of 2 parts, a controller and wire harness for various models. For example:

BRP069A41 -> Controller Only
BRP069A42/43/45/81 -> Variants of BRP069A41 controller with differenct wire harness.

Also applied to BRP069B41 (Europe), BRP072A42/BRP072B42/BRP072C42 (Asia)

It is possible to build wire harness by yourself in case like some variant is not available in your country or you want to swap controller between Daikin devices. Moreover, x41 model is a lot cheaper, like a half price of x81 model.


## A81

Original A81 wire harness for use with Daikin Sky Air device
![original_a81_wire_harness](https://user-images.githubusercontent.com/44964969/62939548-c1f4d600-bdfb-11e9-95c8-4628c0121dcd.jpg)

Cable and Header pin mapping
![cable_header_pin_mapping](https://user-images.githubusercontent.com/44964969/62939571-d1741f00-bdfb-11e9-96ac-6f0fe0eacfc7.jpg)

JST Connector part number.
![jst_part_number](https://user-images.githubusercontent.com/44964969/62939597-d9cc5a00-bdfb-11e9-9e97-085322eea2e1.jpg)

## Instruction

1. Find a varaint your need for your device by reading Installation Manual from http://www.onlinecontroller.daikineurope.com/ . Also open your Daikin unit and check that it actually has appropiated socket (like S21) on board.
2. Order JST connectors parts. I use https://lcsc.com/
3. Order JST crimp tool. I recommend one that has multiple sizes like 0.25mm/0.5mm/1.0mm since each header in wire harness has different size.
4. If your device board doesn't has socket but has circuit at that position, it MIGHT be possible to soldering socket onto board. For example, I soldering X50A socket onto board and BRP069A41 works. However, you need surface mounted soldering tool.

![x50a_socket_position](https://user-images.githubusercontent.com/44964969/62941229-c4f1c580-bdff-11e9-98b8-2ec45b25d760.jpg)

## More Information

I don't have access to all Daikin wire harness models. So if you have information please tell me so I can link back to your repository.

