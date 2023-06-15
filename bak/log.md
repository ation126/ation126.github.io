# 20230616 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=9376
self.closeSec=1686845999, self.tradeDate='20230616', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=24940.0, self.close=24971.1, self.high=24973.6, self.low=24940.0, self.vol=982.151, self.amt=24518271.4642 
127.0.0.1 - - [16/Jun/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-06-16 00:20:07,469:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230615   235500    235959  ...         0.0        0.0       0
5760  20230616   000000    000459  ...         0.0        0.0       0
5761  20230616   000500    000959  ...         0.0        0.0       0
5762  20230616   001000    001459  ...         0.0        0.0       0
5763  20230616   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-16 00:20:07,499:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686845999, self.tradeDate='20230616', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=24940.0, self.close=24971.1, self.high=24973.6, self.low=24940.0, self.vol=982.151, self.amt=24518271.4642, ukdf['pct'].iloc[-1]=0.001247 , ukdf['amount'].iloc[-1]=24518271.4642, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '26405.66318773482', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24968.75873993', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [16/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=9377
self.closeSec=1686846299, self.tradeDate='20230616', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=24971.1, self.close=24976.9, self.high=24976.9, self.low=24960.0, self.vol=549.315, self.amt=13716457.2311 
2023-06-16 00:25:00,760:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230616   000000    000459  ...         0.0        0.0       0
5761  20230616   000500    000959  ...         0.0        0.0       0
5762  20230616   001000    001459  ...         0.0        0.0       0
5763  20230616   001500    001959  ...         0.0        0.0       0
5764  20230616   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-16 00:25:00,760:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686846299, self.tradeDate='20230616', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=24971.1, self.close=24976.9, self.high=24976.9, self.low=24960.0, self.vol=549.315, self.amt=13716457.2311, ukdf['pct'].iloc[-1]=0.000232 , ukdf['amount'].iloc[-1]=13716457.2311, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '26292.288', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24976.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1686845999, self.tradeDate='20230616', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=24940.0, self.close=24971.1, self.high=24973.6, self.low=24940.0 
127.0.0.1 - - [16/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-16 00:20:05,038:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686845999, self.tradeDate='20230616', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=24940.0, self.close=24971.1, self.high=24973.6, self.low=24940.0   
2023-06-16 00:20:06,519:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230615   235500    235959  1686844799  ...  24941.1 -0.000305   1727    5
1440  20230616   000000    000459  1686845099  ...  24918.2 -0.001170   1440    0
1441  20230616   000500    000959  1686845399  ...  24918.4  0.001689   1441    1
1442  20230616   001000    001459  1686845699  ...  24935.0 -0.000857   1442    2
1443  20230616   001500    001959  1686845999  ...  24940.0  0.001247   1443    3

[5 rows x 11 columns]
2023-06-16 00:20:06,529:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.7106994665763716, self.count=9379 

self.closeSec=1686846299, self.tradeDate='20230616', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=24971.1, self.close=24976.9, self.high=24976.9, self.low=24960.0 
127.0.0.1 - - [16/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-06-16 00:25:00,708:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686846299, self.tradeDate='20230616', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=24971.1, self.close=24976.9, self.high=24976.9, self.low=24960.0   
2023-06-16 00:25:00,739:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230616   000000    000459  1686845099  ...  24918.2 -0.001170   1440    0
1441  20230616   000500    000959  1686845399  ...  24918.4  0.001689   1441    1
1442  20230616   001000    001459  1686845699  ...  24935.0 -0.000857   1442    2
1443  20230616   001500    001959  1686845999  ...  24940.0  0.001247   1443    3
1444  20230616   002000    002459  1686846299  ...  24960.0  0.000232   1444    4

[5 rows x 11 columns]
2023-06-16 00:25:00,741:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-16 00:00:20,486:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230615    212959  24944.4  ...  48.750000  0.409846  0.813962
5803  20230615    215959  25057.2  ...  48.750000  0.408066  0.812853
5804  20230615    222959  25044.9  ...  48.750000  0.407155  0.810975
5805  20230615    225959  25039.9  ...  48.333333  0.400799  0.810873
5806  20230615    232959  25004.4  ...  47.916667  0.395476  0.811918

[5 rows x 33 columns]
0.5294117647058824
acc is : 0.5294117647058824
2023-06-16 00:00:20,581:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.537861  0.462139       0  ...  1.107255  -1.0    0.0  0.922774
540     0  0.516215  0.483785       0  ...  1.107480  -1.0    0.0  0.922586
541     0  0.507407  0.492593       0  ...  1.109051  -1.0    0.0  0.921278
542     0  0.503684  0.496316       0  ...  1.110381  -1.0    0.0  0.920172
543     0  0.503148  0.496852       0  ...  1.111537  -1.0    0.0  0.919214

[5 rows x 10 columns]
2023-06-16 00:00:20,604:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.539066  0.460934       0  ...  1.039215  -1.0    0.0  0.925399
46     0  0.517516  0.482484       0  ...  1.039427  -1.0    0.0  0.923331
47     0  0.507524  0.492476       0  ...  1.040900  -1.0    0.0  0.922022
48     0  0.503751  0.496249       0  ...  1.042149  -1.0    0.0  0.920583
49     0  0.503148  0.496852       0  ...  1.111537  -1.0    0.0  0.919214

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.898', 'enterprice': '25555.4', 'countrevence': '0', 'unrealprofit': '16948.50589368976', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24947.88312088', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [16/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-16 00:00:04,387:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42393F1686844803721I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1686844804126316, 'quantity': '29.128', 'price': '24948.4', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1686844802798, 'updatetime': 1686844804126, 'tradetype': 'usdt', 'selfid': 42393, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1686844804126, 'clientorderid': '42393F1686844803721I0L59', 'price': '24948.4', 'quantity': '29.128', 'commission': '726.6969952', 'commissionasset': 'USDT', 'tradetime': 1686844804126, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1686844804126}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4688 

self.closeSec=1686845399, self.tradeDate='20230616', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='24948.4', self.close='24961.4'
127.0.0.1 - - [16/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-06-16 00:10:01,152:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686845399, self.tradeDate='20230616', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='24948.4', self.close='24961.4'
2023-06-16 00:10:01,173:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230615   232000    232959  1686842999  25004.9  24974.4 -0.001224
573  20230615   233000    233959  1686843599  24975.2  24979.3  0.000196
574  20230615   234000    234959  1686844199  24979.2  24957.4 -0.000877
575  20230615   235000    235959  1686844799  24957.3  24948.4 -0.000361
576  20230616   000000    000959  1686845399  24948.4  24961.4  0.000521
2023-06-16 00:10:01,174:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4689 

self.closeSec=1686845999, self.tradeDate='20230616', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='24961.4', self.close='24971.1'
127.0.0.1 - - [16/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-16 00:20:07,328:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686845999, self.tradeDate='20230616', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='24961.4', self.close='24971.1'
2023-06-16 00:20:08,088:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230615   233000    233959  1686843599  24975.2  24979.3  0.000196
574  20230615   234000    234959  1686844199  24979.2  24957.4 -0.000877
575  20230615   235000    235959  1686844799  24957.3  24948.4 -0.000361
576  20230616   000000    000959  1686845399  24948.4  24961.4  0.000521
577  20230616   001000    001959  1686845999  24961.4  24971.1  0.000389
2023-06-16 00:20:08,089:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-06-16 00:00:02,306:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-06-16 00:00:02,436:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:6160000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230615, closeTime:235959, close:24948.4, total:980576.7580187, pct_pre:-0.03921213545660163, thd:-0.23861541737407083, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4691 

self.closeSec=1686845399, self.tradeDate='20230616', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='24948.4', self.close='24961.4'
127.0.0.1 - - [16/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-06-16 00:10:01,126:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686845399, self.tradeDate='20230616', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='24948.4', self.close='24961.4'
2023-06-16 00:10:01,135:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230615   232000    232959  1686842999  25004.9  24974.4
17421  20230615   233000    233959  1686843599  24975.2  24979.3
17422  20230615   234000    234959  1686844199  24979.2  24957.4
17423  20230615   235000    235959  1686844799  24957.3  24948.4
17424  20230616   000000    000959  1686845399  24948.4  24961.4
2023-06-16 00:10:01,135:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4692 

self.closeSec=1686845999, self.tradeDate='20230616', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='24961.4', self.close='24971.1'
127.0.0.1 - - [16/Jun/2023 00:20:05] "POST / HTTP/1.1" 200 -
2023-06-16 00:20:09,261:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686845999, self.tradeDate='20230616', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='24961.4', self.close='24971.1'
2023-06-16 00:20:09,421:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230615   233000    233959  1686843599  24975.2  24979.3
17422  20230615   234000    234959  1686844199  24979.2  24957.4
17423  20230615   235000    235959  1686844799  24957.3  24948.4
17424  20230616   000000    000959  1686845399  24948.4  24961.4
17425  20230616   001000    001959  1686845999  24961.4  24971.1
2023-06-16 00:20:09,422:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [16/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-16 00:00:04,626:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42394F1686844803812I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1686844804185745, 'quantity': '52.104', 'price': '24948.4', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1686844802929, 'updatetime': 1686844804185, 'tradetype': 'usdt', 'selfid': 42394, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1686844804185, 'clientorderid': '42394F1686844803812I0L2', 'price': '24948.4', 'quantity': '52.104', 'commission': '1299.9114336', 'commissionasset': 'USDT', 'tradetime': 1686844804185, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1686844804185}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4691 

self.closeSec=1686845399, self.tradeDate='20230616', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='24948.4', self.close='24961.4'
127.0.0.1 - - [16/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-06-16 00:10:01,160:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686845399, self.tradeDate='20230616', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='24948.4', self.close='24961.4'
2023-06-16 00:10:01,177:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230615   232000    232959  1686842999  25004.9  24974.4
12237  20230615   233000    233959  1686843599  24975.2  24979.3
12238  20230615   234000    234959  1686844199  24979.2  24957.4
12239  20230615   235000    235959  1686844799  24957.3  24948.4
12240  20230616   000000    000959  1686845399  24948.4  24961.4
2023-06-16 00:10:01,177:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4692 

self.closeSec=1686845999, self.tradeDate='20230616', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='24961.4', self.close='24971.1'
127.0.0.1 - - [16/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-16 00:20:08,892:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686845999, self.tradeDate='20230616', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='24961.4', self.close='24971.1'
2023-06-16 00:20:09,193:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230615   233000    233959  1686843599  24975.2  24979.3
12238  20230615   234000    234959  1686844199  24979.2  24957.4
12239  20230615   235000    235959  1686844799  24957.3  24948.4
12240  20230616   000000    000959  1686845399  24948.4  24961.4
12241  20230616   001000    001959  1686845999  24961.4  24971.1
2023-06-16 00:20:09,193:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=9376
self.closeSec=1686845999, self.tradeDate='20230616', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=24940.0, self.close=24971.1, self.high=24973.6, self.low=24940.0, self.vol=982.151, self.amt=24518271.4642 
127.0.0.1 - - [16/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-16 00:20:07,458:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230615   235500    235959  ...         0.0        0.0       0
5760  20230616   000000    000459  ...         0.0        0.0       0
5761  20230616   000500    000959  ...         0.0        0.0       0
5762  20230616   001000    001459  ...         0.0        0.0       0
5763  20230616   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-16 00:20:07,480:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686845999, self.tradeDate='20230616', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=24940.0, self.close=24971.1, self.high=24973.6, self.low=24940.0, self.vol=982.151, self.amt=24518271.4642, ukdf['pct'].iloc[-1]=0.001247 , ukdf['amount'].iloc[-1]=24518271.4642, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-69648.33564025987', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24968.75873993', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [16/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=9377
self.closeSec=1686846299, self.tradeDate='20230616', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=24971.1, self.close=24976.9, self.high=24976.9, self.low=24960.0, self.vol=549.315, self.amt=13716457.2311 
2023-06-16 00:25:00,761:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230616   000000    000459  ...         0.0        0.0       0
5761  20230616   000500    000959  ...         0.0        0.0       0
5762  20230616   001000    001459  ...         0.0        0.0       0
5763  20230616   001500    001959  ...         0.0        0.0       0
5764  20230616   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-16 00:25:00,761:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686846299, self.tradeDate='20230616', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=24971.1, self.close=24976.9, self.high=24976.9, self.low=24960.0, self.vol=549.315, self.amt=13716457.2311, ukdf['pct'].iloc[-1]=0.000232 , ukdf['amount'].iloc[-1]=13716457.2311, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-69345.9611', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24976.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230615   120000    155959  1686815999  ...    723  0.274178 -0.697865    -1.0
724  20230615   160000    195959  1686830399  ...    724  0.405072 -0.112337     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '114088.8046', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25010.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1492324.2295523998, self.flagDict['side']='sell', self.tradeCount=4, self.count=195127.0.0.1 - - [16/Jun/2023 00:00:01] "POST / HTTP/1.1" 200 -

self.closeSec=1686844799, self.tradeDate='20230615', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=25007.0, self.close=24948.4, self.high=25100.0, self.low=24910.9, self.vol=70290.723, self.amt=1757902412.6862 
2023-06-16 00:00:01,881:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1686844799, self.tradeDate='20230615', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=25007.0, self.close=24948.4, self.high=25100.0, self.low=24910.9, self.vol=70290.723, self.amt=1757902412.6862 
2023-06-16 00:00:01,901:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230615   040000    075959  ...  225751.005  5.685134e+09 -0.028797
722  20230615   080000    115959  ...   41759.388  1.048287e+09 -0.002433
723  20230615   120000    155959  ...   67274.308  1.680181e+09 -0.003201
724  20230615   160000    195959  ...   68636.788  1.711896e+09  0.001297
725  20230615   200000    235959  ...   70290.723  1.757902e+09 -0.002343

[5 rows x 11 columns]
2023-06-16 00:00:03,275:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230615   040000    075959  1686787199  ...    721  0.012039 -1.782105    -1.0
722  20230615   080000    115959  1686801599  ...    722  0.109595 -1.395185    -1.0
723  20230615   120000    155959  1686815999  ...    723  0.274178 -0.697865    -1.0
724  20230615   160000    195959  1686830399  ...    724  0.405072 -0.112337     NaN
725  20230615   200000    235959  1686844799  ...    725  0.498045  0.326385     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '117514.6132', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24948.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


