# 20230314 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=30748
self.closeSec=1678753199, self.tradeDate='20230314', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=24016.9, self.close=24100.1, self.high=24142.3, self.low=24000.9, self.vol=4153.261, self.amt=100080476.9157 
127.0.0.1 - - [14/Mar/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-03-14 08:20:06,922:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230314   075500    075959  ...         0.0        0.0       0
5856  20230314   080000    080459  ...         0.0        0.0       0
5857  20230314   080500    080959  ...         0.0        0.0       0
5858  20230314   081000    081459  ...         0.0        0.0       0
5859  20230314   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-14 08:20:06,933:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678753199, self.tradeDate='20230314', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=24016.9, self.close=24100.1, self.high=24142.3, self.low=24000.9, self.vol=4153.261, self.amt=100080476.9157, ukdf['pct'].iloc[-1]=0.003464 , ukdf['amount'].iloc[-1]=100080476.9157, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-455195.3344', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24093.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=30749
self.closeSec=1678753499, self.tradeDate='20230314', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=24100.2, self.close=24120.2, self.high=24146.0, self.low=24084.3, self.vol=1454.043, self.amt=35063549.7307 
127.0.0.1 - - [14/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-03-14 08:25:01,603:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230314   080000    080459  ...         0.0        0.0       0
5857  20230314   080500    080959  ...         0.0        0.0       0
5858  20230314   081000    081459  ...         0.0        0.0       0
5859  20230314   081500    081959  ...         0.0        0.0       0
5860  20230314   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-14 08:25:01,604:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678753499, self.tradeDate='20230314', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=24100.2, self.close=24120.2, self.high=24146.0, self.low=24084.3, self.vol=1454.043, self.amt=35063549.7307, ukdf['pct'].iloc[-1]=0.000834 , ukdf['amount'].iloc[-1]=35063549.7307, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-456663.6288', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24118.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1678753199, self.tradeDate='20230314', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=24016.9, self.close=24100.1, self.high=24142.3, self.low=24000.9 
127.0.0.1 - - [14/Mar/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-03-14 08:20:04,250:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678753199, self.tradeDate='20230314', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=24016.9, self.close=24100.1, self.high=24142.3, self.low=24000.9   
2023-03-14 08:20:05,362:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230314   075500    075959  1678751999  ...  24054.3  0.002540   1535    5
1536  20230314   080000    080459  1678752299  ...  24073.0 -0.001858   1536    0
1537  20230314   080500    080959  1678752599  ...  24020.1 -0.000739   1537    1
1538  20230314   081000    081459  1678752899  ...  23990.0 -0.001596   1538    2
1539  20230314   081500    081959  1678753199  ...  24000.9  0.003464   1539    3

[5 rows x 11 columns]
2023-03-14 08:20:05,362:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [14/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=55, self.factor=0.17279409209649216, self.count=31315 

self.closeSec=1678753499, self.tradeDate='20230314', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=24100.2, self.close=24120.2, self.high=24146.0, self.low=24084.3 
2023-03-14 08:25:01,515:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678753499, self.tradeDate='20230314', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=24100.2, self.close=24120.2, self.high=24146.0, self.low=24084.3   
2023-03-14 08:25:01,570:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230314   080000    080459  1678752299  ...  24073.0 -0.001858   1536    0
1537  20230314   080500    080959  1678752599  ...  24020.1 -0.000739   1537    1
1538  20230314   081000    081459  1678752899  ...  23990.0 -0.001596   1538    2
1539  20230314   081500    081959  1678753199  ...  24000.9  0.003464   1539    3
1540  20230314   082000    082459  1678753499  ...  24084.3  0.000834   1540    4

[5 rows x 11 columns]
2023-03-14 08:25:01,578:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-14 08:00:34,132:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230314    052959  24160.4  ...  51.250000  0.689625  0.136551
5771  20230314    055959  24095.2  ...  51.666667  0.689704  0.137782
5772  20230314    062959  24096.6  ...  52.083333  0.696466  0.135992
5773  20230314    065959  24216.1  ...  52.083333  0.696453  0.134325
5774  20230314    072959  24216.1  ...  52.083333  0.675663  0.136754

[5 rows x 33 columns]
0.5619223659889094
acc is : 0.5619223659889094
2023-03-14 08:00:34,299:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.386829  0.613171       1  ...  1.078651  -1.0    0.0  1.034748
537     1  0.423387  0.576613       1  ...  1.073297  -1.0    0.0  1.039884
538     1  0.465124  0.534876       0  ...  1.073301  -1.0    0.0  1.039880
539     1  0.443517  0.556483       0  ...  1.080490  -1.0    0.0  1.032915
540     1  0.370015  0.629985       1  ...  1.077615  -1.0    0.0  1.035663

[5 rows x 10 columns]
2023-03-14 08:00:34,338:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.387230  0.612770       1  ...  1.078651  -1.0    0.0  1.031961
46     1  0.423170  0.576830       1  ...  1.073297  -1.0    0.0  1.038658
47     1  0.464572  0.535428       0  ...  1.073301  -1.0    0.0  1.040577
48     1  0.443517  0.556483       0  ...  1.080490  -1.0    0.0  1.032915
49     1  0.370015  0.629985       1  ...  1.077615  -1.0    0.0  1.035663

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '30.238', 'enterprice': '24295.7', 'countrevence': '0', 'unrealprofit': '4747.366', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24138.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230314   075000    075959  1678751999  24085.1  24119.5  0.001432
2023-03-14 08:00:02,279:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15656 

self.closeSec=1678752599, self.tradeDate='20230314', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='24119.5', self.close='24055.3'
2023-03-14 08:10:01,605:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678752599, self.tradeDate='20230314', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='24119.5', self.close='24055.3'
127.0.0.1 - - [14/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-03-14 08:10:01,631:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230314   072000    072959  1678750199    23967  24053.9  0.003605
621  20230314   073000    073959  1678750799  24053.9    24000 -0.002241
622  20230314   074000    074959  1678751399    24000    24085  0.003542
623  20230314   075000    075959  1678751999  24085.1  24119.5  0.001432
624  20230314   080000    080959  1678752599  24119.5  24055.3 -0.002662
2023-03-14 08:10:01,631:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15657 

self.closeSec=1678753199, self.tradeDate='20230314', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='24055.4', self.close='24100.1'
127.0.0.1 - - [14/Mar/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-03-14 08:20:05,483:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678753199, self.tradeDate='20230314', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='24055.4', self.close='24100.1'
2023-03-14 08:20:06,271:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230314   073000    073959  1678750799  24053.9    24000 -0.002241
622  20230314   074000    074959  1678751399    24000    24085  0.003542
623  20230314   075000    075959  1678751999  24085.1  24119.5  0.001432
624  20230314   080000    080959  1678752599  24119.5  24055.3 -0.002662
625  20230314   081000    081959  1678753199  24055.4  24100.1  0.001862
2023-03-14 08:20:06,272:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230314   075000    075959  1678751999  24085.1  24119.5
2023-03-14 08:00:02,319:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15657 

self.closeSec=1678752599, self.tradeDate='20230314', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='24119.5', self.close='24055.3'
2023-03-14 08:10:01,582:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678752599, self.tradeDate='20230314', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='24119.5', self.close='24055.3'
127.0.0.1 - - [14/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-03-14 08:10:01,639:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230314   072000    072959  1678750199    23967  24053.9
17469  20230314   073000    073959  1678750799  24053.9    24000
17470  20230314   074000    074959  1678751399    24000    24085
17471  20230314   075000    075959  1678751999  24085.1  24119.5
17472  20230314   080000    080959  1678752599  24119.5  24055.3
2023-03-14 08:10:01,639:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15658 

self.closeSec=1678753199, self.tradeDate='20230314', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='24055.4', self.close='24100.1'
127.0.0.1 - - [14/Mar/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-03-14 08:20:08,093:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678753199, self.tradeDate='20230314', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='24055.4', self.close='24100.1'
2023-03-14 08:20:08,192:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230314   073000    073959  1678750799  24053.9    24000
17470  20230314   074000    074959  1678751399    24000    24085
17471  20230314   075000    075959  1678751999  24085.1  24119.5
17472  20230314   080000    080959  1678752599  24119.5  24055.3
17473  20230314   081000    081959  1678753199  24055.4  24100.1
2023-03-14 08:20:08,192:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230314   075000    075959  1678751999  24085.1  24119.5
2023-03-14 08:00:02,305:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15657 

self.closeSec=1678752599, self.tradeDate='20230314', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='24119.5', self.close='24055.3'
2023-03-14 08:10:01,597:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678752599, self.tradeDate='20230314', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='24119.5', self.close='24055.3'
127.0.0.1 - - [14/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-03-14 08:10:01,641:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230314   072000    072959  1678750199    23967  24053.9
12141  20230314   073000    073959  1678750799  24053.9    24000
12142  20230314   074000    074959  1678751399    24000    24085
12143  20230314   075000    075959  1678751999  24085.1  24119.5
12144  20230314   080000    080959  1678752599  24119.5  24055.3
2023-03-14 08:10:01,641:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15658 

self.closeSec=1678753199, self.tradeDate='20230314', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='24055.4', self.close='24100.1'
127.0.0.1 - - [14/Mar/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-03-14 08:20:07,643:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678753199, self.tradeDate='20230314', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='24055.4', self.close='24100.1'
2023-03-14 08:20:07,943:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230314   073000    073959  1678750799  24053.9    24000
12142  20230314   074000    074959  1678751399    24000    24085
12143  20230314   075000    075959  1678751999  24085.1  24119.5
12144  20230314   080000    080959  1678752599  24119.5  24055.3
12145  20230314   081000    081959  1678753199  24055.4  24100.1
2023-03-14 08:20:07,944:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--: 127.0.0.1 - - [14/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
 version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=26746
self.closeSec=1678753199, self.tradeDate='20230314', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=24016.9, self.close=24100.1, self.high=24142.3, self.low=24000.9, self.vol=4153.261, self.amt=100080476.9157 
2023-03-14 08:20:01,876:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230314   075500    075959  ...         0.0        0.0       0
5856  20230314   080000    080459  ...         0.0        0.0       0
5857  20230314   080500    080959  ...         0.0        0.0       0
5858  20230314   081000    081459  ...         0.0        0.0       0
5859  20230314   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-14 08:20:01,879:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678753199, self.tradeDate='20230314', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=24016.9, self.close=24100.1, self.high=24142.3, self.low=24000.9, self.vol=4153.261, self.amt=100080476.9157, ukdf['pct'].iloc[-1]=0.003464 , ukdf['amount'].iloc[-1]=100080476.9157, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=26747
self.closeSec=1678753499, self.tradeDate='20230314', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=24100.2, self.close=24120.2, self.high=24146.0, self.low=24084.3, self.vol=1454.043, self.amt=35063549.7307 
127.0.0.1 - - [14/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-03-14 08:25:01,614:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230314   080000    080459  ...         0.0        0.0       0
5857  20230314   080500    080959  ...         0.0        0.0       0
5858  20230314   081000    081459  ...         0.0        0.0       0
5859  20230314   081500    081959  ...         0.0        0.0       0
5860  20230314   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-14 08:25:01,614:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678753499, self.tradeDate='20230314', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=24100.2, self.close=24120.2, self.high=24146.0, self.low=24084.3, self.vol=1454.043, self.amt=35063549.7307, ukdf['pct'].iloc[-1]=0.000834 , ukdf['amount'].iloc[-1]=35063549.7307, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230313   200000    235959  1678723199  ...    719  1.272734  2.633642     1.0
720  20230314   000000    035959  1678737599  ...    720  1.190338  2.289389     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.825', 'enterprice': '20070', 'countrevence': '0', 'unrealprofit': '236620.22960577925', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24308.60688949', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1119287.34225, self.flagDict['side']='buy', self.tradeCount=24, self.count=652
self.closeSec=1678751999, self.tradeDate='20230314', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=24314.6, self.close=24117.9, self.high=24350.0, self.low=23935.7, self.vol=88630.517, self.amt=2139523204.36383 
127.0.0.1 - - [14/Mar/2023 08:00:02] "POST / HTTP/1.1" 200 -
2023-03-14 08:00:02,088:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1678751999, self.tradeDate='20230314', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=24314.6, self.close=24117.9, self.high=24350.0, self.low=23935.7, self.vol=88630.517, self.amt=2139523204.36383 
2023-03-14 08:00:02,129:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230313   120000    155959  ...  107549.845  2.405123e+09  0.010346
718  20230313   160000    195959  ...  212765.433  4.701409e+09 -0.015990
719  20230313   200000    235959  ...  677353.141  1.575063e+10  0.086744
720  20230314   000000    035959  ...  228551.466  5.508260e+09  0.012729
721  20230314   040000    075959  ...   88630.517  2.139523e+09 -0.008090

[5 rows x 11 columns]
2023-03-14 08:00:04,392:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230313   120000    155959  1678694399  ...    717  0.785806  0.877901     1.0
718  20230313   160000    195959  1678708799  ...    718  0.906902  1.339733     1.0
719  20230313   200000    235959  1678723199  ...    719  1.272734  2.633642     1.0
720  20230314   000000    035959  1678737599  ...    720  1.190338  2.289389     1.0
721  20230314   040000    075959  1678751999  ...    721  1.073077  1.854290     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.825', 'enterprice': '20070', 'countrevence': '0', 'unrealprofit': '226264.3075', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24123.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


