# 20230619 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=10432
self.closeSec=1687162799, self.tradeDate='20230619', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26423.6, self.close=26441.6, self.high=26443.5, self.low=26423.5, self.vol=528.842, self.amt=13979254.1403 
127.0.0.1 - - [19/Jun/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-06-19 16:20:08,080:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230619   155500    155959  ...         0.0        0.0       0
5952  20230619   160000    160459  ...         0.0        0.0       0
5953  20230619   160500    160959  ...         0.0        0.0       0
5954  20230619   161000    161459  ...         0.0        0.0       0
5955  20230619   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-19 16:20:08,114:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687162799, self.tradeDate='20230619', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26423.6, self.close=26441.6, self.high=26443.5, self.low=26423.5, self.vol=528.842, self.amt=13979254.1403, ukdf['pct'].iloc[-1]=0.000681 , ukdf['amount'].iloc[-1]=13979254.1403, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '5893.17621581304', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26441.72204396', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [19/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=10433
self.closeSec=1687163099, self.tradeDate='20230619', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26441.7, self.close=26442.1, self.high=26445.3, self.low=26430.0, self.vol=398.93, self.amt=10546722.9903 
2023-06-19 16:25:00,798:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230619   160000    160459  ...         0.0        0.0       0
5953  20230619   160500    160959  ...         0.0        0.0       0
5954  20230619   161000    161459  ...         0.0        0.0       0
5955  20230619   161500    161959  ...         0.0        0.0       0
5956  20230619   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-19 16:25:00,798:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687163099, self.tradeDate='20230619', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26441.7, self.close=26442.1, self.high=26445.3, self.low=26430.0, self.vol=398.93, self.amt=10546722.9903, ukdf['pct'].iloc[-1]=1.9e-05 , ukdf['amount'].iloc[-1]=10546722.9903, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '5873.9868', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26443.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1687162799, self.tradeDate='20230619', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26423.6, self.close=26441.6, self.high=26443.5, self.low=26423.5 
127.0.0.1 - - [19/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-19 16:20:05,110:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687162799, self.tradeDate='20230619', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26423.6, self.close=26441.6, self.high=26443.5, self.low=26423.5   
2023-06-19 16:20:06,800:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230619   155500    155959  1687161599  ...  26412.0 -0.000034   1631    5
1632  20230619   160000    160459  1687161899  ...  26408.1 -0.000163   1632    0
1633  20230619   160500    160959  1687162199  ...  26406.1 -0.000076   1633    1
1634  20230619   161000    161459  1687162499  ...  26400.3  0.000553   1634    2
1635  20230619   161500    161959  1687162799  ...  26423.5  0.000681   1635    3

[5 rows x 11 columns]
2023-06-19 16:20:06,809:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [19/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=117, self.factor=0.4954476171492869, self.count=10435 

self.closeSec=1687163099, self.tradeDate='20230619', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26441.7, self.close=26442.1, self.high=26445.3, self.low=26430.0 
2023-06-19 16:25:00,725:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687163099, self.tradeDate='20230619', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26441.7, self.close=26442.1, self.high=26445.3, self.low=26430.0   
2023-06-19 16:25:00,770:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230619   160000    160459  1687161899  ...  26408.1 -0.000163   1632    0
1633  20230619   160500    160959  1687162199  ...  26406.1 -0.000076   1633    1
1634  20230619   161000    161459  1687162499  ...  26400.3  0.000553   1634    2
1635  20230619   161500    161959  1687162799  ...  26423.5  0.000681   1635    3
1636  20230619   162000    162459  1687163099  ...  26430.0  0.000019   1636    4

[5 rows x 11 columns]
2023-06-19 16:25:00,773:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-19 16:00:18,481:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230619    132959  26418.0  ...  52.916667  0.509868  0.594998
5787  20230619    135959  26421.9  ...  53.333333  0.517749  0.591500
5788  20230619    142959  26449.8  ...  52.916667  0.512505  0.590660
5789  20230619    145959  26432.4  ...  52.500000  0.508188  0.591868
5790  20230619    152959  26418.0  ...  52.500000  0.503498  0.595154

[5 rows x 33 columns]
0.577490774907749
acc is : 0.577490774907749
2023-06-19 16:00:18,586:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.500385  0.499615       1  ...  1.035390   1.0    0.0  1.002809
538     0  0.509760  0.490240       0  ...  1.034708   1.0    0.0  1.002150
539     0  0.501457  0.498543       0  ...  1.034149   1.0    0.0  1.001608
540     0  0.503216  0.496784       0  ...  1.033542   1.0    0.0  1.001020
541     1  0.498600  0.501400       1  ...  1.034039   1.0    0.0  1.001501

[5 rows x 10 columns]
2023-06-19 16:00:18,608:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.500550  0.499450       1  ...  1.035390   1.0    0.0  1.007063
46     0  0.509990  0.490010       0  ...  1.034708   1.0    0.0  1.005218
47     0  0.501520  0.498480       0  ...  1.034149   1.0    0.0  1.003502
48     0  0.503379  0.496621       0  ...  1.033542   1.0    0.0  1.001502
49     1  0.498600  0.501400       1  ...  1.034039   1.0    0.0  1.001501

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.127', 'enterprice': '25424', 'countrevence': '0', 'unrealprofit': '27857.01495433483', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26414.40121429', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230619   155000    155959  1687161599    26423  26415.3 -0.000295
2023-06-19 16:00:02,082:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5216 

self.closeSec=1687162199, self.tradeDate='20230619', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26415.2', self.close='26409'
2023-06-19 16:10:01,117:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687162199, self.tradeDate='20230619', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26415.2', self.close='26409'
127.0.0.1 - - [19/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-06-19 16:10:01,156:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230619   152000    152959  1687159799    26400  26402.6  0.000098
525  20230619   153000    153959  1687160399  26402.5  26398.1 -0.000170
526  20230619   154000    154959  1687160999    26398  26423.1  0.000947
527  20230619   155000    155959  1687161599    26423  26415.3 -0.000295
528  20230619   160000    160959  1687162199  26415.2    26409 -0.000238
2023-06-19 16:10:01,156:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5217 

self.closeSec=1687162799, self.tradeDate='20230619', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26408.9', self.close='26441.6'
127.0.0.1 - - [19/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-19 16:20:07,661:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687162799, self.tradeDate='20230619', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26408.9', self.close='26441.6'
2023-06-19 16:20:08,490:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230619   153000    153959  1687160399  26402.5  26398.1 -0.000170
526  20230619   154000    154959  1687160999    26398  26423.1  0.000947
527  20230619   155000    155959  1687161599    26423  26415.3 -0.000295
528  20230619   160000    160959  1687162199  26415.2    26409 -0.000238
529  20230619   161000    161959  1687162799  26408.9  26441.6  0.001234
2023-06-19 16:20:08,499:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230619   155000    155959  1687161599    26423  26415.3
2023-06-19 16:00:02,093:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5219 

self.closeSec=1687162199, self.tradeDate='20230619', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26415.2', self.close='26409'
2023-06-19 16:10:01,147:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687162199, self.tradeDate='20230619', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26415.2', self.close='26409'
127.0.0.1 - - [19/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-06-19 16:10:01,161:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230619   152000    152959  1687159799    26400  26402.6
17517  20230619   153000    153959  1687160399  26402.5  26398.1
17518  20230619   154000    154959  1687160999    26398  26423.1
17519  20230619   155000    155959  1687161599    26423  26415.3
17520  20230619   160000    160959  1687162199  26415.2    26409
2023-06-19 16:10:01,161:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5220 

self.closeSec=1687162799, self.tradeDate='20230619', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26408.9', self.close='26441.6'
127.0.0.1 - - [19/Jun/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-06-19 16:20:10,125:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687162799, self.tradeDate='20230619', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26408.9', self.close='26441.6'
2023-06-19 16:20:10,271:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230619   153000    153959  1687160399  26402.5  26398.1
17518  20230619   154000    154959  1687160999    26398  26423.1
17519  20230619   155000    155959  1687161599    26423  26415.3
17520  20230619   160000    160959  1687162199  26415.2    26409
17521  20230619   161000    161959  1687162799  26408.9  26441.6
2023-06-19 16:20:10,272:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230619   155000    155959  1687161599    26423  26415.3
2023-06-19 16:00:02,102:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [19/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5219 

self.closeSec=1687162199, self.tradeDate='20230619', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26415.2', self.close='26409'
2023-06-19 16:10:01,127:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687162199, self.tradeDate='20230619', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26415.2', self.close='26409'
2023-06-19 16:10:01,152:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230619   152000    152959  1687159799    26400  26402.6
12189  20230619   153000    153959  1687160399  26402.5  26398.1
12190  20230619   154000    154959  1687160999    26398  26423.1
12191  20230619   155000    155959  1687161599    26423  26415.3
12192  20230619   160000    160959  1687162199  26415.2    26409
2023-06-19 16:10:01,152:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5220 

self.closeSec=1687162799, self.tradeDate='20230619', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26408.9', self.close='26441.6'
127.0.0.1 - - [19/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-19 16:20:09,604:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687162799, self.tradeDate='20230619', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26408.9', self.close='26441.6'
2023-06-19 16:20:10,001:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230619   153000    153959  1687160399  26402.5  26398.1
12190  20230619   154000    154959  1687160999    26398  26423.1
12191  20230619   155000    155959  1687161599    26423  26415.3
12192  20230619   160000    160959  1687162199  26415.2    26409
12193  20230619   161000    161959  1687162799  26408.9  26441.6
2023-06-19 16:20:10,003:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=10432
self.closeSec=1687162799, self.tradeDate='20230619', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26423.6, self.close=26441.6, self.high=26443.5, self.low=26423.5, self.vol=528.842, self.amt=13979254.1403 
127.0.0.1 - - [19/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-19 16:20:08,061:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230619   155500    155959  ...         0.0        0.0       0
5952  20230619   160000    160459  ...         0.0        0.0       0
5953  20230619   160500    160959  ...         0.0        0.0       0
5954  20230619   161000    161459  ...         0.0        0.0       0
5955  20230619   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-19 16:20:08,101:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687162799, self.tradeDate='20230619', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26423.6, self.close=26441.6, self.high=26443.5, self.low=26423.5, self.vol=528.842, self.amt=13979254.1403, ukdf['pct'].iloc[-1]=0.000681 , ukdf['amount'].iloc[-1]=13979254.1403, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-14941.00556528164', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26441.72204396', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=10433
self.closeSec=1687163099, self.tradeDate='20230619', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26441.7, self.close=26442.1, self.high=26445.3, self.low=26430.0, self.vol=398.93, self.amt=10546722.9903 
127.0.0.1 - - [19/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-06-19 16:25:00,794:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230619   160000    160459  ...         0.0        0.0       0
5953  20230619   160500    160959  ...         0.0        0.0       0
5954  20230619   161000    161459  ...         0.0        0.0       0
5955  20230619   161500    161959  ...         0.0        0.0       0
5956  20230619   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-19 16:25:00,795:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687163099, self.tradeDate='20230619', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26441.7, self.close=26442.1, self.high=26445.3, self.low=26430.0, self.vol=398.93, self.amt=10546722.9903, ukdf['pct'].iloc[-1]=1.9e-05 , ukdf['amount'].iloc[-1]=10546722.9903, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-14889.8269', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26443.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230619   040000    075959  1687132799  ...    721  0.609595  1.127262     1.0
722  20230619   080000    115959  1687147199  ...    722  0.741899  1.777152     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.175', 'enterprice': '26590', 'countrevence': '0', 'unrealprofit': '-11488.845027372', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26389.05824176', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [19/Jun/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1518762.96675, self.flagDict['side']='buy', self.tradeCount=5, self.count=217
self.closeSec=1687161599, self.tradeDate='20230619', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26393.4, self.close=26415.3, self.high=26468.5, self.low=26354.8, self.vol=19572.1, self.amt=516997369.8337 
2023-06-19 16:00:01,620:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1687161599, self.tradeDate='20230619', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26393.4, self.close=26415.3, self.high=26468.5, self.low=26354.8, self.vol=19572.1, self.amt=516997369.8337 
2023-06-19 16:00:01,650:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230618   200000    235959  ...  33224.650  8.807581e+08  0.002227
720  20230619   000000    035959  ...  32518.414  8.648519e+08  0.003545
721  20230619   040000    075959  ...  80903.422  2.137750e+09 -0.011707
722  20230619   080000    115959  ...  32200.784  8.495103e+08  0.002423
723  20230619   120000    155959  ...  19572.100  5.169974e+08  0.000826

[5 rows x 11 columns]
2023-06-19 16:00:03,032:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230618   200000    235959  1687103999  ...    719  0.592151  1.080556     1.0
720  20230619   000000    035959  1687118399  ...    720  0.594437  1.072011     1.0
721  20230619   040000    075959  1687132799  ...    721  0.609595  1.127262     1.0
722  20230619   080000    115959  1687147199  ...    722  0.741899  1.777152     1.0
723  20230619   120000    155959  1687161599  ...    723  0.696930  1.516073     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.175', 'enterprice': '26590', 'countrevence': '0', 'unrealprofit': '-9994.19', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26415.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


