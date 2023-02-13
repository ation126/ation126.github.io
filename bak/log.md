# 20230214 00:36:12

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [14/Feb/2023 00:30:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=22590
self.closeSec=1676305799, self.tradeDate='20230214', self.openTime='002500', self.closeTime='002959', self.symbol='BTCUSDT', self.open=21586.0, self.close=21521.4, self.high=21590.7, self.low=21500.0, self.vol=5736.519, self.amt=123516867.8655 
2023-02-14 00:30:02,000:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5761  20230214   000500    000959  ...         0.0        0.0       0
5762  20230214   001000    001459  ...         0.0        0.0       0
5763  20230214   001500    001959  ...         0.0        0.0       0
5764  20230214   002000    002459  ...         0.0        0.0       0
5765  20230214   002500    002959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-14 00:30:02,006:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676305799, self.tradeDate='20230214', self.openTime='002500', self.closeTime='002959',self.symbol='BTCUSDT',self.open=21586.0, self.close=21521.4, self.high=21590.7, self.low=21500.0, self.vol=5736.519, self.amt=123516867.8655, ukdf['pct'].iloc[-1]=-0.002988 , ukdf['amount'].iloc[-1]=123516867.8655, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5765, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-300555.0496', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21523.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=22591
self.closeSec=1676306099, self.tradeDate='20230214', self.openTime='003000', self.closeTime='003459', self.symbol='BTCUSDT', self.open=21521.4, self.close=21484.0, self.high=21540.8, self.low=21462.4, self.vol=7389.753, self.amt=158823043.6314 
127.0.0.1 - - [14/Feb/2023 00:35:01] "POST / HTTP/1.1" 200 -
2023-02-14 00:35:01,661:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5762  20230214   001000    001459  ...         0.0        0.0       0
5763  20230214   001500    001959  ...         0.0        0.0       0
5764  20230214   002000    002459  ...         0.0        0.0       0
5765  20230214   002500    002959  ...         0.0        0.0       0
5766  20230214   003000    003459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-14 00:35:01,662:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676306099, self.tradeDate='20230214', self.openTime='003000', self.closeTime='003459',self.symbol='BTCUSDT',self.open=21521.4, self.close=21484.0, self.high=21540.8, self.low=21462.4, self.vol=7389.753, self.amt=158823043.6314, ukdf['pct'].iloc[-1]=-0.001738 , ukdf['amount'].iloc[-1]=158823043.6314, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5766, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-298141.992', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21483.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

1444  20230214   002000    002459  1676305499  ...  21581.4 -0.000278   1444    4
1445  20230214   002500    002959  1676305799  ...  21500.0 -0.002988   1445    5

[5 rows x 11 columns]
2023-02-14 00:30:01,708:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-02-14 00:30:01,926:INFO:factorcheck2:main.py:145:handleKline:185239: df_panel.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...       pct  index  idx    factor
197  20230213   222500    222959  1676298599  ... -0.001260   1709    5  0.571410
198  20230213   225500    225959  1676300399  ...  0.000425   1715    5  0.573027
199  20230213   232500    232959  1676302199  ...  0.000435   1721    5  0.575982
200  20230213   235500    235959  1676303999  ... -0.000264   1727    5  0.582630
201  20230214   002500    002959  1676305799  ... -0.002988   1445    5  0.590528

[5 rows x 12 columns]
127.0.0.1 - - [14/Feb/2023 00:35:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=49, self.factor=0.5905277831157866, self.count=23157 

self.closeSec=1676306099, self.tradeDate='20230214', self.openTime='003000', self.closeTime='003459', self.symbol='BTCUSDT', self.open=21521.4, self.close=21484.0, self.high=21540.8, self.low=21462.4 
2023-02-14 00:35:01,519:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676306099, self.tradeDate='20230214', self.openTime='003000', self.closeTime='003459',self.symbol='BTCUSDT',self.open=21521.4, self.close=21484.0, self.high=21540.8, self.low=21462.4   
2023-02-14 00:35:01,561:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1442  20230214   001000    001459  1676304899  ...  21600.5 -0.000079   1442    2
1443  20230214   001500    001959  1676305199  ...  21581.9 -0.001364   1443    3
1444  20230214   002000    002459  1676305499  ...  21581.4 -0.000278   1444    4
1445  20230214   002500    002959  1676305799  ...  21500.0 -0.002988   1445    5
1446  20230214   003000    003459  1676306099  ...  21462.4 -0.001738   1446    0

[5 rows x 11 columns]
2023-02-14 00:35:01,562:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-14 00:30:32,626:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5755  20230213    215959  21610.1  ...  45.000000  0.440004  0.645420
5756  20230213    222959  21564.6  ...  45.000000  0.438105  0.653056
5757  20230213    225959  21556.4  ...  45.416667  0.468806  0.648564
5758  20230213    232959  21662.7  ...  45.416667  0.461806  0.647530
5759  20230213    235959  21633.8  ...  45.416667  0.443005  0.655328

[5 rows x 33 columns]
0.5287569573283859
acc is : 0.5287569573283859
2023-02-14 00:30:32,812:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
534     1  0.482090  0.517910       0  ...  1.009299  -1.0    0.0  0.906298
535     1  0.492121  0.507879       1  ...  1.004322  -1.0    0.0  0.910768
536     0  0.518048  0.481952       0  ...  1.005662  -1.0    0.0  0.909553
537     1  0.492175  0.507825       0  ...  1.009404  -1.0    0.0  0.906168
538     1  0.476760  0.523240       0  ...  1.010903  -1.0    0.0  0.904823

[5 rows x 10 columns]
2023-02-14 00:30:32,851:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.480399  0.519601       0  ...  1.009299  -1.0    0.0  0.905963
46     1  0.490317  0.509683       1  ...  1.004322  -1.0    0.0  0.910431
47     0  0.515726  0.484274       0  ...  1.005662  -1.0    0.0  0.908285
48     1  0.490350  0.509650       0  ...  1.009404  -1.0    0.0  0.906096
49     1  0.476760  0.523240       0  ...  1.010903  -1.0    0.0  0.904823

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.252', 'enterprice': '22924.6', 'countrevence': '0', 'unrealprofit': '45378.564', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21517.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

576  20230214   000000    000959  1676304599  21553.3  21623.1  0.003238
2023-02-14 00:10:01,837:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11577 

self.closeSec=1676305199, self.tradeDate='20230214', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='21623.2', self.close='21591.9'
127.0.0.1 - - [14/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-02-14 00:20:01,896:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676305199, self.tradeDate='20230214', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='21623.2', self.close='21591.9'
2023-02-14 00:20:01,920:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230213   233000    233959  1676302799  21633.8  21654.5  0.000957
574  20230213   234000    234959  1676303399  21654.5  21590.1 -0.002974
575  20230213   235000    235959  1676303999    21590  21553.3 -0.001704
576  20230214   000000    000959  1676304599  21553.3  21623.1  0.003238
577  20230214   001000    001959  1676305199  21623.2  21591.9 -0.001443
2023-02-14 00:20:01,920:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [14/Feb/2023 00:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11578 

self.closeSec=1676305799, self.tradeDate='20230214', self.openTime='002000', self.closeTime='002959', self.symbol='BTCUSDT', self.open='21592', self.close='21521.3'
2023-02-14 00:30:01,897:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676305799, self.tradeDate='20230214', self.openTime='002000', self.closeTime='002959',self.symbol='BTCUSDT',self.open='21592', self.close='21521.3'
2023-02-14 00:30:01,954:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
574  20230213   234000    234959  1676303399  21654.5  21590.1 -0.002974
575  20230213   235000    235959  1676303999    21590  21553.3 -0.001704
576  20230214   000000    000959  1676304599  21553.3  21623.1  0.003238
577  20230214   001000    001959  1676305199  21623.2  21591.9 -0.001443
578  20230214   002000    002959  1676305799    21592  21521.3 -0.003270
2023-02-14 00:30:01,954:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/percentile_regression_step2/log.txt ----- -----

127.0.0.1 - - [13/Feb/2023 23:30:01] "POST / HTTP/1.1" 200 -
2023-02-13 23:30:02,787:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/13 21:00:00  210000  21610.0  ...     NaN     NaN       0
145  2023/02/13 21:30:00  213000  21564.5  ...     NaN     NaN       0
146  2023/02/13 22:00:00  220000  21556.4  ...     NaN     NaN       0
147  2023/02/13 22:30:00  223000  21662.7  ...     NaN     NaN       0
148  2023/02/13 23:00:00  230000  21633.8  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [14/Feb/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-02-14 00:00:03,781:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/13 21:30:00  213000  21564.5  ...     NaN     NaN       0
145  2023/02/13 22:00:00  220000  21556.4  ...     NaN     NaN       0
146  2023/02/13 22:30:00  223000  21662.7  ...     NaN     NaN       0
147  2023/02/13 23:00:00  230000  21633.8  ...     NaN     NaN       0
148  2023/02/13 23:30:00  233000  21553.3  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [14/Feb/2023 00:30:01] "POST / HTTP/1.1" 200 -
2023-02-14 00:30:02,941:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/13 22:00:00  220000  21556.4  ...     NaN     NaN       0
145  2023/02/13 22:30:00  223000  21662.7  ...     NaN     NaN       0
146  2023/02/13 23:00:00  230000  21633.8  ...     NaN     NaN       0
147  2023/02/13 23:30:00  233000  21553.3  ...     NaN     NaN       0
148  2023/02/14 00:00:00  000000  21521.3  ...     NaN     NaN       0

[5 rows x 10 columns]


## /root/FIL/strategy/pyemd/log.txt ----- -----

17424  20230214   000000    000959  1676304599  21553.3  21623.1
2023-02-14 00:10:01,779:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [14/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11578 

self.closeSec=1676305199, self.tradeDate='20230214', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='21623.2', self.close='21591.9'
2023-02-14 00:20:01,906:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676305199, self.tradeDate='20230214', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='21623.2', self.close='21591.9'
2023-02-14 00:20:01,933:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230213   233000    233959  1676302799  21633.8  21654.5
17422  20230213   234000    234959  1676303399  21654.5  21590.1
17423  20230213   235000    235959  1676303999    21590  21553.3
17424  20230214   000000    000959  1676304599  21553.3  21623.1
17425  20230214   001000    001959  1676305199  21623.2  21591.9
2023-02-14 00:20:01,933:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [14/Feb/2023 00:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11579 

self.closeSec=1676305799, self.tradeDate='20230214', self.openTime='002000', self.closeTime='002959', self.symbol='BTCUSDT', self.open='21592', self.close='21521.3'
2023-02-14 00:30:01,932:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676305799, self.tradeDate='20230214', self.openTime='002000', self.closeTime='002959',self.symbol='BTCUSDT',self.open='21592', self.close='21521.3'
2023-02-14 00:30:01,989:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17422  20230213   234000    234959  1676303399  21654.5  21590.1
17423  20230213   235000    235959  1676303999    21590  21553.3
17424  20230214   000000    000959  1676304599  21553.3  21623.1
17425  20230214   001000    001959  1676305199  21623.2  21591.9
17426  20230214   002000    002959  1676305799    21592  21521.3
2023-02-14 00:30:01,990:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12240  20230214   000000    000959  1676304599  21553.3  21623.1
2023-02-14 00:10:01,854:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11578 

self.closeSec=1676305199, self.tradeDate='20230214', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='21623.2', self.close='21591.9'
127.0.0.1 - - [14/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-02-14 00:20:01,916:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676305199, self.tradeDate='20230214', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='21623.2', self.close='21591.9'
2023-02-14 00:20:01,925:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230213   233000    233959  1676302799  21633.8  21654.5
12238  20230213   234000    234959  1676303399  21654.5  21590.1
12239  20230213   235000    235959  1676303999    21590  21553.3
12240  20230214   000000    000959  1676304599  21553.3  21623.1
12241  20230214   001000    001959  1676305199  21623.2  21591.9
2023-02-14 00:20:01,925:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
127.0.0.1 - - [14/Feb/2023 00:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11579 

self.closeSec=1676305799, self.tradeDate='20230214', self.openTime='002000', self.closeTime='002959', self.symbol='BTCUSDT', self.open='21592', self.close='21521.3'
2023-02-14 00:30:01,927:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676305799, self.tradeDate='20230214', self.openTime='002000', self.closeTime='002959',self.symbol='BTCUSDT',self.open='21592', self.close='21521.3'
2023-02-14 00:30:01,964:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12238  20230213   234000    234959  1676303399  21654.5  21590.1
12239  20230213   235000    235959  1676303999    21590  21553.3
12240  20230214   000000    000959  1676304599  21553.3  21623.1
12241  20230214   001000    001959  1676305199  21623.2  21591.9
12242  20230214   002000    002959  1676305799    21592  21521.3
2023-02-14 00:30:01,964:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=18588
self.closeSec=1676305799, self.tradeDate='20230214', self.openTime='002500', self.closeTime='002959', self.symbol='BTCUSDT', self.open=21586.0, self.close=21521.4, self.high=21590.7, self.low=21500.0, self.vol=5736.519, self.amt=123516867.8655 
127.0.0.1 - - [14/Feb/2023 00:30:01] "POST / HTTP/1.1" 200 -
2023-02-14 00:30:01,723:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5761  20230214   000500    000959  ...         0.0        0.0       0
5762  20230214   001000    001459  ...         0.0        0.0       0
5763  20230214   001500    001959  ...         0.0        0.0       0
5764  20230214   002000    002459  ...         0.0        0.0       0
5765  20230214   002500    002959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-14 00:30:01,725:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676305799, self.tradeDate='20230214', self.openTime='002500', self.closeTime='002959',self.symbol='BTCUSDT',self.open=21586.0, self.close=21521.4, self.high=21590.7, self.low=21500.0, self.vol=5736.519, self.amt=123516867.8655, ukdf['pct'].iloc[-1]=-0.002988 , ukdf['amount'].iloc[-1]=123516867.8655, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5765, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=18589
self.closeSec=1676306099, self.tradeDate='20230214', self.openTime='003000', self.closeTime='003459', self.symbol='BTCUSDT', self.open=21521.4, self.close=21484.0, self.high=21540.8, self.low=21462.4, self.vol=7389.753, self.amt=158823043.6314 
127.0.0.1 - - [14/Feb/2023 00:35:01] "POST / HTTP/1.1" 200 -
2023-02-14 00:35:01,645:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5762  20230214   001000    001459  ...         0.0        0.0       0
5763  20230214   001500    001959  ...         0.0        0.0       0
5764  20230214   002000    002459  ...         0.0        0.0       0
5765  20230214   002500    002959  ...         0.0        0.0       0
5766  20230214   003000    003459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-14 00:35:01,645:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676306099, self.tradeDate='20230214', self.openTime='003000', self.closeTime='003459',self.symbol='BTCUSDT',self.open=21521.4, self.close=21484.0, self.high=21540.8, self.low=21462.4, self.vol=7389.753, self.amt=158823043.6314, ukdf['pct'].iloc[-1]=-0.001738 , ukdf['amount'].iloc[-1]=158823043.6314, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5766, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230213   120000    155959  1676275199  ...    723  0.793234  0.870017     1.0
724  20230213   160000    195959  1676289599  ...    724  0.624625 -0.005675     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.94', 'enterprice': '21730.2', 'countrevence': '0', 'unrealprofit': '-5702.432', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '21597.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [14/Feb/2023 00:00:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=932161.693212, self.flagDict['side']='buy', self.tradeCount=18, self.count=482
self.closeSec=1676303999, self.tradeDate='20230213', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=21595.9, self.close=21553.3, self.high=21688.0, self.low=21544.8, self.vol=76257.797, self.amt=1648761210.7731 
2023-02-14 00:00:02,927:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1676303999, self.tradeDate='20230213', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=21595.9, self.close=21553.3, self.high=21688.0, self.low=21544.8, self.vol=76257.797, self.amt=1648761210.7731 
2023-02-14 00:00:02,980:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230213   040000    075959  ...   76306.684  1.662002e+09 -0.009644
722  20230213   080000    115959  ...   67134.107  1.459458e+09  0.001369
723  20230213   120000    155959  ...   37460.868  8.178804e+08  0.002582
724  20230213   160000    195959  ...  140932.155  3.044415e+09 -0.011955
725  20230213   200000    235959  ...   76257.797  1.648761e+09 -0.001973

[5 rows x 11 columns]
2023-02-14 00:00:05,187:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230213   040000    075959  1676246399  ...    721  0.937283  1.627230     1.0
722  20230213   080000    115959  1676260799  ...    722  0.966171  1.733999     1.0
723  20230213   120000    155959  1676275199  ...    723  0.793234  0.870017     1.0
724  20230213   160000    195959  1676289599  ...    724  0.624625 -0.005675     NaN
725  20230213   200000    235959  1676303999  ...    725  0.615151 -0.080985     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.94', 'enterprice': '21730.2', 'countrevence': '0', 'unrealprofit': '-7449.7488623112', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '21556.70794452', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


