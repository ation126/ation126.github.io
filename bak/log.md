# 20230225 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [25/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=25756
self.closeSec=1677255599, self.tradeDate='20230225', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=23081.5, self.close=23062.1, self.high=23144.3, self.low=23062.1, self.vol=6927.194, self.amt=160046059.9332 
2023-02-25 00:20:01,948:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230224   235500    235959  ...         0.0        0.0       0
5760  20230225   000000    000459  ...         0.0        0.0       0
5761  20230225   000500    000959  ...         0.0        0.0       0
5762  20230225   001000    001459  ...         0.0        0.0       0
5763  20230225   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-25 00:20:01,951:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677255599, self.tradeDate='20230225', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=23081.5, self.close=23062.1, self.high=23144.3, self.low=23062.1, self.vol=6927.194, self.amt=160046059.9332, ukdf['pct'].iloc[-1]=-0.000914 , ukdf['amount'].iloc[-1]=160046059.9332, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-393184.39577922864', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23063.20713539', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=25757
self.closeSec=1677255899, self.tradeDate='20230225', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=23062.1, self.close=23057.4, self.high=23131.3, self.low=22965.0, self.vol=13064.922, self.amt=301259872.8381 
127.0.0.1 - - [25/Feb/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-02-25 00:25:01,739:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230225   000000    000459  ...         0.0        0.0       0
5761  20230225   000500    000959  ...         0.0        0.0       0
5762  20230225   001000    001459  ...         0.0        0.0       0
5763  20230225   001500    001959  ...         0.0        0.0       0
5764  20230225   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-25 00:25:01,741:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677255899, self.tradeDate='20230225', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=23062.1, self.close=23057.4, self.high=23131.3, self.low=22965.0, self.vol=13064.922, self.amt=301259872.8381, ukdf['pct'].iloc[-1]=-0.000204 , ukdf['amount'].iloc[-1]=301259872.8381, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-392985.3856', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23059.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1677255599, self.tradeDate='20230225', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=23081.5, self.close=23062.1, self.high=23144.3, self.low=23062.1 
2023-02-25 00:20:01,661:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677255599, self.tradeDate='20230225', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=23081.5, self.close=23062.1, self.high=23144.3, self.low=23062.1   
127.0.0.1 - - [25/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-02-25 00:20:01,720:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230224   235500    235959  1677254399  ...  23310.5 -0.002036   1727    5
1440  20230225   000000    000459  1677254699  ...  22976.8 -0.014642   1440    0
1441  20230225   000500    000959  1677254999  ...  22915.0  0.006910   1441    1
1442  20230225   001000    001459  1677255299  ...  23060.7 -0.003071   1442    2
1443  20230225   001500    001959  1677255599  ...  23062.1 -0.000914   1443    3

[5 rows x 11 columns]
2023-02-25 00:20:01,720:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6662316310914416, self.count=26323 

self.closeSec=1677255899, self.tradeDate='20230225', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=23062.1, self.close=23057.4, self.high=23131.3, self.low=22965.0 
2023-02-25 00:25:01,704:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677255899, self.tradeDate='20230225', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=23062.1, self.close=23057.4, self.high=23131.3, self.low=22965.0   
127.0.0.1 - - [25/Feb/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-02-25 00:25:01,739:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230225   000000    000459  1677254699  ...  22976.8 -0.014642   1440    0
1441  20230225   000500    000959  1677254999  ...  22915.0  0.006910   1441    1
1442  20230225   001000    001459  1677255299  ...  23060.7 -0.003071   1442    2
1443  20230225   001500    001959  1677255599  ...  23062.1 -0.000914   1443    3
1444  20230225   002000    002459  1677255899  ...  22965.0 -0.000204   1444    4

[5 rows x 11 columns]
2023-02-25 00:25:01,739:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-25 00:00:37,756:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230224    212959  23875.9  ...  50.000000  0.470503  0.629960
5803  20230224    215959  23886.5  ...  50.000000  0.448183  0.638349
5804  20230224    222959  23770.1  ...  49.583333  0.439749  0.652494
5805  20230224    225959  23723.8  ...  49.583333  0.456971  0.655266
5806  20230224    232959  23800.0  ...  49.166667  0.420210  0.670237

[5 rows x 33 columns]
0.5275735294117647
acc is : 0.5275735294117647
2023-02-25 00:00:37,928:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.525944  0.474056       0  ...  1.021525   1.0    0.0  1.087513
540     1  0.491825  0.508175       0  ...  1.019540   1.0    0.0  1.085400
541     1  0.497736  0.502264       1  ...  1.022819   1.0    0.0  1.088891
542     0  0.523944  0.476056       0  ...  1.013674   1.0    0.0  1.079155
543     1  0.454640  0.545360       0  ...  1.002921   1.0    0.0  1.067708

[5 rows x 10 columns]
2023-02-25 00:00:37,959:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.525632  0.474368       0  ...  1.021525   1.0    0.0  1.088734
46     1  0.491892  0.508108       0  ...  1.019540   1.0    0.0  1.087519
47     1  0.497764  0.502236       1  ...  1.022819   1.0    0.0  1.091017
48     0  0.523540  0.476460       0  ...  1.013674   1.0    0.0  1.079100
49     1  0.454640  0.545360       0  ...  1.002921   1.0    0.0  1.067708

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '33.103', 'enterprice': '23978.6', 'countrevence': '0', 'unrealprofit': '-21563.2942', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23327.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-02-25 00:00:03,787:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41815F1677254403321I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1677254403447976, 'quantity': '41.176', 'price': '23337.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1677254402952, 'updatetime': 1677254403447, 'tradetype': 'usdt', 'selfid': 41815, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1677254403447, 'clientorderid': '41815F1677254403321I0L59', 'price': '23337.2', 'quantity': '41.176', 'commission': '960.9325472', 'commissionasset': 'USDT', 'tradetime': 1677254403447, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1677254403447}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [25/Feb/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13160 

self.closeSec=1677254999, self.tradeDate='20230225', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='23337.1', self.close='23154.3'
2023-02-25 00:10:02,013:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677254999, self.tradeDate='20230225', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='23337.1', self.close='23154.3'
127.0.0.1 - - [25/Feb/2023 00:10:02] "POST / HTTP/1.1" 200 -
2023-02-25 00:10:02,061:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230224   232000    232959  1677252599  23663.4  23587.3 -0.003195
573  20230224   233000    233959  1677253199  23587.4  23434.2 -0.006491
574  20230224   234000    234959  1677253799  23429.2  23429.5 -0.000201
575  20230224   235000    235959  1677254399  23426.5  23337.1 -0.003944
576  20230225   000000    000959  1677254999  23337.1  23154.3 -0.007833
2023-02-25 00:10:02,061:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [25/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13161 

self.closeSec=1677255599, self.tradeDate='20230225', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='23150.9', self.close='23062.1'
2023-02-25 00:20:01,800:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677255599, self.tradeDate='20230225', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='23150.9', self.close='23062.1'
2023-02-25 00:20:01,883:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230224   233000    233959  1677253199  23587.4  23434.2 -0.006491
574  20230224   234000    234959  1677253799  23429.2  23429.5 -0.000201
575  20230224   235000    235959  1677254399  23426.5  23337.1 -0.003944
576  20230225   000000    000959  1677254999  23337.1  23154.3 -0.007833
577  20230225   001000    001959  1677255599  23150.9  23062.1 -0.003982
2023-02-25 00:20:01,883:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-02-25 00:00:02,715:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-02-25 00:00:02,828:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:2250000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230224, closeTime:235959, close:23337.1, total:979069.1011917, pct_pre:-0.0033138491278132953, thd:0.39167739535747575, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13161 

self.closeSec=1677254999, self.tradeDate='20230225', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='23337.1', self.close='23154.3'
127.0.0.1 - - [25/Feb/2023 00:10:02] "POST / HTTP/1.1" 200 -
2023-02-25 00:10:02,029:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677254999, self.tradeDate='20230225', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='23337.1', self.close='23154.3'
2023-02-25 00:10:02,078:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230224   232000    232959  1677252599  23663.4  23587.3
17421  20230224   233000    233959  1677253199  23587.4  23434.2
17422  20230224   234000    234959  1677253799  23429.2  23429.5
17423  20230224   235000    235959  1677254399  23426.5  23337.1
17424  20230225   000000    000959  1677254999  23337.1  23154.3
2023-02-25 00:10:02,078:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [25/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13162 

self.closeSec=1677255599, self.tradeDate='20230225', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='23150.9', self.close='23062.1'
2023-02-25 00:20:01,865:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677255599, self.tradeDate='20230225', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='23150.9', self.close='23062.1'
2023-02-25 00:20:01,892:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230224   233000    233959  1677253199  23587.4  23434.2
17422  20230224   234000    234959  1677253799  23429.2  23429.5
17423  20230224   235000    235959  1677254399  23426.5  23337.1
17424  20230225   000000    000959  1677254999  23337.1  23154.3
17425  20230225   001000    001959  1677255599  23150.9  23062.1
2023-02-25 00:20:01,892:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [25/Feb/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-02-25 00:00:04,385:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41816F1677254403985I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1677254404177688, 'quantity': '48.073', 'price': '23337.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1677254403175, 'updatetime': 1677254404177, 'tradetype': 'usdt', 'selfid': 41816, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1677254404177, 'clientorderid': '41816F1677254403985I0L2', 'price': '23337.2', 'quantity': '48.073', 'commission': '1121.8892156', 'commissionasset': 'USDT', 'tradetime': 1677254404177, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1677254404177}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13161 

self.closeSec=1677254999, self.tradeDate='20230225', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='23337.1', self.close='23154.3'
127.0.0.1 - - [25/Feb/2023 00:10:02] "POST / HTTP/1.1" 200 -
2023-02-25 00:10:02,036:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677254999, self.tradeDate='20230225', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='23337.1', self.close='23154.3'
2023-02-25 00:10:02,071:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230224   232000    232959  1677252599  23663.4  23587.3
12237  20230224   233000    233959  1677253199  23587.4  23434.2
12238  20230224   234000    234959  1677253799  23429.2  23429.5
12239  20230224   235000    235959  1677254399  23426.5  23337.1
12240  20230225   000000    000959  1677254999  23337.1  23154.3
2023-02-25 00:10:02,074:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
127.0.0.1 - - [25/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13162 

self.closeSec=1677255599, self.tradeDate='20230225', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='23150.9', self.close='23062.1'
2023-02-25 00:20:01,851:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677255599, self.tradeDate='20230225', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='23150.9', self.close='23062.1'
2023-02-25 00:20:01,900:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230224   233000    233959  1677253199  23587.4  23434.2
12238  20230224   234000    234959  1677253799  23429.2  23429.5
12239  20230224   235000    235959  1677254399  23426.5  23337.1
12240  20230225   000000    000959  1677254999  23337.1  23154.3
12241  20230225   001000    001959  1677255599  23150.9  23062.1
2023-02-25 00:20:01,900:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [25/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=21754
self.closeSec=1677255599, self.tradeDate='20230225', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=23081.5, self.close=23062.1, self.high=23144.3, self.low=23062.1, self.vol=6927.194, self.amt=160046059.9332 
2023-02-25 00:20:01,735:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230224   235500    235959  ...         0.0        0.0       0
5760  20230225   000000    000459  ...         0.0        0.0       0
5761  20230225   000500    000959  ...         0.0        0.0       0
5762  20230225   001000    001459  ...         0.0        0.0       0
5763  20230225   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-25 00:20:01,743:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677255599, self.tradeDate='20230225', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=23081.5, self.close=23062.1, self.high=23144.3, self.low=23062.1, self.vol=6927.194, self.amt=160046059.9332, ukdf['pct'].iloc[-1]=-0.000914 , ukdf['amount'].iloc[-1]=160046059.9332, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=21755
self.closeSec=1677255899, self.tradeDate='20230225', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=23062.1, self.close=23057.4, self.high=23131.3, self.low=22965.0, self.vol=13064.922, self.amt=301259872.8381 
127.0.0.1 - - [25/Feb/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-02-25 00:25:01,754:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230225   000000    000459  ...         0.0        0.0       0
5761  20230225   000500    000959  ...         0.0        0.0       0
5762  20230225   001000    001459  ...         0.0        0.0       0
5763  20230225   001500    001959  ...         0.0        0.0       0
5764  20230225   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-25 00:25:01,754:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677255899, self.tradeDate='20230225', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=23062.1, self.close=23057.4, self.high=23131.3, self.low=22965.0, self.vol=13064.922, self.amt=301259872.8381, ukdf['pct'].iloc[-1]=-0.000204 , ukdf['amount'].iloc[-1]=301259872.8381, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230224   120000    155959  1677225599  ...    723  0.630339  0.043797     NaN
724  20230224   160000    195959  1677239999  ...    724  0.696564  0.198814     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.465', 'enterprice': '24934.8', 'countrevence': '0', 'unrealprofit': '38538.56249488245', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23877.93554107', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=908338.234518, self.flagDict['side']='sell', self.tradeCount=21, self.count=548
self.closeSec=1677254399, self.tradeDate='20230224', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=23876.3, self.close=23337.1, self.high=24029.3, self.low=23310.5, self.vol=231711.797, self.amt=5483990627.1797 
127.0.0.1 - - [25/Feb/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-02-25 00:00:02,348:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1677254399, self.tradeDate='20230224', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=23876.3, self.close=23337.1, self.high=24029.3, self.low=23310.5, self.vol=231711.797, self.amt=5483990627.1797 
2023-02-25 00:00:02,381:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230224   040000    075959  ...   60185.891  1.438425e+09 -0.001398
722  20230224   080000    115959  ...   59502.415  1.427399e+09  0.000685
723  20230224   120000    155959  ...   55400.746  1.321314e+09 -0.005162
724  20230224   160000    195959  ...   60283.249  1.437744e+09  0.002305
725  20230224   200000    235959  ...  231711.797  5.483991e+09 -0.022587

[5 rows x 11 columns]
2023-02-25 00:00:05,152:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230224   040000    075959  1677196799  ...    721  0.559513 -0.113242     NaN
722  20230224   080000    115959  1677211199  ...    722  0.576195 -0.081610     NaN
723  20230224   120000    155959  1677225599  ...    723  0.630339  0.043797     NaN
724  20230224   160000    195959  1677239999  ...    724  0.696564  0.198814     NaN
725  20230224   200000    235959  1677254399  ...    725  0.622744  0.003444     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.465', 'enterprice': '24934.8', 'countrevence': '0', 'unrealprofit': '58256.484', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23337.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


