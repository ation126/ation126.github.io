# 20230212 16:36:04

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [12/Feb/2023 16:30:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=22206
self.closeSec=1676190599, self.tradeDate='20230212', self.openTime='162500', self.closeTime='162959', self.symbol='BTCUSDT', self.open=21800.4, self.close=21801.4, self.high=21801.5, self.low=21800.4, self.vol=115.794, self.amt=2524385.9676 
2023-02-12 16:30:00,630:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5953  20230212   160500    160959  ...         0.0        0.0       0
5954  20230212   161000    161459  ...         0.0        0.0       0
5955  20230212   161500    161959  ...         0.0        0.0       0
5956  20230212   162000    162459  ...         0.0        0.0       0
5957  20230212   162500    162959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-12 16:30:00,631:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676190599, self.tradeDate='20230212', self.openTime='162500', self.closeTime='162959',self.symbol='BTCUSDT',self.open=21800.4, self.close=21801.4, self.high=21801.5, self.low=21800.4, self.vol=115.794, self.amt=2524385.9676, ukdf['pct'].iloc[-1]=4.1e-05 , ukdf['amount'].iloc[-1]=2524385.9676, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5957, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-317259.9072', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21801.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [12/Feb/2023 16:35:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=22207
self.closeSec=1676190899, self.tradeDate='20230212', self.openTime='163000', self.closeTime='163459', self.symbol='BTCUSDT', self.open=21801.5, self.close=21803.4, self.high=21803.4, self.low=21799.2, self.vol=224.154, self.amt=4886768.4102 
2023-02-12 16:35:00,512:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5954  20230212   161000    161459  ...         0.0        0.0       0
5955  20230212   161500    161959  ...         0.0        0.0       0
5956  20230212   162000    162459  ...         0.0        0.0       0
5957  20230212   162500    162959  ...         0.0        0.0       0
5958  20230212   163000    163459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-12 16:35:00,512:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676190899, self.tradeDate='20230212', self.openTime='163000', self.closeTime='163459',self.symbol='BTCUSDT',self.open=21801.5, self.close=21803.4, self.high=21803.4, self.low=21799.2, self.vol=224.154, self.amt=4886768.4102, ukdf['pct'].iloc[-1]=9.2e-05 , ukdf['amount'].iloc[-1]=4886768.4102, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5958, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-317419.05162771024', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21804.14464949', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

1636  20230212   162000    162459  1676190299  ...  21800.0  0.000023   1636    4
1637  20230212   162500    162959  1676190599  ...  21800.4  0.000041   1637    5

[5 rows x 11 columns]
2023-02-12 16:30:00,667:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
2023-02-12 16:30:00,736:INFO:factorcheck2:main.py:145:handleKline:185239: df_panel.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...       pct  index  idx    factor
229  20230212   142500    142959  1676183399  ... -0.000078   1613    5  0.458641
230  20230212   145500    145959  1676185199  ...  0.000165   1619    5  0.455227
231  20230212   152500    152959  1676186999  ...  0.000023   1625    5  0.452367
232  20230212   155500    155959  1676188799  ... -0.000193   1631    5  0.450644
233  20230212   162500    162959  1676190599  ...  0.000041   1637    5  0.447586

[5 rows x 12 columns]

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=34, self.factor=0.4475863397845777, self.count=22773 

self.closeSec=1676190899, self.tradeDate='20230212', self.openTime='163000', self.closeTime='163459', self.symbol='BTCUSDT', self.open=21801.5, self.close=21803.4, self.high=21803.4, self.low=21799.2 
2023-02-12 16:35:00,416:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676190899, self.tradeDate='20230212', self.openTime='163000', self.closeTime='163459',self.symbol='BTCUSDT',self.open=21801.5, self.close=21803.4, self.high=21803.4, self.low=21799.2   
127.0.0.1 - - [12/Feb/2023 16:35:00] "POST / HTTP/1.1" 200 -
2023-02-12 16:35:00,486:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1634  20230212   161000    161459  1676189699  ...  21799.9  0.000060   1634    2
1635  20230212   161500    161959  1676189999  ...  21800.0 -0.000060   1635    3
1636  20230212   162000    162459  1676190299  ...  21800.0  0.000023   1636    4
1637  20230212   162500    162959  1676190599  ...  21800.4  0.000041   1637    5
1638  20230212   163000    163459  1676190899  ...  21799.2  0.000092   1638    0

[5 rows x 11 columns]
2023-02-12 16:35:00,486:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-12 16:30:32,544:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5787  20230212    135959  21788.2  ...  45.833333  0.482050  0.342030
5788  20230212    142959  21791.2  ...  45.833333  0.482416  0.342021
5789  20230212    145959  21792.0  ...  46.250000  0.486855  0.339546
5790  20230212    152959  21803.0  ...  45.833333  0.485086  0.338264
5791  20230212    155959  21798.3  ...  45.833333  0.481044  0.339397

[5 rows x 33 columns]
0.514760147601476
acc is : 0.514760147601476
2023-02-12 16:30:32,704:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.495695  0.504305       1  ...  1.007078  -1.0    0.0  0.945153
538     1  0.496487  0.503513       1  ...  1.006579  -1.0    0.0  0.945621
539     1  0.499416  0.500584       0  ...  1.006787  -1.0    0.0  0.945426
540     1  0.496080  0.503920       0  ...  1.007258  -1.0    0.0  0.944983
541     1  0.492810  0.507190       1  ...  1.006648  -1.0    0.0  0.945556

[5 rows x 10 columns]
2023-02-12 16:30:32,739:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.495670  0.504330       1  ...  1.007078  -1.0    0.0  0.943356
46     1  0.496078  0.503922       1  ...  1.006579  -1.0    0.0  0.943056
47     1  0.499400  0.500600       0  ...  1.006787  -1.0    0.0  0.946316
48     1  0.495719  0.504281       0  ...  1.007258  -1.0    0.0  0.944185
49     1  0.492810  0.507190       1  ...  1.006648  -1.0    0.0  0.945556

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.252', 'enterprice': '22924.6', 'countrevence': '0', 'unrealprofit': '36276.8261565314', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21799.80692805', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

528  20230212   160000    160959  1676189399  21788.2    21800  0.000542
2023-02-12 16:10:01,576:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [12/Feb/2023 16:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11385 

self.closeSec=1676189999, self.tradeDate='20230212', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='21800', self.close='21800'
2023-02-12 16:20:00,752:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676189999, self.tradeDate='20230212', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='21800', self.close='21800'
2023-02-12 16:20:00,784:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230212   153000    153959  1676187599  21798.3  21789.4 -0.000413
526  20230212   154000    154959  1676188199  21789.4  21796.3  0.000317
527  20230212   155000    155959  1676188799  21796.2  21788.2 -0.000372
528  20230212   160000    160959  1676189399  21788.2    21800  0.000542
529  20230212   161000    161959  1676189999    21800    21800  0.000000
2023-02-12 16:20:00,785:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [12/Feb/2023 16:30:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11386 

self.closeSec=1676190599, self.tradeDate='20230212', self.openTime='162000', self.closeTime='162959', self.symbol='BTCUSDT', self.open='21800.1', self.close='21801.4'
2023-02-12 16:30:00,758:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676190599, self.tradeDate='20230212', self.openTime='162000', self.closeTime='162959',self.symbol='BTCUSDT',self.open='21800.1', self.close='21801.4'
2023-02-12 16:30:00,813:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
526  20230212   154000    154959  1676188199  21789.4  21796.3  0.000317
527  20230212   155000    155959  1676188799  21796.2  21788.2 -0.000372
528  20230212   160000    160959  1676189399  21788.2    21800  0.000542
529  20230212   161000    161959  1676189999    21800    21800  0.000000
530  20230212   162000    162959  1676190599  21800.1  21801.4  0.000064
2023-02-12 16:30:00,813:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17520  20230212   160000    160959  1676189399  21788.2    21800
2023-02-12 16:10:01,550:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11386 

self.closeSec=1676189999, self.tradeDate='20230212', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='21800', self.close='21800'
2023-02-12 16:20:00,776:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676189999, self.tradeDate='20230212', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='21800', self.close='21800'
127.0.0.1 - - [12/Feb/2023 16:20:00] "POST / HTTP/1.1" 200 -
2023-02-12 16:20:00,813:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230212   153000    153959  1676187599  21798.3  21789.4
17518  20230212   154000    154959  1676188199  21789.4  21796.3
17519  20230212   155000    155959  1676188799  21796.2  21788.2
17520  20230212   160000    160959  1676189399  21788.2    21800
17521  20230212   161000    161959  1676189999    21800    21800
2023-02-12 16:20:00,813:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [12/Feb/2023 16:30:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11387 

self.closeSec=1676190599, self.tradeDate='20230212', self.openTime='162000', self.closeTime='162959', self.symbol='BTCUSDT', self.open='21800.1', self.close='21801.4'
2023-02-12 16:30:00,761:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676190599, self.tradeDate='20230212', self.openTime='162000', self.closeTime='162959',self.symbol='BTCUSDT',self.open='21800.1', self.close='21801.4'
2023-02-12 16:30:00,818:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17518  20230212   154000    154959  1676188199  21789.4  21796.3
17519  20230212   155000    155959  1676188799  21796.2  21788.2
17520  20230212   160000    160959  1676189399  21788.2    21800
17521  20230212   161000    161959  1676189999    21800    21800
17522  20230212   162000    162959  1676190599  21800.1  21801.4
2023-02-12 16:30:00,819:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12192  20230212   160000    160959  1676189399  21788.2    21800
2023-02-12 16:10:01,579:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11386 

self.closeSec=1676189999, self.tradeDate='20230212', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='21800', self.close='21800'
2023-02-12 16:20:00,728:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676189999, self.tradeDate='20230212', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='21800', self.close='21800'
127.0.0.1 - - [12/Feb/2023 16:20:00] "POST / HTTP/1.1" 200 -
2023-02-12 16:20:00,805:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230212   153000    153959  1676187599  21798.3  21789.4
12190  20230212   154000    154959  1676188199  21789.4  21796.3
12191  20230212   155000    155959  1676188799  21796.2  21788.2
12192  20230212   160000    160959  1676189399  21788.2    21800
12193  20230212   161000    161959  1676189999    21800    21800
2023-02-12 16:20:00,805:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11387 

self.closeSec=1676190599, self.tradeDate='20230212', self.openTime='162000', self.closeTime='162959', self.symbol='BTCUSDT', self.open='21800.1', self.close='21801.4'
2023-02-12 16:30:00,767:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676190599, self.tradeDate='20230212', self.openTime='162000', self.closeTime='162959',self.symbol='BTCUSDT',self.open='21800.1', self.close='21801.4'
127.0.0.1 - - [12/Feb/2023 16:30:00] "POST / HTTP/1.1" 200 -
2023-02-12 16:30:00,818:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12190  20230212   154000    154959  1676188199  21789.4  21796.3
12191  20230212   155000    155959  1676188799  21796.2  21788.2
12192  20230212   160000    160959  1676189399  21788.2    21800
12193  20230212   161000    161959  1676189999    21800    21800
12194  20230212   162000    162959  1676190599  21800.1  21801.4
2023-02-12 16:30:00,818:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=18204
self.closeSec=1676190599, self.tradeDate='20230212', self.openTime='162500', self.closeTime='162959', self.symbol='BTCUSDT', self.open=21800.4, self.close=21801.4, self.high=21801.5, self.low=21800.4, self.vol=115.794, self.amt=2524385.9676 
127.0.0.1 - - [12/Feb/2023 16:30:00] "POST / HTTP/1.1" 200 -
2023-02-12 16:30:00,710:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5953  20230212   160500    160959  ...         0.0        0.0       0
5954  20230212   161000    161459  ...         0.0        0.0       0
5955  20230212   161500    161959  ...         0.0        0.0       0
5956  20230212   162000    162459  ...         0.0        0.0       0
5957  20230212   162500    162959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-12 16:30:00,717:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676190599, self.tradeDate='20230212', self.openTime='162500', self.closeTime='162959',self.symbol='BTCUSDT',self.open=21800.4, self.close=21801.4, self.high=21801.5, self.low=21800.4, self.vol=115.794, self.amt=2524385.9676, ukdf['pct'].iloc[-1]=4.1e-05 , ukdf['amount'].iloc[-1]=2524385.9676, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5957, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=18205
self.closeSec=1676190899, self.tradeDate='20230212', self.openTime='163000', self.closeTime='163459', self.symbol='BTCUSDT', self.open=21801.5, self.close=21803.4, self.high=21803.4, self.low=21799.2, self.vol=224.154, self.amt=4886768.4102 
127.0.0.1 - - [12/Feb/2023 16:35:00] "POST / HTTP/1.1" 200 -
2023-02-12 16:35:00,463:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5954  20230212   161000    161459  ...         0.0        0.0       0
5955  20230212   161500    161959  ...         0.0        0.0       0
5956  20230212   162000    162459  ...         0.0        0.0       0
5957  20230212   162500    162959  ...         0.0        0.0       0
5958  20230212   163000    163459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-12 16:35:00,464:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676190899, self.tradeDate='20230212', self.openTime='163000', self.closeTime='163459',self.symbol='BTCUSDT',self.open=21801.5, self.close=21803.4, self.high=21803.4, self.low=21799.2, self.vol=224.154, self.amt=4886768.4102, ukdf['pct'].iloc[-1]=9.2e-05 , ukdf['amount'].iloc[-1]=4886768.4102, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5958, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230212   040000    075959  1676159999  ...    721  0.909492  1.737454     1.0
722  20230212   080000    115959  1676174399  ...    722  0.910063  1.700538     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.94', 'enterprice': '21730.2', 'countrevence': '0', 'unrealprofit': '1828.2251308444', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '21772.77627226', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [12/Feb/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=932161.693212, self.flagDict['side']='buy', self.tradeCount=18, self.count=474
self.closeSec=1676188799, self.tradeDate='20230212', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=21772.1, self.close=21788.2, self.high=21806.9, self.low=21754.0, self.vol=13806.384, self.amt=300756371.8272 
2023-02-12 16:00:01,068:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1676188799, self.tradeDate='20230212', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=21772.1, self.close=21788.2, self.high=21806.9, self.low=21754.0, self.vol=13806.384, self.amt=300756371.8272 
2023-02-12 16:00:01,101:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230211   200000    235959  ...  37452.026  8.133733e+08  0.001734
720  20230212   000000    035959  ...  34876.792  7.556790e+08 -0.003424
721  20230212   040000    075959  ...  48036.847  1.046276e+09  0.009181
722  20230212   080000    115959  ...  23886.510  5.208709e+08 -0.003624
723  20230212   120000    155959  ...  13806.384  3.007564e+08  0.000739

[5 rows x 11 columns]
2023-02-12 16:00:03,012:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230211   200000    235959  1676131199  ...    719  0.904919  1.807932     1.0
720  20230212   000000    035959  1676145599  ...    720  0.939167  1.927672     1.0
721  20230212   040000    075959  1676159999  ...    721  0.909492  1.737454     1.0
722  20230212   080000    115959  1676174399  ...    722  0.910063  1.700538     1.0
723  20230212   120000    155959  1676188799  ...    723  0.916684  1.695624     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.94', 'enterprice': '21730.2', 'countrevence': '0', 'unrealprofit': '2599.9647007976', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '21790.74878204', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


