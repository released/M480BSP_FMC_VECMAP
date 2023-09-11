# M480BSP_FMC_VECMAP
 M480BSP_FMC_VECMAP

update @ 2022/09/11

1. with 2 project , use differnt sct file , to entry differnt vector map

- BANK1 : start address : 0x00 , length : 0x40000

- BANK2 : start address : 0x40000 , length : 0x40000

2. Below is BANK1 KEIL linker setting and sct file

![image](https://github.com/released/M480BSP_FMC_VECMAP/blob/main/KEIL_LINKER_BANK1.jpg)
		
Below is BANK2 KEIL linker setting and sct file

![image](https://github.com/released/M480BSP_FMC_VECMAP/blob/main/KEIL_LINKER_BANK2.jpg)
	
3. need to set config : boot from APROM with IAP ,

![image](https://github.com/released/M480BSP_FMC_VECMAP/blob/main/ICP_Config.jpg)

4. below is log file , 

BANK1

![image](https://github.com/released/M480BSP_FMC_VECMAP/blob/main/bank1.jpg)
	
BANK2

![image](https://github.com/released/M480BSP_FMC_VECMAP/blob/main/bank2.jpg)

5. Below is BANK1 map file , to locate vector address

![image](https://github.com/released/M480BSP_FMC_VECMAP/blob/main/map_file_BANK1.jpg)

Below is BANK2 map file , to locate vector address

![image](https://github.com/released/M480BSP_FMC_VECMAP/blob/main/map_file_BANK2.jpg)

