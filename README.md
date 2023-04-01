# Oil-and-gas-production-forecast
Oil and gas production forecast calculation, considering surface equipment limitation and well operating requiments

This scipt is developed for automated oil and gas production calculation for feild expiriencing assossiated gas processing constraing
It automatically considers gas capcity constraing of the surface equipment 
and considers minimum production from wells with high GOR through Min Choke parameter

Script is designed to calculate maximum oil production considering given limitations (max gas processing capacity is used for wells with lowest Gas-Oil-Ratio)

CONTENT:
1) Input data spreadsheet (sythetic data to demonstrate the process)
2) Script (Jupiter Notebook)

![image](https://user-images.githubusercontent.com/112522254/229304356-f196ab90-5d12-4476-b4b2-b094afa71907.png)

RESULT OF CALCULATION USING INPUT DATA FROM THE ATTACHED TABLE

	  Date	      Oil, kbd	 Gas, Mcfd	Well with marginal GOR	GOR of Marginal Well
0	  2022-12-15	22.404341	  117.59580	Well_8	                5.414727
1	  2023-01-15	21.923816 	117.11385	Well_8	                5.550776
2	  2023-02-15	21.286433	  115.66800	Well_8                	5.690243
3	  2023-03-15	20.669536 	114.22215	Well_8	                5.833213
4	  2023-04-15	20.998814 	112.29435	Well_1	                5.427561
5	  2023-05-15	20.195127 	109.88460	Well_1	                5.566729
6	  2023-06-15	19.421015 	107.47485	Well_1	                5.709466
7	  2023-07-15	18.922377 	106.51095	Well_1                	5.855863
8 	2023-08-15	18.679721 	106.99290	Well_1                	6.006013
9 	2023-09-15	18.596272 	108.43875	Well_1                	6.160013
10	2023-10-15	18.736562 	111.33045	Well_1	                6.317962
11	2023-11-15	18.860580 	114.22215	Well_1                	6.479961
12	2023-12-15	18.185127 	117.59580	Well_8                	7.292924
13	2024-01-15	17.814255 	117.11385	Well_8                	7.476163
14	2024-02-15	18.107816	  115.66800	Well_1                	6.991310
15	2024-03-15	17.594416 	114.22215	Well_1                	7.170575
16	2024-04-15	17.032061	  112.29435	Well_1                	7.354435
17	2024-05-15	16.425130	  109.88460	Well_1	                7.543011
18	2024-06-15	16.381803	  107.47485	Well_7	                7.298913
19	2024-07-15	15.976556	  106.51095	Well_7	                7.486065
20	2024-08-15	15.771751	  106.99290	Well_7	                7.678015
21	2024-09-15	15.691686	  108.43875	Well_7	                7.874887
22	2024-10-15	15.280380 	111.33045	Well_1	                8.560944
23	2024-11-15	15.358399 	114.22215	Well_1	                8.780455
24	2024-12-15	15.478500	  117.59580	Well_1	                9.005595
25	2025-01-15	15.167558 	117.11385	Well_1	                9.236508
26	2025-02-15	14.762707 	115.66800	Well_1	                9.473341
27	2025-03-15	14.370561 	114.22215	Well_1	                9.716247
28	2025-04-15	13.942353	  112.29435	Well_1	                9.965382
29	2025-05-15	13.881942 	109.88460	Well_7                	9.642895
30	2025-06-15	13.411186	  107.47485	Well_7                	9.890149
31	2025-07-15	13.099669 	106.51095	Well_7                  10.143742
32	2025-08-15	12.936138	  106.99290	Well_7	                10.403838
33	2025-09-15	12.864726 	108.43875	Well_7	                10.670603
34	2025-10-15	12.922685 	111.33045	Well_7                	10.944208
35	2025-11-15	12.971460 	114.22215	Well_7	                11.224829
36	2025-12-15	12.692868 	117.59580	Well_1	                12.202731
