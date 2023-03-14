# 20230314 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=30844
self.closeSec=1678781999, self.tradeDate='20230314', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=24164.2, self.close=24235.2, self.high=24235.2, self.low=24155.6, self.vol=3034.931, self.amt=73441490.6672 
127.0.0.1 - - [14/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-14 16:20:03,739:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230314   155500    155959  ...         0.0        0.0       0
5952  20230314   160000    160459  ...         0.0        0.0       0
5953  20230314   160500    160959  ...         0.0        0.0       0
5954  20230314   161000    161459  ...         0.0        0.0       0
5955  20230314   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-14 16:20:03,758:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678781999, self.tradeDate='20230314', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=24164.2, self.close=24235.2, self.high=24235.2, self.low=24155.6, self.vol=3034.931, self.amt=73441490.6672, ukdf['pct'].iloc[-1]=0.002934 , ukdf['amount'].iloc[-1]=73441490.6672, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-463786.00427996464', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24236.45907139', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=30845
self.closeSec=1678782299, self.tradeDate='20230314', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=24235.1, self.close=24223.5, self.high=24243.0, self.low=24201.4, self.vol=1363.651, self.amt=33030240.8802 
127.0.0.1 - - [14/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-03-14 16:25:01,647:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230314   160000    160459  ...         0.0        0.0       0
5953  20230314   160500    160959  ...         0.0        0.0       0
5954  20230314   161000    161459  ...         0.0        0.0       0
5955  20230314   161500    161959  ...         0.0        0.0       0
5956  20230314   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-14 16:25:01,649:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678782299, self.tradeDate='20230314', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=24235.1, self.close=24223.5, self.high=24243.0, self.low=24201.4, self.vol=1363.651, self.amt=33030240.8802, ukdf['pct'].iloc[-1]=-0.000483 , ukdf['amount'].iloc[-1]=33030240.8802, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-462794.05719209728', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24219.97497328', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1678781999, self.tradeDate='20230314', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=24164.2, self.close=24235.2, self.high=24235.2, self.low=24155.6 
127.0.0.1 - - [14/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-14 16:20:01,921:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678781999, self.tradeDate='20230314', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=24164.2, self.close=24235.2, self.high=24235.2, self.low=24155.6   
2023-03-14 16:20:01,969:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230314   155500    155959  1678780799  ...  24244.1 -0.000787   1631    5
1632  20230314   160000    160459  1678781099  ...  24223.9 -0.001113   1632    0
1633  20230314   160500    160959  1678781399  ...  24193.5  0.000582   1633    1
1634  20230314   161000    161459  1678781699  ...  24121.7 -0.003041   1634    2
1635  20230314   161500    161959  1678781999  ...  24155.6  0.002934   1635    3

[5 rows x 11 columns]
2023-03-14 16:20:01,969:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [14/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=71, self.factor=0.13282274670475208, self.count=31411 

self.closeSec=1678782299, self.tradeDate='20230314', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=24235.1, self.close=24223.5, self.high=24243.0, self.low=24201.4 
2023-03-14 16:25:01,524:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678782299, self.tradeDate='20230314', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=24235.1, self.close=24223.5, self.high=24243.0, self.low=24201.4   
2023-03-14 16:25:01,571:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230314   160000    160459  1678781099  ...  24223.9 -0.001113   1632    0
1633  20230314   160500    160959  1678781399  ...  24193.5  0.000582   1633    1
1634  20230314   161000    161459  1678781699  ...  24121.7 -0.003041   1634    2
1635  20230314   161500    161959  1678781999  ...  24155.6  0.002934   1635    3
1636  20230314   162000    162459  1678782299  ...  24201.4 -0.000483   1636    4

[5 rows x 11 columns]
2023-03-14 16:25:01,571:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-14 16:00:34,613:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230314    132959  24417.9  ...  52.500000  0.679406  0.107461
5787  20230314    135959  24363.9  ...  52.500000  0.674519  0.111812
5788  20230314    142959  24324.1  ...  52.916667  0.678651  0.115031
5789  20230314    145959  24384.9  ...  52.500000  0.671185  0.119234
5790  20230314    152959  24332.6  ...  52.500000  0.657235  0.125422

[5 rows x 33 columns]
0.5627306273062731
acc is : 0.5627306273062731
2023-03-14 16:00:34,769:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.443498  0.556502       0  ...  1.098204  -1.0    0.0  1.039189
538     1  0.441741  0.558259       1  ...  1.095459  -1.0    0.0  1.041787
539     1  0.476054  0.523946       0  ...  1.097804  -1.0    0.0  1.039557
540     1  0.430335  0.569665       0  ...  1.102257  -1.0    0.0  1.035340
541     1  0.401458  0.598542       1  ...  1.101488  -1.0    0.0  1.036062

[5 rows x 10 columns]
2023-03-14 16:00:34,806:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.443454  0.556546       0  ...  1.098204  -1.0    0.0  1.037275
46     1  0.441660  0.558340       1  ...  1.090603  -1.0    0.0  1.040316
47     1  0.475985  0.524015       0  ...  1.097804  -1.0    0.0  1.037328
48     1  0.430337  0.569663       0  ...  1.097370  -1.0    0.0  1.035725
49     1  0.401458  0.598542       1  ...  1.101488  -1.0    0.0  1.036062

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '30.238', 'enterprice': '24295.7', 'countrevence': '0', 'unrealprofit': '708.35129437956', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24272.27413538', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230314   155000    155959  1678780799  24172.3  24251.9  0.003904
2023-03-14 16:00:02,207:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [14/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15704 

self.closeSec=1678781399, self.tradeDate='20230314', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='24252.3', self.close='24238'
2023-03-14 16:10:01,764:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678781399, self.tradeDate='20230314', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='24252.3', self.close='24238'
2023-03-14 16:10:01,804:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230314   152000    152959  1678778999  24374.8    24234 -0.005776
525  20230314   153000    153959  1678779599  24234.1  24259.9  0.001069
526  20230314   154000    154959  1678780199  24259.8  24157.6 -0.004217
527  20230314   155000    155959  1678780799  24172.3  24251.9  0.003904
528  20230314   160000    160959  1678781399  24252.3    24238 -0.000573
2023-03-14 16:10:01,805:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15705 

self.closeSec=1678781999, self.tradeDate='20230314', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='24238', self.close='24235.2'
127.0.0.1 - - [14/Mar/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-03-14 16:20:03,977:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678781999, self.tradeDate='20230314', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='24238', self.close='24235.2'
2023-03-14 16:20:04,379:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230314   153000    153959  1678779599  24234.1  24259.9  0.001069
526  20230314   154000    154959  1678780199  24259.8  24157.6 -0.004217
527  20230314   155000    155959  1678780799  24172.3  24251.9  0.003904
528  20230314   160000    160959  1678781399  24252.3    24238 -0.000573
529  20230314   161000    161959  1678781999    24238  24235.2 -0.000116
2023-03-14 16:20:04,380:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230314   155000    155959  1678780799  24172.3  24251.9
2023-03-14 16:00:02,237:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15705 

self.closeSec=1678781399, self.tradeDate='20230314', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='24252.3', self.close='24238'
2023-03-14 16:10:01,730:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678781399, self.tradeDate='20230314', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='24252.3', self.close='24238'
127.0.0.1 - - [14/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-03-14 16:10:01,745:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230314   152000    152959  1678778999  24374.8    24234
17517  20230314   153000    153959  1678779599  24234.1  24259.9
17518  20230314   154000    154959  1678780199  24259.8  24157.6
17519  20230314   155000    155959  1678780799  24172.3  24251.9
17520  20230314   160000    160959  1678781399  24252.3    24238
2023-03-14 16:10:01,745:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15706 

self.closeSec=1678781999, self.tradeDate='20230314', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='24238', self.close='24235.2'
127.0.0.1 - - [14/Mar/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-03-14 16:20:05,365:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678781999, self.tradeDate='20230314', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='24238', self.close='24235.2'
2023-03-14 16:20:05,470:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230314   153000    153959  1678779599  24234.1  24259.9
17518  20230314   154000    154959  1678780199  24259.8  24157.6
17519  20230314   155000    155959  1678780799  24172.3  24251.9
17520  20230314   160000    160959  1678781399  24252.3    24238
17521  20230314   161000    161959  1678781999    24238  24235.2
2023-03-14 16:20:05,471:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230314   155000    155959  1678780799  24172.3  24251.9
2023-03-14 16:00:02,208:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15705 

self.closeSec=1678781399, self.tradeDate='20230314', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='24252.3', self.close='24238'
2023-03-14 16:10:01,733:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678781399, self.tradeDate='20230314', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='24252.3', self.close='24238'
127.0.0.1 - - [14/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-03-14 16:10:01,790:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230314   152000    152959  1678778999  24374.8    24234
12189  20230314   153000    153959  1678779599  24234.1  24259.9
12190  20230314   154000    154959  1678780199  24259.8  24157.6
12191  20230314   155000    155959  1678780799  24172.3  24251.9
12192  20230314   160000    160959  1678781399  24252.3    24238
2023-03-14 16:10:01,790:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15706 

self.closeSec=1678781999, self.tradeDate='20230314', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='24238', self.close='24235.2'
127.0.0.1 - - [14/Mar/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-03-14 16:20:05,001:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678781999, self.tradeDate='20230314', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='24238', self.close='24235.2'
2023-03-14 16:20:05,198:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230314   153000    153959  1678779599  24234.1  24259.9
12190  20230314   154000    154959  1678780199  24259.8  24157.6
12191  20230314   155000    155959  1678780799  24172.3  24251.9
12192  20230314   160000    160959  1678781399  24252.3    24238
12193  20230314   161000    161959  1678781999    24238  24235.2
2023-03-14 16:20:05,198:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [14/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=26842
self.closeSec=1678781999, self.tradeDate='20230314', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=24164.2, self.close=24235.2, self.high=24235.2, self.low=24155.6, self.vol=3034.931, self.amt=73441490.6672 
2023-03-14 16:20:01,762:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230314   155500    155959  ...         0.0        0.0       0
5952  20230314   160000    160459  ...         0.0        0.0       0
5953  20230314   160500    160959  ...         0.0        0.0       0
5954  20230314   161000    161459  ...         0.0        0.0       0
5955  20230314   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-14 16:20:01,765:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678781999, self.tradeDate='20230314', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=24164.2, self.close=24235.2, self.high=24235.2, self.low=24155.6, self.vol=3034.931, self.amt=73441490.6672, ukdf['pct'].iloc[-1]=0.002934 , ukdf['amount'].iloc[-1]=73441490.6672, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [14/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=26843
self.closeSec=1678782299, self.tradeDate='20230314', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=24235.1, self.close=24223.5, self.high=24243.0, self.low=24201.4, self.vol=1363.651, self.amt=33030240.8802 
2023-03-14 16:25:01,618:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230314   160000    160459  ...         0.0        0.0       0
5953  20230314   160500    160959  ...         0.0        0.0       0
5954  20230314   161000    161459  ...         0.0        0.0       0
5955  20230314   161500    161959  ...         0.0        0.0       0
5956  20230314   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-14 16:25:01,619:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678782299, self.tradeDate='20230314', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=24235.1, self.close=24223.5, self.high=24243.0, self.low=24201.4, self.vol=1363.651, self.amt=33030240.8802, ukdf['pct'].iloc[-1]=-0.000483 , ukdf['amount'].iloc[-1]=33030240.8802, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230314   040000    075959  1678751999  ...    721  1.073077  1.854290     1.0
722  20230314   080000    115959  1678766399  ...    722  1.051448  1.762806     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.825', 'enterprice': '20070', 'countrevence': '0', 'unrealprofit': '240527.595', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24378.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [14/Mar/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1119287.34225, self.flagDict['side']='buy', self.tradeCount=24, self.count=654
self.closeSec=1678780799, self.tradeDate='20230314', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=24379.9, self.close=24251.9, self.high=24850.0, self.low=24148.0, self.vol=154883.625, self.amt=3782950074.57172 
2023-03-14 16:00:01,932:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1678780799, self.tradeDate='20230314', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=24379.9, self.close=24251.9, self.high=24850.0, self.low=24148.0, self.vol=154883.625, self.amt=3782950074.57172 
2023-03-14 16:00:01,974:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230313   200000    235959  ...  677353.141  1.575063e+10  0.086744
720  20230314   000000    035959  ...  228551.466  5.508260e+09  0.012729
721  20230314   040000    075959  ...   88630.517  2.139523e+09 -0.008090
722  20230314   080000    115959  ...  103809.190  2.519117e+09  0.010863
723  20230314   120000    155959  ...  154883.625  3.782950e+09 -0.005250

[5 rows x 11 columns]
2023-03-14 16:00:04,283:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230313   200000    235959  1678723199  ...    719  1.272734  2.633642     1.0
720  20230314   000000    035959  1678737599  ...    720  1.190338  2.289389     1.0
721  20230314   040000    075959  1678751999  ...    721  1.073077  1.854290     1.0
722  20230314   080000    115959  1678766399  ...    722  1.051448  1.762806     1.0
723  20230314   120000    155959  1678780799  ...    723  1.056560  1.757535     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.825', 'enterprice': '20070', 'countrevence': '0', 'unrealprofit': '233822.8904431035', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24258.49781358', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


