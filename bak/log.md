# 20230326 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=34300
self.closeSec=1679818799, self.tradeDate='20230326', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27502.2, self.close=27495.2, self.high=27510.0, self.low=27495.2, self.vol=272.359, self.amt=7490375.3009 
127.0.0.1 - - [26/Mar/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-03-26 16:20:08,681:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230326   155500    155959  ...         0.0        0.0       0
5952  20230326   160000    160459  ...         0.0        0.0       0
5953  20230326   160500    160959  ...         0.0        0.0       0
5954  20230326   161000    161459  ...         0.0        0.0       0
5955  20230326   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-26 16:20:08,700:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679818799, self.tradeDate='20230326', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27502.2, self.close=27495.2, self.high=27510.0, self.low=27495.2, self.vol=272.359, self.amt=7490375.3009, ukdf['pct'].iloc[-1]=-0.000255 , ukdf['amount'].iloc[-1]=7490375.3009, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-660040.456', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27497.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [26/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=34301
self.closeSec=1679819099, self.tradeDate='20230326', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27495.3, self.close=27492.0, self.high=27502.0, self.low=27492.0, self.vol=245.678, self.amt=6755026.3015 
2023-03-26 16:25:01,609:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230326   160000    160459  ...         0.0        0.0       0
5953  20230326   160500    160959  ...         0.0        0.0       0
5954  20230326   161000    161459  ...         0.0        0.0       0
5955  20230326   161500    161959  ...         0.0        0.0       0
5956  20230326   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-26 16:25:01,609:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679819099, self.tradeDate='20230326', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27495.3, self.close=27492.0, self.high=27502.0, self.low=27492.0, self.vol=245.678, self.amt=6755026.3015, ukdf['pct'].iloc[-1]=-0.000116 , ukdf['amount'].iloc[-1]=6755026.3015, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-659736.29280766992', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27492.74544017', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1679818799, self.tradeDate='20230326', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27502.2, self.close=27495.2, self.high=27510.0, self.low=27495.2 
127.0.0.1 - - [26/Mar/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-03-26 16:20:06,860:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679818799, self.tradeDate='20230326', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27502.2, self.close=27495.2, self.high=27510.0, self.low=27495.2   
2023-03-26 16:20:07,920:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230326   155500    155959  1679817599  ...  27471.4  0.000761   1631    5
1632  20230326   160000    160459  1679817899  ...  27491.2  0.000167   1632    0
1633  20230326   160500    160959  1679818199  ...  27489.6  0.000211   1633    1
1634  20230326   161000    161459  1679818499  ...  27499.0 -0.000022   1634    2
1635  20230326   161500    161959  1679818799  ...  27495.2 -0.000255   1635    3

[5 rows x 11 columns]
2023-03-26 16:20:07,921:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [26/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=428, self.factor=0.5062052450250255, self.count=34867 

self.closeSec=1679819099, self.tradeDate='20230326', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27495.3, self.close=27492.0, self.high=27502.0, self.low=27492.0 
2023-03-26 16:25:01,504:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679819099, self.tradeDate='20230326', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27495.3, self.close=27492.0, self.high=27502.0, self.low=27492.0   
2023-03-26 16:25:01,546:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230326   160000    160459  1679817899  ...  27491.2  0.000167   1632    0
1633  20230326   160500    160959  1679818199  ...  27489.6  0.000211   1633    1
1634  20230326   161000    161459  1679818499  ...  27499.0 -0.000022   1634    2
1635  20230326   161500    161959  1679818799  ...  27495.2 -0.000255   1635    3
1636  20230326   162000    162459  1679819099  ...  27492.0 -0.000116   1636    4

[5 rows x 11 columns]
2023-03-26 16:25:01,550:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-26 16:00:35,099:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230326    132959  27506.0  ...  50.416667  0.480166  0.477867
5787  20230326    135959  27472.0  ...  50.833333  0.489878  0.472048
5788  20230326    142959  27531.7  ...  50.833333  0.483178  0.471036
5789  20230326    145959  27488.2  ...  50.833333  0.482357  0.470630
5790  20230326    152959  27482.9  ...  51.250000  0.486569  0.467702

[5 rows x 33 columns]
0.5239852398523985
acc is : 0.5239852398523985
2023-03-26 16:00:35,299:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.517640  0.482360       1  ...  1.067665   1.0    0.0  1.112725
538     0  0.546129  0.453871       0  ...  1.065978   1.0    0.0  1.110967
539     0  0.521264  0.478736       0  ...  1.065773   1.0    0.0  1.110752
540     0  0.530561  0.469439       1  ...  1.066746   1.0    0.0  1.111767
541     0  0.539076  0.460924       0  ...  1.066141   1.0    0.0  1.111136

[5 rows x 10 columns]
2023-03-26 16:00:35,340:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.517734  0.482266       1  ...  1.051117   1.0    0.0  1.113476
46     0  0.546048  0.453952       0  ...  1.015496   1.0    0.0  1.114046
47     0  0.521325  0.478675       0  ...  1.049254   1.0    0.0  1.113331
48     0  0.530640  0.469360       1  ...  1.016228   1.0    0.0  1.127220
49     0  0.539076  0.460924       0  ...  1.066141   1.0    0.0  1.111136

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230326   155000    155959  1679817599  27479.2  27492.4  0.000477
2023-03-26 16:00:02,155:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [26/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17432 

self.closeSec=1679818199, self.tradeDate='20230326', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27492.4', self.close='27502.8'
2023-03-26 16:10:01,628:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679818199, self.tradeDate='20230326', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27492.4', self.close='27502.8'
2023-03-26 16:10:01,704:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230326   152000    152959  1679815799  27487.8    27508  0.000735
525  20230326   153000    153959  1679816399  27507.9  27485.3 -0.000825
526  20230326   154000    154959  1679816999  27485.4  27479.3 -0.000218
527  20230326   155000    155959  1679817599  27479.2  27492.4  0.000477
528  20230326   160000    160959  1679818199  27492.4  27502.8  0.000378
2023-03-26 16:10:01,704:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17433 

self.closeSec=1679818799, self.tradeDate='20230326', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27502.9', self.close='27495.2'
127.0.0.1 - - [26/Mar/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-03-26 16:20:07,771:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679818799, self.tradeDate='20230326', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27502.9', self.close='27495.2'
2023-03-26 16:20:08,460:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230326   153000    153959  1679816399  27507.9  27485.3 -0.000825
526  20230326   154000    154959  1679816999  27485.4  27479.3 -0.000218
527  20230326   155000    155959  1679817599  27479.2  27492.4  0.000477
528  20230326   160000    160959  1679818199  27492.4  27502.8  0.000378
529  20230326   161000    161959  1679818799  27502.9  27495.2 -0.000276
2023-03-26 16:20:08,461:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230326   155000    155959  1679817599  27479.2  27492.4
2023-03-26 16:00:02,168:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [26/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17433 

self.closeSec=1679818199, self.tradeDate='20230326', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27492.4', self.close='27502.8'
2023-03-26 16:10:01,663:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679818199, self.tradeDate='20230326', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27492.4', self.close='27502.8'
2023-03-26 16:10:01,712:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230326   152000    152959  1679815799  27487.8    27508
17517  20230326   153000    153959  1679816399  27507.9  27485.3
17518  20230326   154000    154959  1679816999  27485.4  27479.3
17519  20230326   155000    155959  1679817599  27479.2  27492.4
17520  20230326   160000    160959  1679818199  27492.4  27502.8
2023-03-26 16:10:01,712:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17434 

self.closeSec=1679818799, self.tradeDate='20230326', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27502.9', self.close='27495.2'
127.0.0.1 - - [26/Mar/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-03-26 16:20:10,213:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679818799, self.tradeDate='20230326', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27502.9', self.close='27495.2'
2023-03-26 16:20:10,278:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230326   153000    153959  1679816399  27507.9  27485.3
17518  20230326   154000    154959  1679816999  27485.4  27479.3
17519  20230326   155000    155959  1679817599  27479.2  27492.4
17520  20230326   160000    160959  1679818199  27492.4  27502.8
17521  20230326   161000    161959  1679818799  27502.9  27495.2
2023-03-26 16:20:10,279:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230326   155000    155959  1679817599  27479.2  27492.4
2023-03-26 16:00:02,162:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [26/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17433 

self.closeSec=1679818199, self.tradeDate='20230326', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27492.4', self.close='27502.8'
2023-03-26 16:10:01,603:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679818199, self.tradeDate='20230326', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27492.4', self.close='27502.8'
2023-03-26 16:10:01,691:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230326   152000    152959  1679815799  27487.8    27508
12189  20230326   153000    153959  1679816399  27507.9  27485.3
12190  20230326   154000    154959  1679816999  27485.4  27479.3
12191  20230326   155000    155959  1679817599  27479.2  27492.4
12192  20230326   160000    160959  1679818199  27492.4  27502.8
2023-03-26 16:10:01,691:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17434 

self.closeSec=1679818799, self.tradeDate='20230326', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27502.9', self.close='27495.2'
127.0.0.1 - - [26/Mar/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-03-26 16:20:09,859:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679818799, self.tradeDate='20230326', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27502.9', self.close='27495.2'
2023-03-26 16:20:10,093:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230326   153000    153959  1679816399  27507.9  27485.3
12190  20230326   154000    154959  1679816999  27485.4  27479.3
12191  20230326   155000    155959  1679817599  27479.2  27492.4
12192  20230326   160000    160959  1679818199  27492.4  27502.8
12193  20230326   161000    161959  1679818799  27502.9  27495.2
2023-03-26 16:20:10,094:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=30298
self.closeSec=1679818799, self.tradeDate='20230326', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27502.2, self.close=27495.2, self.high=27510.0, self.low=27495.2, self.vol=272.359, self.amt=7490375.3009 
127.0.0.1 - - [26/Mar/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-03-26 16:20:05,000:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230326   155500    155959  ...         0.0        0.0       0
5952  20230326   160000    160459  ...         0.0        0.0       0
5953  20230326   160500    160959  ...         0.0        0.0       0
5954  20230326   161000    161459  ...         0.0        0.0       0
5955  20230326   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-26 16:20:05,022:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679818799, self.tradeDate='20230326', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27502.2, self.close=27495.2, self.high=27510.0, self.low=27495.2, self.vol=272.359, self.amt=7490375.3009, ukdf['pct'].iloc[-1]=-0.000255 , ukdf['amount'].iloc[-1]=7490375.3009, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=30299
self.closeSec=1679819099, self.tradeDate='20230326', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27495.3, self.close=27492.0, self.high=27502.0, self.low=27492.0, self.vol=245.678, self.amt=6755026.3015 
127.0.0.1 - - [26/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-03-26 16:25:01,613:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230326   160000    160459  ...         0.0        0.0       0
5953  20230326   160500    160959  ...         0.0        0.0       0
5954  20230326   161000    161459  ...         0.0        0.0       0
5955  20230326   161500    161959  ...         0.0        0.0       0
5956  20230326   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-26 16:25:01,614:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679819099, self.tradeDate='20230326', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27495.3, self.close=27492.0, self.high=27502.0, self.low=27492.0, self.vol=245.678, self.amt=6755026.3015, ukdf['pct'].iloc[-1]=-0.000116 , ukdf['amount'].iloc[-1]=6755026.3015, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230326   040000    075959  1679788799  ...    721  0.041372 -1.584813    -1.0
722  20230326   080000    115959  1679803199  ...    722  0.042398 -1.541904    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '30762.7968', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27518.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [26/Mar/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1507151.9559834, self.flagDict['side']='sell', self.tradeCount=27, self.count=726
self.closeSec=1679817599, self.tradeDate='20230326', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27517.2, self.close=27492.4, self.high=27560.0, self.low=27444.7, self.vol=25075.949, self.amt=689475205.5954 
2023-03-26 16:00:01,984:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1679817599, self.tradeDate='20230326', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=27517.2, self.close=27492.4, self.high=27560.0, self.low=27444.7, self.vol=25075.949, self.amt=689475205.5954 
2023-03-26 16:00:02,013:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230325   200000    235959  ...  74885.923  2.063696e+09  0.006832
720  20230326   000000    035959  ...  83903.179  2.300180e+09 -0.016415
721  20230326   040000    075959  ...  46178.862  1.264141e+09  0.009853
722  20230326   080000    115959  ...  38527.410  1.061184e+09  0.002550
723  20230326   120000    155959  ...  25075.949  6.894752e+08 -0.000905

[5 rows x 11 columns]
2023-03-26 16:00:04,349:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230325   200000    235959  1679759999  ...    719  0.033079 -1.693519    -1.0
720  20230326   000000    035959  1679774399  ...    720  0.038373 -1.634950    -1.0
721  20230326   040000    075959  1679788799  ...    721  0.041372 -1.584813    -1.0
722  20230326   080000    115959  1679803199  ...    722  0.042398 -1.541904    -1.0
723  20230326   120000    155959  1679817599  ...    723  0.037986 -1.514059    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '32153.7822', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27492.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


