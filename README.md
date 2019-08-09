Pin	  Name
1	    LAD0
2	    VCC3
3   	LAD1
4   	(empty)
5	    LAD2
6	    LCLK
7	    LAD3
8	    GND
9	    LFRAME
10	  NC
11	  SERIEQ
12	  LRESET

Layout of 12 pin chip
1     2
3	
5   	6
7	    8
9	    10
11   	12


Here is how to connet a 12-Pin TPM chip to a 20-Pin port on a motherboard. Tested with a Gigabyte Z270X Ultra Gamin rev 1 and a TPM 2.0 chip

20-Pin		Name      12-Pin
1	        LCLK      6
2	        GND	      8
3       	LFRAME	  9
4	        (empty)	
5	        LRESET	  12
6         NC	
7	        LAD3	    7
8	        LAD2	    5
9	        VCC3	    2
10	      LAD1	    3
11	      LAD0	    1
12	      GND	      8
13	      NC	
14	      ID	
15	      SB3V	
16	      SERIQ	    11
17	      GND	      8
18	      NC	
19	      NC	
20	      SUSCLK	
