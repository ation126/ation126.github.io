# 20230212 08:36:17

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=22110
self.closeSec=1676161799, self.tradeDate='20230212', self.openTime='082500', self.closeTime='082959', self.symbol='BTCUSDT', self.open=21841.3, self.close=21836.7, self.high=21848.1, self.low=21833.2, self.vol=320.214, self.amt=6994041.7365 
127.0.0.1 - - [12/Feb/2023 08:30:00] "POST / HTTP/1.1" 200 -
2023-02-12 08:30:00,626:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5857  20230212   080500    080959  ...         0.0        0.0       0
5858  20230212   081000    081459  ...         0.0        0.0       0
5859  20230212   081500    081959  ...         0.0        0.0       0
5860  20230212   082000    082459  ...         0.0        0.0       0
5861  20230212   082500    082959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-12 08:30:00,627:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676161799, self.tradeDate='20230212', self.openTime='082500', self.closeTime='082959',self.symbol='BTCUSDT',self.open=21841.3, self.close=21836.7, self.high=21848.1, self.low=21833.2, self.vol=320.214, self.amt=6994041.7365, ukdf['pct'].iloc[-1]=-0.000206 , ukdf['amount'].iloc[-1]=6994041.7365, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5861, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-319478.18179942928', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21838.36311153', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=22111
self.closeSec=1676162099, self.tradeDate='20230212', self.openTime='083000', self.closeTime='083459', self.symbol='BTCUSDT', self.open=21836.8, self.close=21826.6, self.high=21837.8, self.low=21821.4, self.vol=394.298, self.amt=8607246.0207 
127.0.0.1 - - [12/Feb/2023 08:35:00] "POST / HTTP/1.1" 200 -
2023-02-12 08:35:00,535:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5858  20230212   081000    081459  ...         0.0        0.0       0
5859  20230212   081500    081959  ...         0.0        0.0       0
5860  20230212   082000    082459  ...         0.0        0.0       0
5861  20230212   082500    082959  ...         0.0        0.0       0
5862  20230212   083000    083459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-12 08:35:00,537:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676162099, self.tradeDate='20230212', self.openTime='083000', self.closeTime='083459',self.symbol='BTCUSDT',self.open=21836.8, self.close=21826.6, self.high=21837.8, self.low=21821.4, self.vol=394.298, self.amt=8607246.0207, ukdf['pct'].iloc[-1]=-0.000463 , ukdf['amount'].iloc[-1]=8607246.0207, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5862, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-318770.3248', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21826.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

1540  20230212   082000    082459  1676161499  ...  21834.6  0.000307   1540    4
1541  20230212   082500    082959  1676161799  ...  21833.2 -0.000206   1541    5

[5 rows x 11 columns]
2023-02-12 08:30:00,596:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
2023-02-12 08:30:00,724:INFO:factorcheck2:main.py:145:handleKline:185239: df_panel.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...       pct  index  idx    factor
213  20230212   062500    062959  1676154599  ... -0.000454   1517    5  0.526654
214  20230212   065500    065959  1676156399  ... -0.000385   1523    5  0.514642
215  20230212   072500    072959  1676158199  ...  0.001186   1529    5  0.503727
216  20230212   075500    075959  1676159999  ... -0.000595   1535    5  0.494114
217  20230212   082500    082959  1676161799  ... -0.000206   1541    5  0.486257

[5 rows x 12 columns]

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=18, self.factor=0.4862565381013553, self.count=22677 

self.closeSec=1676162099, self.tradeDate='20230212', self.openTime='083000', self.closeTime='083459', self.symbol='BTCUSDT', self.open=21836.8, self.close=21826.6, self.high=21837.8, self.low=21821.4 
2023-02-12 08:35:00,436:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676162099, self.tradeDate='20230212', self.openTime='083000', self.closeTime='083459',self.symbol='BTCUSDT',self.open=21836.8, self.close=21826.6, self.high=21837.8, self.low=21821.4   
127.0.0.1 - - [12/Feb/2023 08:35:00] "POST / HTTP/1.1" 200 -
2023-02-12 08:35:00,489:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1538  20230212   081000    081459  1676160899  ...  21832.8 -0.000288   1538    2
1539  20230212   081500    081959  1676161199  ...  21830.0 -0.000302   1539    3
1540  20230212   082000    082459  1676161499  ...  21834.6  0.000307   1540    4
1541  20230212   082500    082959  1676161799  ...  21833.2 -0.000206   1541    5
1542  20230212   083000    083459  1676162099  ...  21821.4 -0.000463   1542    0

[5 rows x 11 columns]
2023-02-12 08:35:00,489:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-12 08:30:33,130:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5771  20230212    055959  21684.0  ...  45.833333  0.488357  0.392017
5772  20230212    062959  21815.7  ...  45.833333  0.483384  0.379338
5773  20230212    065959  21800.1  ...  46.250000  0.487712  0.367765
5774  20230212    072959  21812.7  ...  46.666667  0.504030  0.347724
5775  20230212    075959  21861.2  ...  46.250000  0.500674  0.333838

[5 rows x 33 columns]
0.5083179297597042
acc is : 0.5083179297597042
2023-02-12 08:30:33,345:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.534076  0.465924       0  ...  1.015446  -1.0    0.0  0.941962
537     0  0.504171  0.495829       1  ...  1.014859  -1.0    0.0  0.942506
538     0  0.506402  0.493598       1  ...  1.012603  -1.0    0.0  0.944602
539     0  0.520496  0.479504       0  ...  1.013066  -1.0    0.0  0.944170
540     0  0.507605  0.492395       0  ...  1.013738  -1.0    0.0  0.943543

[5 rows x 10 columns]
2023-02-12 08:30:33,387:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.534719  0.465281       0  ...  1.015446  -1.0    0.0  0.943074
46     0  0.505035  0.494965       1  ...  1.014859  -1.0    0.0  0.944220
47     0  0.506751  0.493249       1  ...  1.012603  -1.0    0.0  0.945337
48     0  0.520843  0.479157       0  ...  1.013066  -1.0    0.0  0.944904
49     0  0.507605  0.492395       0  ...  1.013738  -1.0    0.0  0.943543

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.252', 'enterprice': '22924.6', 'countrevence': '0', 'unrealprofit': '35086.56335414384', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21836.71201308', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

624  20230212   080000    080959  1676160599  21851.2  21847.4 -0.000178
2023-02-12 08:10:01,737:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11337 

self.closeSec=1676161199, self.tradeDate='20230212', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='21845.1', self.close='21834.6'
2023-02-12 08:20:00,549:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676161199, self.tradeDate='20230212', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='21845.1', self.close='21834.6'
127.0.0.1 - - [12/Feb/2023 08:20:00] "POST / HTTP/1.1" 200 -
2023-02-12 08:20:00,609:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230212   073000    073959  1676158799  21861.2  21852.9 -0.000380
622  20230212   074000    074959  1676159399  21855.4  21856.8  0.000178
623  20230212   075000    075959  1676159999  21856.9  21851.3 -0.000252
624  20230212   080000    080959  1676160599  21851.2  21847.4 -0.000178
625  20230212   081000    081959  1676161199  21845.1  21834.6 -0.000586
2023-02-12 08:20:00,618:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11338 

self.closeSec=1676161799, self.tradeDate='20230212', self.openTime='082000', self.closeTime='082959', self.symbol='BTCUSDT', self.open='21834.6', self.close='21836.7'
2023-02-12 08:30:00,744:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676161799, self.tradeDate='20230212', self.openTime='082000', self.closeTime='082959',self.symbol='BTCUSDT',self.open='21834.6', self.close='21836.7'
127.0.0.1 - - [12/Feb/2023 08:30:00] "POST / HTTP/1.1" 200 -
2023-02-12 08:30:00,786:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
622  20230212   074000    074959  1676159399  21855.4  21856.8  0.000178
623  20230212   075000    075959  1676159999  21856.9  21851.3 -0.000252
624  20230212   080000    080959  1676160599  21851.2  21847.4 -0.000178
625  20230212   081000    081959  1676161199  21845.1  21834.6 -0.000586
626  20230212   082000    082959  1676161799  21834.6  21836.7  0.000096
2023-02-12 08:30:00,786:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17472  20230212   080000    080959  1676160599  21851.2  21847.4
2023-02-12 08:10:01,792:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [12/Feb/2023 08:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11338 

self.closeSec=1676161199, self.tradeDate='20230212', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='21845.1', self.close='21834.6'
2023-02-12 08:20:00,536:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676161199, self.tradeDate='20230212', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='21845.1', self.close='21834.6'
2023-02-12 08:20:00,651:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230212   073000    073959  1676158799  21861.2  21852.9
17470  20230212   074000    074959  1676159399  21855.4  21856.8
17471  20230212   075000    075959  1676159999  21856.9  21851.3
17472  20230212   080000    080959  1676160599  21851.2  21847.4
17473  20230212   081000    081959  1676161199  21845.1  21834.6
2023-02-12 08:20:00,651:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [12/Feb/2023 08:30:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11339 

self.closeSec=1676161799, self.tradeDate='20230212', self.openTime='082000', self.closeTime='082959', self.symbol='BTCUSDT', self.open='21834.6', self.close='21836.7'
2023-02-12 08:30:00,797:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676161799, self.tradeDate='20230212', self.openTime='082000', self.closeTime='082959',self.symbol='BTCUSDT',self.open='21834.6', self.close='21836.7'
2023-02-12 08:30:00,833:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17470  20230212   074000    074959  1676159399  21855.4  21856.8
17471  20230212   075000    075959  1676159999  21856.9  21851.3
17472  20230212   080000    080959  1676160599  21851.2  21847.4
17473  20230212   081000    081959  1676161199  21845.1  21834.6
17474  20230212   082000    082959  1676161799  21834.6  21836.7
2023-02-12 08:30:00,833:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12144  20230212   080000    080959  1676160599  21851.2  21847.4
2023-02-12 08:10:01,800:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [12/Feb/2023 08:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11338 

self.closeSec=1676161199, self.tradeDate='20230212', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='21845.1', self.close='21834.6'
2023-02-12 08:20:00,557:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676161199, self.tradeDate='20230212', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='21845.1', self.close='21834.6'
2023-02-12 08:20:00,600:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230212   073000    073959  1676158799  21861.2  21852.9
12142  20230212   074000    074959  1676159399  21855.4  21856.8
12143  20230212   075000    075959  1676159999  21856.9  21851.3
12144  20230212   080000    080959  1676160599  21851.2  21847.4
12145  20230212   081000    081959  1676161199  21845.1  21834.6
2023-02-12 08:20:00,600:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11339 

self.closeSec=1676161799, self.tradeDate='20230212', self.openTime='082000', self.closeTime='082959', self.symbol='BTCUSDT', self.open='21834.6', self.close='21836.7'
2023-02-12 08:30:00,758:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676161799, self.tradeDate='20230212', self.openTime='082000', self.closeTime='082959',self.symbol='BTCUSDT',self.open='21834.6', self.close='21836.7'
127.0.0.1 - - [12/Feb/2023 08:30:00] "POST / HTTP/1.1" 200 -
2023-02-12 08:30:00,789:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12142  20230212   074000    074959  1676159399  21855.4  21856.8
12143  20230212   075000    075959  1676159999  21856.9  21851.3
12144  20230212   080000    080959  1676160599  21851.2  21847.4
12145  20230212   081000    081959  1676161199  21845.1  21834.6
12146  20230212   082000    082959  1676161799  21834.6  21836.7
2023-02-12 08:30:00,789:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [12/Feb/2023 08:30:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=18108
self.closeSec=1676161799, self.tradeDate='20230212', self.openTime='082500', self.closeTime='082959', self.symbol='BTCUSDT', self.open=21841.3, self.close=21836.7, self.high=21848.1, self.low=21833.2, self.vol=320.214, self.amt=6994041.7365 
2023-02-12 08:30:00,600:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5857  20230212   080500    080959  ...         0.0        0.0       0
5858  20230212   081000    081459  ...         0.0        0.0       0
5859  20230212   081500    081959  ...         0.0        0.0       0
5860  20230212   082000    082459  ...         0.0        0.0       0
5861  20230212   082500    082959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-12 08:30:00,604:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676161799, self.tradeDate='20230212', self.openTime='082500', self.closeTime='082959',self.symbol='BTCUSDT',self.open=21841.3, self.close=21836.7, self.high=21848.1, self.low=21833.2, self.vol=320.214, self.amt=6994041.7365, ukdf['pct'].iloc[-1]=-0.000206 , ukdf['amount'].iloc[-1]=6994041.7365, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5861, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=18109
self.closeSec=1676162099, self.tradeDate='20230212', self.openTime='083000', self.closeTime='083459', self.symbol='BTCUSDT', self.open=21836.8, self.close=21826.6, self.high=21837.8, self.low=21821.4, self.vol=394.298, self.amt=8607246.0207 
127.0.0.1 - - [12/Feb/2023 08:35:00] "POST / HTTP/1.1" 200 -
2023-02-12 08:35:00,541:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5858  20230212   081000    081459  ...         0.0        0.0       0
5859  20230212   081500    081959  ...         0.0        0.0       0
5860  20230212   082000    082459  ...         0.0        0.0       0
5861  20230212   082500    082959  ...         0.0        0.0       0
5862  20230212   083000    083459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-12 08:35:00,562:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676162099, self.tradeDate='20230212', self.openTime='083000', self.closeTime='083459',self.symbol='BTCUSDT',self.open=21836.8, self.close=21826.6, self.high=21837.8, self.low=21821.4, self.vol=394.298, self.amt=8607246.0207, ukdf['pct'].iloc[-1]=-0.000463 , ukdf['amount'].iloc[-1]=8607246.0207, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5862, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230211   200000    235959  1676131199  ...    719  0.904919  1.807932     1.0
720  20230212   000000    035959  1676145599  ...    720  0.939167  1.927672     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.94', 'enterprice': '21730.2', 'countrevence': '0', 'unrealprofit': '-3296.6052998544', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '21653.42763624', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=932161.693212, self.flagDict['side']='buy', self.tradeCount=18, self.count=472
self.closeSec=1676159999, self.tradeDate='20230212', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=21652.6, self.close=21851.3, self.high=21891.9, self.low=21635.5, self.vol=48036.847, self.amt=1046276063.8233 
127.0.0.1 - - [12/Feb/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-02-12 08:00:01,044:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1676159999, self.tradeDate='20230212', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=21652.6, self.close=21851.3, self.high=21891.9, self.low=21635.5, self.vol=48036.847, self.amt=1046276063.8233 
2023-02-12 08:00:01,108:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230211   120000    155959  ...  17658.503  3.826146e+08  0.000605
718  20230211   160000    195959  ...  16676.367  3.614731e+08  0.000341
719  20230211   200000    235959  ...  37452.026  8.133733e+08  0.001734
720  20230212   000000    035959  ...  34876.792  7.556790e+08 -0.003424
721  20230212   040000    075959  ...  48036.847  1.046276e+09  0.009181

[5 rows x 11 columns]
2023-02-12 08:00:03,248:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230211   120000    155959  1676102399  ...    717  0.829825  1.509562     1.0
718  20230211   160000    195959  1676116799  ...    718  0.877107  1.707445     1.0
719  20230211   200000    235959  1676131199  ...    719  0.904919  1.807932     1.0
720  20230212   000000    035959  1676145599  ...    720  0.939167  1.927672     1.0
721  20230212   040000    075959  1676159999  ...    721  0.909492  1.737454     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.94', 'enterprice': '21730.2', 'countrevence': '0', 'unrealprofit': '5195.74', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '21851.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


