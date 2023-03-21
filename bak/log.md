# 20230321 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=32764
self.closeSec=1679357999, self.tradeDate='20230321', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27769.9, self.close=27771.1, self.high=27788.0, self.low=27714.3, self.vol=1525.082, self.amt=42334876.874 
127.0.0.1 - - [21/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-21 08:20:04,793:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230321   075500    075959  ...         0.0        0.0       0
5856  20230321   080000    080459  ...         0.0        0.0       0
5857  20230321   080500    080959  ...         0.0        0.0       0
5858  20230321   081000    081459  ...         0.0        0.0       0
5859  20230321   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-21 08:20:04,814:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679357999, self.tradeDate='20230321', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27769.9, self.close=27771.1, self.high=27788.0, self.low=27714.3, self.vol=1525.082, self.amt=42334876.874, ukdf['pct'].iloc[-1]=7e-06 , ukdf['amount'].iloc[-1]=42334876.874, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-676482.10299190672', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27771.02598697', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [21/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=32765
self.closeSec=1679358299, self.tradeDate='20230321', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27769.6, self.close=27846.1, self.high=27875.4, self.low=27765.2, self.vol=2653.479, self.amt=73820780.1907 
2023-03-21 08:25:01,621:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230321   080000    080459  ...         0.0        0.0       0
5857  20230321   080500    080959  ...         0.0        0.0       0
5858  20230321   081000    081459  ...         0.0        0.0       0
5859  20230321   081500    081959  ...         0.0        0.0       0
5860  20230321   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-21 08:25:01,623:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679358299, self.tradeDate='20230321', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27769.6, self.close=27846.1, self.high=27875.4, self.low=27765.2, self.vol=2653.479, self.amt=73820780.1907, ukdf['pct'].iloc[-1]=0.002701 , ukdf['amount'].iloc[-1]=73820780.1907, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-681199.28003920288', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27849.41566138', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1679357999, self.tradeDate='20230321', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27769.9, self.close=27771.1, self.high=27788.0, self.low=27714.3 
127.0.0.1 - - [21/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-21 08:20:03,060:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679357999, self.tradeDate='20230321', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27769.9, self.close=27771.1, self.high=27788.0, self.low=27714.3   
2023-03-21 08:20:03,402:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230321   075500    075959  1679356799  ...  27667.0  0.000831   1535    5
1536  20230321   080000    080459  1679357099  ...  27689.5  0.000880   1536    0
1537  20230321   080500    080959  1679357399  ...  27665.0 -0.001969   1537    1
1538  20230321   081000    081459  1679357699  ...  27653.7  0.003233   1538    2
1539  20230321   081500    081959  1679357999  ...  27714.3  0.000007   1539    3

[5 rows x 11 columns]
2023-03-21 08:20:03,402:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [21/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=172, self.factor=0.384152673703752, self.count=33331 

self.closeSec=1679358299, self.tradeDate='20230321', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27769.6, self.close=27846.1, self.high=27875.4, self.low=27765.2 
2023-03-21 08:25:01,531:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679358299, self.tradeDate='20230321', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27769.6, self.close=27846.1, self.high=27875.4, self.low=27765.2   
2023-03-21 08:25:01,599:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230321   080000    080459  1679357099  ...  27689.5  0.000880   1536    0
1537  20230321   080500    080959  1679357399  ...  27665.0 -0.001969   1537    1
1538  20230321   081000    081459  1679357699  ...  27653.7  0.003233   1538    2
1539  20230321   081500    081959  1679357999  ...  27714.3  0.000007   1539    3
1540  20230321   082000    082459  1679358299  ...  27765.2  0.002701   1540    4

[5 rows x 11 columns]
2023-03-21 08:25:01,599:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-21 08:00:32,736:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230321    052959  27988.9  ...  52.083333  0.548532  0.424734
5771  20230321    055959  28074.5  ...  51.666667  0.538747  0.420891
5772  20230321    062959  27983.0  ...  51.250000  0.530110  0.421312
5773  20230321    065959  27901.1  ...  51.666667  0.533474  0.419938
5774  20230321    072959  27937.1  ...  51.666667  0.519299  0.425256

[5 rows x 33 columns]
0.5341959334565619
acc is : 0.5341959334565619
2023-03-21 08:00:32,888:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.560893  0.439107       0  ...  1.219575   1.0    0.0  1.301650
537     0  0.526267  0.473733       0  ...  1.216006   1.0    0.0  1.297840
538     0  0.511677  0.488323       1  ...  1.217579   1.0    0.0  1.299519
539     0  0.536077  0.463923       0  ...  1.211700   1.0    0.0  1.293245
540     1  0.458231  0.541769       0  ...  1.207420   1.0    0.0  1.288677

[5 rows x 10 columns]
2023-03-21 08:00:32,911:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.560610  0.439390       0  ...  1.217765   1.0    0.0  1.293270
46     0  0.523876  0.476124       0  ...  1.214201   1.0    0.0  1.291849
47     0  0.511853  0.488147       1  ...  1.226395   1.0    0.0  1.301220
48     0  0.536077  0.463923       0  ...  1.211700   1.0    0.0  1.293245
49     1  0.458231  0.541769       0  ...  1.207420   1.0    0.0  1.288677

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230321   075000    075959  1679356799  27684.3  27711.6  0.000986
2023-03-21 08:00:02,113:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [21/Mar/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16664 

self.closeSec=1679357399, self.tradeDate='20230321', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27704.1', self.close='27681.4'
2023-03-21 08:10:02,112:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679357399, self.tradeDate='20230321', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27704.1', self.close='27681.4'
2023-03-21 08:10:02,118:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230321   072000    072959  1679354999  27804.9  27802.3 -0.000273
621  20230321   073000    073959  1679355599  27802.3  27714.7 -0.003151
622  20230321   074000    074959  1679356199  27714.6  27684.3 -0.001097
623  20230321   075000    075959  1679356799  27684.3  27711.6  0.000986
624  20230321   080000    080959  1679357399  27704.1  27681.4 -0.001090
2023-03-21 08:10:02,118:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16665 

self.closeSec=1679357999, self.tradeDate='20230321', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27681.5', self.close='27771.1'
127.0.0.1 - - [21/Mar/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-03-21 08:20:04,224:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679357999, self.tradeDate='20230321', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27681.5', self.close='27771.1'
2023-03-21 08:20:04,793:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230321   073000    073959  1679355599  27802.3  27714.7 -0.003151
622  20230321   074000    074959  1679356199  27714.6  27684.3 -0.001097
623  20230321   075000    075959  1679356799  27684.3  27711.6  0.000986
624  20230321   080000    080959  1679357399  27704.1  27681.4 -0.001090
625  20230321   081000    081959  1679357999  27681.5  27771.1  0.003240
2023-03-21 08:20:04,793:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230321   075000    075959  1679356799  27684.3  27711.6
2023-03-21 08:00:02,133:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [21/Mar/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16665 

self.closeSec=1679357399, self.tradeDate='20230321', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27704.1', self.close='27681.4'
2023-03-21 08:10:02,151:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679357399, self.tradeDate='20230321', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27704.1', self.close='27681.4'
2023-03-21 08:10:02,189:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230321   072000    072959  1679354999  27804.9  27802.3
17469  20230321   073000    073959  1679355599  27802.3  27714.7
17470  20230321   074000    074959  1679356199  27714.6  27684.3
17471  20230321   075000    075959  1679356799  27684.3  27711.6
17472  20230321   080000    080959  1679357399  27704.1  27681.4
2023-03-21 08:10:02,189:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16666 

self.closeSec=1679357999, self.tradeDate='20230321', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27681.5', self.close='27771.1'
127.0.0.1 - - [21/Mar/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-03-21 08:20:05,943:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679357999, self.tradeDate='20230321', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27681.5', self.close='27771.1'
2023-03-21 08:20:06,047:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230321   073000    073959  1679355599  27802.3  27714.7
17470  20230321   074000    074959  1679356199  27714.6  27684.3
17471  20230321   075000    075959  1679356799  27684.3  27711.6
17472  20230321   080000    080959  1679357399  27704.1  27681.4
17473  20230321   081000    081959  1679357999  27681.5  27771.1
2023-03-21 08:20:06,048:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230321   075000    075959  1679356799  27684.3  27711.6
2023-03-21 08:00:02,079:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [21/Mar/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16665 

self.closeSec=1679357399, self.tradeDate='20230321', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27704.1', self.close='27681.4'
2023-03-21 08:10:02,148:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679357399, self.tradeDate='20230321', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27704.1', self.close='27681.4'
2023-03-21 08:10:02,180:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230321   072000    072959  1679354999  27804.9  27802.3
12141  20230321   073000    073959  1679355599  27802.3  27714.7
12142  20230321   074000    074959  1679356199  27714.6  27684.3
12143  20230321   075000    075959  1679356799  27684.3  27711.6
12144  20230321   080000    080959  1679357399  27704.1  27681.4
2023-03-21 08:10:02,181:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16666 

self.closeSec=1679357999, self.tradeDate='20230321', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27681.5', self.close='27771.1'
127.0.0.1 - - [21/Mar/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-03-21 08:20:05,643:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679357999, self.tradeDate='20230321', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27681.5', self.close='27771.1'
2023-03-21 08:20:05,855:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230321   073000    073959  1679355599  27802.3  27714.7
12142  20230321   074000    074959  1679356199  27714.6  27684.3
12143  20230321   075000    075959  1679356799  27684.3  27711.6
12144  20230321   080000    080959  1679357399  27704.1  27681.4
12145  20230321   081000    081959  1679357999  27681.5  27771.1
2023-03-21 08:20:05,855:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [21/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=28762
self.closeSec=1679357999, self.tradeDate='20230321', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27769.9, self.close=27771.1, self.high=27788.0, self.low=27714.3, self.vol=1525.082, self.amt=42334876.874 
2023-03-21 08:20:01,608:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230321   075500    075959  ...         0.0        0.0       0
5856  20230321   080000    080459  ...         0.0        0.0       0
5857  20230321   080500    080959  ...         0.0        0.0       0
5858  20230321   081000    081459  ...         0.0        0.0       0
5859  20230321   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-21 08:20:01,610:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679357999, self.tradeDate='20230321', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27769.9, self.close=27771.1, self.high=27788.0, self.low=27714.3, self.vol=1525.082, self.amt=42334876.874, ukdf['pct'].iloc[-1]=7e-06 , ukdf['amount'].iloc[-1]=42334876.874, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=28763
self.closeSec=1679358299, self.tradeDate='20230321', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27769.6, self.close=27846.1, self.high=27875.4, self.low=27765.2, self.vol=2653.479, self.amt=73820780.1907 
127.0.0.1 - - [21/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-03-21 08:25:01,557:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230321   080000    080459  ...         0.0        0.0       0
5857  20230321   080500    080959  ...         0.0        0.0       0
5858  20230321   081000    081459  ...         0.0        0.0       0
5859  20230321   081500    081959  ...         0.0        0.0       0
5860  20230321   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-21 08:25:01,557:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679358299, self.tradeDate='20230321', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27769.6, self.close=27846.1, self.high=27875.4, self.low=27765.2, self.vol=2653.479, self.amt=73820780.1907, ukdf['pct'].iloc[-1]=0.002701 , ukdf['amount'].iloc[-1]=73820780.1907, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230320   200000    235959  1679327999  ...    719  0.950938  0.740984     1.0
720  20230321   000000    035959  1679342399  ...    720  0.897158  0.578626     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.795', 'enterprice': '27400', 'countrevence': '0', 'unrealprofit': '19700.2159706303', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27766.20905234', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [21/Mar/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1472509.017, self.flagDict['side']='buy', self.tradeCount=26, self.count=694
self.closeSec=1679356799, self.tradeDate='20230321', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27769.6, self.close=27704.1, self.high=28180.8, self.low=27566.8, self.vol=95371.337, self.amt=2659753244.24095 
2023-03-21 08:00:01,938:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1679356799, self.tradeDate='20230321', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27769.6, self.close=27704.1, self.high=28180.8, self.low=27566.8, self.vol=95371.337, self.amt=2659753244.24095 
2023-03-21 08:00:01,985:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230320   120000    155959  ...  139390.542  3.864202e+09  0.033164
718  20230320   160000    195959  ...  202307.208  5.701327e+09  0.000295
719  20230320   200000    235959  ...  185779.965  5.191857e+09 -0.017642
720  20230321   000000    035959  ...  159672.805  4.423515e+09  0.003064
721  20230321   040000    075959  ...   95371.337  2.659753e+09 -0.002175

[5 rows x 11 columns]
2023-03-21 08:00:04,255:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230320   120000    155959  1679299199  ...    717  0.997496  0.896116     1.0
718  20230320   160000    195959  1679313599  ...    718  0.958243  0.773173     1.0
719  20230320   200000    235959  1679327999  ...    719  0.950938  0.740984     1.0
720  20230321   000000    035959  1679342399  ...    720  0.897158  0.578626     NaN
721  20230321   040000    075959  1679356799  ...    721  0.837221  0.400174     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.795', 'enterprice': '27400', 'countrevence': '0', 'unrealprofit': '16417.4496721277', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27705.18542006', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


