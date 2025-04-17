---
name: "Savit Arora"
slack_handle: "@savitarora"
github_handle: "@smatguy1108"
tutorial: # n/a
wokwi: # Link to the Wokwi project
--- https://wokwi.com/projects/new/pi-pico

# temp+humidity+pixel+pcb

Replace the wokwi link below with yours

Wokwi link: [https://wokwi.com/projects/new/pi-pico)

<!-- Uncomment the line below if you need a soldering iron -->
<!-- ⚠️ I would like to [solder my pcb on my own to learn how to solder and give u less work], so I would need a soldering iron. -->

Describe your board in 2-3 sentences. What are you making? What will it do? Please add a lot of pictures here!!
im making a pcb with a temp and humidity sensor. the temp and humidity sensor will control the leds based on the temp and humidity the potentiometer will control the brightness.
A simplified BOM table
Reference	Value	Footprint	Datasheet	Qty	DNP	Exclude from BOM	Exclude from Board
C1,C2,C3,C4,C5,C6,C7,C8,C9,C10,C11,C12,C14,C15,C16,C17,C18,C19,C20,C21,C22,C23,C24,C25,C26,C27,C28,C29,C30,C31,C32,C33	100nF	Capacitor_SMD:C_0805_2012Metric	~	32			
C13	100uF	Capacitor_SMD:C_0805_2012Metric	~	1			
LED1,LED2,LED3,LED4,LED5,LED6,LED7,LED8,LED9,LED10,LED11,LED12,LED13,LED14,LED15,LED16,LED17,LED18,LED19,LED20,LED21,LED22,LED23,LED24,LED25,LED26,LED27,LED28,LED29,LED30,LED31,LED32	WS2812B	WS2812B.pretty-master:WS2812B		32			
RV1	R_Potentiometer	RV100F-30-4K1B-B10K-B301:TRIM_RV100F-30-4K1B-B10K-B301	~	1			
U1	XIAO-RP2040-DIP	Seeed Studio XIAO Series Library:XIAO-RP2040-DIP		1			
U2	AHT20	AHT20:PSON100P300X300X110-6N		1			


Tell us a little bit about your design process. What were some challenges? What helped?
the schematic was hard but i used the kicad discord for help
Some images of your design (make sure to include both the PCB and Schematic!): ![image](https://github.com/user-attachments/assets/c38f5f9e-42ba-4bf3-a0bf-06ac11a7fb22)
