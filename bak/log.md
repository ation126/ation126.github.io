# 20230330 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=35356
self.closeSec=1680135599, self.tradeDate='20230330', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28357.7, self.close=28398.5, self.high=28421.0, self.low=28353.0, self.vol=1530.628, self.amt=43463678.2532 
127.0.0.1 - - [30/Mar/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-03-30 08:20:09,704:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230330   075500    075959  ...         0.0        0.0       0
5856  20230330   080000    080459  ...         0.0        0.0       0
5857  20230330   080500    080959  ...         0.0        0.0       0
5858  20230330   081000    081459  ...         0.0        0.0       0
5859  20230330   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-30 08:20:09,714:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680135599, self.tradeDate='20230330', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28357.7, self.close=28398.5, self.high=28421.0, self.low=28353.0, self.vol=1530.628, self.amt=43463678.2532, ukdf['pct'].iloc[-1]=0.001435 , ukdf['amount'].iloc[-1]=43463678.2532, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-714353.27955552016', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28400.36619841', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [30/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=35357
self.closeSec=1680135899, self.tradeDate='20230330', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28398.5, self.close=28405.2, self.high=28435.0, self.low=28395.0, self.vol=1688.663, self.amt=47981430.3752 
2023-03-30 08:25:01,609:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230330   080000    080459  ...         0.0        0.0       0
5857  20230330   080500    080959  ...         0.0        0.0       0
5858  20230330   081000    081459  ...         0.0        0.0       0
5859  20230330   081500    081959  ...         0.0        0.0       0
5860  20230330   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-30 08:25:01,609:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680135899, self.tradeDate='20230330', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28398.5, self.close=28405.2, self.high=28435.0, self.low=28395.0, self.vol=1688.663, self.amt=47981430.3752, ukdf['pct'].iloc[-1]=0.000236 , ukdf['amount'].iloc[-1]=47981430.3752, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-714676.43112337856', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28405.73630556', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1680135599, self.tradeDate='20230330', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28357.7, self.close=28398.5, self.high=28421.0, self.low=28353.0 
127.0.0.1 - - [30/Mar/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-03-30 08:20:07,443:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680135599, self.tradeDate='20230330', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28357.7, self.close=28398.5, self.high=28421.0, self.low=28353.0   
2023-03-30 08:20:08,753:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230330   075500    075959  1680134399  ...  28300.0  0.000201   1535    5
1536  20230330   080000    080459  1680134699  ...  28307.2 -0.001027   1536    0
1537  20230330   080500    080959  1680134999  ...  28300.0  0.001561   1537    1
1538  20230330   081000    081459  1680135299  ...  28334.7  0.000148   1538    2
1539  20230330   081500    081959  1680135599  ...  28353.0  0.001435   1539    3

[5 rows x 11 columns]
2023-03-30 08:20:08,763:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=8, self.factor=0.2548094952322773, self.count=35923 

self.closeSec=1680135899, self.tradeDate='20230330', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28398.5, self.close=28405.2, self.high=28435.0, self.low=28395.0 
127.0.0.1 - - [30/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-03-30 08:25:01,537:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680135899, self.tradeDate='20230330', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28398.5, self.close=28405.2, self.high=28435.0, self.low=28395.0   
2023-03-30 08:25:01,601:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230330   080000    080459  1680134699  ...  28307.2 -0.001027   1536    0
1537  20230330   080500    080959  1680134999  ...  28300.0  0.001561   1537    1
1538  20230330   081000    081459  1680135299  ...  28334.7  0.000148   1538    2
1539  20230330   081500    081959  1680135599  ...  28353.0  0.001435   1539    3
1540  20230330   082000    082459  1680135899  ...  28395.0  0.000236   1540    4

[5 rows x 11 columns]
2023-03-30 08:25:01,602:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-30 08:00:35,853:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230330    052959  28377.9  ...  50.833333  0.597971  0.193330
5771  20230330    055959  28450.6  ...  50.416667  0.570253  0.198517
5772  20230330    062959  28281.2  ...  50.416667  0.581465  0.198936
5773  20230330    065959  28376.0  ...  50.833333  0.581510  0.199307
5774  20230330    072959  28376.6  ...  50.833333  0.585594  0.197894

[5 rows x 33 columns]
0.5027726432532348
acc is : 0.5027726432532348
2023-03-30 08:00:36,011:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.530077  0.469923       0  ...  0.968707   1.0    0.0  1.043579
537     1  0.465025  0.534975       1  ...  0.972040   1.0    0.0  1.047170
538     0  0.520382  0.479618       1  ...  0.972054   1.0    0.0  1.047184
539     1  0.498374  0.501626       1  ...  0.973263   1.0    0.0  1.048487
540     0  0.510895  0.489105       0  ...  0.970752   1.0    0.0  1.045782

[5 rows x 10 columns]
2023-03-30 08:00:36,050:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.530917  0.469083       0  ...  0.968707   1.0    0.0  1.038940
46     1  0.466866  0.533134       1  ...  0.972040   1.0    0.0  1.046378
47     0  0.519329  0.480671       1  ...  0.972054   1.0    0.0  1.037801
48     0  0.500405  0.499595       1  ...  0.973263   1.0    0.0  1.048487
49     0  0.510895  0.489105       0  ...  0.970752   1.0    0.0  1.045782

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230330   075000    075959  1680134399  28371.6  28338.5 -0.001163
2023-03-30 08:00:01,908:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [30/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17960 

self.closeSec=1680134999, self.tradeDate='20230330', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28338.6', self.close='28353.6'
2023-03-30 08:10:01,650:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680134999, self.tradeDate='20230330', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='28338.6', self.close='28353.6'
2023-03-30 08:10:01,697:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230330   072000    072959  1680132599  28390.1  28411.8  0.000768
621  20230330   073000    073959  1680133199  28411.8  28369.9 -0.001475
622  20230330   074000    074959  1680133799  28369.9  28371.5  0.000056
623  20230330   075000    075959  1680134399  28371.6  28338.5 -0.001163
624  20230330   080000    080959  1680134999  28338.6  28353.6  0.000533
2023-03-30 08:10:01,697:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17961 

self.closeSec=1680135599, self.tradeDate='20230330', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28353.6', self.close='28398.5'
127.0.0.1 - - [30/Mar/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-03-30 08:20:08,283:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680135599, self.tradeDate='20230330', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='28353.6', self.close='28398.5'
2023-03-30 08:20:09,254:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230330   073000    073959  1680133199  28411.8  28369.9 -0.001475
622  20230330   074000    074959  1680133799  28369.9  28371.5  0.000056
623  20230330   075000    075959  1680134399  28371.6  28338.5 -0.001163
624  20230330   080000    080959  1680134999  28338.6  28353.6  0.000533
625  20230330   081000    081959  1680135599  28353.6  28398.5  0.001584
2023-03-30 08:20:09,262:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230330   075000    075959  1680134399  28371.6  28338.5
2023-03-30 08:00:01,984:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [30/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17961 

self.closeSec=1680134999, self.tradeDate='20230330', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28338.6', self.close='28353.6'
2023-03-30 08:10:01,680:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680134999, self.tradeDate='20230330', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='28338.6', self.close='28353.6'
2023-03-30 08:10:01,699:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230330   072000    072959  1680132599  28390.1  28411.8
17469  20230330   073000    073959  1680133199  28411.8  28369.9
17470  20230330   074000    074959  1680133799  28369.9  28371.5
17471  20230330   075000    075959  1680134399  28371.6  28338.5
17472  20230330   080000    080959  1680134999  28338.6  28353.6
2023-03-30 08:10:01,699:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17962 

self.closeSec=1680135599, self.tradeDate='20230330', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28353.6', self.close='28398.5'
127.0.0.1 - - [30/Mar/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-03-30 08:20:11,018:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680135599, self.tradeDate='20230330', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='28353.6', self.close='28398.5'
2023-03-30 08:20:11,140:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230330   073000    073959  1680133199  28411.8  28369.9
17470  20230330   074000    074959  1680133799  28369.9  28371.5
17471  20230330   075000    075959  1680134399  28371.6  28338.5
17472  20230330   080000    080959  1680134999  28338.6  28353.6
17473  20230330   081000    081959  1680135599  28353.6  28398.5
2023-03-30 08:20:11,140:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230330   075000    075959  1680134399  28371.6  28338.5
2023-03-30 08:00:01,981:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17961 

self.closeSec=1680134999, self.tradeDate='20230330', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28338.6', self.close='28353.6'
2023-03-30 08:10:01,616:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680134999, self.tradeDate='20230330', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='28338.6', self.close='28353.6'
127.0.0.1 - - [30/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-03-30 08:10:01,639:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230330   072000    072959  1680132599  28390.1  28411.8
12141  20230330   073000    073959  1680133199  28411.8  28369.9
12142  20230330   074000    074959  1680133799  28369.9  28371.5
12143  20230330   075000    075959  1680134399  28371.6  28338.5
12144  20230330   080000    080959  1680134999  28338.6  28353.6
2023-03-30 08:10:01,639:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17962 

self.closeSec=1680135599, self.tradeDate='20230330', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28353.6', self.close='28398.5'
127.0.0.1 - - [30/Mar/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-03-30 08:20:10,614:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680135599, self.tradeDate='20230330', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='28353.6', self.close='28398.5'
2023-03-30 08:20:10,876:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230330   073000    073959  1680133199  28411.8  28369.9
12142  20230330   074000    074959  1680133799  28369.9  28371.5
12143  20230330   075000    075959  1680134399  28371.6  28338.5
12144  20230330   080000    080959  1680134999  28338.6  28353.6
12145  20230330   081000    081959  1680135599  28353.6  28398.5
2023-03-30 08:20:10,877:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=31354
self.closeSec=1680135599, self.tradeDate='20230330', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28357.7, self.close=28398.5, self.high=28421.0, self.low=28353.0, self.vol=1530.628, self.amt=43463678.2532 
127.0.0.1 - - [30/Mar/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-03-30 08:20:07,993:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230330   075500    075959  ...         0.0        0.0       0
5856  20230330   080000    080459  ...         0.0        0.0       0
5857  20230330   080500    080959  ...         0.0        0.0       0
5858  20230330   081000    081459  ...         0.0        0.0       0
5859  20230330   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-30 08:20:08,023:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680135599, self.tradeDate='20230330', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28357.7, self.close=28398.5, self.high=28421.0, self.low=28353.0, self.vol=1530.628, self.amt=43463678.2532, ukdf['pct'].iloc[-1]=0.001435 , ukdf['amount'].iloc[-1]=43463678.2532, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [30/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=31355
self.closeSec=1680135899, self.tradeDate='20230330', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28398.5, self.close=28405.2, self.high=28435.0, self.low=28395.0, self.vol=1688.663, self.amt=47981430.3752 
2023-03-30 08:25:01,638:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230330   080000    080459  ...         0.0        0.0       0
5857  20230330   080500    080959  ...         0.0        0.0       0
5858  20230330   081000    081459  ...         0.0        0.0       0
5859  20230330   081500    081959  ...         0.0        0.0       0
5860  20230330   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-30 08:25:01,638:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680135899, self.tradeDate='20230330', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28398.5, self.close=28405.2, self.high=28435.0, self.low=28395.0, self.vol=1688.663, self.amt=47981430.3752, ukdf['pct'].iloc[-1]=0.000236 , ukdf['amount'].iloc[-1]=47981430.3752, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230329   200000    235959  1680105599  ...    719  0.409578 -0.188305     NaN
720  20230330   000000    035959  1680119999  ...    720  0.436156 -0.104025     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '-16416.43108780746', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28396.77219841', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [30/Mar/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1507151.9559834, self.flagDict['side']='sell', self.tradeCount=27, self.count=748
self.closeSec=1680134399, self.tradeDate='20230330', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=28406.2, self.close=28338.5, self.high=28500.0, self.low=28200.0, self.vol=59350.476, self.amt=1683516482.484 
2023-03-30 08:00:01,811:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1680134399, self.tradeDate='20230330', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=28406.2, self.close=28338.5, self.high=28500.0, self.low=28200.0, self.vol=59350.476, self.amt=1683516482.484 
2023-03-30 08:00:01,892:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230329   120000    155959  ...  154440.639  4.298772e+09  0.026453
718  20230329   160000    195959  ...  170742.766  4.848562e+09  0.009609
719  20230329   200000    235959  ...  132706.077  3.766132e+09  0.002780
720  20230330   000000    035959  ...   91922.458  2.599163e+09 -0.000711
721  20230330   040000    075959  ...   59350.476  1.683516e+09 -0.002380

[5 rows x 11 columns]
2023-03-30 08:00:04,252:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230329   120000    155959  1680076799  ...    717  0.220758 -0.671756    -1.0
718  20230329   160000    195959  1680091199  ...    718  0.336155 -0.381777     NaN
719  20230329   200000    235959  1680105599  ...    719  0.409578 -0.188305     NaN
720  20230330   000000    035959  1680119999  ...    720  0.436156 -0.104025     NaN
721  20230330   040000    075959  1680134399  ...    721  0.463239 -0.015555     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '-13286.8644', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28338.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


