# 20230328 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=34876
self.closeSec=1679991599, self.tradeDate='20230328', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26947.2, self.close=26951.8, self.high=26962.1, self.low=26937.6, self.vol=781.739, self.amt=21068348.3782 
127.0.0.1 - - [28/Mar/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-03-28 16:20:08,564:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230328   155500    155959  ...         0.0        0.0       0
5952  20230328   160000    160459  ...         0.0        0.0       0
5953  20230328   160500    160959  ...         0.0        0.0       0
5954  20230328   161000    161459  ...         0.0        0.0       0
5955  20230328   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-28 16:20:08,585:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679991599, self.tradeDate='20230328', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26947.2, self.close=26951.8, self.high=26962.1, self.low=26937.6, self.vol=781.739, self.amt=21068348.3782, ukdf['pct'].iloc[-1]=0.000174 , ukdf['amount'].iloc[-1]=21068348.3782, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-627503.2928', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26957.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=34877
self.closeSec=1679991899, self.tradeDate='20230328', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26951.7, self.close=26931.0, self.high=26959.7, self.low=26910.0, self.vol=1148.793, self.amt=30940317.5112 
127.0.0.1 - - [28/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-03-28 16:25:01,583:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230328   160000    160459  ...         0.0        0.0       0
5953  20230328   160500    160959  ...         0.0        0.0       0
5954  20230328   161000    161459  ...         0.0        0.0       0
5955  20230328   161500    161959  ...         0.0        0.0       0
5956  20230328   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-28 16:25:01,586:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679991899, self.tradeDate='20230328', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26951.7, self.close=26931.0, self.high=26959.7, self.low=26910.0, self.vol=1148.793, self.amt=30940317.5112, ukdf['pct'].iloc[-1]=-0.000772 , ukdf['amount'].iloc[-1]=30940317.5112, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-625932.6992', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26931', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1679991599, self.tradeDate='20230328', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26947.2, self.close=26951.8, self.high=26962.1, self.low=26937.6 
127.0.0.1 - - [28/Mar/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-03-28 16:20:06,052:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679991599, self.tradeDate='20230328', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26947.2, self.close=26951.8, self.high=26962.1, self.low=26937.6   
2023-03-28 16:20:07,155:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230328   155500    155959  1679990399  ...  26912.2 -0.001826   1631    5
1632  20230328   160000    160459  1679990699  ...  26920.0 -0.000909   1632    0
1633  20230328   160500    160959  1679990999  ...  26927.5  0.001032   1633    1
1634  20230328   161000    161459  1679991299  ...  26945.0 -0.000356   1634    2
1635  20230328   161500    161959  1679991599  ...  26937.6  0.000174   1635    3

[5 rows x 11 columns]
2023-03-28 16:20:07,164:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [28/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.675613339901663, self.count=35443 

self.closeSec=1679991899, self.tradeDate='20230328', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26951.7, self.close=26931.0, self.high=26959.7, self.low=26910.0 
2023-03-28 16:25:01,542:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679991899, self.tradeDate='20230328', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26951.7, self.close=26931.0, self.high=26959.7, self.low=26910.0   
2023-03-28 16:25:01,599:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230328   160000    160459  1679990699  ...  26920.0 -0.000909   1632    0
1633  20230328   160500    160959  1679990999  ...  26927.5  0.001032   1633    1
1634  20230328   161000    161459  1679991299  ...  26945.0 -0.000356   1634    2
1635  20230328   161500    161959  1679991599  ...  26937.6  0.000174   1635    3
1636  20230328   162000    162459  1679991899  ...  26910.0 -0.000772   1636    4

[5 rows x 11 columns]
2023-03-28 16:25:01,600:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-28 16:00:34,073:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230328    132959  26953.4  ...  47.916667  0.416032  0.646328
5787  20230328    135959  26902.0  ...  47.916667  0.427353  0.648545
5788  20230328    142959  26962.7  ...  47.916667  0.446268  0.645969
5789  20230328    145959  27067.7  ...  47.500000  0.444528  0.644104
5790  20230328    152959  27055.6  ...  47.500000  0.439806  0.643068

[5 rows x 33 columns]
0.503690036900369
acc is : 0.503690036900369
2023-03-28 16:00:34,214:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.529519  0.470481       1  ...  0.959631   1.0    0.0  1.082643
538     0  0.566037  0.433963       1  ...  0.963368   1.0    0.0  1.086859
539     0  0.583125  0.416875       0  ...  0.962934   1.0    0.0  1.086370
540     0  0.558668  0.441332       0  ...  0.961763   1.0    0.0  1.085049
541     0  0.548155  0.451845       0  ...  0.959296   1.0    0.0  1.082266

[5 rows x 10 columns]
2023-03-28 16:00:34,240:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.528785  0.471215       1  ...  0.976280   1.0    0.0  1.079851
46     0  0.565544  0.434456       1  ...  0.963368   1.0    0.0  1.085756
47     0  0.581988  0.418012       0  ...  0.979640   1.0    0.0  1.082640
48     0  0.558274  0.441726       0  ...  0.961763   1.0    0.0  1.083839
49     0  0.548155  0.451845       0  ...  0.959296   1.0    0.0  1.082266

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230328   155000    155959  1679990399  27030.1  26953.4 -0.002838
2023-03-28 16:00:02,093:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [28/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17720 

self.closeSec=1679990999, self.tradeDate='20230328', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26947.3', self.close='26956.7'
2023-03-28 16:10:01,573:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679990999, self.tradeDate='20230328', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26947.3', self.close='26956.7'
2023-03-28 16:10:01,621:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230328   152000    152959  1679988599    27024  27022.7 -0.000048
525  20230328   153000    153959  1679989199  27022.7    27040  0.000640
526  20230328   154000    154959  1679989799  27039.9  27030.1 -0.000366
527  20230328   155000    155959  1679990399  27030.1  26953.4 -0.002838
528  20230328   160000    160959  1679990999  26947.3  26956.7  0.000122
2023-03-28 16:10:01,626:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17721 

self.closeSec=1679991599, self.tradeDate='20230328', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26956.7', self.close='26951.8'
127.0.0.1 - - [28/Mar/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-03-28 16:20:07,864:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679991599, self.tradeDate='20230328', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26956.7', self.close='26951.8'
2023-03-28 16:20:08,525:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230328   153000    153959  1679989199  27022.7    27040  0.000640
526  20230328   154000    154959  1679989799  27039.9  27030.1 -0.000366
527  20230328   155000    155959  1679990399  27030.1  26953.4 -0.002838
528  20230328   160000    160959  1679990999  26947.3  26956.7  0.000122
529  20230328   161000    161959  1679991599  26956.7  26951.8 -0.000182
2023-03-28 16:20:08,525:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/percentile_regression_step2/log.txt ----- -----

127.0.0.1 - - [21/Feb/2023 09:30:01] "POST / HTTP/1.1" 200 -
2023-02-21 09:30:03,026:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/21 07:00:00  070000  24795.1  ...     NaN     NaN       0
145  2023/02/21 07:30:00  073000  24849.9  ...     NaN     NaN       0
146  2023/02/21 08:00:00  080000  24819.0  ...     NaN     NaN       0
147  2023/02/21 08:30:00  083000  24860.9  ...     NaN     NaN       0
148  2023/02/21 09:00:00  090000  24831.0  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [21/Feb/2023 10:00:02] "POST / HTTP/1.1" 200 -
2023-02-21 10:00:03,553:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/21 07:30:00  073000  24849.9  ...     NaN     NaN       0
145  2023/02/21 08:00:00  080000  24819.0  ...     NaN     NaN       0
146  2023/02/21 08:30:00  083000  24860.9  ...     NaN     NaN       0
147  2023/02/21 09:00:00  090000  24831.0  ...     NaN     NaN       0
148  2023/02/21 09:30:00  093000  24870.0  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [21/Feb/2023 10:30:01] "POST / HTTP/1.1" 200 -
2023-02-21 10:30:03,245:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/21 08:00:00  080000  24819.0  ...     NaN     NaN       0
145  2023/02/21 08:30:00  083000  24860.9  ...     NaN     NaN       0
146  2023/02/21 09:00:00  090000  24831.0  ...     NaN     NaN       0
147  2023/02/21 09:30:00  093000  24870.0  ...     NaN     NaN       0
148  2023/02/21 10:00:00  100000  24936.1  ...     NaN     NaN       0

[5 rows x 10 columns]


## /root/FIL/strategy/pyemd/log.txt ----- -----

17519  20230328   155000    155959  1679990399  27030.1  26953.4
2023-03-28 16:00:02,166:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [28/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17721 

self.closeSec=1679990999, self.tradeDate='20230328', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26947.3', self.close='26956.7'
2023-03-28 16:10:01,604:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679990999, self.tradeDate='20230328', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26947.3', self.close='26956.7'
2023-03-28 16:10:01,663:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230328   152000    152959  1679988599    27024  27022.7
17517  20230328   153000    153959  1679989199  27022.7    27040
17518  20230328   154000    154959  1679989799  27039.9  27030.1
17519  20230328   155000    155959  1679990399  27030.1  26953.4
17520  20230328   160000    160959  1679990999  26947.3  26956.7
2023-03-28 16:10:01,663:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17722 

self.closeSec=1679991599, self.tradeDate='20230328', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26956.7', self.close='26951.8'
127.0.0.1 - - [28/Mar/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-03-28 16:20:10,766:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679991599, self.tradeDate='20230328', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26956.7', self.close='26951.8'
2023-03-28 16:20:10,907:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230328   153000    153959  1679989199  27022.7    27040
17518  20230328   154000    154959  1679989799  27039.9  27030.1
17519  20230328   155000    155959  1679990399  27030.1  26953.4
17520  20230328   160000    160959  1679990999  26947.3  26956.7
17521  20230328   161000    161959  1679991599  26956.7  26951.8
2023-03-28 16:20:10,908:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230328   155000    155959  1679990399  27030.1  26953.4
2023-03-28 16:00:02,151:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [28/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17721 

self.closeSec=1679990999, self.tradeDate='20230328', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26947.3', self.close='26956.7'
2023-03-28 16:10:01,618:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679990999, self.tradeDate='20230328', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26947.3', self.close='26956.7'
2023-03-28 16:10:01,662:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230328   152000    152959  1679988599    27024  27022.7
12189  20230328   153000    153959  1679989199  27022.7    27040
12190  20230328   154000    154959  1679989799  27039.9  27030.1
12191  20230328   155000    155959  1679990399  27030.1  26953.4
12192  20230328   160000    160959  1679990999  26947.3  26956.7
2023-03-28 16:10:01,662:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17722 

self.closeSec=1679991599, self.tradeDate='20230328', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26956.7', self.close='26951.8'
127.0.0.1 - - [28/Mar/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-03-28 16:20:10,055:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679991599, self.tradeDate='20230328', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26956.7', self.close='26951.8'
2023-03-28 16:20:10,367:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230328   153000    153959  1679989199  27022.7    27040
12190  20230328   154000    154959  1679989799  27039.9  27030.1
12191  20230328   155000    155959  1679990399  27030.1  26953.4
12192  20230328   160000    160959  1679990999  26947.3  26956.7
12193  20230328   161000    161959  1679991599  26956.7  26951.8
2023-03-28 16:20:10,367:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=30874
self.closeSec=1679991599, self.tradeDate='20230328', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26947.2, self.close=26951.8, self.high=26962.1, self.low=26937.6, self.vol=781.739, self.amt=21068348.3782 
127.0.0.1 - - [28/Mar/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-03-28 16:20:06,562:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230328   155500    155959  ...         0.0        0.0       0
5952  20230328   160000    160459  ...         0.0        0.0       0
5953  20230328   160500    160959  ...         0.0        0.0       0
5954  20230328   161000    161459  ...         0.0        0.0       0
5955  20230328   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-28 16:20:06,591:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679991599, self.tradeDate='20230328', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26947.2, self.close=26951.8, self.high=26962.1, self.low=26937.6, self.vol=781.739, self.amt=21068348.3782, ukdf['pct'].iloc[-1]=0.000174 , ukdf['amount'].iloc[-1]=21068348.3782, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=30875
self.closeSec=1679991899, self.tradeDate='20230328', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26951.7, self.close=26931.0, self.high=26959.7, self.low=26910.0, self.vol=1148.793, self.amt=30940317.5112 
127.0.0.1 - - [28/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-03-28 16:25:01,590:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230328   160000    160459  ...         0.0        0.0       0
5953  20230328   160500    160959  ...         0.0        0.0       0
5954  20230328   161000    161459  ...         0.0        0.0       0
5955  20230328   161500    161959  ...         0.0        0.0       0
5956  20230328   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-28 16:25:01,590:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679991899, self.tradeDate='20230328', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26951.7, self.close=26931.0, self.high=26959.7, self.low=26910.0, self.vol=1148.793, self.amt=30940317.5112, ukdf['pct'].iloc[-1]=-0.000772 , ukdf['amount'].iloc[-1]=30940317.5112, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230328   040000    075959  1679961599  ...    721  0.151166 -0.975929    -1.0
722  20230328   080000    115959  1679975999  ...    722  0.165832 -0.923551    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '61072.14925174818', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26953.94308547', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1507151.9559834, self.flagDict['side']='sell', self.tradeCount=27, self.count=738
self.closeSec=1679990399, self.tradeDate='20230328', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26955.6, self.close=26953.4, self.high=27132.0, self.low=26864.0, self.vol=58393.922, self.amt=1575997044.133 127.0.0.1 - - [28/Mar/2023 16:00:01] "POST / HTTP/1.1" 200 -

2023-03-28 16:00:01,951:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1679990399, self.tradeDate='20230328', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26955.6, self.close=26953.4, self.high=27132.0, self.low=26864.0, self.vol=58393.922, self.amt=1575997044.133 
2023-03-28 16:00:02,016:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230327   200000    235959  ...  308699.095  8.393002e+09 -0.035603
720  20230328   000000    035959  ...  134144.056  3.633684e+09  0.002544
721  20230328   040000    075959  ...   53997.391  1.461752e+09  0.005802
722  20230328   080000    115959  ...   65014.849  1.755064e+09 -0.005776
723  20230328   120000    155959  ...   58393.922  1.575997e+09 -0.000078

[5 rows x 11 columns]
2023-03-28 16:00:04,570:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230327   200000    235959  1679932799  ...    719  0.038575 -1.277641    -1.0
720  20230328   000000    035959  1679947199  ...    720  0.129919 -1.044061    -1.0
721  20230328   040000    075959  1679961599  ...    721  0.151166 -0.975929    -1.0
722  20230328   080000    115959  1679975999  ...    722  0.165832 -0.923551    -1.0
723  20230328   120000    155959  1679990399  ...    723  0.178320 -0.876850    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '61386.0843541062', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26948.0976473', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


