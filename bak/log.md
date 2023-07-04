# 20230704 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=14752
self.closeSec=1688458799, self.tradeDate='20230704', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30948.1, self.close=30940.5, self.high=30948.1, self.low=30919.5, self.vol=524.199, self.amt=16213297.9369 
127.0.0.1 - - [04/Jul/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-07-04 16:20:08,121:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230704   155500    155959  ...         0.0        0.0       0
5952  20230704   160000    160459  ...         0.0        0.0       0
5953  20230704   160500    160959  ...         0.0        0.0       0
5954  20230704   161000    161459  ...         0.0        0.0       0
5955  20230704   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-04 16:20:08,151:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688458799, self.tradeDate='20230704', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30948.1, self.close=30940.5, self.high=30948.1, self.low=30919.5, self.vol=524.199, self.amt=16213297.9369, ukdf['pct'].iloc[-1]=-0.000191 , ukdf['amount'].iloc[-1]=16213297.9369, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-56756.8056', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30940.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=14753
self.closeSec=1688459099, self.tradeDate='20230704', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30940.4, self.close=30960.7, self.high=30968.6, self.low=30940.4, self.vol=590.906, self.amt=18291607.7845 
127.0.0.1 - - [04/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-07-04 16:25:00,786:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230704   160000    160459  ...         0.0        0.0       0
5953  20230704   160500    160959  ...         0.0        0.0       0
5954  20230704   161000    161459  ...         0.0        0.0       0
5955  20230704   161500    161959  ...         0.0        0.0       0
5956  20230704   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-04 16:25:00,786:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688459099, self.tradeDate='20230704', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30940.4, self.close=30960.7, self.high=30968.6, self.low=30940.4, self.vol=590.906, self.amt=18291607.7845, ukdf['pct'].iloc[-1]=0.000653 , ukdf['amount'].iloc[-1]=18291607.7845, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-57098.11140465564', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30965.00853114', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1688458799, self.tradeDate='20230704', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30948.1, self.close=30940.5, self.high=30948.1, self.low=30919.5 
127.0.0.1 - - [04/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-04 16:20:05,367:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688458799, self.tradeDate='20230704', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30948.1, self.close=30940.5, self.high=30948.1, self.low=30919.5   
2023-07-04 16:20:07,196:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230704   155500    155959  1688457599  ...  30888.6 -0.000372   1631    5
1632  20230704   160000    160459  1688457899  ...  30889.5  0.001171   1632    0
1633  20230704   160500    160959  1688458199  ...  30927.9  0.000217   1633    1
1634  20230704   161000    161459  1688458499  ...  30938.6  0.000042   1634    2
1635  20230704   161500    161959  1688458799  ...  30919.5 -0.000191   1635    3

[5 rows x 11 columns]
2023-07-04 16:20:07,209:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [04/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=190, self.factor=0.3224369650278104, self.count=14755 

self.closeSec=1688459099, self.tradeDate='20230704', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30940.4, self.close=30960.7, self.high=30968.6, self.low=30940.4 
2023-07-04 16:25:00,794:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688459099, self.tradeDate='20230704', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30940.4, self.close=30960.7, self.high=30968.6, self.low=30940.4   
2023-07-04 16:25:00,832:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230704   160000    160459  1688457899  ...  30889.5  0.001171   1632    0
1633  20230704   160500    160959  1688458199  ...  30927.9  0.000217   1633    1
1634  20230704   161000    161459  1688458499  ...  30938.6  0.000042   1634    2
1635  20230704   161500    161959  1688458799  ...  30919.5 -0.000191   1635    3
1636  20230704   162000    162459  1688459099  ...  30940.4  0.000653   1636    4

[5 rows x 11 columns]
2023-07-04 16:25:00,832:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-04 16:00:20,222:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230704    132959  31043.6  ...  52.916667  0.549371  0.282543
5787  20230704    135959  31043.8  ...  52.916667  0.528901  0.298500
5788  20230704    142959  30958.9  ...  52.916667  0.544484  0.307307
5789  20230704    145959  31035.3  ...  52.500000  0.533811  0.319132
5790  20230704    152959  30990.0  ...  52.500000  0.537880  0.328582

[5 rows x 33 columns]
0.5202952029520295
acc is : 0.5202952029520295
2023-07-04 16:00:20,341:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.496249  0.503751       0  ...  0.949114   1.0    0.0  1.031949
538     1  0.484588  0.515412       1  ...  0.951453   1.0    0.0  1.034493
539     0  0.515938  0.484062       0  ...  0.950067   1.0    0.0  1.032986
540     0  0.504910  0.495090       1  ...  0.950677   1.0    0.0  1.033649
541     0  0.519060  0.480940       0  ...  0.947372   1.0    0.0  1.030056

[5 rows x 10 columns]
2023-07-04 16:00:20,365:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.496195  0.503805       0  ...  0.949114   1.0    0.0  1.034774
46     1  0.484140  0.515860       1  ...  0.951453   1.0    0.0  1.035338
47     0  0.516021  0.483979       0  ...  0.950067   1.0    0.0  1.037326
48     0  0.504388  0.495612       1  ...  0.950677   1.0    0.0  1.033484
49     0  0.519060  0.480940       0  ...  0.947372   1.0    0.0  1.030056

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.53', 'enterprice': '30560', 'countrevence': '0', 'unrealprofit': '8904.864', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30908.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230704   155000    155959  1688457599  30927.2  30902.3 -0.000802
2023-07-04 16:00:02,131:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [04/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7376 

self.closeSec=1688458199, self.tradeDate='20230704', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30902.2', self.close='30945'
2023-07-04 16:10:01,110:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688458199, self.tradeDate='20230704', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30902.2', self.close='30945'
2023-07-04 16:10:01,146:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230704   152000    152959  1688455799  31007.2    31010  0.000087
525  20230704   153000    153959  1688456399  31010.1  30992.4 -0.000568
526  20230704   154000    154959  1688456999  30992.4  30927.1 -0.002107
527  20230704   155000    155959  1688457599  30927.2  30902.3 -0.000802
528  20230704   160000    160959  1688458199  30902.2    30945  0.001382
2023-07-04 16:10:01,146:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7377 

self.closeSec=1688458799, self.tradeDate='20230704', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30945.1', self.close='30940.4'
127.0.0.1 - - [04/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-04 16:20:07,937:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688458799, self.tradeDate='20230704', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30945.1', self.close='30940.4'
2023-07-04 16:20:08,771:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230704   153000    153959  1688456399  31010.1  30992.4 -0.000568
526  20230704   154000    154959  1688456999  30992.4  30927.1 -0.002107
527  20230704   155000    155959  1688457599  30927.2  30902.3 -0.000802
528  20230704   160000    160959  1688458199  30902.2    30945  0.001382
529  20230704   161000    161959  1688458799  30945.1  30940.4 -0.000149
2023-07-04 16:20:08,781:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230704   155000    155959  1688457599  30927.2  30902.3
2023-07-04 16:00:02,177:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7379 

self.closeSec=1688458199, self.tradeDate='20230704', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30902.2', self.close='30945'
127.0.0.1 - - [04/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-07-04 16:10:01,117:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688458199, self.tradeDate='20230704', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30902.2', self.close='30945'
2023-07-04 16:10:01,148:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230704   152000    152959  1688455799  31007.2    31010
17517  20230704   153000    153959  1688456399  31010.1  30992.4
17518  20230704   154000    154959  1688456999  30992.4  30927.1
17519  20230704   155000    155959  1688457599  30927.2  30902.3
17520  20230704   160000    160959  1688458199  30902.2    30945
2023-07-04 16:10:01,148:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7380 

self.closeSec=1688458799, self.tradeDate='20230704', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30945.1', self.close='30940.4'
127.0.0.1 - - [04/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-04 16:20:10,104:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688458799, self.tradeDate='20230704', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30945.1', self.close='30940.4'
2023-07-04 16:20:10,257:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230704   153000    153959  1688456399  31010.1  30992.4
17518  20230704   154000    154959  1688456999  30992.4  30927.1
17519  20230704   155000    155959  1688457599  30927.2  30902.3
17520  20230704   160000    160959  1688458199  30902.2    30945
17521  20230704   161000    161959  1688458799  30945.1  30940.4
2023-07-04 16:20:10,258:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230704   155000    155959  1688457599  30927.2  30902.3
2023-07-04 16:00:02,177:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7379 

self.closeSec=1688458199, self.tradeDate='20230704', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30902.2', self.close='30945'
2023-07-04 16:10:01,127:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688458199, self.tradeDate='20230704', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30902.2', self.close='30945'
127.0.0.1 - - [04/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-07-04 16:10:01,152:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230704   152000    152959  1688455799  31007.2    31010
12189  20230704   153000    153959  1688456399  31010.1  30992.4
12190  20230704   154000    154959  1688456999  30992.4  30927.1
12191  20230704   155000    155959  1688457599  30927.2  30902.3
12192  20230704   160000    160959  1688458199  30902.2    30945
2023-07-04 16:10:01,154:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7380 

self.closeSec=1688458799, self.tradeDate='20230704', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30945.1', self.close='30940.4'
127.0.0.1 - - [04/Jul/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-07-04 16:20:09,641:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688458799, self.tradeDate='20230704', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30945.1', self.close='30940.4'
2023-07-04 16:20:10,001:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230704   153000    153959  1688456399  31010.1  30992.4
12190  20230704   154000    154959  1688456999  30992.4  30927.1
12191  20230704   155000    155959  1688457599  30927.2  30902.3
12192  20230704   160000    160959  1688458199  30902.2    30945
12193  20230704   161000    161959  1688458799  30945.1  30940.4
2023-07-04 16:20:10,002:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=14752
self.closeSec=1688458799, self.tradeDate='20230704', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30948.1, self.close=30940.5, self.high=30948.1, self.low=30919.5, self.vol=524.199, self.amt=16213297.9369 
127.0.0.1 - - [04/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-04 16:20:08,132:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230704   155500    155959  ...         0.0        0.0       0
5952  20230704   160000    160459  ...         0.0        0.0       0
5953  20230704   160500    160959  ...         0.0        0.0       0
5954  20230704   161000    161459  ...         0.0        0.0       0
5955  20230704   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-04 16:20:08,173:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688458799, self.tradeDate='20230704', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30948.1, self.close=30940.5, self.high=30948.1, self.low=30919.5, self.vol=524.199, self.amt=16213297.9369, ukdf['pct'].iloc[-1]=-0.000191 , ukdf['amount'].iloc[-1]=16213297.9369, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '152148.1065', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30940.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=14753
self.closeSec=1688459099, self.tradeDate='20230704', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30940.4, self.close=30960.7, self.high=30968.6, self.low=30940.4, self.vol=590.906, self.amt=18291607.7845 
127.0.0.1 - - [04/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-07-04 16:25:00,844:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230704   160000    160459  ...         0.0        0.0       0
5953  20230704   160500    160959  ...         0.0        0.0       0
5954  20230704   161000    161459  ...         0.0        0.0       0
5955  20230704   161500    161959  ...         0.0        0.0       0
5956  20230704   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-04 16:25:00,845:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688459099, self.tradeDate='20230704', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30940.4, self.close=30960.7, self.high=30968.6, self.low=30940.4, self.vol=590.906, self.amt=18291607.7845, ukdf['pct'].iloc[-1]=0.000653 , ukdf['amount'].iloc[-1]=18291607.7845, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '153058.37785507074', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30965.00853114', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230704   040000    075959  1688428799  ...    721  0.003309 -1.078267    -1.0
722  20230704   080000    115959  1688443199  ...    722  0.013331 -1.032518    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '-25593.99974580924', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '31187.47607843', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1634064.775524, self.flagDict['side']='sell', self.tradeCount=8, self.count=307
self.closeSec=1688457599, self.tradeDate='20230704', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=31189.8, self.close=30902.3, self.high=31210.7, self.low=30860.0, self.vol=53472.779, self.amt=1658423957.01444 
127.0.0.1 - - [04/Jul/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-07-04 16:00:01,721:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1688457599, self.tradeDate='20230704', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=31189.8, self.close=30902.3, self.high=31210.7, self.low=30860.0, self.vol=53472.779, self.amt=1658423957.01444 
2023-07-04 16:00:01,743:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230703   200000    235959  ...  104314.045  3.220393e+09  0.014340
720  20230704   000000    035959  ...  115662.573  3.598670e+09  0.006291
721  20230704   040000    075959  ...   56721.250  1.764470e+09 -0.003363
722  20230704   080000    115959  ...   43191.597  1.347972e+09  0.001310
723  20230704   120000    155959  ...   53472.779  1.658424e+09 -0.009218

[5 rows x 11 columns]
2023-07-04 16:00:03,064:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230703   200000    235959  1688399999  ...    719  0.000007 -1.130948    -1.0
720  20230704   000000    035959  1688414399  ...    720  0.000231 -1.107635    -1.0
721  20230704   040000    075959  1688428799  ...    721  0.003309 -1.078267    -1.0
722  20230704   080000    115959  1688443199  ...    722  0.013331 -1.032518    -1.0
723  20230704   120000    155959  1688457599  ...    723  0.022771 -0.989740    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '-10375.14476762904', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30901.77256078', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


