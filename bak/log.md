# 20230623 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=11488
self.closeSec=1687479599, self.tradeDate='20230623', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29986.0, self.close=30008.1, self.high=30024.8, self.low=29960.8, self.vol=2508.994, self.amt=75269697.3288 
127.0.0.1 - - [23/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-23 08:20:07,985:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230623   075500    075959  ...         0.0        0.0       0
5856  20230623   080000    080459  ...         0.0        0.0       0
5857  20230623   080500    080959  ...         0.0        0.0       0
5858  20230623   081000    081459  ...         0.0        0.0       0
5859  20230623   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-23 08:20:08,014:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687479599, self.tradeDate='20230623', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29986.0, self.close=30008.1, self.high=30024.8, self.low=29960.8, self.vol=2508.994, self.amt=75269697.3288, ukdf['pct'].iloc[-1]=0.000737 , ukdf['amount'].iloc[-1]=75269697.3288, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-43762.455', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30007.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [23/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=11489
self.closeSec=1687479899, self.tradeDate='20230623', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30008.1, self.close=30029.2, self.high=30035.7, self.low=29978.0, self.vol=1455.613, self.amt=43684207.7323 
2023-06-23 08:25:00,788:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230623   080000    080459  ...         0.0        0.0       0
5857  20230623   080500    080959  ...         0.0        0.0       0
5858  20230623   081000    081459  ...         0.0        0.0       0
5859  20230623   081500    081959  ...         0.0        0.0       0
5860  20230623   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-23 08:25:00,788:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687479899, self.tradeDate='20230623', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30008.1, self.close=30029.2, self.high=30035.7, self.low=29978.0, self.vol=1455.613, self.amt=43684207.7323, ukdf['pct'].iloc[-1]=0.000703 , ukdf['amount'].iloc[-1]=43684207.7323, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-44067.4344', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30029.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1687479599, self.tradeDate='20230623', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29986.0, self.close=30008.1, self.high=30024.8, self.low=29960.8 
127.0.0.1 - - [23/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-23 08:20:05,164:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687479599, self.tradeDate='20230623', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29986.0, self.close=30008.1, self.high=30024.8, self.low=29960.8   
2023-06-23 08:20:06,885:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230623   075500    075959  1687478399  ...  29875.0 -0.000749   1535    5
1536  20230623   080000    080459  1687478699  ...  29865.0  0.001061   1536    0
1537  20230623   080500    080959  1687478999  ...  29895.1  0.000020   1537    1
1538  20230623   081000    081459  1687479299  ...  29904.5  0.002461   1538    2
1539  20230623   081500    081959  1687479599  ...  29960.8  0.000737   1539    3

[5 rows x 11 columns]
2023-06-23 08:20:06,904:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [23/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=293, self.factor=0.40941386836821464, self.count=11491 

self.closeSec=1687479899, self.tradeDate='20230623', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30008.1, self.close=30029.2, self.high=30035.7, self.low=29978.0 
2023-06-23 08:25:00,749:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687479899, self.tradeDate='20230623', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30008.1, self.close=30029.2, self.high=30035.7, self.low=29978.0   
2023-06-23 08:25:00,777:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230623   080000    080459  1687478699  ...  29865.0  0.001061   1536    0
1537  20230623   080500    080959  1687478999  ...  29895.1  0.000020   1537    1
1538  20230623   081000    081459  1687479299  ...  29904.5  0.002461   1538    2
1539  20230623   081500    081959  1687479599  ...  29960.8  0.000737   1539    3
1540  20230623   082000    082459  1687479899  ...  29978.0  0.000703   1540    4

[5 rows x 11 columns]
2023-06-23 08:25:00,778:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-23 08:00:19,299:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230623    052959  30143.1  ...  56.666667  0.555745  0.441960
5771  20230623    055959  30002.3  ...  56.666667  0.559226  0.442601
5772  20230623    062959  30041.8  ...  56.250000  0.557871  0.444008
5773  20230623    065959  30029.8  ...  55.833333  0.545366  0.452578
5774  20230623    072959  29917.6  ...  56.250000  0.550666  0.451914

[5 rows x 33 columns]
0.5656192236598891
acc is : 0.5656192236598891
2023-06-23 08:00:19,407:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.461939  0.538061       1  ...  1.135331   1.0    0.0  1.156410
537     1  0.495363  0.504637       0  ...  1.134878   1.0    0.0  1.155948
538     1  0.469963  0.530037       0  ...  1.130672   1.0    0.0  1.151663
539     1  0.461108  0.538892       1  ...  1.132841   1.0    0.0  1.153873
540     1  0.484919  0.515081       0  ...  1.129024   1.0    0.0  1.149985

[5 rows x 10 columns]
2023-06-23 08:00:19,420:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.461155  0.538845       1  ...  1.135331   1.0    0.0  1.167075
46     1  0.494878  0.505122       0  ...  1.134878   1.0    0.0  1.162904
47     1  0.469792  0.530208       0  ...  1.130672   1.0    0.0  1.156950
48     1  0.461108  0.538892       1  ...  1.132841   1.0    0.0  1.153873
49     1  0.484919  0.515081       0  ...  1.129024   1.0    0.0  1.149985

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.727', 'enterprice': '30025.4', 'countrevence': '0', 'unrealprofit': '-3665.88427782132', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29888.23966484', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230623   075000    075959  1687478399  29948.3    29875 -0.002448
2023-06-23 08:00:02,181:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [23/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5744 

self.closeSec=1687478999, self.tradeDate='20230623', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29875', self.close='29912.4'
2023-06-23 08:10:01,132:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687478999, self.tradeDate='20230623', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29875', self.close='29912.4'
2023-06-23 08:10:01,166:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230623   072000    072959  1687476599  29957.6    29976  0.000618
621  20230623   073000    073959  1687477199    29976  29975.3 -0.000023
622  20230623   074000    074959  1687477799  29975.3  29948.3 -0.000901
623  20230623   075000    075959  1687478399  29948.3    29875 -0.002448
624  20230623   080000    080959  1687478999    29875  29912.4  0.001252
2023-06-23 08:10:01,166:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5745 

self.closeSec=1687479599, self.tradeDate='20230623', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29912.5', self.close='30008.1'
127.0.0.1 - - [23/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-23 08:20:07,773:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687479599, self.tradeDate='20230623', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29912.5', self.close='30008.1'
2023-06-23 08:20:08,585:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230623   073000    073959  1687477199    29976  29975.3 -0.000023
622  20230623   074000    074959  1687477799  29975.3  29948.3 -0.000901
623  20230623   075000    075959  1687478399  29948.3    29875 -0.002448
624  20230623   080000    080959  1687478999    29875  29912.4  0.001252
625  20230623   081000    081959  1687479599  29912.5  30008.1  0.003199
2023-06-23 08:20:08,594:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230623   075000    075959  1687478399  29948.3    29875
2023-06-23 08:00:02,146:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [23/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5747 

self.closeSec=1687478999, self.tradeDate='20230623', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29875', self.close='29912.4'
2023-06-23 08:10:01,144:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687478999, self.tradeDate='20230623', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29875', self.close='29912.4'
2023-06-23 08:10:01,159:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230623   072000    072959  1687476599  29957.6    29976
17469  20230623   073000    073959  1687477199    29976  29975.3
17470  20230623   074000    074959  1687477799  29975.3  29948.3
17471  20230623   075000    075959  1687478399  29948.3    29875
17472  20230623   080000    080959  1687478999    29875  29912.4
2023-06-23 08:10:01,159:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5748 

self.closeSec=1687479599, self.tradeDate='20230623', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29912.5', self.close='30008.1'
127.0.0.1 - - [23/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-23 08:20:10,029:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687479599, self.tradeDate='20230623', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29912.5', self.close='30008.1'
2023-06-23 08:20:10,172:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230623   073000    073959  1687477199    29976  29975.3
17470  20230623   074000    074959  1687477799  29975.3  29948.3
17471  20230623   075000    075959  1687478399  29948.3    29875
17472  20230623   080000    080959  1687478999    29875  29912.4
17473  20230623   081000    081959  1687479599  29912.5  30008.1
2023-06-23 08:20:10,173:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230623   075000    075959  1687478399  29948.3    29875
2023-06-23 08:00:02,187:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5747 

self.closeSec=1687478999, self.tradeDate='20230623', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29875', self.close='29912.4'
127.0.0.1 - - [23/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-06-23 08:10:01,139:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687478999, self.tradeDate='20230623', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29875', self.close='29912.4'
2023-06-23 08:10:01,158:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230623   072000    072959  1687476599  29957.6    29976
12141  20230623   073000    073959  1687477199    29976  29975.3
12142  20230623   074000    074959  1687477799  29975.3  29948.3
12143  20230623   075000    075959  1687478399  29948.3    29875
12144  20230623   080000    080959  1687478999    29875  29912.4
2023-06-23 08:10:01,160:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5748 

self.closeSec=1687479599, self.tradeDate='20230623', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29912.5', self.close='30008.1'
127.0.0.1 - - [23/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-23 08:20:09,467:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687479599, self.tradeDate='20230623', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29912.5', self.close='30008.1'
2023-06-23 08:20:09,825:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230623   073000    073959  1687477199    29976  29975.3
12142  20230623   074000    074959  1687477799  29975.3  29948.3
12143  20230623   075000    075959  1687478399  29948.3    29875
12144  20230623   080000    080959  1687478999    29875  29912.4
12145  20230623   081000    081959  1687479599  29912.5  30008.1
2023-06-23 08:20:09,826:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=11488
self.closeSec=1687479599, self.tradeDate='20230623', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29986.0, self.close=30008.1, self.high=30024.8, self.low=29960.8, self.vol=2508.994, self.amt=75269697.3288 
127.0.0.1 - - [23/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-23 08:20:07,955:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230623   075500    075959  ...         0.0        0.0       0
5856  20230623   080000    080459  ...         0.0        0.0       0
5857  20230623   080500    080959  ...         0.0        0.0       0
5858  20230623   081000    081459  ...         0.0        0.0       0
5859  20230623   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-23 08:20:07,995:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687479599, self.tradeDate='20230623', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29986.0, self.close=30008.1, self.high=30024.8, self.low=29960.8, self.vol=2508.994, self.amt=75269697.3288, ukdf['pct'].iloc[-1]=0.000737 , ukdf['amount'].iloc[-1]=75269697.3288, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '117491.8394', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30007.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [23/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=11489
self.closeSec=1687479899, self.tradeDate='20230623', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30008.1, self.close=30029.2, self.high=30035.7, self.low=29978.0, self.vol=1455.613, self.amt=43684207.7323 
2023-06-23 08:25:00,808:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230623   080000    080459  ...         0.0        0.0       0
5857  20230623   080500    080959  ...         0.0        0.0       0
5858  20230623   081000    081459  ...         0.0        0.0       0
5859  20230623   081500    081959  ...         0.0        0.0       0
5860  20230623   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-23 08:25:00,808:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687479899, self.tradeDate='20230623', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30008.1, self.close=30029.2, self.high=30035.7, self.low=29978.0, self.vol=1455.613, self.amt=43684207.7323, ukdf['pct'].iloc[-1]=0.000703 , ukdf['amount'].iloc[-1]=43684207.7323, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '118305.2273', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30029.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230622   200000    235959  1687449599  ...    719  1.165810  2.001616     1.0
720  20230623   000000    035959  1687463999  ...    720  1.132999  1.838901     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.344', 'enterprice': '27977.7', 'countrevence': '0', 'unrealprofit': '119100.8684186016', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30210.3947439', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [23/Jun/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1490949.9863712, self.flagDict['side']='buy', self.tradeCount=7, self.count=239
self.closeSec=1687478399, self.tradeDate='20230623', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=30208.7, self.close=29875.0, self.high=30260.0, self.low=29858.4, self.vol=45457.791, self.amt=1365426385.13853 
2023-06-23 08:00:01,745:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1687478399, self.tradeDate='20230623', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=30208.7, self.close=29875.0, self.high=30260.0, self.low=29858.4, self.vol=45457.791, self.amt=1365426385.13853 
2023-06-23 08:00:01,805:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230622   120000    155959  ...   59869.993  1.805752e+09 -0.006248
718  20230622   160000    195959  ...   92709.438  2.784195e+09 -0.005822
719  20230622   200000    235959  ...  177543.354  5.315799e+09 -0.002741
720  20230623   000000    035959  ...  101073.409  3.035134e+09  0.012451
721  20230623   040000    075959  ...   45457.791  1.365426e+09 -0.011050

[5 rows x 11 columns]
2023-06-23 08:00:03,188:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230622   120000    155959  1687420799  ...    717  1.187797  2.221400     1.0
718  20230622   160000    195959  1687435199  ...    718  1.158098  2.047588     1.0
719  20230622   200000    235959  1687449599  ...    719  1.165810  2.001616     1.0
720  20230623   000000    035959  1687463999  ...    720  1.132999  1.838901     1.0
721  20230623   040000    075959  1687478399  ...    721  1.101090  1.690718     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.344', 'enterprice': '27977.7', 'countrevence': '0', 'unrealprofit': '101515.14810316', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29880.72842125', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


