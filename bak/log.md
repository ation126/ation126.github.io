# 20230320 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=32476
self.closeSec=1679271599, self.tradeDate='20230320', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27975.4, self.close=27959.9, self.high=28010.0, self.low=27911.9, self.vol=2426.453, self.amt=67851661.551 
127.0.0.1 - - [20/Mar/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-03-20 08:20:04,738:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230320   075500    075959  ...         0.0        0.0       0
5856  20230320   080000    080459  ...         0.0        0.0       0
5857  20230320   080500    080959  ...         0.0        0.0       0
5858  20230320   081000    081459  ...         0.0        0.0       0
5859  20230320   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-20 08:20:04,757:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679271599, self.tradeDate='20230320', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27975.4, self.close=27959.9, self.high=28010.0, self.low=27911.9, self.vol=2426.453, self.amt=67851661.551, ukdf['pct'].iloc[-1]=-0.000608 , ukdf['amount'].iloc[-1]=67851661.551, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-687662.0003357952', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27956.8126352', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [20/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=32477
self.closeSec=1679271899, self.tradeDate='20230320', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27959.9, self.close=27993.5, self.high=28006.8, self.low=27921.4, self.vol=1528.582, self.amt=42748427.1644 
2023-03-20 08:25:01,577:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230320   080000    080459  ...         0.0        0.0       0
5857  20230320   080500    080959  ...         0.0        0.0       0
5858  20230320   081000    081459  ...         0.0        0.0       0
5859  20230320   081500    081959  ...         0.0        0.0       0
5860  20230320   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-20 08:25:01,578:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679271899, self.tradeDate='20230320', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27959.9, self.close=27993.5, self.high=28006.8, self.low=27921.4, self.vol=1528.582, self.amt=42748427.1644, ukdf['pct'].iloc[-1]=0.001202 , ukdf['amount'].iloc[-1]=42748427.1644, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-689863.6816', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27993.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1679271599, self.tradeDate='20230320', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27975.4, self.close=27959.9, self.high=28010.0, self.low=27911.9 
127.0.0.1 - - [20/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-20 08:20:01,800:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679271599, self.tradeDate='20230320', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27975.4, self.close=27959.9, self.high=28010.0, self.low=27911.9   
2023-03-20 08:20:02,298:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230320   075500    075959  1679270399  ...  27872.0  0.002291   1535    5
1536  20230320   080000    080459  1679270699  ...  27938.0 -0.000390   1536    0
1537  20230320   080500    080959  1679270999  ...  27766.2 -0.000422   1537    1
1538  20230320   081000    081459  1679271299  ...  27845.5  0.001572   1538    2
1539  20230320   081500    081959  1679271599  ...  27911.9 -0.000608   1539    3

[5 rows x 11 columns]
2023-03-20 08:20:02,299:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=124, self.factor=0.37094656639269386, self.count=33043 

self.closeSec=1679271899, self.tradeDate='20230320', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27959.9, self.close=27993.5, self.high=28006.8, self.low=27921.4 
127.0.0.1 - - [20/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-03-20 08:25:01,508:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679271899, self.tradeDate='20230320', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27959.9, self.close=27993.5, self.high=28006.8, self.low=27921.4   
2023-03-20 08:25:01,537:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230320   080000    080459  1679270699  ...  27938.0 -0.000390   1536    0
1537  20230320   080500    080959  1679270999  ...  27766.2 -0.000422   1537    1
1538  20230320   081000    081459  1679271299  ...  27845.5  0.001572   1538    2
1539  20230320   081500    081959  1679271599  ...  27911.9 -0.000608   1539    3
1540  20230320   082000    082459  1679271899  ...  27921.4  0.001202   1540    4

[5 rows x 11 columns]
2023-03-20 08:25:01,538:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-20 08:00:34,452:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230320    052959  27879.6  ...  50.416667  0.611128  0.290654
5771  20230320    055959  28099.1  ...  50.000000  0.592956  0.289492
5772  20230320    062959  27965.0  ...  50.000000  0.597749  0.286186
5773  20230320    065959  28017.8  ...  50.000000  0.605193  0.279613
5774  20230320    072959  28100.4  ...  50.416667  0.615731  0.268414

[5 rows x 33 columns]
0.5489833641404805
acc is : 0.5489833641404805
2023-03-20 08:00:34,604:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
536     0  0.567232  0.432768       0  ...  1.151415   1.0 -0.0016  1.266668
537     1  0.453393  0.546607       1  ...  1.153585   1.0  0.0000  1.269056
538     0  0.512828  0.487172       1  ...  1.156990   1.0  0.0000  1.272801
539     0  0.559208  0.440792       1  ...  1.161935   1.0  0.0000  1.278241
540     0  0.587524  0.412476       0  ...  1.151032   1.0  0.0000  1.266247

[5 rows x 10 columns]
2023-03-20 08:00:34,637:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.566791  0.433209       0  ...  1.162259   1.0 -0.0016  1.263698
46     1  0.453581  0.546419       1  ...  1.151675   1.0  0.0000  1.269004
47     0  0.512783  0.487217       1  ...  1.167887   1.0  0.0000  1.269684
48     0  0.559208  0.440792       1  ...  1.161935   1.0  0.0000  1.278241
49     0  0.587524  0.412476       0  ...  1.151032   1.0  0.0000  1.266247

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230320   075000    075959  1679270399  28077.8  27955.7 -0.004349
2023-03-20 08:00:01,907:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [20/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16520 

self.closeSec=1679270999, self.tradeDate='20230320', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27955.8', self.close='27938.5'
2023-03-20 08:10:01,872:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679270999, self.tradeDate='20230320', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27955.8', self.close='27938.5'
2023-03-20 08:10:01,891:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230320   072000    072959  1679268599  28214.8  28220.5  0.000149
621  20230320   073000    073959  1679269199  28220.6  28137.5 -0.002941
622  20230320   074000    074959  1679269799  28137.6  28077.8 -0.002122
623  20230320   075000    075959  1679270399  28077.8  27955.7 -0.004349
624  20230320   080000    080959  1679270999  27955.8  27938.5 -0.000615
2023-03-20 08:10:01,891:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16521 

self.closeSec=1679271599, self.tradeDate='20230320', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27933', self.close='27959.9'
127.0.0.1 - - [20/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-20 08:20:02,907:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679271599, self.tradeDate='20230320', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27933', self.close='27959.9'
2023-03-20 08:20:03,598:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230320   073000    073959  1679269199  28220.6  28137.5 -0.002941
622  20230320   074000    074959  1679269799  28137.6  28077.8 -0.002122
623  20230320   075000    075959  1679270399  28077.8  27955.7 -0.004349
624  20230320   080000    080959  1679270999  27955.8  27938.5 -0.000615
625  20230320   081000    081959  1679271599    27933  27959.9  0.000766
2023-03-20 08:20:03,607:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230320   075000    075959  1679270399  28077.8  27955.7
2023-03-20 08:00:01,872:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16521 

self.closeSec=1679270999, self.tradeDate='20230320', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27955.8', self.close='27938.5'
2023-03-20 08:10:01,879:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679270999, self.tradeDate='20230320', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27955.8', self.close='27938.5'
127.0.0.1 - - [20/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-03-20 08:10:01,905:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230320   072000    072959  1679268599  28214.8  28220.5
17469  20230320   073000    073959  1679269199  28220.6  28137.5
17470  20230320   074000    074959  1679269799  28137.6  28077.8
17471  20230320   075000    075959  1679270399  28077.8  27955.7
17472  20230320   080000    080959  1679270999  27955.8  27938.5
2023-03-20 08:10:01,905:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16522 

self.closeSec=1679271599, self.tradeDate='20230320', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27933', self.close='27959.9'
127.0.0.1 - - [20/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-20 08:20:05,624:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679271599, self.tradeDate='20230320', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27933', self.close='27959.9'
2023-03-20 08:20:05,781:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230320   073000    073959  1679269199  28220.6  28137.5
17470  20230320   074000    074959  1679269799  28137.6  28077.8
17471  20230320   075000    075959  1679270399  28077.8  27955.7
17472  20230320   080000    080959  1679270999  27955.8  27938.5
17473  20230320   081000    081959  1679271599    27933  27959.9
2023-03-20 08:20:05,782:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230320   075000    075959  1679270399  28077.8  27955.7
2023-03-20 08:00:01,943:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16521 

self.closeSec=1679270999, self.tradeDate='20230320', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27955.8', self.close='27938.5'
2023-03-20 08:10:01,897:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679270999, self.tradeDate='20230320', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27955.8', self.close='27938.5'
127.0.0.1 - - [20/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-03-20 08:10:01,926:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230320   072000    072959  1679268599  28214.8  28220.5
12141  20230320   073000    073959  1679269199  28220.6  28137.5
12142  20230320   074000    074959  1679269799  28137.6  28077.8
12143  20230320   075000    075959  1679270399  28077.8  27955.7
12144  20230320   080000    080959  1679270999  27955.8  27938.5
2023-03-20 08:10:01,926:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16522 

self.closeSec=1679271599, self.tradeDate='20230320', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27933', self.close='27959.9'
127.0.0.1 - - [20/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-20 08:20:05,147:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679271599, self.tradeDate='20230320', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27933', self.close='27959.9'
2023-03-20 08:20:05,429:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230320   073000    073959  1679269199  28220.6  28137.5
12142  20230320   074000    074959  1679269799  28137.6  28077.8
12143  20230320   075000    075959  1679270399  28077.8  27955.7
12144  20230320   080000    080959  1679270999  27955.8  27938.5
12145  20230320   081000    081959  1679271599    27933  27959.9
2023-03-20 08:20:05,429:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--: 127.0.0.1 - - [20/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
 version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=28474
self.closeSec=1679271599, self.tradeDate='20230320', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27975.4, self.close=27959.9, self.high=28010.0, self.low=27911.9, self.vol=2426.453, self.amt=67851661.551 
2023-03-20 08:20:01,636:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230320   075500    075959  ...         0.0        0.0       0
5856  20230320   080000    080459  ...         0.0        0.0       0
5857  20230320   080500    080959  ...         0.0        0.0       0
5858  20230320   081000    081459  ...         0.0        0.0       0
5859  20230320   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-20 08:20:01,638:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679271599, self.tradeDate='20230320', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27975.4, self.close=27959.9, self.high=28010.0, self.low=27911.9, self.vol=2426.453, self.amt=67851661.551, ukdf['pct'].iloc[-1]=-0.000608 , ukdf['amount'].iloc[-1]=67851661.551, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [20/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=28475
self.closeSec=1679271899, self.tradeDate='20230320', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27959.9, self.close=27993.5, self.high=28006.8, self.low=27921.4, self.vol=1528.582, self.amt=42748427.1644 
2023-03-20 08:25:01,615:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230320   080000    080459  ...         0.0        0.0       0
5857  20230320   080500    080959  ...         0.0        0.0       0
5858  20230320   081000    081459  ...         0.0        0.0       0
5859  20230320   081500    081959  ...         0.0        0.0       0
5860  20230320   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-20 08:25:01,616:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679271899, self.tradeDate='20230320', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27959.9, self.close=27993.5, self.high=28006.8, self.low=27921.4, self.vol=1528.582, self.amt=42748427.1644, ukdf['pct'].iloc[-1]=0.001202 , ukdf['amount'].iloc[-1]=42748427.1644, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230319   200000    235959  1679241599  ...    719  0.978582  0.898154     1.0
720  20230320   000000    035959  1679255999  ...    720  1.021906  1.009114     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.795', 'enterprice': '27400', 'countrevence': '0', 'unrealprofit': '45591.2625', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28247.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1472509.017, self.flagDict['side']='buy', self.tradeCount=26, self.count=688
self.closeSec=1679270399, self.tradeDate='20230320', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=28245.4, self.close=27955.7, self.high=28397.0, self.low=27722.4, self.vol=146620.436, self.amt=4111873921.63342 
127.0.0.1 - - [20/Mar/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-03-20 08:00:01,808:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1679270399, self.tradeDate='20230320', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=28245.4, self.close=27955.7, self.high=28397.0, self.low=27722.4, self.vol=146620.436, self.amt=4111873921.63342 
2023-03-20 08:00:01,962:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230319   120000    155959  ...   62219.778  1.681303e+09 -0.008505
718  20230319   160000    195959  ...   69530.397  1.879203e+09  0.007002
719  20230319   200000    235959  ...  164948.133  4.515101e+09  0.014073
720  20230320   000000    035959  ...  261334.591  7.308131e+09  0.025822
721  20230320   040000    075959  ...  146620.436  4.111874e+09 -0.010253

[5 rows x 11 columns]
2023-03-20 08:00:04,234:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230319   120000    155959  1679212799  ...    717  1.010286  1.019974     1.0
718  20230319   160000    195959  1679227199  ...    718  0.969619  0.885534     1.0
719  20230319   200000    235959  1679241599  ...    719  0.978582  0.898154     1.0
720  20230320   000000    035959  1679255999  ...    720  1.021906  1.009114     1.0
721  20230320   040000    075959  1679270399  ...    721  1.027322  1.009618     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.795', 'enterprice': '27400', 'countrevence': '0', 'unrealprofit': '29936.9175', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27956.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


