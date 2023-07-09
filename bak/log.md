# 20230709 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=16192
self.closeSec=1688890799, self.tradeDate='20230709', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30285.6, self.close=30274.9, self.high=30285.6, self.low=30271.9, self.vol=296.223, self.amt=8969358.7905 
127.0.0.1 - - [09/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-09 16:20:07,558:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230709   155500    155959  ...         0.0        0.0       0
5952  20230709   160000    160459  ...         0.0        0.0       0
5953  20230709   160500    160959  ...         0.0        0.0       0
5954  20230709   161000    161459  ...         0.0        0.0       0
5955  20230709   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-09 16:20:07,589:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688890799, self.tradeDate='20230709', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30285.6, self.close=30274.9, self.high=30285.6, self.low=30271.9, self.vol=296.223, self.amt=8969358.7905, ukdf['pct'].iloc[-1]=-0.00035 , ukdf['amount'].iloc[-1]=8969358.7905, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-47489.0526', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30275', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=16193
self.closeSec=1688891099, self.tradeDate='20230709', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30275.0, self.close=30273.4, self.high=30275.0, self.low=30269.1, self.vol=162.246, self.amt=4911686.4479 
127.0.0.1 - - [09/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-07-09 16:25:00,947:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230709   160000    160459  ...         0.0        0.0       0
5953  20230709   160500    160959  ...         0.0        0.0       0
5954  20230709   161000    161459  ...         0.0        0.0       0
5955  20230709   161500    161959  ...         0.0        0.0       0
5956  20230709   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-09 16:25:00,947:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688891099, self.tradeDate='20230709', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30275.0, self.close=30273.4, self.high=30275.0, self.low=30269.1, self.vol=162.246, self.amt=4911686.4479, ukdf['pct'].iloc[-1]=-5e-05 , ukdf['amount'].iloc[-1]=4911686.4479, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-47466.771', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30273.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1688890799, self.tradeDate='20230709', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30285.6, self.close=30274.9, self.high=30285.6, self.low=30271.9 
127.0.0.1 - - [09/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-09 16:20:05,187:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688890799, self.tradeDate='20230709', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30285.6, self.close=30274.9, self.high=30285.6, self.low=30271.9   
2023-07-09 16:20:06,790:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230709   155500    155959  1688889599  ...  30244.1  0.000192   1631    5
1632  20230709   160000    160459  1688889899  ...  30249.9  0.000426   1632    0
1633  20230709   160500    160959  1688890199  ...  30262.8  0.000416   1633    1
1634  20230709   161000    161459  1688890499  ...  30275.1  0.000330   1634    2
1635  20230709   161500    161959  1688890799  ...  30271.9 -0.000350   1635    3

[5 rows x 11 columns]
2023-07-09 16:20:06,799:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=31, self.factor=0.46371984598212995, self.count=16195 

self.closeSec=1688891099, self.tradeDate='20230709', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30275.0, self.close=30273.4, self.high=30275.0, self.low=30269.1 
127.0.0.1 - - [09/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-07-09 16:25:00,839:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688891099, self.tradeDate='20230709', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30275.0, self.close=30273.4, self.high=30275.0, self.low=30269.1   
2023-07-09 16:25:00,897:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230709   160000    160459  1688889899  ...  30249.9  0.000426   1632    0
1633  20230709   160500    160959  1688890199  ...  30262.8  0.000416   1633    1
1634  20230709   161000    161459  1688890499  ...  30275.1  0.000330   1634    2
1635  20230709   161500    161959  1688890799  ...  30271.9 -0.000350   1635    3
1636  20230709   162000    162459  1688891099  ...  30269.1 -0.000050   1636    4

[5 rows x 11 columns]
2023-07-09 16:25:00,903:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-09 16:00:18,842:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230709    132959  30266.4  ...  46.666667  0.502426  0.414893
5787  20230709    135959  30267.3  ...  46.666667  0.496694  0.413813
5788  20230709    142959  30249.3  ...  46.250000  0.493261  0.414733
5789  20230709    145959  30238.5  ...  46.666667  0.494427  0.414961
5790  20230709    152959  30242.3  ...  46.666667  0.497429  0.413571

[5 rows x 33 columns]
0.5701107011070111
acc is : 0.5701107011070111
2023-07-09 16:00:18,945:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.504056  0.495944       0  ...  0.942524   1.0    0.0  0.988520
538     0  0.500401  0.499599       0  ...  0.942190   1.0    0.0  0.988170
539     1  0.499890  0.500110       1  ...  0.942299   1.0    0.0  0.988285
540     0  0.503058  0.496942       1  ...  0.942577   1.0    0.0  0.988575
541     0  0.506798  0.493202       0  ...  0.942542   1.0    0.0  0.988539

[5 rows x 10 columns]
2023-07-09 16:00:18,972:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.505048  0.494952       0  ...  0.977885   1.0    0.0  0.989519
46     0  0.500964  0.499036       0  ...  0.952026   1.0    0.0  0.987315
47     1  0.499909  0.500091       1  ...  0.942299   1.0    0.0  0.985627
48     0  0.503541  0.496459       1  ...  0.942577   1.0    0.0  0.991245
49     0  0.506798  0.493202       0  ...  0.942542   1.0    0.0  0.988539

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.764', 'enterprice': '30087.2', 'countrevence': '0', 'unrealprofit': '4056.67103623288', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30251.01323842', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230709   155000    155959  1688889599  30242.3    30250  0.000258
2023-07-09 16:00:02,227:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [09/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8096 

self.closeSec=1688890199, self.tradeDate='20230709', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30250', self.close='30275.5'
2023-07-09 16:10:01,178:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688890199, self.tradeDate='20230709', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30250', self.close='30275.5'
2023-07-09 16:10:01,194:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230709   152000    152959  1688887799  30265.3  30251.1 -0.000472
525  20230709   153000    153959  1688888399  30251.1  30242.6 -0.000281
526  20230709   154000    154959  1688888999  30242.7  30242.2 -0.000013
527  20230709   155000    155959  1688889599  30242.3    30250  0.000258
528  20230709   160000    160959  1688890199    30250  30275.5  0.000843
2023-07-09 16:10:01,195:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8097 

self.closeSec=1688890799, self.tradeDate='20230709', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30275.6', self.close='30274.9'
127.0.0.1 - - [09/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-09 16:20:07,428:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688890799, self.tradeDate='20230709', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30275.6', self.close='30274.9'
2023-07-09 16:20:08,179:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230709   153000    153959  1688888399  30251.1  30242.6 -0.000281
526  20230709   154000    154959  1688888999  30242.7  30242.2 -0.000013
527  20230709   155000    155959  1688889599  30242.3    30250  0.000258
528  20230709   160000    160959  1688890199    30250  30275.5  0.000843
529  20230709   161000    161959  1688890799  30275.6  30274.9 -0.000020
2023-07-09 16:20:08,188:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230709   155000    155959  1688889599  30242.3    30250
2023-07-09 16:00:02,255:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [09/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8099 

self.closeSec=1688890199, self.tradeDate='20230709', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30250', self.close='30275.5'
2023-07-09 16:10:01,186:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688890199, self.tradeDate='20230709', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30250', self.close='30275.5'
2023-07-09 16:10:01,200:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230709   152000    152959  1688887799  30265.3  30251.1
17517  20230709   153000    153959  1688888399  30251.1  30242.6
17518  20230709   154000    154959  1688888999  30242.7  30242.2
17519  20230709   155000    155959  1688889599  30242.3    30250
17520  20230709   160000    160959  1688890199    30250  30275.5
2023-07-09 16:10:01,200:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8100 

self.closeSec=1688890799, self.tradeDate='20230709', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30275.6', self.close='30274.9'
127.0.0.1 - - [09/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-09 16:20:09,369:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688890799, self.tradeDate='20230709', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30275.6', self.close='30274.9'
2023-07-09 16:20:09,569:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230709   153000    153959  1688888399  30251.1  30242.6
17518  20230709   154000    154959  1688888999  30242.7  30242.2
17519  20230709   155000    155959  1688889599  30242.3    30250
17520  20230709   160000    160959  1688890199    30250  30275.5
17521  20230709   161000    161959  1688890799  30275.6  30274.9
2023-07-09 16:20:09,570:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230709   155000    155959  1688889599  30242.3    30250
2023-07-09 16:00:02,246:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [09/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8099 

self.closeSec=1688890199, self.tradeDate='20230709', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30250', self.close='30275.5'
2023-07-09 16:10:01,176:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688890199, self.tradeDate='20230709', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30250', self.close='30275.5'
2023-07-09 16:10:01,191:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230709   152000    152959  1688887799  30265.3  30251.1
12189  20230709   153000    153959  1688888399  30251.1  30242.6
12190  20230709   154000    154959  1688888999  30242.7  30242.2
12191  20230709   155000    155959  1688889599  30242.3    30250
12192  20230709   160000    160959  1688890199    30250  30275.5
2023-07-09 16:10:01,191:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8100 

self.closeSec=1688890799, self.tradeDate='20230709', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30275.6', self.close='30274.9'
127.0.0.1 - - [09/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-09 16:20:09,071:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688890799, self.tradeDate='20230709', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30275.6', self.close='30274.9'
2023-07-09 16:20:09,379:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230709   153000    153959  1688888399  30251.1  30242.6
12190  20230709   154000    154959  1688888999  30242.7  30242.2
12191  20230709   155000    155959  1688889599  30242.3    30250
12192  20230709   160000    160959  1688890199    30250  30275.5
12193  20230709   161000    161959  1688890799  30275.6  30274.9
2023-07-09 16:20:09,380:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=16192
self.closeSec=1688890799, self.tradeDate='20230709', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30285.6, self.close=30274.9, self.high=30285.6, self.low=30271.9, self.vol=296.223, self.amt=8969358.7905 
127.0.0.1 - - [09/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-09 16:20:07,549:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230709   155500    155959  ...         0.0        0.0       0
5952  20230709   160000    160459  ...         0.0        0.0       0
5953  20230709   160500    160959  ...         0.0        0.0       0
5954  20230709   161000    161459  ...         0.0        0.0       0
5955  20230709   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-09 16:20:07,589:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688890799, self.tradeDate='20230709', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30285.6, self.close=30274.9, self.high=30285.6, self.low=30271.9, self.vol=296.223, self.amt=8969358.7905, ukdf['pct'].iloc[-1]=-0.00035 , ukdf['amount'].iloc[-1]=8969358.7905, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '127430.771', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30275', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=16193
self.closeSec=1688891099, self.tradeDate='20230709', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30275.0, self.close=30273.4, self.high=30275.0, self.low=30269.1, self.vol=162.246, self.amt=4911686.4479 
127.0.0.1 - - [09/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-07-09 16:25:00,949:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230709   160000    160459  ...         0.0        0.0       0
5953  20230709   160500    160959  ...         0.0        0.0       0
5954  20230709   161000    161459  ...         0.0        0.0       0
5955  20230709   161500    161959  ...         0.0        0.0       0
5956  20230709   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-09 16:25:00,949:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688891099, self.tradeDate='20230709', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30275.0, self.close=30273.4, self.high=30275.0, self.low=30269.1, self.vol=162.246, self.amt=4911686.4479, ukdf['pct'].iloc[-1]=-5e-05 , ukdf['amount'].iloc[-1]=4911686.4479, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '127371.3454', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30273.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230709   040000    075959  1688860799  ...    721  0.358795  0.194950     NaN
722  20230709   080000    115959  1688875199  ...    722  0.351068  0.198917     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.05', 'enterprice': '30750.9', 'countrevence': '0', 'unrealprofit': '-25113.87', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30277.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1629703.909755, self.flagDict['side']='buy', self.tradeCount=9, self.count=337
self.closeSec=1688889599, self.tradeDate='20230709', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=30277.6, self.close=30250.0, self.high=30289.1, self.low=30218.2, self.vol=12970.718, self.amt=392427945.0756 
127.0.0.1 - - [09/Jul/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-07-09 16:00:01,706:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1688889599, self.tradeDate='20230709', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=30277.6, self.close=30250.0, self.high=30289.1, self.low=30218.2, self.vol=12970.718, self.amt=392427945.0756 
2023-07-09 16:00:01,729:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230708   200000    235959  ...  15361.803  4.637049e+08  0.000378
720  20230709   000000    035959  ...  31842.636  9.610810e+08 -0.003202
721  20230709   040000    075959  ...  19275.386  5.815407e+08  0.005625
722  20230709   080000    115959  ...  29538.533  8.953542e+08  0.000274
723  20230709   120000    155959  ...  12970.718  3.924279e+08 -0.000912

[5 rows x 11 columns]
2023-07-09 16:00:02,978:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230708   200000    235959  1688831999  ...    719  0.422333  0.360380     NaN
720  20230709   000000    035959  1688846399  ...    720  0.417043  0.377134     NaN
721  20230709   040000    075959  1688860799  ...    721  0.358795  0.194950     NaN
722  20230709   080000    115959  1688875199  ...    722  0.351068  0.198917     NaN
723  20230709   120000    155959  1688889599  ...    723  0.342819  0.197953     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.05', 'enterprice': '30750.9', 'countrevence': '0', 'unrealprofit': '-26515.1574589655', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30251.08553329', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


