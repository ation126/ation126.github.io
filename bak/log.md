# 20230213 00:36:04

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [13/Feb/2023 00:30:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=22302
self.closeSec=1676219399, self.tradeDate='20230213', self.openTime='002500', self.closeTime='002959', self.symbol='BTCUSDT', self.open=21920.1, self.close=21932.3, self.high=21935.3, self.low=21901.0, self.vol=1091.162, self.amt=23917167.1996 
2023-02-13 00:30:00,600:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5761  20230213   000500    000959  ...         0.0        0.0       0
5762  20230213   001000    001459  ...         0.0        0.0       0
5763  20230213   001500    001959  ...         0.0        0.0       0
5764  20230213   002000    002459  ...         0.0        0.0       0
5765  20230213   002500    002959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-13 00:30:00,601:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676219399, self.tradeDate='20230213', self.openTime='002500', self.closeTime='002959',self.symbol='BTCUSDT',self.open=21920.1, self.close=21932.3, self.high=21935.3, self.low=21901.0, self.vol=1091.162, self.amt=23917167.1996, ukdf['pct'].iloc[-1]=0.000557 , ukdf['amount'].iloc[-1]=23917167.1996, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5765, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-325124.9104', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21932.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=22303
self.closeSec=1676219699, self.tradeDate='20230213', self.openTime='003000', self.closeTime='003459', self.symbol='BTCUSDT', self.open=21932.2, self.close=22002.6, self.high=22052.3, self.low=21921.8, self.vol=5814.904, self.amt=127904774.5889 
127.0.0.1 - - [13/Feb/2023 00:35:00] "POST / HTTP/1.1" 200 -
2023-02-13 00:35:00,504:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5762  20230213   001000    001459  ...         0.0        0.0       0
5763  20230213   001500    001959  ...         0.0        0.0       0
5764  20230213   002000    002459  ...         0.0        0.0       0
5765  20230213   002500    002959  ...         0.0        0.0       0
5766  20230213   003000    003459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-13 00:35:00,505:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676219699, self.tradeDate='20230213', self.openTime='003000', self.closeTime='003459',self.symbol='BTCUSDT',self.open=21932.2, self.close=22002.6, self.high=22052.3, self.low=21921.8, self.vol=5814.904, self.amt=127904774.5889, ukdf['pct'].iloc[-1]=0.003205 , ukdf['amount'].iloc[-1]=127904774.5889, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5766, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-329263.19723078816', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22000.96972266', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

1444  20230213   002000    002459  1676219099  ...  21918.9 -0.002031   1444    4
1445  20230213   002500    002959  1676219399  ...  21901.0  0.000557   1445    5

[5 rows x 11 columns]
2023-02-13 00:30:00,600:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-02-13 00:30:00,677:INFO:factorcheck2:main.py:145:handleKline:185239: df_panel.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...       pct  index  idx    factor
197  20230212   222500    222959  1676212199  ...  0.000353   1709    5  0.402115
198  20230212   225500    225959  1676213999  ...  0.000630   1715    5  0.393056
199  20230212   232500    232959  1676215799  ... -0.000995   1721    5  0.386803
200  20230212   235500    235959  1676217599  ...  0.001502   1727    5  0.378469
201  20230213   002500    002959  1676219399  ...  0.000557   1445    5  0.370258

[5 rows x 12 columns]

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=1, self.factor=0.3702581781422948, self.count=22869 

self.closeSec=1676219699, self.tradeDate='20230213', self.openTime='003000', self.closeTime='003459', self.symbol='BTCUSDT', self.open=21932.2, self.close=22002.6, self.high=22052.3, self.low=21921.8 
127.0.0.1 - - [13/Feb/2023 00:35:00] "POST / HTTP/1.1" 200 -
2023-02-13 00:35:00,441:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676219699, self.tradeDate='20230213', self.openTime='003000', self.closeTime='003459',self.symbol='BTCUSDT',self.open=21932.2, self.close=22002.6, self.high=22052.3, self.low=21921.8   
2023-02-13 00:35:00,468:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1442  20230213   001000    001459  1676218499  ...  21942.3 -0.000150   1442    2
1443  20230213   001500    001959  1676218799  ...  21922.5  0.000993   1443    3
1444  20230213   002000    002459  1676219099  ...  21918.9 -0.002031   1444    4
1445  20230213   002500    002959  1676219399  ...  21901.0  0.000557   1445    5
1446  20230213   003000    003459  1676219699  ...  21921.8  0.003205   1446    0

[5 rows x 11 columns]
2023-02-13 00:35:00,468:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-13 00:30:35,064:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5755  20230212    215959  21787.7  ...  45.833333  0.488988  0.323221
5756  20230212    222959  21807.8  ...  46.250000  0.496383  0.326390
5757  20230212    225959  21826.0  ...  46.250000  0.529910  0.320462
5758  20230212    232959  21913.8  ...  46.250000  0.518372  0.320194
5759  20230212    235959  21885.0  ...  46.250000  0.534981  0.311487

[5 rows x 33 columns]
0.5250463821892394
acc is : 0.5250463821892394
2023-02-13 00:30:35,270:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
534     1  0.494055  0.505945       1  ...  1.005486  -1.0    0.0  0.949200
535     1  0.493162  0.506838       1  ...  1.001436  -1.0    0.0  0.953023
536     0  0.515285  0.484715       0  ...  1.002752  -1.0    0.0  0.951770
537     1  0.496004  0.503996       1  ...  1.000631  -1.0    0.0  0.953784
538     0  0.517201  0.482799       0  ...  1.000909  -1.0    0.0  0.953518

[5 rows x 10 columns]
2023-02-13 00:30:35,299:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.493523  0.506477       1  ...  1.005486  -1.0    0.0  0.946487
46     1  0.492601  0.507399       1  ...  1.001436  -1.0    0.0  0.950299
47     0  0.514416  0.485584       0  ...  1.002752  -1.0    0.0  0.947079
48     1  0.495393  0.504607       1  ...  1.000631  -1.0    0.0  0.950600
49     0  0.517201  0.482799       0  ...  1.000909  -1.0    0.0  0.953518

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.252', 'enterprice': '22924.6', 'countrevence': '0', 'unrealprofit': '32293.72023286332', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21923.30642959', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

576  20230213   000000    000959  1676218199  21931.4  21946.2  0.000675
2023-02-13 00:10:01,575:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [13/Feb/2023 00:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11433 

self.closeSec=1676218799, self.tradeDate='20230213', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='21946.1', self.close='21960.8'
2023-02-13 00:20:00,521:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676218799, self.tradeDate='20230213', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='21946.1', self.close='21960.8'
2023-02-13 00:20:00,583:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230212   233000    233959  1676216399    21885  21904.4  0.000886
574  20230212   234000    234959  1676216999  21904.4  21910.5  0.000278
575  20230212   235000    235959  1676217599  21910.6  21931.4  0.000954
576  20230213   000000    000959  1676218199  21931.4  21946.2  0.000675
577  20230213   001000    001959  1676218799  21946.1  21960.8  0.000665
2023-02-13 00:20:00,583:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [13/Feb/2023 00:30:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11434 

self.closeSec=1676219399, self.tradeDate='20230213', self.openTime='002000', self.closeTime='002959', self.symbol='BTCUSDT', self.open='21960.8', self.close='21932.3'
2023-02-13 00:30:00,704:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676219399, self.tradeDate='20230213', self.openTime='002000', self.closeTime='002959',self.symbol='BTCUSDT',self.open='21960.8', self.close='21932.3'
2023-02-13 00:30:00,790:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
574  20230212   234000    234959  1676216999  21904.4  21910.5  0.000278
575  20230212   235000    235959  1676217599  21910.6  21931.4  0.000954
576  20230213   000000    000959  1676218199  21931.4  21946.2  0.000675
577  20230213   001000    001959  1676218799  21946.1  21960.8  0.000665
578  20230213   002000    002959  1676219399  21960.8  21932.3 -0.001298
2023-02-13 00:30:00,795:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/percentile_regression_step2/log.txt ----- -----

    return _evaluate(op, op_str, a, b)  # type: ignore[misc]
  File "/usr/local/lib/python3.8/dist-packages/pandas/core/computation/expressions.py", line 69, in _evaluate_standard
    return op(a, b)
TypeError: unsupported operand type(s) for /: 'str' and 'float'

During handling of the above exception, another exception occurred:

Traceback (most recent call last):
  File "/root/FIL/strategy/percentile_regression_step2/FIL_lib/client.py", line 95, in __start_handle
    handle_call(handle_data)
  File "main.py", line 186, in handleKline
    factor = self.get_signal(data)
  File "main.py", line 138, in get_signal
    df_id['pct'] = df_id['close'] / df_id['close'].shift(1) - 1
  File "/usr/local/lib/python3.8/dist-packages/pandas/core/ops/common.py", line 70, in new_method
    return method(self, other)
  File "/usr/local/lib/python3.8/dist-packages/pandas/core/arraylike.py", line 124, in __truediv__
    return self._arith_method(other, operator.truediv)
  File "/usr/local/lib/python3.8/dist-packages/pandas/core/series.py", line 5639, in _arith_method
    return base.IndexOpsMixin._arith_method(self, other, op)
  File "/usr/local/lib/python3.8/dist-packages/pandas/core/base.py", line 1295, in _arith_method
    result = ops.arithmetic_op(lvalues, rvalues, op)
  File "/usr/local/lib/python3.8/dist-packages/pandas/core/ops/array_ops.py", line 222, in arithmetic_op
    res_values = _na_arithmetic_op(left, right, op)
  File "/usr/local/lib/python3.8/dist-packages/pandas/core/ops/array_ops.py", line 170, in _na_arithmetic_op
    result = _masked_arith_op(left, right, op)
  File "/usr/local/lib/python3.8/dist-packages/pandas/core/ops/array_ops.py", line 108, in _masked_arith_op
    result[mask] = op(xrav[mask], yrav[mask])
TypeError: unsupported operand type(s) for /: 'str' and 'float'
127.0.0.1 - - [11/Feb/2023 22:30:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/pyemd/log.txt ----- -----

17424  20230213   000000    000959  1676218199  21931.4  21946.2
2023-02-13 00:10:01,603:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11434 

self.closeSec=1676218799, self.tradeDate='20230213', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='21946.1', self.close='21960.8'
127.0.0.1 - - [13/Feb/2023 00:20:00] "POST / HTTP/1.1" 200 -
2023-02-13 00:20:00,514:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676218799, self.tradeDate='20230213', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='21946.1', self.close='21960.8'
2023-02-13 00:20:00,529:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230212   233000    233959  1676216399    21885  21904.4
17422  20230212   234000    234959  1676216999  21904.4  21910.5
17423  20230212   235000    235959  1676217599  21910.6  21931.4
17424  20230213   000000    000959  1676218199  21931.4  21946.2
17425  20230213   001000    001959  1676218799  21946.1  21960.8
2023-02-13 00:20:00,543:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11435 

self.closeSec=1676219399, self.tradeDate='20230213', self.openTime='002000', self.closeTime='002959', self.symbol='BTCUSDT', self.open='21960.8', self.close='21932.3'
127.0.0.1 - - [13/Feb/2023 00:30:00] "POST / HTTP/1.1" 200 -
2023-02-13 00:30:00,734:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676219399, self.tradeDate='20230213', self.openTime='002000', self.closeTime='002959',self.symbol='BTCUSDT',self.open='21960.8', self.close='21932.3'
2023-02-13 00:30:00,799:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17422  20230212   234000    234959  1676216999  21904.4  21910.5
17423  20230212   235000    235959  1676217599  21910.6  21931.4
17424  20230213   000000    000959  1676218199  21931.4  21946.2
17425  20230213   001000    001959  1676218799  21946.1  21960.8
17426  20230213   002000    002959  1676219399  21960.8  21932.3
2023-02-13 00:30:00,799:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12240  20230213   000000    000959  1676218199  21931.4  21946.2
2023-02-13 00:10:01,595:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
127.0.0.1 - - [13/Feb/2023 00:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11434 

self.closeSec=1676218799, self.tradeDate='20230213', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='21946.1', self.close='21960.8'
2023-02-13 00:20:00,543:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676218799, self.tradeDate='20230213', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='21946.1', self.close='21960.8'
2023-02-13 00:20:00,592:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230212   233000    233959  1676216399    21885  21904.4
12238  20230212   234000    234959  1676216999  21904.4  21910.5
12239  20230212   235000    235959  1676217599  21910.6  21931.4
12240  20230213   000000    000959  1676218199  21931.4  21946.2
12241  20230213   001000    001959  1676218799  21946.1  21960.8
2023-02-13 00:20:00,592:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11435 

self.closeSec=1676219399, self.tradeDate='20230213', self.openTime='002000', self.closeTime='002959', self.symbol='BTCUSDT', self.open='21960.8', self.close='21932.3'
127.0.0.1 - - [13/Feb/2023 00:30:00] "POST / HTTP/1.1" 200 -
2023-02-13 00:30:00,779:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676219399, self.tradeDate='20230213', self.openTime='002000', self.closeTime='002959',self.symbol='BTCUSDT',self.open='21960.8', self.close='21932.3'
2023-02-13 00:30:00,812:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12238  20230212   234000    234959  1676216999  21904.4  21910.5
12239  20230212   235000    235959  1676217599  21910.6  21931.4
12240  20230213   000000    000959  1676218199  21931.4  21946.2
12241  20230213   001000    001959  1676218799  21946.1  21960.8
12242  20230213   002000    002959  1676219399  21960.8  21932.3
2023-02-13 00:30:00,817:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [13/Feb/2023 00:30:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=18300
self.closeSec=1676219399, self.tradeDate='20230213', self.openTime='002500', self.closeTime='002959', self.symbol='BTCUSDT', self.open=21920.1, self.close=21932.3, self.high=21935.3, self.low=21901.0, self.vol=1091.162, self.amt=23917167.1996 
2023-02-13 00:30:00,663:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5761  20230213   000500    000959  ...         0.0        0.0       0
5762  20230213   001000    001459  ...         0.0        0.0       0
5763  20230213   001500    001959  ...         0.0        0.0       0
5764  20230213   002000    002459  ...         0.0        0.0       0
5765  20230213   002500    002959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-13 00:30:00,664:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676219399, self.tradeDate='20230213', self.openTime='002500', self.closeTime='002959',self.symbol='BTCUSDT',self.open=21920.1, self.close=21932.3, self.high=21935.3, self.low=21901.0, self.vol=1091.162, self.amt=23917167.1996, ukdf['pct'].iloc[-1]=0.000557 , ukdf['amount'].iloc[-1]=23917167.1996, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5765, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=18301
self.closeSec=1676219699, self.tradeDate='20230213', self.openTime='003000', self.closeTime='003459', self.symbol='BTCUSDT', self.open=21932.2, self.close=22002.6, self.high=22052.3, self.low=21921.8, self.vol=5814.904, self.amt=127904774.5889 
127.0.0.1 - - [13/Feb/2023 00:35:00] "POST / HTTP/1.1" 200 -
2023-02-13 00:35:00,464:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5762  20230213   001000    001459  ...         0.0        0.0       0
5763  20230213   001500    001959  ...         0.0        0.0       0
5764  20230213   002000    002459  ...         0.0        0.0       0
5765  20230213   002500    002959  ...         0.0        0.0       0
5766  20230213   003000    003459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-13 00:35:00,467:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676219699, self.tradeDate='20230213', self.openTime='003000', self.closeTime='003459',self.symbol='BTCUSDT',self.open=21932.2, self.close=22002.6, self.high=22052.3, self.low=21921.8, self.vol=5814.904, self.amt=127904774.5889, ukdf['pct'].iloc[-1]=0.003205 , ukdf['amount'].iloc[-1]=127904774.5889, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5766, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230212   120000    155959  1676188799  ...    723  0.916684  1.695624     1.0
724  20230212   160000    195959  1676203199  ...    724  0.964438  1.883472     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.94', 'enterprice': '21730.2', 'countrevence': '0', 'unrealprofit': '6376.9842012232', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '21878.70918028', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [13/Feb/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=932161.693212, self.flagDict['side']='buy', self.tradeCount=18, self.count=476
self.closeSec=1676217599, self.tradeDate='20230212', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=21877.6, self.close=21931.3, self.high=22000.5, self.low=21750.0, self.vol=66423.188, self.amt=1452623137.9822 
2023-02-13 00:00:01,215:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1676217599, self.tradeDate='20230212', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=21877.6, self.close=21931.3, self.high=22000.5, self.low=21750.0, self.vol=66423.188, self.amt=1452623137.9822 
2023-02-13 00:00:01,260:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230212   040000    075959  ...  48036.847  1.046276e+09  0.009181
722  20230212   080000    115959  ...  23886.510  5.208709e+08 -0.003624
723  20230212   120000    155959  ...  13806.384  3.007564e+08  0.000739
724  20230212   160000    195959  ...  38816.768  8.486016e+08  0.004103
725  20230212   200000    235959  ...  66423.188  1.452623e+09  0.002455

[5 rows x 11 columns]
2023-02-13 00:00:03,475:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230212   040000    075959  1676159999  ...    721  0.909492  1.737454     1.0
722  20230212   080000    115959  1676174399  ...    722  0.910063  1.700538     1.0
723  20230212   120000    155959  1676188799  ...    723  0.916684  1.695624     1.0
724  20230212   160000    195959  1676203199  ...    724  0.964438  1.883472     1.0
725  20230212   200000    235959  1676217599  ...    725  1.041296  2.195449     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.94', 'enterprice': '21730.2', 'countrevence': '0', 'unrealprofit': '8809.7594162978', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '21935.36440187', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


