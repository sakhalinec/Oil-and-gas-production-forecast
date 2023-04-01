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

Date	Oil, kbd	Gas, Mcfd	Well with marginal GOR	GOR of Marginal Well
15.12.2022	22,404341	117,5958	Well_8	5,414727
15.01.2023	21,923816	117,11385	Well_8	5,550776
15.02.2023	21,286433	115,668	Well_8	5,690243
15.03.2023	20,669536	114,22215	Well_8	5,833213
15.04.2023	20,998814	112,29435	Well_1	5,427561
15.05.2023	20,195127	109,8846	Well_1	5,566729
15.06.2023	19,421015	107,47485	Well_1	5,709466
15.07.2023	18,922377	106,51095	Well_1	5,855863
15.08.2023	18,679721	106,9929	Well_1	6,006013
15.09.2023	18,596272	108,43875	Well_1	6,160013
15.10.2023	18,736562	111,33045	Well_1	6,317962
15.11.2023	18,86058	114,22215	Well_1	6,479961
15.12.2023	18,185127	117,5958	Well_8	7,292924
15.01.2024	17,814255	117,11385	Well_8	7,476163
15.02.2024	18,107816	115,668	Well_1	6,99131
15.03.2024	17,594416	114,22215	Well_1	7,170575
15.04.2024	17,032061	112,29435	Well_1	7,354435
15.05.2024	16,42513	109,8846	Well_1	7,543011
15.06.2024	16,381803	107,47485	Well_7	7,298913
15.07.2024	15,976556	106,51095	Well_7	7,486065
15.08.2024	15,771751	106,9929	Well_7	7,678015
15.09.2024	15,691686	108,43875	Well_7	7,874887
15.10.2024	15,28038	111,33045	Well_1	8,560944
15.11.2024	15,358399	114,22215	Well_1	8,780455
15.12.2024	15,4785	117,5958	Well_1	9,005595
15.01.2025	15,167558	117,11385	Well_1	9,236508
15.02.2025	14,762707	115,668	Well_1	9,473341
15.03.2025	14,370561	114,22215	Well_1	9,716247
15.04.2025	13,942353	112,29435	Well_1	9,965382
15.05.2025	13,881942	109,8846	Well_7	9,642895
15.06.2025	13,411186	107,47485	Well_7	9,890149
15.07.2025	13,099669	106,51095	Well_7	10,143742
15.08.2025	12,936138	106,9929	Well_7	10,403838
15.09.2025	12,864726	108,43875	Well_7	10,670603
15.10.2025	12,922685	111,33045	Well_7	10,944208
![image](https://user-images.githubusercontent.com/112522254/229304697-ef68a860-ec1e-4019-b958-ac81b4c3067e.png)
	
