# 20230220 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [20/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=24412
self.closeSec=1676852399, self.tradeDate='20230220', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=24380.0, self.close=24387.9, self.high=24409.7, self.low=24372.4, self.vol=1771.805, self.amt=43208436.6309 
2023-02-20 08:20:01,571:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230220   075500    075959  ...         0.0        0.0       0
5856  20230220   080000    080459  ...         0.0        0.0       0
5857  20230220   080500    080959  ...         0.0        0.0       0
5858  20230220   081000    081459  ...         0.0        0.0       0
5859  20230220   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-20 08:20:01,572:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676852399, self.tradeDate='20230220', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=24380.0, self.close=24387.9, self.high=24409.7, self.low=24372.4, self.vol=1771.805, self.amt=43208436.6309, ukdf['pct'].iloc[-1]=0.000324 , ukdf['amount'].iloc[-1]=43208436.6309, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-472899.1136', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24387.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=24413
self.closeSec=1676852699, self.tradeDate='20230220', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=24387.8, self.close=24366.2, self.high=24392.2, self.low=24345.1, self.vol=909.472, self.amt=22156371.7292 
127.0.0.1 - - [20/Feb/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-02-20 08:25:01,637:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230220   080000    080459  ...         0.0        0.0       0
5857  20230220   080500    080959  ...         0.0        0.0       0
5858  20230220   081000    081459  ...         0.0        0.0       0
5859  20230220   081500    081959  ...         0.0        0.0       0
5860  20230220   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-20 08:25:01,640:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676852699, self.tradeDate='20230220', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=24387.8, self.close=24366.2, self.high=24392.2, self.low=24345.1, self.vol=909.472, self.amt=22156371.7292, ukdf['pct'].iloc[-1]=-0.00089 , ukdf['amount'].iloc[-1]=22156371.7292, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-471593.2944', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24366.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=247, self.factor=0.5615840228360564, self.count=24978 

self.closeSec=1676852399, self.tradeDate='20230220', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=24380.0, self.close=24387.9, self.high=24409.7, self.low=24372.4 
2023-02-20 08:20:01,511:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676852399, self.tradeDate='20230220', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=24380.0, self.close=24387.9, self.high=24409.7, self.low=24372.4   
2023-02-20 08:20:01,553:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230220   075500    075959  1676851199  ...  24179.4 -0.002290   1535    5
1536  20230220   080000    080459  1676851499  ...  24263.5  0.004507   1536    0
1537  20230220   080500    080959  1676851799  ...  24330.2 -0.001276   1537    1
1538  20230220   081000    081459  1676852099  ...  24340.0  0.001236   1538    2
1539  20230220   081500    081959  1676852399  ...  24372.4  0.000324   1539    3

[5 rows x 11 columns]
2023-02-20 08:20:01,553:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [20/Feb/2023 08:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=247, self.factor=0.5615840228360564, self.count=24979 

self.closeSec=1676852699, self.tradeDate='20230220', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=24387.8, self.close=24366.2, self.high=24392.2, self.low=24345.1 
2023-02-20 08:25:01,530:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676852699, self.tradeDate='20230220', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=24387.8, self.close=24366.2, self.high=24392.2, self.low=24345.1   
2023-02-20 08:25:01,602:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230220   080000    080459  1676851499  ...  24263.5  0.004507   1536    0
1537  20230220   080500    080959  1676851799  ...  24330.2 -0.001276   1537    1
1538  20230220   081000    081459  1676852099  ...  24340.0  0.001236   1538    2
1539  20230220   081500    081959  1676852399  ...  24372.4  0.000324   1539    3
1540  20230220   082000    082459  1676852699  ...  24345.1 -0.000890   1540    4

[5 rows x 11 columns]
2023-02-20 08:25:01,602:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-20 08:00:34,538:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230220    052959  24516.6  ...  52.083333  0.497534  0.627713
5771  20230220    055959  24520.1  ...  52.500000  0.500230  0.632036
5772  20230220    062959  24536.8  ...  52.500000  0.500116  0.636120
5773  20230220    065959  24536.1  ...  52.500000  0.492308  0.643253
5774  20230220    072959  24488.5  ...  52.083333  0.477061  0.656572

[5 rows x 33 columns]
0.5101663585951941
acc is : 0.5101663585951941
2023-02-20 08:00:34,695:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.511759  0.488241       1  ...  1.057210  -1.0    0.0  1.066850
537     0  0.511281  0.488719       0  ...  1.057241  -1.0    0.0  1.066819
538     0  0.509094  0.490906       0  ...  1.059296  -1.0    0.0  1.064745
539     0  0.513465  0.486535       0  ...  1.063436  -1.0    0.0  1.060584
540     1  0.479780  0.520220       0  ...  1.068964  -1.0    0.0  1.055071

[5 rows x 10 columns]
2023-02-20 08:00:34,727:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.512199  0.487801       1  ...  1.057210  -1.0    0.0  1.073243
46     0  0.512310  0.487690       0  ...  1.057241  -1.0    0.0  1.076263
47     0  0.509621  0.490379       0  ...  1.059296  -1.0    0.0  1.066675
48     0  0.513465  0.486535       0  ...  1.063436  -1.0    0.0  1.060584
49     1  0.479780  0.520220       0  ...  1.068964  -1.0    0.0  1.055071

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '35.348', 'enterprice': '24430.6', 'countrevence': '0', 'unrealprofit': '5054.764', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24287.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230220   075000    075959  1676851199    24356  24265.9 -0.003699
2023-02-20 08:00:02,185:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12488 

self.closeSec=1676851799, self.tradeDate='20230220', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='24265.9', self.close='24350'
2023-02-20 08:10:01,634:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676851799, self.tradeDate='20230220', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='24265.9', self.close='24350'
127.0.0.1 - - [20/Feb/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-02-20 08:10:01,675:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230220   072000    072959  1676849399  24424.9  24392.7 -0.001318
621  20230220   073000    073959  1676849999  24392.8  24396.3  0.000148
622  20230220   074000    074959  1676850599  24396.3    24356 -0.001652
623  20230220   075000    075959  1676851199    24356  24265.9 -0.003699
624  20230220   080000    080959  1676851799  24265.9    24350  0.003466
2023-02-20 08:10:01,675:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [20/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12489 

self.closeSec=1676852399, self.tradeDate='20230220', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='24350', self.close='24387.9'
2023-02-20 08:20:01,712:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676852399, self.tradeDate='20230220', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='24350', self.close='24387.9'
2023-02-20 08:20:01,732:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230220   073000    073959  1676849999  24392.8  24396.3  0.000148
622  20230220   074000    074959  1676850599  24396.3    24356 -0.001652
623  20230220   075000    075959  1676851199    24356  24265.9 -0.003699
624  20230220   080000    080959  1676851799  24265.9    24350  0.003466
625  20230220   081000    081959  1676852399    24350  24387.9  0.001556
2023-02-20 08:20:01,733:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/percentile_regression_step2/log.txt ----- -----

127.0.0.1 - - [20/Feb/2023 07:00:02] "POST / HTTP/1.1" 200 -
2023-02-20 07:00:03,271:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/20 04:30:00  043000  24516.6  ...     NaN     NaN       0
145  2023/02/20 05:00:00  050000  24520.0  ...     NaN     NaN       0
146  2023/02/20 05:30:00  053000  24536.8  ...     NaN     NaN       0
147  2023/02/20 06:00:00  060000  24536.1  ...     NaN     NaN       0
148  2023/02/20 06:30:00  063000  24488.4  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [20/Feb/2023 07:30:01] "POST / HTTP/1.1" 200 -
2023-02-20 07:30:02,640:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/20 05:00:00  050000  24520.0  ...     NaN     NaN       0
145  2023/02/20 05:30:00  053000  24536.8  ...     NaN     NaN       0
146  2023/02/20 06:00:00  060000  24536.1  ...     NaN     NaN       0
147  2023/02/20 06:30:00  063000  24488.4  ...     NaN     NaN       0
148  2023/02/20 07:00:00  070000  24392.7  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [20/Feb/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-02-20 08:00:02,888:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/20 05:30:00  053000  24536.8  ...     NaN     NaN       0
145  2023/02/20 06:00:00  060000  24536.1  ...     NaN     NaN       0
146  2023/02/20 06:30:00  063000  24488.4  ...     NaN     NaN       0
147  2023/02/20 07:00:00  070000  24392.7  ...     NaN     NaN       0
148  2023/02/20 07:30:00  073000  24265.9  ...     NaN     NaN       0

[5 rows x 10 columns]


## /root/FIL/strategy/pyemd/log.txt ----- -----

17471  20230220   075000    075959  1676851199    24356  24265.9
2023-02-20 08:00:02,206:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12489 

self.closeSec=1676851799, self.tradeDate='20230220', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='24265.9', self.close='24350'
2023-02-20 08:10:01,608:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676851799, self.tradeDate='20230220', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='24265.9', self.close='24350'
127.0.0.1 - - [20/Feb/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-02-20 08:10:01,623:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230220   072000    072959  1676849399  24424.9  24392.7
17469  20230220   073000    073959  1676849999  24392.8  24396.3
17470  20230220   074000    074959  1676850599  24396.3    24356
17471  20230220   075000    075959  1676851199    24356  24265.9
17472  20230220   080000    080959  1676851799  24265.9    24350
2023-02-20 08:10:01,623:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [20/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12490 

self.closeSec=1676852399, self.tradeDate='20230220', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='24350', self.close='24387.9'
2023-02-20 08:20:01,723:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676852399, self.tradeDate='20230220', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='24350', self.close='24387.9'
2023-02-20 08:20:01,746:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230220   073000    073959  1676849999  24392.8  24396.3
17470  20230220   074000    074959  1676850599  24396.3    24356
17471  20230220   075000    075959  1676851199    24356  24265.9
17472  20230220   080000    080959  1676851799  24265.9    24350
17473  20230220   081000    081959  1676852399    24350  24387.9
2023-02-20 08:20:01,749:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230220   075000    075959  1676851199    24356  24265.9
2023-02-20 08:00:02,193:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12489 

self.closeSec=1676851799, self.tradeDate='20230220', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='24265.9', self.close='24350'
2023-02-20 08:10:01,661:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676851799, self.tradeDate='20230220', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='24265.9', self.close='24350'
127.0.0.1 - - [20/Feb/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-02-20 08:10:01,683:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230220   072000    072959  1676849399  24424.9  24392.7
12141  20230220   073000    073959  1676849999  24392.8  24396.3
12142  20230220   074000    074959  1676850599  24396.3    24356
12143  20230220   075000    075959  1676851199    24356  24265.9
12144  20230220   080000    080959  1676851799  24265.9    24350
2023-02-20 08:10:01,683:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12490 

self.closeSec=1676852399, self.tradeDate='20230220', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='24350', self.close='24387.9'
2023-02-20 08:20:01,741:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676852399, self.tradeDate='20230220', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='24350', self.close='24387.9'
127.0.0.1 - - [20/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-02-20 08:20:01,755:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230220   073000    073959  1676849999  24392.8  24396.3
12142  20230220   074000    074959  1676850599  24396.3    24356
12143  20230220   075000    075959  1676851199    24356  24265.9
12144  20230220   080000    080959  1676851799  24265.9    24350
12145  20230220   081000    081959  1676852399    24350  24387.9
2023-02-20 08:20:01,757:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=20410
self.closeSec=1676852399, self.tradeDate='20230220', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=24380.0, self.close=24387.9, self.high=24409.7, self.low=24372.4, self.vol=1771.805, self.amt=43208436.6309 
127.0.0.1 - - [20/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-02-20 08:20:01,615:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230220   075500    075959  ...         0.0        0.0       0
5856  20230220   080000    080459  ...         0.0        0.0       0
5857  20230220   080500    080959  ...         0.0        0.0       0
5858  20230220   081000    081459  ...         0.0        0.0       0
5859  20230220   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-20 08:20:01,618:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676852399, self.tradeDate='20230220', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=24380.0, self.close=24387.9, self.high=24409.7, self.low=24372.4, self.vol=1771.805, self.amt=43208436.6309, ukdf['pct'].iloc[-1]=0.000324 , ukdf['amount'].iloc[-1]=43208436.6309, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [20/Feb/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=20411
self.closeSec=1676852699, self.tradeDate='20230220', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=24387.8, self.close=24366.2, self.high=24392.2, self.low=24345.1, self.vol=909.472, self.amt=22156371.7292 
2023-02-20 08:25:01,614:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230220   080000    080459  ...         0.0        0.0       0
5857  20230220   080500    080959  ...         0.0        0.0       0
5858  20230220   081000    081459  ...         0.0        0.0       0
5859  20230220   081500    081959  ...         0.0        0.0       0
5860  20230220   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-20 08:25:01,620:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676852699, self.tradeDate='20230220', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=24387.8, self.close=24366.2, self.high=24392.2, self.low=24345.1, self.vol=909.472, self.amt=22156371.7292, ukdf['pct'].iloc[-1]=-0.00089 , ukdf['amount'].iloc[-1]=22156371.7292, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230219   200000    235959  1676822399  ...    719  0.433753 -0.664721    -1.0
720  20230220   000000    035959  1676836799  ...    720  0.282635 -1.069867    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.465', 'enterprice': '24934.8', 'countrevence': '0', 'unrealprofit': '15391.8765', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24512.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [20/Feb/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=908338.234518, self.flagDict['side']='sell', self.tradeCount=21, self.count=520
self.closeSec=1676851199, self.tradeDate='20230220', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=24512.5, self.close=24265.9, self.high=24578.4, self.low=24179.4, self.vol=81659.528, self.amt=1993888063.40497 
2023-02-20 08:00:01,940:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1676851199, self.tradeDate='20230220', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=24512.5, self.close=24265.9, self.high=24578.4, self.low=24179.4, self.vol=81659.528, self.amt=1993888063.40497 
2023-02-20 08:00:02,006:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230219   120000    155959  ...   59061.967  1.459276e+09 -0.004468
718  20230219   160000    195959  ...   34964.341  8.610220e+08  0.003609
719  20230219   200000    235959  ...  103278.998  2.564951e+09  0.010813
720  20230220   000000    035959  ...  235528.484  5.813210e+09 -0.016830
721  20230220   040000    075959  ...   81659.528  1.993888e+09 -0.010060

[5 rows x 11 columns]
2023-02-20 08:00:04,123:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230219   120000    155959  1676793599  ...    717  0.730658  0.154030     NaN
718  20230219   160000    195959  1676807999  ...    718  0.569196 -0.293501     NaN
719  20230219   200000    235959  1676822399  ...    719  0.433753 -0.664721    -1.0
720  20230220   000000    035959  1676836799  ...    720  0.282635 -1.069867    -1.0
721  20230220   040000    075959  1676851199  ...    721  0.152017 -1.404157    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.465', 'enterprice': '24934.8', 'countrevence': '0', 'unrealprofit': '24231.46506196845', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24270.28704067', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


