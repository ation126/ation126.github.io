# 20230326 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=34204
self.closeSec=1679789999, self.tradeDate='20230326', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27433.4, self.close=27430.7, self.high=27442.2, self.low=27400.0, self.vol=1131.907, self.amt=31038755.7554 
127.0.0.1 - - [26/Mar/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-03-26 08:20:07,896:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230326   075500    075959  ...         0.0        0.0       0
5856  20230326   080000    080459  ...         0.0        0.0       0
5857  20230326   080500    080959  ...         0.0        0.0       0
5858  20230326   081000    081459  ...         0.0        0.0       0
5859  20230326   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-26 08:20:07,909:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679789999, self.tradeDate='20230326', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27433.4, self.close=27430.7, self.high=27442.2, self.low=27400.0, self.vol=1131.907, self.amt=31038755.7554, ukdf['pct'].iloc[-1]=-0.000102 , ukdf['amount'].iloc[-1]=31038755.7554, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-656018.10983213584', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27430.95697009', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [26/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=34205
self.closeSec=1679790299, self.tradeDate='20230326', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27430.7, self.close=27420.5, self.high=27430.9, self.low=27415.1, self.vol=308.055, self.amt=8448098.9011 
2023-03-26 08:25:01,552:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230326   080000    080459  ...         0.0        0.0       0
5857  20230326   080500    080959  ...         0.0        0.0       0
5858  20230326   081000    081459  ...         0.0        0.0       0
5859  20230326   081500    081959  ...         0.0        0.0       0
5860  20230326   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-26 08:25:01,552:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679790299, self.tradeDate='20230326', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27430.7, self.close=27420.5, self.high=27430.9, self.low=27415.1, self.vol=308.055, self.amt=8448098.9011, ukdf['pct'].iloc[-1]=-0.000372 , ukdf['amount'].iloc[-1]=8448098.9011, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-655388.8512', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27420.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1679789999, self.tradeDate='20230326', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27433.4, self.close=27430.7, self.high=27442.2, self.low=27400.0 
127.0.0.1 - - [26/Mar/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-03-26 08:20:05,921:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679789999, self.tradeDate='20230326', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27433.4, self.close=27430.7, self.high=27442.2, self.low=27400.0   
2023-03-26 08:20:07,012:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230326   075500    075959  1679788799  ...  27445.2 -0.000007   1535    5
1536  20230326   080000    080459  1679789099  ...  27439.7 -0.000087   1536    0
1537  20230326   080500    080959  1679789399  ...  27438.7  0.000044   1537    1
1538  20230326   081000    081459  1679789699  ...  27433.4 -0.000459   1538    2
1539  20230326   081500    081959  1679789999  ...  27400.0 -0.000102   1539    3

[5 rows x 11 columns]
2023-03-26 08:20:07,012:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [26/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=412, self.factor=0.5618796767061343, self.count=34771 

self.closeSec=1679790299, self.tradeDate='20230326', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27430.7, self.close=27420.5, self.high=27430.9, self.low=27415.1 
2023-03-26 08:25:01,519:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679790299, self.tradeDate='20230326', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27430.7, self.close=27420.5, self.high=27430.9, self.low=27415.1   
2023-03-26 08:25:01,590:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230326   080000    080459  1679789099  ...  27439.7 -0.000087   1536    0
1537  20230326   080500    080959  1679789399  ...  27438.7  0.000044   1537    1
1538  20230326   081000    081459  1679789699  ...  27433.4 -0.000459   1538    2
1539  20230326   081500    081959  1679789999  ...  27400.0 -0.000102   1539    3
1540  20230326   082000    082459  1679790299  ...  27415.1 -0.000372   1540    4

[5 rows x 11 columns]
2023-03-26 08:25:01,590:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-26 08:00:35,016:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230326    052959  27341.4  ...  50.000000  0.466225  0.569252
5771  20230326    055959  27377.4  ...  50.416667  0.468561  0.571320
5772  20230326    062959  27394.2  ...  50.833333  0.478094  0.566311
5773  20230326    065959  27462.4  ...  50.416667  0.474533  0.564481
5774  20230326    072959  27434.4  ...  50.416667  0.472481  0.564399

[5 rows x 33 columns]
0.5138632162661737
acc is : 0.5138632162661737
2023-03-26 08:00:35,184:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.545285  0.454715       1  ...  1.113018   1.0    0.0  1.063448
537     0  0.557871  0.442129       1  ...  1.115793   1.0    0.0  1.066099
538     0  0.579243  0.420757       0  ...  1.114655   1.0    0.0  1.065012
539     0  0.542654  0.457346       0  ...  1.114005   1.0    0.0  1.064391
540     0  0.540021  0.459979       1  ...  1.115179   1.0    0.0  1.065513

[5 rows x 10 columns]
2023-03-26 08:00:35,220:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.545280  0.454720       1  ...  1.119485   1.0    0.0  1.057226
46     0  0.558779  0.441221       1  ...  1.116081   1.0    0.0  1.065760
47     0  0.579543  0.420457       0  ...  1.120177   1.0    0.0  1.059738
48     0  0.543325  0.456675       0  ...  1.114005   1.0    0.0  1.064391
49     0  0.540021  0.459979       1  ...  1.115179   1.0    0.0  1.065513

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230326   075000    075959  1679788799  27455.3  27447.3 -0.000295
2023-03-26 08:00:02,140:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [26/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17384 

self.closeSec=1679789399, self.tradeDate='20230326', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27447.2', self.close='27446.1'
2023-03-26 08:10:01,613:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679789399, self.tradeDate='20230326', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27447.2', self.close='27446.1'
2023-03-26 08:10:01,643:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230326   072000    072959  1679786999  27446.6  27418.4 -0.001031
621  20230326   073000    073959  1679787599  27418.4  27452.9  0.001258
622  20230326   074000    074959  1679788199  27452.8  27455.4  0.000091
623  20230326   075000    075959  1679788799  27455.3  27447.3 -0.000295
624  20230326   080000    080959  1679789399  27447.2  27446.1 -0.000044
2023-03-26 08:10:01,643:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17385 

self.closeSec=1679789999, self.tradeDate='20230326', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27446', self.close='27430.7'
127.0.0.1 - - [26/Mar/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-03-26 08:20:06,811:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679789999, self.tradeDate='20230326', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27446', self.close='27430.7'
2023-03-26 08:20:07,572:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230326   073000    073959  1679787599  27418.4  27452.9  0.001258
622  20230326   074000    074959  1679788199  27452.8  27455.4  0.000091
623  20230326   075000    075959  1679788799  27455.3  27447.3 -0.000295
624  20230326   080000    080959  1679789399  27447.2  27446.1 -0.000044
625  20230326   081000    081959  1679789999    27446  27430.7 -0.000561
2023-03-26 08:20:07,581:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230326   075000    075959  1679788799  27455.3  27447.3
2023-03-26 08:00:02,108:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17385 

self.closeSec=1679789399, self.tradeDate='20230326', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27447.2', self.close='27446.1'
2023-03-26 08:10:01,627:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679789399, self.tradeDate='20230326', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27447.2', self.close='27446.1'
127.0.0.1 - - [26/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-03-26 08:10:01,665:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230326   072000    072959  1679786999  27446.6  27418.4
17469  20230326   073000    073959  1679787599  27418.4  27452.9
17470  20230326   074000    074959  1679788199  27452.8  27455.4
17471  20230326   075000    075959  1679788799  27455.3  27447.3
17472  20230326   080000    080959  1679789399  27447.2  27446.1
2023-03-26 08:10:01,666:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17386 

self.closeSec=1679789999, self.tradeDate='20230326', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27446', self.close='27430.7'
127.0.0.1 - - [26/Mar/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-03-26 08:20:09,633:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679789999, self.tradeDate='20230326', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27446', self.close='27430.7'
2023-03-26 08:20:09,765:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230326   073000    073959  1679787599  27418.4  27452.9
17470  20230326   074000    074959  1679788199  27452.8  27455.4
17471  20230326   075000    075959  1679788799  27455.3  27447.3
17472  20230326   080000    080959  1679789399  27447.2  27446.1
17473  20230326   081000    081959  1679789999    27446  27430.7
2023-03-26 08:20:09,765:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230326   075000    075959  1679788799  27455.3  27447.3
2023-03-26 08:00:02,131:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17385 

self.closeSec=1679789399, self.tradeDate='20230326', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27447.2', self.close='27446.1'
2023-03-26 08:10:01,603:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679789399, self.tradeDate='20230326', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27447.2', self.close='27446.1'
127.0.0.1 - - [26/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-03-26 08:10:01,638:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230326   072000    072959  1679786999  27446.6  27418.4
12141  20230326   073000    073959  1679787599  27418.4  27452.9
12142  20230326   074000    074959  1679788199  27452.8  27455.4
12143  20230326   075000    075959  1679788799  27455.3  27447.3
12144  20230326   080000    080959  1679789399  27447.2  27446.1
2023-03-26 08:10:01,638:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17386 

self.closeSec=1679789999, self.tradeDate='20230326', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27446', self.close='27430.7'
127.0.0.1 - - [26/Mar/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-03-26 08:20:09,101:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679789999, self.tradeDate='20230326', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27446', self.close='27430.7'
2023-03-26 08:20:09,410:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230326   073000    073959  1679787599  27418.4  27452.9
12142  20230326   074000    074959  1679788199  27452.8  27455.4
12143  20230326   075000    075959  1679788799  27455.3  27447.3
12144  20230326   080000    080959  1679789399  27447.2  27446.1
12145  20230326   081000    081959  1679789999    27446  27430.7
2023-03-26 08:20:09,411:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--: 127.0.0.1 - - [26/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
 version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=30202
self.closeSec=1679789999, self.tradeDate='20230326', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27433.4, self.close=27430.7, self.high=27442.2, self.low=27400.0, self.vol=1131.907, self.amt=31038755.7554 
2023-03-26 08:20:03,351:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230326   075500    075959  ...         0.0        0.0       0
5856  20230326   080000    080459  ...         0.0        0.0       0
5857  20230326   080500    080959  ...         0.0        0.0       0
5858  20230326   081000    081459  ...         0.0        0.0       0
5859  20230326   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-26 08:20:03,381:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679789999, self.tradeDate='20230326', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27433.4, self.close=27430.7, self.high=27442.2, self.low=27400.0, self.vol=1131.907, self.amt=31038755.7554, ukdf['pct'].iloc[-1]=-0.000102 , ukdf['amount'].iloc[-1]=31038755.7554, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [26/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=30203
self.closeSec=1679790299, self.tradeDate='20230326', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27430.7, self.close=27420.5, self.high=27430.9, self.low=27415.1, self.vol=308.055, self.amt=8448098.9011 
2023-03-26 08:25:01,567:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230326   080000    080459  ...         0.0        0.0       0
5857  20230326   080500    080959  ...         0.0        0.0       0
5858  20230326   081000    081459  ...         0.0        0.0       0
5859  20230326   081500    081959  ...         0.0        0.0       0
5860  20230326   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-26 08:25:01,568:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679790299, self.tradeDate='20230326', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27430.7, self.close=27420.5, self.high=27430.9, self.low=27415.1, self.vol=308.055, self.amt=8448098.9011, ukdf['pct'].iloc[-1]=-0.000372 , ukdf['amount'].iloc[-1]=8448098.9011, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230325   200000    235959  1679759999  ...    719  0.033079 -1.693519    -1.0
720  20230326   000000    035959  1679774399  ...    720  0.038373 -1.634950    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '49463.226', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27170.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [26/Mar/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1507151.9559834, self.flagDict['side']='sell', self.tradeCount=27, self.count=724
self.closeSec=1679788799, self.tradeDate='20230326', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27179.4, self.close=27447.3, self.high=27522.0, self.low=27139.7, self.vol=46178.862, self.amt=1264141340.08546 
2023-03-26 08:00:01,961:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1679788799, self.tradeDate='20230326', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27179.4, self.close=27447.3, self.high=27522.0, self.low=27139.7, self.vol=46178.862, self.amt=1264141340.08546 
2023-03-26 08:00:02,029:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230325   120000    155959  ...  39018.021  1.072444e+09 -0.003450
718  20230325   160000    195959  ...  49158.275  1.348154e+09 -0.001016
719  20230325   200000    235959  ...  74885.923  2.063696e+09  0.006832
720  20230326   000000    035959  ...  83903.179  2.300180e+09 -0.016415
721  20230326   040000    075959  ...  46178.862  1.264141e+09  0.009853

[5 rows x 11 columns]
2023-03-26 08:00:04,640:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230325   120000    155959  1679731199  ...    717  0.025766 -1.811750    -1.0
718  20230325   160000    195959  1679745599  ...    718  0.029472 -1.750828    -1.0
719  20230325   200000    235959  1679759999  ...    719  0.033079 -1.693519    -1.0
720  20230326   000000    035959  1679774399  ...    720  0.038373 -1.634950    -1.0
721  20230326   040000    075959  1679788799  ...    721  0.041372 -1.584813    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '34581.2934', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27447.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


