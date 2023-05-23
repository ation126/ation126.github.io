# 20230524 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=2752
self.closeSec=1684858799, self.tradeDate='20230524', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27294.5, self.close=27268.9, self.high=27297.3, self.low=27257.6, self.vol=961.638, self.amt=26225873.1097 
127.0.0.1 - - [24/May/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-05-24 00:20:05,356:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230523   235500    235959  ...    0.172461   0.303371       0
5760  20230524   000000    000459  ...    0.172350   0.303361       0
5761  20230524   000500    000959  ...    0.172240   0.303351       0
5762  20230524   001000    001459  ...    0.172129   0.303341       0
5763  20230524   001500    001959  ...    0.172016   0.303330       0

[5 rows x 18 columns]
2023-05-24 00:20:05,376:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684858799, self.tradeDate='20230524', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27294.5, self.close=27268.9, self.high=27297.3, self.low=27257.6, self.vol=961.638, self.amt=26225873.1097, ukdf['pct'].iloc[-1]=-0.000934 , ukdf['amount'].iloc[-1]=26225873.1097, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.17201586537284488, signal=0, value_std=0.30332950897946304 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-5624.7114', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27268.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [24/May/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=2753
self.closeSec=1684859099, self.tradeDate='20230524', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27268.8, self.close=27285.4, self.high=27288.7, self.low=27262.1, self.vol=422.007, self.amt=11510775.1904 
2023-05-24 00:25:00,844:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230524   000000    000459  ...    0.172350   0.303361       0
5761  20230524   000500    000959  ...    0.172240   0.303351       0
5762  20230524   001000    001459  ...    0.172129   0.303341       0
5763  20230524   001500    001959  ...    0.172016   0.303330       0
5764  20230524   002000    002459  ...    0.171903   0.303318       0

[5 rows x 18 columns]
2023-05-24 00:25:00,844:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684859099, self.tradeDate='20230524', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27268.8, self.close=27285.4, self.high=27288.7, self.low=27262.1, self.vol=422.007, self.amt=11510775.1904, ukdf['pct'].iloc[-1]=0.000605 , ukdf['amount'].iloc[-1]=11510775.1904, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.17190255955211423, signal=0, value_std=0.30331755871475935 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-5891.64592025988', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27287.96806838', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1684858799, self.tradeDate='20230524', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27294.5, self.close=27268.9, self.high=27297.3, self.low=27257.6 
127.0.0.1 - - [24/May/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-05-24 00:20:02,960:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684858799, self.tradeDate='20230524', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27294.5, self.close=27268.9, self.high=27297.3, self.low=27257.6   
2023-05-24 00:20:04,105:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230523   235500    235959  1684857599  ...  27292.0  0.000524   1727    5
1440  20230524   000000    000459  1684857899  ...  27291.6 -0.000696   1440    0
1441  20230524   000500    000959  1684858199  ...  27266.0 -0.000722   1441    1
1442  20230524   001000    001459  1684858499  ...  27256.6  0.000821   1442    2
1443  20230524   001500    001959  1684858799  ...  27257.6 -0.000934   1443    3

[5 rows x 11 columns]
2023-05-24 00:20:04,115:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [24/May/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=11, self.factor=0.361158631959162, self.count=2755 

self.closeSec=1684859099, self.tradeDate='20230524', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27268.8, self.close=27285.4, self.high=27288.7, self.low=27262.1 
2023-05-24 00:25:00,751:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684859099, self.tradeDate='20230524', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27268.8, self.close=27285.4, self.high=27288.7, self.low=27262.1   
2023-05-24 00:25:00,828:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230524   000000    000459  1684857899  ...  27291.6 -0.000696   1440    0
1441  20230524   000500    000959  1684858199  ...  27266.0 -0.000722   1441    1
1442  20230524   001000    001459  1684858499  ...  27256.6  0.000821   1442    2
1443  20230524   001500    001959  1684858799  ...  27257.6 -0.000934   1443    3
1444  20230524   002000    002459  1684859099  ...  27262.1  0.000605   1444    4

[5 rows x 11 columns]
2023-05-24 00:25:00,830:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-24 00:00:35,495:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230523    212959  27271.8  ...  49.166667  0.561604  0.295039
5803  20230523    215959  27258.4  ...  48.750000  0.553181  0.302013
5804  20230523    222959  27229.7  ...  48.750000  0.564393  0.304218
5805  20230523    225959  27277.9  ...  49.166667  0.571892  0.303331
5806  20230523    232959  27310.8  ...  49.583333  0.572849  0.302127

[5 rows x 33 columns]
0.5367647058823529
acc is : 0.5367647058823529
2023-05-24 00:00:35,663:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.480672  0.519328       0  ...  0.937695   1.0    0.0  1.035586
540     1  0.474888  0.525112       1  ...  0.939351   1.0    0.0  1.037415
541     1  0.491866  0.508134       1  ...  0.940484   1.0    0.0  1.038666
542     1  0.486718  0.513282       1  ...  0.940629   1.0    0.0  1.038826
543     1  0.492468  0.507532       0  ...  0.940481   1.0    0.0  1.038663

[5 rows x 10 columns]
2023-05-24 00:00:35,696:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.480797  0.519203       0  ...  0.937695   1.0    0.0  1.040871
46     1  0.474809  0.525191       1  ...  0.939351   1.0    0.0  1.037688
47     1  0.491906  0.508094       1  ...  0.940484   1.0    0.0  1.038939
48     1  0.486635  0.513365       1  ...  0.940629   1.0    0.0  1.038684
49     1  0.492468  0.507532       0  ...  0.940481   1.0    0.0  1.038663

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.741', 'enterprice': '27035', 'countrevence': '0', 'unrealprofit': '7581.0735', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27318.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-05-24 00:00:04,419:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42244F1684857603788I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1684857604220918, 'quantity': '25.518', 'price': '27312.4', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1684857602886, 'updatetime': 1684857604220, 'tradetype': 'usdt', 'selfid': 42244, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1684857604220, 'clientorderid': '42244F1684857603788I0L59', 'price': '27312.4', 'quantity': '25.518', 'commission': '696.9578232', 'commissionasset': 'USDT', 'tradetime': 1684857604220, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1684857604220}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [24/May/2023 00:00:04] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [24/May/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1376 

self.closeSec=1684858199, self.tradeDate='20230524', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27310.8', self.close='27271.9'
2023-05-24 00:10:01,200:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684858199, self.tradeDate='20230524', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27310.8', self.close='27271.9'
2023-05-24 00:10:01,256:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230523   232000    232959  1684855799    27299  27316.9  0.000696
573  20230523   233000    233959  1684856399  27316.9  27300.9 -0.000586
574  20230523   234000    234959  1684856999  27300.9  27302.6  0.000062
575  20230523   235000    235959  1684857599  27302.6  27310.7  0.000297
576  20230524   000000    000959  1684858199  27310.8  27271.9 -0.001421
2023-05-24 00:10:01,260:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1377 

self.closeSec=1684858799, self.tradeDate='20230524', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27272', self.close='27268.9'
127.0.0.1 - - [24/May/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-05-24 00:20:05,815:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684858799, self.tradeDate='20230524', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27272', self.close='27268.9'
2023-05-24 00:20:06,346:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230523   233000    233959  1684856399  27316.9  27300.9 -0.000586
574  20230523   234000    234959  1684856999  27300.9  27302.6  0.000062
575  20230523   235000    235959  1684857599  27302.6  27310.7  0.000297
576  20230524   000000    000959  1684858199  27310.8  27271.9 -0.001421
577  20230524   001000    001959  1684858799    27272  27268.9 -0.000110
2023-05-24 00:20:06,347:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-05-24 00:00:02,358:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-05-24 00:00:02,507:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:5240000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230523, closeTime:235959, close:27310.7, total:973579.8686232, pct_pre:0.013898238267201712, thd:-0.8096939244329078, side:sell 
127.0.0.1 - - [24/May/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1379 

self.closeSec=1684858199, self.tradeDate='20230524', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27310.8', self.close='27271.9'
2023-05-24 00:10:01,217:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684858199, self.tradeDate='20230524', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27310.8', self.close='27271.9'
2023-05-24 00:10:01,272:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230523   232000    232959  1684855799    27299  27316.9
17421  20230523   233000    233959  1684856399  27316.9  27300.9
17422  20230523   234000    234959  1684856999  27300.9  27302.6
17423  20230523   235000    235959  1684857599  27302.6  27310.7
17424  20230524   000000    000959  1684858199  27310.8  27271.9
2023-05-24 00:10:01,273:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1380 

self.closeSec=1684858799, self.tradeDate='20230524', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27272', self.close='27268.9'
127.0.0.1 - - [24/May/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-05-24 00:20:07,291:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684858799, self.tradeDate='20230524', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27272', self.close='27268.9'
2023-05-24 00:20:07,392:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230523   233000    233959  1684856399  27316.9  27300.9
17422  20230523   234000    234959  1684856999  27300.9  27302.6
17423  20230523   235000    235959  1684857599  27302.6  27310.7
17424  20230524   000000    000959  1684858199  27310.8  27271.9
17425  20230524   001000    001959  1684858799    27272  27268.9
2023-05-24 00:20:07,392:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [24/May/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-05-24 00:00:04,664:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42245F1684857603910I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1684857604341696, 'quantity': '47.451', 'price': '27312.4', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1684857603011, 'updatetime': 1684857604341, 'tradetype': 'usdt', 'selfid': 42245, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1684857604341, 'clientorderid': '42245F1684857603910I0L2', 'price': '27312.4', 'quantity': '47.451', 'commission': '1296.0006924', 'commissionasset': 'USDT', 'tradetime': 1684857604341, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1684857604341}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [24/May/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1379 

self.closeSec=1684858199, self.tradeDate='20230524', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27310.8', self.close='27271.9'
2023-05-24 00:10:01,213:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684858199, self.tradeDate='20230524', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27310.8', self.close='27271.9'
2023-05-24 00:10:01,266:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230523   232000    232959  1684855799    27299  27316.9
12237  20230523   233000    233959  1684856399  27316.9  27300.9
12238  20230523   234000    234959  1684856999  27300.9  27302.6
12239  20230523   235000    235959  1684857599  27302.6  27310.7
12240  20230524   000000    000959  1684858199  27310.8  27271.9
2023-05-24 00:10:01,266:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1380 

self.closeSec=1684858799, self.tradeDate='20230524', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27272', self.close='27268.9'
127.0.0.1 - - [24/May/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-05-24 00:20:07,008:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684858799, self.tradeDate='20230524', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27272', self.close='27268.9'
2023-05-24 00:20:07,191:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230523   233000    233959  1684856399  27316.9  27300.9
12238  20230523   234000    234959  1684856999  27300.9  27302.6
12239  20230523   235000    235959  1684857599  27302.6  27310.7
12240  20230524   000000    000959  1684858199  27310.8  27271.9
12241  20230524   001000    001959  1684858799    27272  27268.9
2023-05-24 00:20:07,191:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=2752
self.closeSec=1684858799, self.tradeDate='20230524', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27294.5, self.close=27268.9, self.high=27297.3, self.low=27257.6, self.vol=961.638, self.amt=26225873.1097 
127.0.0.1 - - [24/May/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-05-24 00:20:05,474:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230523   235500    235959  ...         0.0        0.0       0
5760  20230524   000000    000459  ...         0.0        0.0       0
5761  20230524   000500    000959  ...         0.0        0.0       0
5762  20230524   001000    001459  ...         0.0        0.0       0
5763  20230524   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-24 00:20:05,495:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684858799, self.tradeDate='20230524', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27294.5, self.close=27268.9, self.high=27297.3, self.low=27257.6, self.vol=961.638, self.amt=26225873.1097, ukdf['pct'].iloc[-1]=-0.000934 , ukdf['amount'].iloc[-1]=26225873.1097, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '15777.4968', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27268.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=2753
self.closeSec=1684859099, self.tradeDate='20230524', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27268.8, self.close=27285.4, self.high=27288.7, self.low=27262.1, self.vol=422.007, self.amt=11510775.1904 
127.0.0.1 - - [24/May/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-05-24 00:25:00,888:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230524   000000    000459  ...         0.0        0.0       0
5761  20230524   000500    000959  ...         0.0        0.0       0
5762  20230524   001000    001459  ...         0.0        0.0       0
5763  20230524   001500    001959  ...         0.0        0.0       0
5764  20230524   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-24 00:25:00,889:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684859099, self.tradeDate='20230524', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27268.8, self.close=27285.4, self.high=27288.7, self.low=27262.1, self.vol=422.007, self.amt=11510775.1904, ukdf['pct'].iloc[-1]=0.000605 , ukdf['amount'].iloc[-1]=11510775.1904, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '16489.41802770158', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27287.96806838', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230523   120000    155959  1684828799  ...    723  0.225133 -0.915867    -1.0
724  20230523   160000    195959  1684843199  ...    724  0.255594 -0.760390    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.549', 'enterprice': '27070.5', 'countrevence': '0', 'unrealprofit': '-13416.31748234667', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27330.76338983', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1394061.7472955, self.flagDict['side']='sell', self.tradeCount=2, self.count=57
self.closeSec=1684857599, self.tradeDate='20230523', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=27327.0, self.close=27310.7, self.high=27383.0, self.low=27159.3, self.vol=63502.505, self.amt=1732442231.70318 
127.0.0.1 - - [24/May/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-05-24 00:00:01,879:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1684857599, self.tradeDate='20230523', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=27327.0, self.close=27310.7, self.high=27383.0, self.low=27159.3, self.vol=63502.505, self.amt=1732442231.70318 
2023-05-24 00:00:01,903:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230523   040000    075959  ...   19533.419  5.250148e+08 -0.000626
722  20230523   080000    115959  ...  112108.995  3.042695e+09  0.019165
723  20230523   120000    155959  ...   83809.328  2.292565e+09 -0.002150
724  20230523   160000    195959  ...   32695.377  8.924195e+08  0.001139
725  20230523   200000    235959  ...   63502.505  1.732442e+09 -0.000593

[5 rows x 11 columns]
2023-05-24 00:00:03,948:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230523   040000    075959  1684799999  ...    721  0.070159 -1.676941    -1.0
722  20230523   080000    115959  1684814399  ...    722  0.058479 -1.698103    -1.0
723  20230523   120000    155959  1684828799  ...    723  0.225133 -0.915867    -1.0
724  20230523   160000    195959  1684843199  ...    724  0.255594 -0.760390    -1.0
725  20230523   200000    235959  1684857599  ...    725  0.307050 -0.510986     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.549', 'enterprice': '27070.5', 'countrevence': '0', 'unrealprofit': '-12510.04980690399', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27313.18268651', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


