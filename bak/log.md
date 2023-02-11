# 20230212 00:36:06

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [12/Feb/2023 00:30:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=22014
self.closeSec=1676132999, self.tradeDate='20230212', self.openTime='002500', self.closeTime='002959', self.symbol='BTCUSDT', self.open=21714.9, self.close=21717.1, self.high=21717.6, self.low=21703.7, self.vol=475.216, self.amt=10317582.8465 
2023-02-12 00:30:00,941:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5761  20230212   000500    000959  ...         0.0        0.0       0
5762  20230212   001000    001459  ...         0.0        0.0       0
5763  20230212   001500    001959  ...         0.0        0.0       0
5764  20230212   002000    002459  ...         0.0        0.0       0
5765  20230212   002500    002959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-12 00:30:00,943:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676132999, self.tradeDate='20230212', self.openTime='002500', self.closeTime='002959',self.symbol='BTCUSDT',self.open=21714.9, self.close=21717.1, self.high=21717.6, self.low=21703.7, self.vol=475.216, self.amt=10317582.8465, ukdf['pct'].iloc[-1]=0.000111 , ukdf['amount'].iloc[-1]=10317582.8465, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5765, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-312048.6656', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21714.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=22015
self.closeSec=1676133299, self.tradeDate='20230212', self.openTime='003000', self.closeTime='003459', self.symbol='BTCUSDT', self.open=21717.0, self.close=21690.6, self.high=21717.0, self.low=21690.6, self.vol=665.801, self.amt=14449159.1873 
127.0.0.1 - - [12/Feb/2023 00:35:00] "POST / HTTP/1.1" 200 -
2023-02-12 00:35:00,564:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5762  20230212   001000    001459  ...         0.0        0.0       0
5763  20230212   001500    001959  ...         0.0        0.0       0
5764  20230212   002000    002459  ...         0.0        0.0       0
5765  20230212   002500    002959  ...         0.0        0.0       0
5766  20230212   003000    003459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-12 00:35:00,564:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676133299, self.tradeDate='20230212', self.openTime='003000', self.closeTime='003459',self.symbol='BTCUSDT',self.open=21717.0, self.close=21690.6, self.high=21717.0, self.low=21690.6, self.vol=665.801, self.amt=14449159.1873, ukdf['pct'].iloc[-1]=-0.00122 , ukdf['amount'].iloc[-1]=14449159.1873, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5766, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-310778.40543282544', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21693.79091719', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

1444  20230212   002000    002459  1676132699  ...  21689.8  0.000346   1444    4
1445  20230212   002500    002959  1676132999  ...  21703.7  0.000111   1445    5

[5 rows x 11 columns]
2023-02-12 00:30:00,869:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
2023-02-12 00:30:00,947:INFO:factorcheck2:main.py:145:handleKline:185239: df_panel.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...       pct  index  idx    factor
197  20230211   222500    222959  1676125799  ... -0.000313   1709    5  0.626826
198  20230211   225500    225959  1676127599  ...  0.000741   1715    5  0.615116
199  20230211   232500    232959  1676129399  ... -0.000152   1721    5  0.605605
200  20230211   235500    235959  1676131199  ...  0.000378   1727    5  0.592434
201  20230212   002500    002959  1676132999  ...  0.000111   1445    5  0.580663

[5 rows x 12 columns]
127.0.0.1 - - [12/Feb/2023 00:35:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=2, self.factor=0.5806630365935486, self.count=22581 

self.closeSec=1676133299, self.tradeDate='20230212', self.openTime='003000', self.closeTime='003459', self.symbol='BTCUSDT', self.open=21717.0, self.close=21690.6, self.high=21717.0, self.low=21690.6 
2023-02-12 00:35:00,449:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676133299, self.tradeDate='20230212', self.openTime='003000', self.closeTime='003459',self.symbol='BTCUSDT',self.open=21717.0, self.close=21690.6, self.high=21717.0, self.low=21690.6   
2023-02-12 00:35:00,530:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1442  20230212   001000    001459  1676132099  ...  21712.2 -0.000249   1442    2
1443  20230212   001500    001959  1676132399  ...  21706.3 -0.000230   1443    3
1444  20230212   002000    002459  1676132699  ...  21689.8  0.000346   1444    4
1445  20230212   002500    002959  1676132999  ...  21703.7  0.000111   1445    5
1446  20230212   003000    003459  1676133299  ...  21690.6 -0.001220   1446    0

[5 rows x 11 columns]
2023-02-12 00:35:00,530:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-12 00:30:38,317:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...  alpha58   alpha67   alpha72
5755  20230211    215959  21725.4  ...    46.25  0.445779  0.420183
5756  20230211    222959  21738.3  ...    46.25  0.440390  0.405080
5757  20230211    225959  21719.0  ...    46.25  0.448359  0.387114
5758  20230211    232959  21741.6  ...    46.25  0.442526  0.373855
5759  20230211    235959  21721.1  ...    46.25  0.444612  0.359184

[5 rows x 33 columns]
0.5176252319109462
acc is : 0.5176252319109462
2023-02-12 00:30:38,505:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
534     0  0.509269  0.490731       0  ...  1.022214  -1.0    0.0  0.951707
535     1  0.498939  0.501061       1  ...  1.021150  -1.0    0.0  0.952697
536     0  0.507064  0.492936       0  ...  1.022113  -1.0    0.0  0.951799
537     1  0.497161  0.502839       1  ...  1.021840  -1.0    0.0  0.952053
538     1  0.499527  0.500473       0  ...  1.022301  -1.0    0.0  0.951624

[5 rows x 10 columns]
2023-02-12 00:30:38,526:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.506390  0.493610       0  ...  1.022214  -1.0    0.0  0.952371
46     1  0.496276  0.503724       1  ...  1.021150  -1.0    0.0  0.953362
47     0  0.503818  0.496182       0  ...  1.022113  -1.0    0.0  0.950325
48     1  0.493357  0.506643       1  ...  1.021840  -1.0    0.0  0.945976
49     1  0.499527  0.500473       0  ...  1.022301  -1.0    0.0  0.951624

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.252', 'enterprice': '22924.6', 'countrevence': '0', 'unrealprofit': '39128.1264', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21711.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

576  20230212   000000    000959  1676131799  21726.9  21717.6 -0.000428
2023-02-12 00:10:01,568:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11289 

self.closeSec=1676132399, self.tradeDate='20230212', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='21717.6', self.close='21707.2'
2023-02-12 00:20:00,513:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676132399, self.tradeDate='20230212', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='21717.6', self.close='21707.2'
127.0.0.1 - - [12/Feb/2023 00:20:00] "POST / HTTP/1.1" 200 -
2023-02-12 00:20:00,542:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230211   233000    233959  1676129999  21721.1  21720.4 -0.000032
574  20230211   234000    234959  1676130599  21720.4  21711.3 -0.000419
575  20230211   235000    235959  1676131199  21711.3  21726.9  0.000719
576  20230212   000000    000959  1676131799  21726.9  21717.6 -0.000428
577  20230212   001000    001959  1676132399  21717.6  21707.2 -0.000479
2023-02-12 00:20:00,544:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [12/Feb/2023 00:30:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11290 

self.closeSec=1676132999, self.tradeDate='20230212', self.openTime='002000', self.closeTime='002959', self.symbol='BTCUSDT', self.open='21707.1', self.close='21717.1'
2023-02-12 00:30:01,004:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676132999, self.tradeDate='20230212', self.openTime='002000', self.closeTime='002959',self.symbol='BTCUSDT',self.open='21707.1', self.close='21717.1'
2023-02-12 00:30:01,065:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
574  20230211   234000    234959  1676130599  21720.4  21711.3 -0.000419
575  20230211   235000    235959  1676131199  21711.3  21726.9  0.000719
576  20230212   000000    000959  1676131799  21726.9  21717.6 -0.000428
577  20230212   001000    001959  1676132399  21717.6  21707.2 -0.000479
578  20230212   002000    002959  1676132999  21707.1  21717.1  0.000456
2023-02-12 00:30:01,065:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17424  20230212   000000    000959  1676131799  21726.9  21717.6
2023-02-12 00:10:01,580:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [12/Feb/2023 00:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11290 

self.closeSec=1676132399, self.tradeDate='20230212', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='21717.6', self.close='21707.2'
2023-02-12 00:20:00,534:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676132399, self.tradeDate='20230212', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='21717.6', self.close='21707.2'
2023-02-12 00:20:00,584:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230211   233000    233959  1676129999  21721.1  21720.4
17422  20230211   234000    234959  1676130599  21720.4  21711.3
17423  20230211   235000    235959  1676131199  21711.3  21726.9
17424  20230212   000000    000959  1676131799  21726.9  21717.6
17425  20230212   001000    001959  1676132399  21717.6  21707.2
2023-02-12 00:20:00,588:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [12/Feb/2023 00:30:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11291 

self.closeSec=1676132999, self.tradeDate='20230212', self.openTime='002000', self.closeTime='002959', self.symbol='BTCUSDT', self.open='21707.1', self.close='21717.1'
2023-02-12 00:30:00,985:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676132999, self.tradeDate='20230212', self.openTime='002000', self.closeTime='002959',self.symbol='BTCUSDT',self.open='21707.1', self.close='21717.1'
2023-02-12 00:30:01,044:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17422  20230211   234000    234959  1676130599  21720.4  21711.3
17423  20230211   235000    235959  1676131199  21711.3  21726.9
17424  20230212   000000    000959  1676131799  21726.9  21717.6
17425  20230212   001000    001959  1676132399  21717.6  21707.2
17426  20230212   002000    002959  1676132999  21707.1  21717.1
2023-02-12 00:30:01,044:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12240  20230212   000000    000959  1676131799  21726.9  21717.6
2023-02-12 00:10:01,578:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
127.0.0.1 - - [12/Feb/2023 00:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11290 

self.closeSec=1676132399, self.tradeDate='20230212', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='21717.6', self.close='21707.2'
2023-02-12 00:20:00,543:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676132399, self.tradeDate='20230212', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='21717.6', self.close='21707.2'
2023-02-12 00:20:00,586:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230211   233000    233959  1676129999  21721.1  21720.4
12238  20230211   234000    234959  1676130599  21720.4  21711.3
12239  20230211   235000    235959  1676131199  21711.3  21726.9
12240  20230212   000000    000959  1676131799  21726.9  21717.6
12241  20230212   001000    001959  1676132399  21717.6  21707.2
2023-02-12 00:20:00,587:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11291 

self.closeSec=1676132999, self.tradeDate='20230212', self.openTime='002000', self.closeTime='002959', self.symbol='BTCUSDT', self.open='21707.1', self.close='21717.1'
127.0.0.1 - - [12/Feb/2023 00:30:00] "POST / HTTP/1.1" 200 -
2023-02-12 00:30:01,000:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676132999, self.tradeDate='20230212', self.openTime='002000', self.closeTime='002959',self.symbol='BTCUSDT',self.open='21707.1', self.close='21717.1'
2023-02-12 00:30:01,078:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12238  20230211   234000    234959  1676130599  21720.4  21711.3
12239  20230211   235000    235959  1676131199  21711.3  21726.9
12240  20230212   000000    000959  1676131799  21726.9  21717.6
12241  20230212   001000    001959  1676132399  21717.6  21707.2
12242  20230212   002000    002959  1676132999  21707.1  21717.1
2023-02-12 00:30:01,078:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=18012
self.closeSec=1676132999, self.tradeDate='20230212', self.openTime='002500', self.closeTime='002959', self.symbol='BTCUSDT', self.open=21714.9, self.close=21717.1, self.high=21717.6, self.low=21703.7, self.vol=475.216, self.amt=10317582.8465 
127.0.0.1 - - [12/Feb/2023 00:30:00] "POST / HTTP/1.1" 200 -
2023-02-12 00:30:00,844:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5761  20230212   000500    000959  ...         0.0        0.0       0
5762  20230212   001000    001459  ...         0.0        0.0       0
5763  20230212   001500    001959  ...         0.0        0.0       0
5764  20230212   002000    002459  ...         0.0        0.0       0
5765  20230212   002500    002959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-12 00:30:00,846:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676132999, self.tradeDate='20230212', self.openTime='002500', self.closeTime='002959',self.symbol='BTCUSDT',self.open=21714.9, self.close=21717.1, self.high=21717.6, self.low=21703.7, self.vol=475.216, self.amt=10317582.8465, ukdf['pct'].iloc[-1]=0.000111 , ukdf['amount'].iloc[-1]=10317582.8465, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5765, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=18013
self.closeSec=1676133299, self.tradeDate='20230212', self.openTime='003000', self.closeTime='003459', self.symbol='BTCUSDT', self.open=21717.0, self.close=21690.6, self.high=21717.0, self.low=21690.6, self.vol=665.801, self.amt=14449159.1873 
127.0.0.1 - - [12/Feb/2023 00:35:00] "POST / HTTP/1.1" 200 -
2023-02-12 00:35:00,477:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5762  20230212   001000    001459  ...         0.0        0.0       0
5763  20230212   001500    001959  ...         0.0        0.0       0
5764  20230212   002000    002459  ...         0.0        0.0       0
5765  20230212   002500    002959  ...         0.0        0.0       0
5766  20230212   003000    003459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-12 00:35:00,478:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676133299, self.tradeDate='20230212', self.openTime='003000', self.closeTime='003459',self.symbol='BTCUSDT',self.open=21717.0, self.close=21690.6, self.high=21717.0, self.low=21690.6, self.vol=665.801, self.amt=14449159.1873, ukdf['pct'].iloc[-1]=-0.00122 , ukdf['amount'].iloc[-1]=14449159.1873, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5766, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230211   120000    155959  1676102399  ...    723  0.829825  1.509562     1.0
724  20230211   160000    195959  1676116799  ...    724  0.877107  1.707445     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.94', 'enterprice': '21730.2', 'countrevence': '0', 'unrealprofit': '-1764.834', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '21689.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=932161.693212, self.flagDict['side']='buy', self.tradeCount=18, self.count=470
self.closeSec=1676131199, self.tradeDate='20230211', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=21689.2, self.close=21726.9, self.high=21770.0, self.low=21651.1, self.vol=37452.026, self.amt=813373286.8795 
127.0.0.1 - - [12/Feb/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-02-12 00:00:01,195:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1676131199, self.tradeDate='20230211', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=21689.2, self.close=21726.9, self.high=21770.0, self.low=21651.1, self.vol=37452.026, self.amt=813373286.8795 
2023-02-12 00:00:01,233:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230211   040000    075959  ...  69883.004  1.508450e+09 -0.006644
722  20230211   080000    115959  ...  34548.958  7.481311e+08  0.002322
723  20230211   120000    155959  ...  17658.503  3.826146e+08  0.000605
724  20230211   160000    195959  ...  16676.367  3.614731e+08  0.000341
725  20230211   200000    235959  ...  37452.026  8.133733e+08  0.001734

[5 rows x 11 columns]
2023-02-12 00:00:03,413:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230211   040000    075959  1676073599  ...    721  0.751064  1.182652     1.0
722  20230211   080000    115959  1676087999  ...    722  0.785671  1.324595     1.0
723  20230211   120000    155959  1676102399  ...    723  0.829825  1.509562     1.0
724  20230211   160000    195959  1676116799  ...    724  0.877107  1.707445     1.0
725  20230211   200000    235959  1676131199  ...    725  0.904919  1.807932     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.94', 'enterprice': '21730.2', 'countrevence': '0', 'unrealprofit': '-141.702', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '21726.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


