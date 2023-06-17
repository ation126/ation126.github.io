# 20230617 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=9760
self.closeSec=1686961199, self.tradeDate='20230617', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26345.6, self.close=26344.7, self.high=26362.2, self.low=26339.4, self.vol=828.186, self.amt=21824391.6794 
127.0.0.1 - - [17/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-17 08:20:07,353:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230617   075500    075959  ...         0.0        0.0       0
5856  20230617   080000    080459  ...         0.0        0.0       0
5857  20230617   080500    080959  ...         0.0        0.0       0
5858  20230617   081000    081459  ...         0.0        0.0       0
5859  20230617   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-17 08:20:07,382:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686961199, self.tradeDate='20230617', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26345.6, self.close=26344.7, self.high=26362.2, self.low=26339.4, self.vol=828.186, self.amt=21824391.6794, ukdf['pct'].iloc[-1]=-3e-05 , ukdf['amount'].iloc[-1]=21824391.6794, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '7273.8441420249', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26342.57886385', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=9761
self.closeSec=1686961499, self.tradeDate='20230617', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26344.6, self.close=26336.0, self.high=26344.7, self.low=26320.0, self.vol=780.367, self.amt=20548910.9085 
127.0.0.1 - - [17/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-06-17 08:25:00,813:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230617   080000    080459  ...         0.0        0.0       0
5857  20230617   080500    080959  ...         0.0        0.0       0
5858  20230617   081000    081459  ...         0.0        0.0       0
5859  20230617   081500    081959  ...         0.0        0.0       0
5860  20230617   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-17 08:25:00,813:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686961499, self.tradeDate='20230617', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26344.6, self.close=26336.0, self.high=26344.7, self.low=26320.0, self.vol=780.367, self.amt=20548910.9085, ukdf['pct'].iloc[-1]=-0.00033 , ukdf['amount'].iloc[-1]=20548910.9085, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '7364.0688', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26336.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1686961199, self.tradeDate='20230617', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26345.6, self.close=26344.7, self.high=26362.2, self.low=26339.4 
127.0.0.1 - - [17/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-17 08:20:04,771:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686961199, self.tradeDate='20230617', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26345.6, self.close=26344.7, self.high=26362.2, self.low=26339.4   
2023-06-17 08:20:06,302:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230617   075500    075959  1686959999  ...  26330.2 -0.000027   1535    5
1536  20230617   080000    080459  1686960299  ...  26321.2 -0.000182   1536    0
1537  20230617   080500    080959  1686960599  ...  26322.7 -0.000216   1537    1
1538  20230617   081000    081459  1686960899  ...  26316.5  0.000760   1538    2
1539  20230617   081500    081959  1686961199  ...  26339.4 -0.000030   1539    3

[5 rows x 11 columns]
2023-06-17 08:20:06,311:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--: 127.0.0.1 - - [17/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=5, self.factor=0.2564454940874696, self.count=9763 

self.closeSec=1686961499, self.tradeDate='20230617', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26344.6, self.close=26336.0, self.high=26344.7, self.low=26320.0 
2023-06-17 08:25:00,762:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686961499, self.tradeDate='20230617', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26344.6, self.close=26336.0, self.high=26344.7, self.low=26320.0   
2023-06-17 08:25:00,799:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230617   080000    080459  1686960299  ...  26321.2 -0.000182   1536    0
1537  20230617   080500    080959  1686960599  ...  26322.7 -0.000216   1537    1
1538  20230617   081000    081459  1686960899  ...  26316.5  0.000760   1538    2
1539  20230617   081500    081959  1686961199  ...  26339.4 -0.000030   1539    3
1540  20230617   082000    082459  1686961499  ...  26320.0 -0.000330   1540    4

[5 rows x 11 columns]
2023-06-17 08:25:00,800:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-17 08:00:18,408:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230617    052959  26398.0  ...  50.000000  0.621029  0.180449
5771  20230617    055959  26301.1  ...  50.000000  0.618533  0.179824
5772  20230617    062959  26290.0  ...  50.416667  0.628014  0.175919
5773  20230617    065959  26359.0  ...  50.416667  0.627323  0.172418
5774  20230617    072959  26356.0  ...  50.416667  0.620511  0.170562

[5 rows x 33 columns]
0.5526802218114603
acc is : 0.5526802218114603
2023-06-17 08:00:18,488:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.475837  0.524163       0  ...  1.094221   1.0    0.0  1.025467
537     1  0.490045  0.509955       1  ...  1.097093   1.0    0.0  1.028158
538     0  0.505613  0.494387       0  ...  1.096968   1.0    0.0  1.028041
539     1  0.494783  0.505217       0  ...  1.095748   1.0    0.0  1.026899
540     1  0.484197  0.515803       1  ...  1.096135   1.0    0.0  1.027261

[5 rows x 10 columns]
2023-06-17 08:00:18,500:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.478275  0.521725       0  ...  1.109336   1.0    0.0  1.011438
46     1  0.492735  0.507265       1  ...  1.106521   1.0    0.0  1.019363
47     0  0.505508  0.494492       0  ...  1.103760   1.0    0.0  1.021693
48     1  0.494916  0.505084       0  ...  1.095748   1.0    0.0  1.026899
49     1  0.484197  0.515803       1  ...  1.096135   1.0    0.0  1.027261

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.127', 'enterprice': '25424', 'countrevence': '0', 'unrealprofit': '25702.4526', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26337.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230617   075000    075959  1686959999    26331    26336  0.000190
2023-06-17 08:00:02,220:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [17/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4880 

self.closeSec=1686960599, self.tradeDate='20230617', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26335.9', self.close='26325.5'
2023-06-17 08:10:01,139:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686960599, self.tradeDate='20230617', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26335.9', self.close='26325.5'
2023-06-17 08:10:01,169:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230617   072000    072959  1686958199  26362.1  26326.7 -0.001343
621  20230617   073000    073959  1686958799  26326.7  26329.3  0.000099
622  20230617   074000    074959  1686959399  26329.2    26331  0.000065
623  20230617   075000    075959  1686959999    26331    26336  0.000190
624  20230617   080000    080959  1686960599  26335.9  26325.5 -0.000399
2023-06-17 08:10:01,169:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4881 

self.closeSec=1686961199, self.tradeDate='20230617', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26325.4', self.close='26344.7'
127.0.0.1 - - [17/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-17 08:20:07,432:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686961199, self.tradeDate='20230617', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26325.4', self.close='26344.7'
2023-06-17 08:20:08,272:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230617   073000    073959  1686958799  26326.7  26329.3  0.000099
622  20230617   074000    074959  1686959399  26329.2    26331  0.000065
623  20230617   075000    075959  1686959999    26331    26336  0.000190
624  20230617   080000    080959  1686960599  26335.9  26325.5 -0.000399
625  20230617   081000    081959  1686961199  26325.4  26344.7  0.000729
2023-06-17 08:20:08,281:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230617   075000    075959  1686959999    26331    26336
2023-06-17 08:00:02,239:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4883 

self.closeSec=1686960599, self.tradeDate='20230617', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26335.9', self.close='26325.5'
2023-06-17 08:10:01,150:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686960599, self.tradeDate='20230617', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26335.9', self.close='26325.5'
127.0.0.1 - - [17/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-06-17 08:10:01,175:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230617   072000    072959  1686958199  26362.1  26326.7
17469  20230617   073000    073959  1686958799  26326.7  26329.3
17470  20230617   074000    074959  1686959399  26329.2    26331
17471  20230617   075000    075959  1686959999    26331    26336
17472  20230617   080000    080959  1686960599  26335.9  26325.5
2023-06-17 08:10:01,175:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4884 

self.closeSec=1686961199, self.tradeDate='20230617', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26325.4', self.close='26344.7'
127.0.0.1 - - [17/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-17 08:20:09,546:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686961199, self.tradeDate='20230617', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26325.4', self.close='26344.7'
2023-06-17 08:20:09,690:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230617   073000    073959  1686958799  26326.7  26329.3
17470  20230617   074000    074959  1686959399  26329.2    26331
17471  20230617   075000    075959  1686959999    26331    26336
17472  20230617   080000    080959  1686960599  26335.9  26325.5
17473  20230617   081000    081959  1686961199  26325.4  26344.7
2023-06-17 08:20:09,691:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230617   075000    075959  1686959999    26331    26336
2023-06-17 08:00:02,223:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [17/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4883 

self.closeSec=1686960599, self.tradeDate='20230617', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26335.9', self.close='26325.5'
2023-06-17 08:10:01,147:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686960599, self.tradeDate='20230617', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26335.9', self.close='26325.5'
2023-06-17 08:10:01,174:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230617   072000    072959  1686958199  26362.1  26326.7
12141  20230617   073000    073959  1686958799  26326.7  26329.3
12142  20230617   074000    074959  1686959399  26329.2    26331
12143  20230617   075000    075959  1686959999    26331    26336
12144  20230617   080000    080959  1686960599  26335.9  26325.5
2023-06-17 08:10:01,174:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4884 

self.closeSec=1686961199, self.tradeDate='20230617', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26325.4', self.close='26344.7'
127.0.0.1 - - [17/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-17 08:20:09,072:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686961199, self.tradeDate='20230617', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26325.4', self.close='26344.7'
2023-06-17 08:20:09,401:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230617   073000    073959  1686958799  26326.7  26329.3
12142  20230617   074000    074959  1686959399  26329.2    26331
12143  20230617   075000    075959  1686959999    26331    26336
12144  20230617   080000    080959  1686960599  26335.9  26325.5
12145  20230617   081000    081959  1686961199  26325.4  26344.7
2023-06-17 08:20:09,402:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=9760
self.closeSec=1686961199, self.tradeDate='20230617', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26345.6, self.close=26344.7, self.high=26362.2, self.low=26339.4, self.vol=828.186, self.amt=21824391.6794 
127.0.0.1 - - [17/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-17 08:20:07,352:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230617   075500    075959  ...         0.0        0.0       0
5856  20230617   080000    080459  ...         0.0        0.0       0
5857  20230617   080500    080959  ...         0.0        0.0       0
5858  20230617   081000    081459  ...         0.0        0.0       0
5859  20230617   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-17 08:20:07,373:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686961199, self.tradeDate='20230617', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26345.6, self.close=26344.7, self.high=26362.2, self.low=26339.4, self.vol=828.186, self.amt=21824391.6794, ukdf['pct'].iloc[-1]=-3e-05 , ukdf['amount'].iloc[-1]=21824391.6794, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-18623.28241774715', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26342.57886385', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=9761
self.closeSec=1686961499, self.tradeDate='20230617', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26344.6, self.close=26336.0, self.high=26344.7, self.low=26320.0, self.vol=780.367, self.amt=20548910.9085 
127.0.0.1 - - [17/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-06-17 08:25:00,812:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230617   080000    080459  ...         0.0        0.0       0
5857  20230617   080500    080959  ...         0.0        0.0       0
5858  20230617   081000    081459  ...         0.0        0.0       0
5859  20230617   081500    081959  ...         0.0        0.0       0
5860  20230617   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-17 08:25:00,814:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686961499, self.tradeDate='20230617', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26344.6, self.close=26336.0, self.high=26344.7, self.low=26320.0, self.vol=780.367, self.amt=20548910.9085, ukdf['pct'].iloc[-1]=-0.00033 , ukdf['amount'].iloc[-1]=20548910.9085, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-18863.9139', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26336.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230616   200000    235959  1686931199  ...    719  0.386754 -0.095560     NaN
720  20230617   000000    035959  1686945599  ...    720  0.404326  0.008649     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '38704.4656', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26377', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [17/Jun/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1492324.2295523998, self.flagDict['side']='sell', self.tradeCount=4, self.count=203
self.closeSec=1686959999, self.tradeDate='20230617', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26371.1, self.close=26336.0, self.high=26450.0, self.low=26273.7, self.vol=37660.921, self.amt=992499174.6699 
2023-06-17 08:00:01,761:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1686959999, self.tradeDate='20230617', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26371.1, self.close=26336.0, self.high=26450.0, self.low=26273.7, self.vol=37660.921, self.amt=992499174.6699 
2023-06-17 08:00:01,816:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230616   120000    155959  ...   40458.494  1.033506e+09 -0.000767
718  20230616   160000    195959  ...   43200.142  1.103317e+09 -0.002480
719  20230616   200000    235959  ...  151837.917  3.878343e+09  0.014515
720  20230617   000000    035959  ...  216896.427  5.674569e+09  0.020753
721  20230617   040000    075959  ...   37660.921  9.924992e+08 -0.001233

[5 rows x 11 columns]
2023-06-17 08:00:03,245:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230616   120000    155959  1686902399  ...    717  0.444552  0.148233     NaN
718  20230616   160000    195959  1686916799  ...    718  0.452034  0.201527     NaN
719  20230616   200000    235959  1686931199  ...    719  0.386754 -0.095560     NaN
720  20230617   000000    035959  1686945599  ...    720  0.404326  0.008649     NaN
721  20230617   040000    075959  1686959999  ...    721  0.422262  0.120551     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '40968.41984072074', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26335.96105861', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


