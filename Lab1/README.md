*I pledge my Honor that I have abided by the Stevens Honor System- Joy Son*

![image](https://user-images.githubusercontent.com/98338109/231576838-24ab30a8-8c89-4199-8a18-6ff2c85505b5.png)

# LAB 1

## Install GHDL and GTKWave
$ cat /etc/os-release

![image](https://user-images.githubusercontent.com/98338109/231577167-11b7dc91-dd65-40c6-a70a-48338d2313d8.png)

$ sudo apt update

![image](https://user-images.githubusercontent.com/98338109/231577202-d591eb03-8cef-4cc4-864c-d9654328182c.png)

$ sudo apt install gtkwave

![image](https://user-images.githubusercontent.com/98338109/231577440-b0374b17-babb-4d71-9449-3c8a612f7fee.png)

$ sudo apt install git make gnat zlib1g-dev

![image](https://user-images.githubusercontent.com/98338109/231577648-84462fa6-4cba-4b59-bb75-cb48ec9003ce.png)

$ git clone https://github.com/ghdl/ghdl

![image](https://user-images.githubusercontent.com/98338109/231577811-946bd559-4be5-4e36-a875-28132b64ec0a.png)

$ cd ghdl

![image](https://user-images.githubusercontent.com/98338109/231577858-d39d6144-1cf9-48e3-a789-368926e7accf.png)

$ ./configure --prefix=/usr/local

![image](https://user-images.githubusercontent.com/98338109/231577961-ef6011a1-e99f-45d0-a0b0-2f8a65148515.png)

$ make

![image](https://user-images.githubusercontent.com/98338109/231578294-4b19c46d-8cf1-4a02-8946-b0ddfeb46e5d.png)
...
![image](https://user-images.githubusercontent.com/98338109/231578373-5315f49f-65c7-409e-9752-464b8adfabcb.png)

$ sudo make install

![image](https://user-images.githubusercontent.com/98338109/231578463-627b7b61-ea76-4e40-8903-556b77657c9d.png)
![image](https://user-images.githubusercontent.com/98338109/231578503-f7bd237d-65d1-4fe7-8b87-3a1b4a93de23.png)

- Quick Start Guide

$ git clone https://github.com/kevinwlu/dsd.git
$ mkdir vhdl
$ cd vhdl
$ cp ~/dsd/ghdl/*vhdl .

![image](https://user-images.githubusercontent.com/98338109/231578875-21782262-4b8a-47fc-8966-5fb7ad1daae2.png)

## Run the Half Adder example

$ ghdl -a ha.vhdl
$ ghdl -a ha_tb.vhdl
$ ghdl -e ha_tb
$ ghdl -r ha_tb --vcd=ha.vcd
ha_tb.vhdl:47:5:@5ns:(assertion error): Reached end of test

![image](https://user-images.githubusercontent.com/98338109/231579235-aeafe1ee-c956-4486-9225-6fb8dad3a0fb.png)

$ gtkwave ha.vcd

![image](https://user-images.githubusercontent.com/98338109/231579672-a23238c8-1e4d-4665-90c7-73894d62aa11.png)
![image](https://user-images.githubusercontent.com/98338109/231580137-6ee6f270-b738-49f3-b1e1-ee4440ffe9cd.png)

## Run another example such as D Flip-Flop or 4-to-1 Multiplexer

$ ghdl -a dff.vhdl
$ ghdl -a dff_tb.vhdl
$ ghdl -e dff_tb
$ ghdl -r dff_tb --vcd=dff.vcd

![image](https://user-images.githubusercontent.com/98338109/231580398-0fba6478-f6da-4459-bca4-ee4879805a81.png)

$ gtkwave dff.vcd

![image](https://user-images.githubusercontent.com/98338109/231581004-54565206-c3ae-4eb9-857d-36592a86ff29.png)
![image](https://user-images.githubusercontent.com/98338109/231580970-db10d31a-cfb5-4c55-af79-f1ac79f4cd74.png)
