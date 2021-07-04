# 非高速部分 {#A7B3F5B8-0345161-24A7CC7450D03B8-755227 .task}

1.  \#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\# system constraints \#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\# 

2.  create\_clock -period 8.000 \[get\_ports sys\_clk\_125m\] 

3.  set\_property PACKAGE\_PIN AG12 \[get\_ports sys\_clk\_125m\] 

4.  set\_property IOSTANDARD LVCMOS18 \[get\_ports sys\_clk\_125m\] 

5.  \#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\# mini SAS HD port constraints \#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\# 

6.  set\_property PACKAGE\_PIN P6 \[get\_ports mini\_sas\_refclk\_p\] 

7.  set\_property PACKAGE\_PIN P5 \[get\_ports mini\_sas\_refclk\_n\] 

8.  \#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\# GPIO constraints \#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\# 

9.  set\_property PACKAGE\_PIN A23 \[get\_ports \{led\_o\[0\]\}\] 

10. set\_property PACKAGE\_PIN E27 \[get\_ports \{led\_o\[1\]\}\] 

11. set\_property PACKAGE\_PIN D26 \[get\_ports \{led\_o\[2\]\}\] 

12. set\_property PACKAGE\_PIN F25 \[get\_ports \{led\_o\[3\]\}\] 

13. set\_property PACKAGE\_PIN A22 \[get\_ports \{led\_o\[4\]\}\] 

14. set\_property PACKAGE\_PIN C23 \[get\_ports \{led\_o\[5\]\}\] 

15. set\_property PACKAGE\_PIN AM32 \[get\_ports \{pcie\_wake\}\] 

16. set\_property IOSTANDARD LVCMOS12 \[get\_ports \{led\_o\[0\]\}\] 

17. set\_property IOSTANDARD LVCMOS12 \[get\_ports \{led\_o\[1\]\}\] 

18. set\_property IOSTANDARD LVCMOS12 \[get\_ports \{led\_o\[2\]\}\] 

19. set\_property IOSTANDARD LVCMOS12 \[get\_ports \{led\_o\[3\]\}\] 

20. set\_property IOSTANDARD LVCMOS12 \[get\_ports \{led\_o\[4\]\}\] 

21. set\_property IOSTANDARD LVCMOS12 \[get\_ports \{led\_o\[5\]\}\] 

22. set\_property IOSTANDARD LVCMOS12 \[get\_ports \{pcie\_wake\}\] 

23. set\_property PACKAGE\_PIN AP13 \[get\_ports pcie\_in\_conn\_1v8\] 

24. set\_property PACKAGE\_PIN J23 \[get\_ports uart\_rx\_0\] 

25. set\_property PACKAGE\_PIN J26 \[get\_ports uart\_rx\_1\] 

26. set\_property PACKAGE\_PIN K27 \[get\_ports uart\_rx\_2\] 

27. set\_property PACKAGE\_PIN H24 \[get\_ports uart\_tx\_0\] 

28. set\_property PACKAGE\_PIN H26 \[get\_ports uart\_tx\_1\] 

29. set\_property PACKAGE\_PIN H23 \[get\_ports uart\_tx\_2\] 

30. set\_property PACKAGE\_PIN G25 \[get\_ports \{debug\_o\[0\]\}\] 

31. set\_property PACKAGE\_PIN G26 \[get\_ports \{debug\_o\[1\]\}\] 

32. set\_property PACKAGE\_PIN H27 \[get\_ports \{debug\_o\[2\]\}\] 

33. set\_property PACKAGE\_PIN G27 \[get\_ports \{debug\_o\[3\]\}\] 

34. set\_property PACKAGE\_PIN AN34 \[get\_ports \{debug\_o\_dir\[0\]\}\] 

35. set\_property PACKAGE\_PIN AP34 \[get\_ports \{debug\_o\_dir\[1\]\}\] 

36. set\_property PACKAGE\_PIN AN31 \[get\_ports \{debug\_o\_dir\[2\]\}\] 

37. set\_property PACKAGE\_PIN AP31 \[get\_ports \{debug\_o\_dir\[3\]\}\] 

38. set\_property PACKAGE\_PIN AN33 \[get\_ports \{debug\_o\_dir\[4\]\}\] 

39. set\_property PACKAGE\_PIN AP8 \[get\_ports sys\_rst\_n\] 

40. set\_property PACKAGE\_PIN AG11 \[get\_ports smb\_clk\_in\] 

41. set\_property IOSTANDARD LVCMOS12 \[get\_ports \{debug\_o\_dir\[0\]\}\] 

42. set\_property IOSTANDARD LVCMOS12 \[get\_ports \{debug\_o\_dir\[1\]\}\] 

43. set\_property IOSTANDARD LVCMOS12 \[get\_ports \{debug\_o\_dir\[2\]\}\] 

44. set\_property IOSTANDARD LVCMOS12 \[get\_ports \{debug\_o\_dir\[3\]\}\] 

45. set\_property IOSTANDARD LVCMOS12 \[get\_ports \{debug\_o\_dir\[4\]\}\] 

46. set\_property IOSTANDARD LVCMOS18 \[get\_ports pcie\_in\_conn\_1v8\] 

47. set\_property IOSTANDARD LVCMOS33 \[get\_ports uart\_rx\_0\] 

48. set\_property IOSTANDARD LVCMOS33 \[get\_ports uart\_rx\_1\] 

49. set\_property IOSTANDARD LVCMOS33 \[get\_ports uart\_rx\_2\] 

50. set\_property IOSTANDARD LVCMOS33 \[get\_ports uart\_tx\_0\] 

51. set\_property IOSTANDARD LVCMOS33 \[get\_ports uart\_tx\_1\] 

52. set\_property IOSTANDARD LVCMOS33 \[get\_ports uart\_tx\_2\] 

53. set\_property IOSTANDARD LVCMOS33 \[get\_ports \{debug\_o\[0\]\}\] 

54. set\_property IOSTANDARD LVCMOS33 \[get\_ports \{debug\_o\[1\]\}\] 

55. set\_property IOSTANDARD LVCMOS33 \[get\_ports \{debug\_o\[2\]\}\] 

56. set\_property IOSTANDARD LVCMOS33 \[get\_ports \{debug\_o\[3\]\}\] 

57. set\_property IOSTANDARD LVCMOS18 \[get\_ports sys\_rst\_n\] 

58. set\_property IOSTANDARD LVCMOS18 \[get\_ports smb\_clk\_in\] 

59. \#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\# ARM JTAG constraints \#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\# 

60. set\_property PACKAGE\_PIN AG9 \[get\_ports \{arm\_jtag\[0\]\}\] 

61. set\_property PACKAGE\_PIN AJ11 \[get\_ports \{arm\_jtag\[1\]\}\] 

62. set\_property PACKAGE\_PIN AP9 \[get\_ports \{arm\_jtag\[2\]\}\] 

63. set\_property PACKAGE\_PIN AP10 \[get\_ports \{arm\_jtag\[3\]\}\] 

64. set\_property PACKAGE\_PIN AP11 \[get\_ports \{arm\_jtag\[4\]\}\] 

65. set\_property IOSTANDARD LVCMOS18 \[get\_ports \{arm\_jtag\[\*\]\}\] 

66. \#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\# SPI constraints \#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\#\# 

67. set\_property PACKAGE\_PIN L22 \[get\_ports spi\_clk\] 

68. set\_property PACKAGE\_PIN R27 \[get\_ports spi\_cs\] 

69. set\_property PACKAGE\_PIN K26 \[get\_ports spi\_din\] 

70. set\_property PACKAGE\_PIN T24 \[get\_ports spi\_dout\] 

71. set\_property PACKAGE\_PIN AL13 \[get\_ports push\_rst\] 

72. set\_property IOSTANDARD LVCMOS18 \[get\_ports push\_rst\] 


**Parent topic:**[FPGAPin脚约束和I/O标准](../concepts/EpicElfug_fpgapin脚约束和i_o标准.md)

