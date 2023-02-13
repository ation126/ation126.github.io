# 20230213 16:36:18

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [13/Feb/2023 16:30:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=22494
self.closeSec=1676276999, self.tradeDate='20230213', self.openTime='162500', self.closeTime='162959', self.symbol='BTCUSDT', self.open=21767.8, self.close=21769.7, self.high=21780.4, self.low=21756.8, self.vol=2070.072, self.amt=45060376.2619 
2023-02-13 16:30:00,645:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5953  20230213   160500    160959  ...         0.0        0.0       0
5954  20230213   161000    161459  ...         0.0        0.0       0
5955  20230213   161500    161959  ...         0.0        0.0       0
5956  20230213   162000    162459  ...         0.0        0.0       0
5957  20230213   162500    162959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-13 16:30:00,645:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676276999, self.tradeDate='20230213', self.openTime='162500', self.closeTime='162959',self.symbol='BTCUSDT',self.open=21767.8, self.close=21769.7, self.high=21780.4, self.low=21756.8, self.vol=2070.072, self.amt=45060376.2619, ukdf['pct'].iloc[-1]=8.3e-05 , ukdf['amount'].iloc[-1]=45060376.2619, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5957, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-315346.3104', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21769.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [13/Feb/2023 16:35:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=22495
self.closeSec=1676277299, self.tradeDate='20230213', self.openTime='163000', self.closeTime='163459', self.symbol='BTCUSDT', self.open=21769.7, self.close=21788.5, self.high=21788.5, self.low=21760.0, self.vol=1295.78, self.amt=28214934.8643 
2023-02-13 16:35:00,521:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5954  20230213   161000    161459  ...         0.0        0.0       0
5955  20230213   161500    161959  ...         0.0        0.0       0
5956  20230213   162000    162459  ...         0.0        0.0       0
5957  20230213   162500    162959  ...         0.0        0.0       0
5958  20230213   163000    163459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-13 16:35:00,521:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676277299, self.tradeDate='20230213', self.openTime='163000', self.closeTime='163459',self.symbol='BTCUSDT',self.open=21769.7, self.close=21788.5, self.high=21788.5, self.low=21760.0, self.vol=1295.78, self.amt=28214934.8643, ukdf['pct'].iloc[-1]=0.000864 , ukdf['amount'].iloc[-1]=28214934.8643, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5958, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-316471.6016', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21788.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

1636  20230213   162000    162459  1676276699  ...  21760.3 -0.001514   1636    4
1637  20230213   162500    162959  1676276999  ...  21756.8  0.000083   1637    5

[5 rows x 11 columns]
2023-02-13 16:30:00,600:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-02-13 16:30:00,678:INFO:factorcheck2:main.py:145:handleKline:185239: df_panel.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...       pct  index  idx    factor
229  20230213   142500    142959  1676269799  ... -0.000261   1613    5  0.486347
230  20230213   145500    145959  1676271599  ...  0.000706   1619    5  0.488546
231  20230213   152500    152959  1676273399  ... -0.000763   1625    5  0.487782
232  20230213   155500    155959  1676275199  ...  0.000531   1631    5  0.487110
233  20230213   162500    162959  1676276999  ...  0.000083   1637    5  0.492290

[5 rows x 12 columns]

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=33, self.factor=0.4922904536704669, self.count=23061 

self.closeSec=1676277299, self.tradeDate='20230213', self.openTime='163000', self.closeTime='163459', self.symbol='BTCUSDT', self.open=21769.7, self.close=21788.5, self.high=21788.5, self.low=21760.0 
2023-02-13 16:35:00,463:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676277299, self.tradeDate='20230213', self.openTime='163000', self.closeTime='163459',self.symbol='BTCUSDT',self.open=21769.7, self.close=21788.5, self.high=21788.5, self.low=21760.0   
127.0.0.1 - - [13/Feb/2023 16:35:00] "POST / HTTP/1.1" 200 -
2023-02-13 16:35:00,495:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1634  20230213   161000    161459  1676276099  ...  21788.8  0.001340   1634    2
1635  20230213   161500    161959  1676276399  ...  21786.4 -0.000944   1635    3
1636  20230213   162000    162459  1676276699  ...  21760.3 -0.001514   1636    4
1637  20230213   162500    162959  1676276999  ...  21756.8  0.000083   1637    5
1638  20230213   163000    163459  1676277299  ...  21760.0  0.000864   1638    0

[5 rows x 11 columns]
2023-02-13 16:35:00,496:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-13 16:30:33,790:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5787  20230213    135959  21836.6  ...  45.000000  0.495007  0.555416
5788  20230213    142959  21820.5  ...  45.416667  0.498938  0.553231
5789  20230213    145959  21832.7  ...  45.416667  0.493079  0.553732
5790  20230213    152959  21814.6  ...  45.416667  0.507332  0.548065
5791  20230213    155959  21858.3  ...  45.000000  0.506965  0.542931

[5 rows x 33 columns]
0.5018450184501845
acc is : 0.5018450184501845
2023-02-13 16:30:33,950:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.493923  0.506077       1  ...  0.996692  -1.0    0.0  0.907623
538     1  0.498858  0.501142       0  ...  0.997518  -1.0    0.0  0.906871
539     1  0.488187  0.511813       1  ...  0.995520  -1.0    0.0  0.908688
540     0  0.504617  0.495383       0  ...  0.995570  -1.0    0.0  0.908642
541     1  0.494129  0.505871       0  ...  0.999555  -1.0    0.0  0.905004

[5 rows x 10 columns]
2023-02-13 16:30:33,967:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.493645  0.506355       1  ...  0.971138  -1.0    0.0  0.918881
46     1  0.498821  0.501179       0  ...  0.971944  -1.0    0.0  0.919284
47     1  0.487852  0.512148       1  ...  0.969996  -1.0    0.0  0.920885
48     0  0.503720  0.496280       0  ...  0.970045  -1.0    0.0  0.903399
49     1  0.494129  0.505871       0  ...  0.999555  -1.0    0.0  0.905004

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.252', 'enterprice': '22924.6', 'countrevence': '0', 'unrealprofit': '37505.0233410754', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21761.72565605', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

528  20230213   160000    160959  1676275799  21857.1  21792.3 -0.002969
2023-02-13 16:10:01,573:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [13/Feb/2023 16:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11529 

self.closeSec=1676276399, self.tradeDate='20230213', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='21792.1', self.close='21800.9'
2023-02-13 16:20:00,549:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676276399, self.tradeDate='20230213', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='21792.1', self.close='21800.9'
2023-02-13 16:20:00,599:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230213   153000    153959  1676273999  21858.3  21846.4 -0.000544
526  20230213   154000    154959  1676274599  21846.5  21842.4 -0.000183
527  20230213   155000    155959  1676275199  21842.4  21857.2  0.000678
528  20230213   160000    160959  1676275799  21857.1  21792.3 -0.002969
529  20230213   161000    161959  1676276399  21792.1  21800.9  0.000395
2023-02-13 16:20:00,603:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11530 

self.closeSec=1676276999, self.tradeDate='20230213', self.openTime='162000', self.closeTime='162959', self.symbol='BTCUSDT', self.open='21801', self.close='21769.7'
2023-02-13 16:30:01,023:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676276999, self.tradeDate='20230213', self.openTime='162000', self.closeTime='162959',self.symbol='BTCUSDT',self.open='21801', self.close='21769.7'
127.0.0.1 - - [13/Feb/2023 16:30:00] "POST / HTTP/1.1" 200 -
2023-02-13 16:30:01,114:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
526  20230213   154000    154959  1676274599  21846.5  21842.4 -0.000183
527  20230213   155000    155959  1676275199  21842.4  21857.2  0.000678
528  20230213   160000    160959  1676275799  21857.1  21792.3 -0.002969
529  20230213   161000    161959  1676276399  21792.1  21800.9  0.000395
530  20230213   162000    162959  1676276999    21801  21769.7 -0.001431
2023-02-13 16:30:01,114:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/percentile_regression_step2/log.txt ----- -----

  File "main.py", line 141, in get_signal
    df_id['min_s'] = df_id['index'].rolling(int(wid)).apply(lambda x: func_min(x, df_id))
  File "/usr/local/lib/python3.8/dist-packages/pandas/core/window/rolling.py", line 1843, in apply
    return super().apply(
  File "/usr/local/lib/python3.8/dist-packages/pandas/core/window/rolling.py", line 1315, in apply
    return self._apply(
  File "/usr/local/lib/python3.8/dist-packages/pandas/core/window/rolling.py", line 590, in _apply
    return self._apply_blockwise(homogeneous_func, name)
  File "/usr/local/lib/python3.8/dist-packages/pandas/core/window/rolling.py", line 442, in _apply_blockwise
    return self._apply_series(homogeneous_func, name)
  File "/usr/local/lib/python3.8/dist-packages/pandas/core/window/rolling.py", line 431, in _apply_series
    result = homogeneous_func(values)
  File "/usr/local/lib/python3.8/dist-packages/pandas/core/window/rolling.py", line 582, in homogeneous_func
    result = calc(values)
  File "/usr/local/lib/python3.8/dist-packages/pandas/core/window/rolling.py", line 579, in calc
    return func(x, start, end, min_periods, *numba_args)
  File "/usr/local/lib/python3.8/dist-packages/pandas/core/window/rolling.py", line 1342, in apply_func
    return window_func(values, begin, end, min_periods)
  File "pandas/_libs/window/aggregations.pyx", line 1315, in pandas._libs.window.aggregations.roll_apply
  File "main.py", line 141, in <lambda>
    df_id['min_s'] = df_id['index'].rolling(int(wid)).apply(lambda x: func_min(x, df_id))
  File "main.py", line 90, in func_min
    ds = df.iloc[idx]
  File "/usr/local/lib/python3.8/dist-packages/pandas/core/indexing.py", line 967, in __getitem__
    return self._getitem_axis(maybe_callable, axis=axis)
  File "/usr/local/lib/python3.8/dist-packages/pandas/core/indexing.py", line 1511, in _getitem_axis
    return self._get_list_axis(key, axis=axis)
  File "/usr/local/lib/python3.8/dist-packages/pandas/core/indexing.py", line 1485, in _get_list_axis
    raise IndexError("positional indexers are out-of-bounds") from err
IndexError: positional indexers are out-of-bounds


## /root/FIL/strategy/pyemd/log.txt ----- -----

17520  20230213   160000    160959  1676275799  21857.1  21792.3
2023-02-13 16:10:01,612:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11530 

self.closeSec=1676276399, self.tradeDate='20230213', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='21792.1', self.close='21800.9'
127.0.0.1 - - [13/Feb/2023 16:20:00] "POST / HTTP/1.1" 200 -
2023-02-13 16:20:00,530:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676276399, self.tradeDate='20230213', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='21792.1', self.close='21800.9'
2023-02-13 16:20:00,553:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230213   153000    153959  1676273999  21858.3  21846.4
17518  20230213   154000    154959  1676274599  21846.5  21842.4
17519  20230213   155000    155959  1676275199  21842.4  21857.2
17520  20230213   160000    160959  1676275799  21857.1  21792.3
17521  20230213   161000    161959  1676276399  21792.1  21800.9
2023-02-13 16:20:00,554:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [13/Feb/2023 16:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11531 

self.closeSec=1676276999, self.tradeDate='20230213', self.openTime='162000', self.closeTime='162959', self.symbol='BTCUSDT', self.open='21801', self.close='21769.7'
2023-02-13 16:30:01,060:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676276999, self.tradeDate='20230213', self.openTime='162000', self.closeTime='162959',self.symbol='BTCUSDT',self.open='21801', self.close='21769.7'
2023-02-13 16:30:01,129:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17518  20230213   154000    154959  1676274599  21846.5  21842.4
17519  20230213   155000    155959  1676275199  21842.4  21857.2
17520  20230213   160000    160959  1676275799  21857.1  21792.3
17521  20230213   161000    161959  1676276399  21792.1  21800.9
17522  20230213   162000    162959  1676276999    21801  21769.7
2023-02-13 16:30:01,129:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12192  20230213   160000    160959  1676275799  21857.1  21792.3
2023-02-13 16:10:01,609:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11530 

self.closeSec=1676276399, self.tradeDate='20230213', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='21792.1', self.close='21800.9'
2023-02-13 16:20:00,545:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676276399, self.tradeDate='20230213', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='21792.1', self.close='21800.9'
127.0.0.1 - - [13/Feb/2023 16:20:00] "POST / HTTP/1.1" 200 -
2023-02-13 16:20:00,560:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230213   153000    153959  1676273999  21858.3  21846.4
12190  20230213   154000    154959  1676274599  21846.5  21842.4
12191  20230213   155000    155959  1676275199  21842.4  21857.2
12192  20230213   160000    160959  1676275799  21857.1  21792.3
12193  20230213   161000    161959  1676276399  21792.1  21800.9
2023-02-13 16:20:00,565:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [13/Feb/2023 16:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11531 

self.closeSec=1676276999, self.tradeDate='20230213', self.openTime='162000', self.closeTime='162959', self.symbol='BTCUSDT', self.open='21801', self.close='21769.7'
2023-02-13 16:30:01,045:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676276999, self.tradeDate='20230213', self.openTime='162000', self.closeTime='162959',self.symbol='BTCUSDT',self.open='21801', self.close='21769.7'
2023-02-13 16:30:01,119:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12190  20230213   154000    154959  1676274599  21846.5  21842.4
12191  20230213   155000    155959  1676275199  21842.4  21857.2
12192  20230213   160000    160959  1676275799  21857.1  21792.3
12193  20230213   161000    161959  1676276399  21792.1  21800.9
12194  20230213   162000    162959  1676276999    21801  21769.7
2023-02-13 16:30:01,119:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [13/Feb/2023 16:30:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=18492
self.closeSec=1676276999, self.tradeDate='20230213', self.openTime='162500', self.closeTime='162959', self.symbol='BTCUSDT', self.open=21767.8, self.close=21769.7, self.high=21780.4, self.low=21756.8, self.vol=2070.072, self.amt=45060376.2619 
2023-02-13 16:30:00,654:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5953  20230213   160500    160959  ...         0.0        0.0       0
5954  20230213   161000    161459  ...         0.0        0.0       0
5955  20230213   161500    161959  ...         0.0        0.0       0
5956  20230213   162000    162459  ...         0.0        0.0       0
5957  20230213   162500    162959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-13 16:30:00,656:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676276999, self.tradeDate='20230213', self.openTime='162500', self.closeTime='162959',self.symbol='BTCUSDT',self.open=21767.8, self.close=21769.7, self.high=21780.4, self.low=21756.8, self.vol=2070.072, self.amt=45060376.2619, ukdf['pct'].iloc[-1]=8.3e-05 , ukdf['amount'].iloc[-1]=45060376.2619, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5957, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [13/Feb/2023 16:35:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=18493
self.closeSec=1676277299, self.tradeDate='20230213', self.openTime='163000', self.closeTime='163459', self.symbol='BTCUSDT', self.open=21769.7, self.close=21788.5, self.high=21788.5, self.low=21760.0, self.vol=1295.78, self.amt=28214934.8643 
2023-02-13 16:35:00,516:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5954  20230213   161000    161459  ...         0.0        0.0       0
5955  20230213   161500    161959  ...         0.0        0.0       0
5956  20230213   162000    162459  ...         0.0        0.0       0
5957  20230213   162500    162959  ...         0.0        0.0       0
5958  20230213   163000    163459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-13 16:35:00,516:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676277299, self.tradeDate='20230213', self.openTime='163000', self.closeTime='163459',self.symbol='BTCUSDT',self.open=21769.7, self.close=21788.5, self.high=21788.5, self.low=21760.0, self.vol=1295.78, self.amt=28214934.8643, ukdf['pct'].iloc[-1]=0.000864 , ukdf['amount'].iloc[-1]=28214934.8643, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5958, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230213   040000    075959  1676246399  ...    721  0.937283  1.627230     1.0
722  20230213   080000    115959  1676260799  ...    722  0.966171  1.733999     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.94', 'enterprice': '21730.2', 'countrevence': '0', 'unrealprofit': '2991.9719519316', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '21799.87796814', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=932161.693212, self.flagDict['side']='buy', self.tradeCount=18, self.count=480
self.closeSec=1676275199, self.tradeDate='20230213', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=21800.9, self.close=21857.2, self.high=21888.0, self.low=21781.5, self.vol=37460.868, self.amt=817880354.5645 
127.0.0.1 - - [13/Feb/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-02-13 16:00:01,053:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1676275199, self.tradeDate='20230213', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=21800.9, self.close=21857.2, self.high=21888.0, self.low=21781.5, self.vol=37460.868, self.amt=817880354.5645 
2023-02-13 16:00:01,092:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230212   200000    235959  ...  66423.188  1.452623e+09  0.002455
720  20230213   000000    035959  ...  57543.929  1.265239e+09  0.002362
721  20230213   040000    075959  ...  76306.684  1.662002e+09 -0.009644
722  20230213   080000    115959  ...  67134.107  1.459458e+09  0.001369
723  20230213   120000    155959  ...  37460.868  8.178804e+08  0.002582

[5 rows x 11 columns]
2023-02-13 16:00:03,472:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230212   200000    235959  1676217599  ...    719  1.041296  2.195449     1.0
720  20230213   000000    035959  1676231999  ...    720  1.011027  2.006100     1.0
721  20230213   040000    075959  1676246399  ...    721  0.937283  1.627230     1.0
722  20230213   080000    115959  1676260799  ...    722  0.966171  1.733999     1.0
723  20230213   120000    155959  1676275199  ...    723  0.793234  0.870017     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.94', 'enterprice': '21730.2', 'countrevence': '0', 'unrealprofit': '5529.7078716152', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '21858.97754708', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


