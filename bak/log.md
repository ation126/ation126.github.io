# 20230323 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=33340
self.closeSec=1679530799, self.tradeDate='20230323', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27280.6, self.close=27345.9, self.high=27378.9, self.low=27276.8, self.vol=2747.97, self.amt=75060329.86766 
127.0.0.1 - - [23/Mar/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-03-23 08:20:05,189:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230323   075500    075959  ...         0.0        0.0       0
5856  20230323   080000    080459  ...         0.0        0.0       0
5857  20230323   080500    080959  ...         0.0        0.0       0
5858  20230323   081000    081459  ...         0.0        0.0       0
5859  20230323   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-23 08:20:05,219:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679530799, self.tradeDate='20230323', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27280.6, self.close=27345.9, self.high=27378.9, self.low=27276.8, self.vol=2747.97, self.amt=75060329.86766, ukdf['pct'].iloc[-1]=0.002394 , ukdf['amount'].iloc[-1]=75060329.86766, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-651092.2848', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27349.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=33341
self.closeSec=1679531099, self.tradeDate='20230323', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27343.0, self.close=27350.2, self.high=27387.8, self.low=27336.6, self.vol=2935.651, self.amt=80323181.4392 
127.0.0.1 - - [23/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-03-23 08:25:01,707:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230323   080000    080459  ...         0.0        0.0       0
5857  20230323   080500    080959  ...         0.0        0.0       0
5858  20230323   081000    081459  ...         0.0        0.0       0
5859  20230323   081500    081959  ...         0.0        0.0       0
5860  20230323   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-23 08:25:01,707:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679531099, self.tradeDate='20230323', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27343.0, self.close=27350.2, self.high=27387.8, self.low=27336.6, self.vol=2935.651, self.amt=80323181.4392, ukdf['pct'].iloc[-1]=0.000157 , ukdf['amount'].iloc[-1]=80323181.4392, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-651365.46902647408', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27353.63975383', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1679530799, self.tradeDate='20230323', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27280.6, self.close=27345.9, self.high=27378.9, self.low=27276.8 
127.0.0.1 - - [23/Mar/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-03-23 08:20:04,129:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679530799, self.tradeDate='20230323', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27280.6, self.close=27345.9, self.high=27378.9, self.low=27276.8   
2023-03-23 08:20:05,028:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230323   075500    075959  1679529599  ...  27231.0 -0.000594   1535    5
1536  20230323   080000    080459  1679529899  ...  27221.6  0.001116   1536    0
1537  20230323   080500    080959  1679530199  ...  27189.3 -0.002571   1537    1
1538  20230323   081000    081459  1679530499  ...  27178.0  0.003181   1538    2
1539  20230323   081500    081959  1679530799  ...  27276.8  0.002394   1539    3

[5 rows x 11 columns]
2023-03-23 08:20:05,029:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=268, self.factor=0.44901934733821425, self.count=33907 

self.closeSec=1679531099, self.tradeDate='20230323', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27343.0, self.close=27350.2, self.high=27387.8, self.low=27336.6 
127.0.0.1 - - [23/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-03-23 08:25:01,623:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679531099, self.tradeDate='20230323', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27343.0, self.close=27350.2, self.high=27387.8, self.low=27336.6   
2023-03-23 08:25:01,671:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230323   080000    080459  1679529899  ...  27221.6  0.001116   1536    0
1537  20230323   080500    080959  1679530199  ...  27189.3 -0.002571   1537    1
1538  20230323   081000    081459  1679530499  ...  27178.0  0.003181   1538    2
1539  20230323   081500    081959  1679530799  ...  27276.8  0.002394   1539    3
1540  20230323   082000    082459  1679531099  ...  27336.6  0.000157   1540    4

[5 rows x 11 columns]
2023-03-23 08:25:01,671:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-23 08:00:33,520:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230323    052959  27294.9  ...  52.916667  0.435768  0.483603
5771  20230323    055959  27270.2  ...  52.500000  0.419971  0.504199
5772  20230323    062959  27065.3  ...  52.500000  0.429210  0.520811
5773  20230323    065959  27154.9  ...  52.500000  0.432725  0.535321
5774  20230323    072959  27189.2  ...  52.916667  0.444054  0.545636

[5 rows x 33 columns]
0.5231053604436229
acc is : 0.5231053604436229
2023-03-23 08:00:33,687:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
536     1  0.455591  0.544409       0  ...  1.258213  -1.0  0.0000  1.344278
537     1  0.427373  0.572627       1  ...  1.254043  -1.0  0.0000  1.348734
538     0  0.620109  0.379891       1  ...  1.253616   1.0 -0.0016  1.350432
539     0  0.566067  0.433933       1  ...  1.258729   1.0  0.0000  1.355941
540     0  0.577456  0.422544       0  ...  1.255672   1.0  0.0000  1.352648

[5 rows x 10 columns]
2023-03-23 08:00:33,717:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     1  0.456136  0.543864       0  ...  1.258213  -1.0  0.0000  1.349735
46     1  0.428006  0.571994       1  ...  1.254043  -1.0  0.0000  1.356509
47     0  0.620814  0.379186       1  ...  1.253616   1.0 -0.0016  1.353936
48     0  0.566067  0.433933       1  ...  1.258729   1.0  0.0000  1.355941
49     0  0.577456  0.422544       0  ...  1.255672   1.0  0.0000  1.352648

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230323   075000    075959  1679529599  27246.4  27233.8 -0.000459
2023-03-23 08:00:02,441:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16952 

self.closeSec=1679530199, self.tradeDate='20230323', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27233.8', self.close='27194.1'
2023-03-23 08:10:01,596:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679530199, self.tradeDate='20230323', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27233.8', self.close='27194.1'
127.0.0.1 - - [23/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-03-23 08:10:01,623:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230323   072000    072959  1679527799  27254.5  27300.1  0.001669
621  20230323   073000    073959  1679528399  27300.2  27252.8 -0.001733
622  20230323   074000    074959  1679528999  27252.8  27246.3 -0.000239
623  20230323   075000    075959  1679529599  27246.4  27233.8 -0.000459
624  20230323   080000    080959  1679530199  27233.8  27194.1 -0.001458
2023-03-23 08:10:01,623:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16953 

self.closeSec=1679530799, self.tradeDate='20230323', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27194.2', self.close='27345.9'
127.0.0.1 - - [23/Mar/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-03-23 08:20:04,498:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679530799, self.tradeDate='20230323', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27194.2', self.close='27345.9'
2023-03-23 08:20:05,159:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230323   073000    073959  1679528399  27300.2  27252.8 -0.001733
622  20230323   074000    074959  1679528999  27252.8  27246.3 -0.000239
623  20230323   075000    075959  1679529599  27246.4  27233.8 -0.000459
624  20230323   080000    080959  1679530199  27233.8  27194.1 -0.001458
625  20230323   081000    081959  1679530799  27194.2  27345.9  0.005582
2023-03-23 08:20:05,160:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230323   075000    075959  1679529599  27246.4  27233.8
2023-03-23 08:00:02,497:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16953 

self.closeSec=1679530199, self.tradeDate='20230323', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27233.8', self.close='27194.1'
2023-03-23 08:10:01,590:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679530199, self.tradeDate='20230323', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27233.8', self.close='27194.1'
127.0.0.1 - - [23/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-03-23 08:10:01,638:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230323   072000    072959  1679527799  27254.5  27300.1
17469  20230323   073000    073959  1679528399  27300.2  27252.8
17470  20230323   074000    074959  1679528999  27252.8  27246.3
17471  20230323   075000    075959  1679529599  27246.4  27233.8
17472  20230323   080000    080959  1679530199  27233.8  27194.1
2023-03-23 08:10:01,638:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16954 

self.closeSec=1679530799, self.tradeDate='20230323', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27194.2', self.close='27345.9'
127.0.0.1 - - [23/Mar/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-03-23 08:20:06,543:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679530799, self.tradeDate='20230323', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27194.2', self.close='27345.9'
2023-03-23 08:20:06,617:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230323   073000    073959  1679528399  27300.2  27252.8
17470  20230323   074000    074959  1679528999  27252.8  27246.3
17471  20230323   075000    075959  1679529599  27246.4  27233.8
17472  20230323   080000    080959  1679530199  27233.8  27194.1
17473  20230323   081000    081959  1679530799  27194.2  27345.9
2023-03-23 08:20:06,619:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230323   075000    075959  1679529599  27246.4  27233.8
2023-03-23 08:00:02,497:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16953 

self.closeSec=1679530199, self.tradeDate='20230323', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27233.8', self.close='27194.1'
2023-03-23 08:10:01,611:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679530199, self.tradeDate='20230323', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27233.8', self.close='27194.1'
127.0.0.1 - - [23/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-03-23 08:10:01,639:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230323   072000    072959  1679527799  27254.5  27300.1
12141  20230323   073000    073959  1679528399  27300.2  27252.8
12142  20230323   074000    074959  1679528999  27252.8  27246.3
12143  20230323   075000    075959  1679529599  27246.4  27233.8
12144  20230323   080000    080959  1679530199  27233.8  27194.1
2023-03-23 08:10:01,639:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16954 

self.closeSec=1679530799, self.tradeDate='20230323', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27194.2', self.close='27345.9'
127.0.0.1 - - [23/Mar/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-03-23 08:20:06,309:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679530799, self.tradeDate='20230323', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27194.2', self.close='27345.9'
2023-03-23 08:20:06,463:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230323   073000    073959  1679528399  27300.2  27252.8
12142  20230323   074000    074959  1679528999  27252.8  27246.3
12143  20230323   075000    075959  1679529599  27246.4  27233.8
12144  20230323   080000    080959  1679530199  27233.8  27194.1
12145  20230323   081000    081959  1679530799  27194.2  27345.9
2023-03-23 08:20:06,463:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [23/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=29338
self.closeSec=1679530799, self.tradeDate='20230323', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27280.6, self.close=27345.9, self.high=27378.9, self.low=27276.8, self.vol=2747.97, self.amt=75060329.86766 
2023-03-23 08:20:01,703:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230323   075500    075959  ...         0.0        0.0       0
5856  20230323   080000    080459  ...         0.0        0.0       0
5857  20230323   080500    080959  ...         0.0        0.0       0
5858  20230323   081000    081459  ...         0.0        0.0       0
5859  20230323   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-23 08:20:01,705:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679530799, self.tradeDate='20230323', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27280.6, self.close=27345.9, self.high=27378.9, self.low=27276.8, self.vol=2747.97, self.amt=75060329.86766, ukdf['pct'].iloc[-1]=0.002394 , ukdf['amount'].iloc[-1]=75060329.86766, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [23/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=29339
self.closeSec=1679531099, self.tradeDate='20230323', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27343.0, self.close=27350.2, self.high=27387.8, self.low=27336.6, self.vol=2935.651, self.amt=80323181.4392 
2023-03-23 08:25:01,698:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230323   080000    080459  ...         0.0        0.0       0
5857  20230323   080500    080959  ...         0.0        0.0       0
5858  20230323   081000    081459  ...         0.0        0.0       0
5859  20230323   081500    081959  ...         0.0        0.0       0
5860  20230323   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-23 08:25:01,700:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679531099, self.tradeDate='20230323', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27343.0, self.close=27350.2, self.high=27387.8, self.low=27336.6, self.vol=2935.651, self.amt=80323181.4392, ukdf['pct'].iloc[-1]=0.000157 , ukdf['amount'].iloc[-1]=80323181.4392, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230322   200000    235959  1679500799  ...    719  0.475192 -0.815555    -1.0
720  20230323   000000    035959  1679515199  ...    720  0.122268 -1.965458    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '74713.25001792564', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26699.94724206', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [23/Mar/2023 08:00:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1507151.9559834, self.flagDict['side']='sell', self.tradeCount=27, self.count=706
self.closeSec=1679529599, self.tradeDate='20230323', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26653.3, self.close=27233.8, self.high=27425.3, self.low=26590.0, self.vol=168601.777, self.amt=4570692545.78547 
2023-03-23 08:00:02,207:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1679529599, self.tradeDate='20230323', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26653.3, self.close=27233.8, self.high=27425.3, self.low=26590.0, self.vol=168601.777, self.amt=4570692545.78547 
2023-03-23 08:00:02,270:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230322   120000    155959  ...   54361.466  1.530369e+09 -0.001759
718  20230322   160000    195959  ...   61658.449  1.732829e+09  0.000901
719  20230322   200000    235959  ...  220961.586  6.291735e+09  0.016814
720  20230323   000000    035959  ...  512199.027  1.430242e+10 -0.067214
721  20230323   040000    075959  ...  168601.777  4.570693e+09  0.021339

[5 rows x 11 columns]
2023-03-23 08:00:04,704:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230322   120000    155959  1679471999  ...    717  0.493981 -0.688068    -1.0
718  20230322   160000    195959  1679486399  ...    718  0.444860 -0.872578    -1.0
719  20230322   200000    235959  1679500799  ...    719  0.475192 -0.815555    -1.0
720  20230323   000000    035959  1679515199  ...    720  0.122268 -1.965458    -1.0
721  20230323   040000    075959  1679529599  ...    721  0.129752 -1.963301    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '45996.32901479028', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27234.65325262', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


