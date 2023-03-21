# 20230322 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=32956
self.closeSec=1679415599, self.tradeDate='20230322', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28039.6, self.close=28099.6, self.high=28108.7, self.low=28022.4, self.vol=1872.004, self.amt=52553228.653 
127.0.0.1 - - [22/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-22 00:20:05,569:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230321   235500    235959  ...         0.0        0.0       0
5760  20230322   000000    000459  ...         0.0        0.0       0
5761  20230322   000500    000959  ...         0.0        0.0       0
5762  20230322   001000    001459  ...         0.0        0.0       0
5763  20230322   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-22 00:20:05,578:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679415599, self.tradeDate='20230322', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28039.6, self.close=28099.6, self.high=28108.7, self.low=28022.4, self.vol=1872.004, self.amt=52553228.653, ukdf['pct'].iloc[-1]=0.00219 , ukdf['amount'].iloc[-1]=52553228.653, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-696585.3408', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28105.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=32957
self.closeSec=1679415899, self.tradeDate='20230322', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28101.0, self.close=28095.0, self.high=28116.5, self.low=28082.1, self.vol=2152.898, self.amt=60498023.4188 
127.0.0.1 - - [22/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-03-22 00:25:01,621:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230322   000000    000459  ...         0.0        0.0       0
5761  20230322   000500    000959  ...         0.0        0.0       0
5762  20230322   001000    001459  ...         0.0        0.0       0
5763  20230322   001500    001959  ...         0.0        0.0       0
5764  20230322   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-22 00:25:01,622:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679415899, self.tradeDate='20230322', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28101.0, self.close=28095.0, self.high=28116.5, self.low=28082.1, self.vol=2152.898, self.amt=60498023.4188, ukdf['pct'].iloc[-1]=-0.000164 , ukdf['amount'].iloc[-1]=60498023.4188, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-696070.00260993904', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28096.53615079', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1679415599, self.tradeDate='20230322', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28039.6, self.close=28099.6, self.high=28108.7, self.low=28022.4 
127.0.0.1 - - [22/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-22 00:20:03,666:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679415599, self.tradeDate='20230322', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28039.6, self.close=28099.6, self.high=28108.7, self.low=28022.4   
2023-03-22 00:20:04,353:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230321   235500    235959  1679414399  ...  28020.0 -0.001219   1727    5
1440  20230322   000000    000459  1679414699  ...  27998.0 -0.000214   1440    0
1441  20230322   000500    000959  1679414999  ...  28005.3  0.001745   1441    1
1442  20230322   001000    001459  1679415299  ...  28026.0 -0.001165   1442    2
1443  20230322   001500    001959  1679415599  ...  28022.4  0.002190   1443    3

[5 rows x 11 columns]
2023-03-22 00:20:04,367:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [22/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=204, self.factor=0.4244704453993291, self.count=33523 

self.closeSec=1679415899, self.tradeDate='20230322', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28101.0, self.close=28095.0, self.high=28116.5, self.low=28082.1 
2023-03-22 00:25:01,498:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679415899, self.tradeDate='20230322', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28101.0, self.close=28095.0, self.high=28116.5, self.low=28082.1   
2023-03-22 00:25:01,567:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230322   000000    000459  1679414699  ...  27998.0 -0.000214   1440    0
1441  20230322   000500    000959  1679414999  ...  28005.3  0.001745   1441    1
1442  20230322   001000    001459  1679415299  ...  28026.0 -0.001165   1442    2
1443  20230322   001500    001959  1679415599  ...  28022.4  0.002190   1443    3
1444  20230322   002000    002459  1679415899  ...  28082.1 -0.000164   1444    4

[5 rows x 11 columns]
2023-03-22 00:25:01,567:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-22 00:00:35,067:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230321    212959  28167.6  ...  51.250000  0.535639  0.437267
5803  20230321    215959  28026.9  ...  50.833333  0.534426  0.424422
5804  20230321    222959  28019.2  ...  50.833333  0.513905  0.424860
5805  20230321    225959  27836.8  ...  50.833333  0.517449  0.422940
5806  20230321    232959  27870.5  ...  51.250000  0.522664  0.417727

[5 rows x 33 columns]
0.5477941176470589
acc is : 0.5477941176470589
2023-03-22 00:00:35,228:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.492167  0.507833       0  ...  1.195366   1.0    0.0  1.404841
540     0  0.534109  0.465891       0  ...  1.187695   1.0    0.0  1.395825
541     1  0.459760  0.540240       1  ...  1.189133   1.0    0.0  1.397515
542     0  0.537280  0.462720       1  ...  1.191245   1.0    0.0  1.399997
543     0  0.522789  0.477211       1  ...  1.195853   1.0    0.0  1.405412

[5 rows x 10 columns]
2023-03-22 00:00:35,263:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.491796  0.508204       0  ...  1.194053   1.0    0.0  1.404975
46     0  0.534351  0.465649       0  ...  1.186390   1.0    0.0  1.401137
47     1  0.459603  0.540397       1  ...  1.187826   1.0    0.0  1.402833
48     0  0.537242  0.462758       1  ...  1.189936   1.0    0.0  1.400657
49     0  0.522789  0.477211       1  ...  1.195853   1.0    0.0  1.405412

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [22/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-22 00:00:03,575:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42033F1679414403169I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1679414403315161, 'quantity': '27.79', 'price': '28029.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1679414402779, 'updatetime': 1679414403315, 'tradetype': 'usdt', 'selfid': 42033, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1679414403315, 'clientorderid': '42033F1679414403169I0L59', 'price': '28029.7', 'quantity': '27.79', 'commission': '778.945363', 'commissionasset': 'USDT', 'tradetime': 1679414403315, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1679414403315}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [22/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16760 

self.closeSec=1679414999, self.tradeDate='20230322', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28028.7', self.close='28070.9'
2023-03-22 00:10:01,879:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679414999, self.tradeDate='20230322', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='28028.7', self.close='28070.9'
2023-03-22 00:10:01,887:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230321   232000    232959  1679412599  27969.6    27920 -0.001777
573  20230321   233000    233959  1679413199    27920  28015.5  0.003420
574  20230321   234000    234959  1679413799  28015.4  28034.9  0.000692
575  20230321   235000    235959  1679414399  28046.6    28028 -0.000246
576  20230322   000000    000959  1679414999  28028.7  28070.9  0.001531
2023-03-22 00:10:01,888:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16761 

self.closeSec=1679415599, self.tradeDate='20230322', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28070.6', self.close='28101'
127.0.0.1 - - [22/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-22 00:20:04,418:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679415599, self.tradeDate='20230322', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='28070.6', self.close='28101'
2023-03-22 00:20:04,977:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230321   233000    233959  1679413199    27920  28015.5  0.003420
574  20230321   234000    234959  1679413799  28015.4  28034.9  0.000692
575  20230321   235000    235959  1679414399  28046.6    28028 -0.000246
576  20230322   000000    000959  1679414999  28028.7  28070.9  0.001531
577  20230322   001000    001959  1679415599  28070.6    28101  0.001072
2023-03-22 00:20:04,986:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-03-22 00:00:03,846:INFO:pyemd2:main.py:303:handleOrderFilled:185189: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42034F1679414403382I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1679414403625388, 'quantity': '37.022', 'price': '28029.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1679414402844, 'updatetime': 1679414403625, 'tradetype': 'usdt', 'selfid': 42034, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1679414403625, 'clientorderid': '42034F1679414403382I0L57', 'price': '28029.7', 'quantity': '37.022', 'commission': '1037.7155534', 'commissionasset': 'USDT', 'tradetime': 1679414403625, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1679414403625}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [22/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16761 

self.closeSec=1679414999, self.tradeDate='20230322', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28028.7', self.close='28070.9'
127.0.0.1 - - [22/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-03-22 00:10:01,875:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679414999, self.tradeDate='20230322', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='28028.7', self.close='28070.9'
2023-03-22 00:10:01,913:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230321   232000    232959  1679412599  27969.6    27920
17421  20230321   233000    233959  1679413199    27920  28015.5
17422  20230321   234000    234959  1679413799  28015.4  28034.9
17423  20230321   235000    235959  1679414399  28046.6    28028
17424  20230322   000000    000959  1679414999  28028.7  28070.9
2023-03-22 00:10:01,913:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16762 

self.closeSec=1679415599, self.tradeDate='20230322', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28070.6', self.close='28101'
127.0.0.1 - - [22/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-22 00:20:06,530:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679415599, self.tradeDate='20230322', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='28070.6', self.close='28101'
2023-03-22 00:20:06,611:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230321   233000    233959  1679413199    27920  28015.5
17422  20230321   234000    234959  1679413799  28015.4  28034.9
17423  20230321   235000    235959  1679414399  28046.6    28028
17424  20230322   000000    000959  1679414999  28028.7  28070.9
17425  20230322   001000    001959  1679415599  28070.6    28101
2023-03-22 00:20:06,611:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [22/Mar/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-03-22 00:00:04,034:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42035F1679414403474I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1679414403645526, 'quantity': '39.46', 'price': '28029.8', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1679414402965, 'updatetime': 1679414403645, 'tradetype': 'usdt', 'selfid': 42035, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1679414403645, 'clientorderid': '42035F1679414403474I0L2', 'price': '28029.8', 'quantity': '39.46', 'commission': '1106.055908', 'commissionasset': 'USDT', 'tradetime': 1679414403645, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1679414403645}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [22/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16761 

self.closeSec=1679414999, self.tradeDate='20230322', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28028.7', self.close='28070.9'
2023-03-22 00:10:01,851:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679414999, self.tradeDate='20230322', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='28028.7', self.close='28070.9'
2023-03-22 00:10:01,898:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230321   232000    232959  1679412599  27969.6    27920
12237  20230321   233000    233959  1679413199    27920  28015.5
12238  20230321   234000    234959  1679413799  28015.4  28034.9
12239  20230321   235000    235959  1679414399  28046.6    28028
12240  20230322   000000    000959  1679414999  28028.7  28070.9
2023-03-22 00:10:01,898:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16762 

self.closeSec=1679415599, self.tradeDate='20230322', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28070.6', self.close='28101'
127.0.0.1 - - [22/Mar/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-03-22 00:20:06,207:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679415599, self.tradeDate='20230322', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='28070.6', self.close='28101'
2023-03-22 00:20:06,412:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230321   233000    233959  1679413199    27920  28015.5
12238  20230321   234000    234959  1679413799  28015.4  28034.9
12239  20230321   235000    235959  1679414399  28046.6    28028
12240  20230322   000000    000959  1679414999  28028.7  28070.9
12241  20230322   001000    001959  1679415599  28070.6    28101
2023-03-22 00:20:06,413:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [22/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=28954
self.closeSec=1679415599, self.tradeDate='20230322', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28039.6, self.close=28099.6, self.high=28108.7, self.low=28022.4, self.vol=1872.004, self.amt=52553228.653 
2023-03-22 00:20:01,742:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230321   235500    235959  ...         0.0        0.0       0
5760  20230322   000000    000459  ...         0.0        0.0       0
5761  20230322   000500    000959  ...         0.0        0.0       0
5762  20230322   001000    001459  ...         0.0        0.0       0
5763  20230322   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-22 00:20:01,744:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679415599, self.tradeDate='20230322', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28039.6, self.close=28099.6, self.high=28108.7, self.low=28022.4, self.vol=1872.004, self.amt=52553228.653, ukdf['pct'].iloc[-1]=0.00219 , ukdf['amount'].iloc[-1]=52553228.653, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [22/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=28955
self.closeSec=1679415899, self.tradeDate='20230322', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28101.0, self.close=28095.0, self.high=28116.5, self.low=28082.1, self.vol=2152.898, self.amt=60498023.4188 
2023-03-22 00:25:01,600:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230322   000000    000459  ...         0.0        0.0       0
5761  20230322   000500    000959  ...         0.0        0.0       0
5762  20230322   001000    001459  ...         0.0        0.0       0
5763  20230322   001500    001959  ...         0.0        0.0       0
5764  20230322   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-22 00:25:01,601:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679415899, self.tradeDate='20230322', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28101.0, self.close=28095.0, self.high=28116.5, self.low=28082.1, self.vol=2152.898, self.amt=60498023.4188, ukdf['pct'].iloc[-1]=-0.000164 , ukdf['amount'].iloc[-1]=60498023.4188, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230321   120000    155959  1679385599  ...    723  0.664354 -0.102804     NaN
724  20230321   160000    195959  1679399999  ...    724  0.552215 -0.430259     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.795', 'enterprice': '27400', 'countrevence': '0', 'unrealprofit': '33782.1200581284', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28027.97880952', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [22/Mar/2023 00:00:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1472509.017, self.flagDict['side']='buy', self.tradeCount=26, self.count=698
self.closeSec=1679414399, self.tradeDate='20230321', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=28026.1, self.close=28028.0, self.high=28252.5, self.low=27706.0, self.vol=166351.235, self.amt=4656915026.61355 
2023-03-22 00:00:02,348:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1679414399, self.tradeDate='20230321', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=28026.1, self.close=28028.0, self.high=28252.5, self.low=27706.0, self.vol=166351.235, self.amt=4656915026.61355 
2023-03-22 00:00:02,413:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230321   040000    075959  ...   95371.337  2.659753e+09 -0.002175
722  20230321   080000    115959  ...   53957.050  1.500153e+09  0.002487
723  20230321   120000    155959  ...  105693.226  2.919067e+09 -0.010157
724  20230321   160000    195959  ...  143510.008  3.996684e+09  0.019468
725  20230321   200000    235959  ...  166351.235  4.656915e+09  0.000068

[5 rows x 11 columns]
2023-03-22 00:00:05,013:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230321   040000    075959  1679356799  ...    721  0.837221  0.400174     NaN
722  20230321   080000    115959  1679371199  ...    722  0.667777 -0.085191     NaN
723  20230321   120000    155959  1679385599  ...    723  0.664354 -0.102804     NaN
724  20230321   160000    195959  1679399999  ...    724  0.552215 -0.430259     NaN
725  20230321   200000    235959  1679414399  ...    725  0.607069 -0.285479     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.795', 'enterprice': '27400', 'countrevence': '0', 'unrealprofit': '33874.7115', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28029.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


