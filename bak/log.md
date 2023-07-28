# 20230728 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=21568
self.closeSec=1690503599, self.tradeDate='20230728', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29222.0, self.close=29218.1, self.high=29222.0, self.low=29211.2, self.vol=286.446, self.amt=8368841.7137 
127.0.0.1 - - [28/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-28 08:20:05,016:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230728   075500    075959  ...         0.0        0.0       0
5856  20230728   080000    080459  ...         0.0        0.0       0
5857  20230728   080500    080959  ...         0.0        0.0       0
5858  20230728   081000    081459  ...         0.0        0.0       0
5859  20230728   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-28 08:20:05,028:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690503599, self.tradeDate='20230728', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29222.0, self.close=29218.1, self.high=29222.0, self.low=29211.2, self.vol=286.446, self.amt=8368841.7137, ukdf['pct'].iloc[-1]=-0.000133 , ukdf['amount'].iloc[-1]=8368841.7137, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-32770.20973782798', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29218.06743773', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [28/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=21569
self.closeSec=1690503899, self.tradeDate='20230728', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29218.1, self.close=29224.4, self.high=29248.8, self.low=29211.1, self.vol=1016.509, self.amt=29713872.5229 
2023-07-28 08:25:00,757:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230728   080000    080459  ...         0.0        0.0       0
5857  20230728   080500    080959  ...         0.0        0.0       0
5858  20230728   081000    081459  ...         0.0        0.0       0
5859  20230728   081500    081959  ...         0.0        0.0       0
5860  20230728   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-28 08:25:00,757:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690503899, self.tradeDate='20230728', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29218.1, self.close=29224.4, self.high=29248.8, self.low=29211.1, self.vol=1016.509, self.amt=29713872.5229, ukdf['pct'].iloc[-1]=0.000216 , ukdf['amount'].iloc[-1]=29713872.5229, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-32876.29912812432', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29225.68551832', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1690503599, self.tradeDate='20230728', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29222.0, self.close=29218.1, self.high=29222.0, self.low=29211.2 
127.0.0.1 - - [28/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-28 08:20:03,386:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690503599, self.tradeDate='20230728', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29222.0, self.close=29218.1, self.high=29222.0, self.low=29211.2   
2023-07-28 08:20:04,377:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230728   075500    075959  1690502399  ...  29199.7  0.000342   1535    5
1536  20230728   080000    080459  1690502699  ...  29199.4 -0.000349   1536    0
1537  20230728   080500    080959  1690502999  ...  29197.6  0.000702   1537    1
1538  20230728   081000    081459  1690503299  ...  29205.5  0.000068   1538    2
1539  20230728   081500    081959  1690503599  ...  29211.2 -0.000133   1539    3

[5 rows x 11 columns]
2023-07-28 08:20:04,377:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6217865293522028, self.count=21571 

self.closeSec=1690503899, self.tradeDate='20230728', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29218.1, self.close=29224.4, self.high=29248.8, self.low=29211.1 
127.0.0.1 - - [28/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-07-28 08:25:00,728:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690503899, self.tradeDate='20230728', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29218.1, self.close=29224.4, self.high=29248.8, self.low=29211.1   
2023-07-28 08:25:00,742:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230728   080000    080459  1690502699  ...  29199.4 -0.000349   1536    0
1537  20230728   080500    080959  1690502999  ...  29197.6  0.000702   1537    1
1538  20230728   081000    081459  1690503299  ...  29205.5  0.000068   1538    2
1539  20230728   081500    081959  1690503599  ...  29211.2 -0.000133   1539    3
1540  20230728   082000    082459  1690503899  ...  29211.1  0.000216   1540    4

[5 rows x 11 columns]
2023-07-28 08:25:00,742:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-28 08:00:17,016:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230728    052959  29133.6  ...  48.333333  0.445535  0.688125
5771  20230728    055959  29168.0  ...  48.750000  0.446154  0.694850
5772  20230728    062959  29169.5  ...  49.166667  0.454394  0.698260
5773  20230728    065959  29190.7  ...  49.166667  0.453064  0.701996
5774  20230728    072959  29186.6  ...  49.166667  0.452602  0.705673

[5 rows x 33 columns]
0.5619223659889094
acc is : 0.5619223659889094
2023-07-28 08:00:17,079:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.514693  0.485307       1  ...  0.918989   1.0    0.0  0.960474
537     0  0.506189  0.493811       1  ...  0.919657   1.0    0.0  0.961172
538     0  0.512201  0.487799       0  ...  0.919528   1.0    0.0  0.961037
539     0  0.505393  0.494607       0  ...  0.919484   1.0    0.0  0.960991
540     0  0.508437  0.491563       1  ...  0.920256   1.0    0.0  0.961798

[5 rows x 10 columns]
2023-07-28 08:00:17,091:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.514802  0.485198       1  ...  0.918989   1.0    0.0  0.960601
46     0  0.506454  0.493546       1  ...  0.919657   1.0    0.0  0.961327
47     0  0.512340  0.487660       0  ...  0.919528   1.0    0.0  0.961680
48     0  0.505393  0.494607       0  ...  0.919484   1.0    0.0  0.960991
49     0  0.508437  0.491563       1  ...  0.920256   1.0    0.0  0.961798

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.818', 'enterprice': '29478', 'countrevence': '0', 'unrealprofit': '-6364.12048085314', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29210.80206227', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230728   075000    075959  1690502399  29192.5  29209.7  0.000589
2023-07-28 08:00:02,178:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10784 

self.closeSec=1690502999, self.tradeDate='20230728', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29209.8', self.close='29220'
2023-07-28 08:10:01,155:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690502999, self.tradeDate='20230728', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29209.8', self.close='29220'
127.0.0.1 - - [28/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-07-28 08:10:01,169:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230728   072000    072959  1690500599  29177.2  29185.2  0.000274
621  20230728   073000    073959  1690501199  29185.2  29190.5  0.000182
622  20230728   074000    074959  1690501799  29190.4  29192.5  0.000069
623  20230728   075000    075959  1690502399  29192.5  29209.7  0.000589
624  20230728   080000    080959  1690502999  29209.8    29220  0.000353
2023-07-28 08:10:01,170:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10785 

self.closeSec=1690503599, self.tradeDate='20230728', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29220', self.close='29218.1'
127.0.0.1 - - [28/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-28 08:20:05,487:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690503599, self.tradeDate='20230728', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29220', self.close='29218.1'
2023-07-28 08:20:05,850:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230728   073000    073959  1690501199  29185.2  29190.5  0.000182
622  20230728   074000    074959  1690501799  29190.4  29192.5  0.000069
623  20230728   075000    075959  1690502399  29192.5  29209.7  0.000589
624  20230728   080000    080959  1690502999  29209.8    29220  0.000353
625  20230728   081000    081959  1690503599    29220  29218.1 -0.000065
2023-07-28 08:20:05,859:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230728   075000    075959  1690502399  29192.5  29209.7
2023-07-28 08:00:02,168:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [28/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10787 

self.closeSec=1690502999, self.tradeDate='20230728', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29209.8', self.close='29220'
2023-07-28 08:10:01,152:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690502999, self.tradeDate='20230728', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29209.8', self.close='29220'
2023-07-28 08:10:01,159:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230728   072000    072959  1690500599  29177.2  29185.2
17469  20230728   073000    073959  1690501199  29185.2  29190.5
17470  20230728   074000    074959  1690501799  29190.4  29192.5
17471  20230728   075000    075959  1690502399  29192.5  29209.7
17472  20230728   080000    080959  1690502999  29209.8    29220
2023-07-28 08:10:01,159:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10788 

self.closeSec=1690503599, self.tradeDate='20230728', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29220', self.close='29218.1'
127.0.0.1 - - [28/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-28 08:20:06,543:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690503599, self.tradeDate='20230728', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29220', self.close='29218.1'
2023-07-28 08:20:06,627:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230728   073000    073959  1690501199  29185.2  29190.5
17470  20230728   074000    074959  1690501799  29190.4  29192.5
17471  20230728   075000    075959  1690502399  29192.5  29209.7
17472  20230728   080000    080959  1690502999  29209.8    29220
17473  20230728   081000    081959  1690503599    29220  29218.1
2023-07-28 08:20:06,627:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230728   075000    075959  1690502399  29192.5  29209.7
2023-07-28 08:00:02,179:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [28/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10787 

self.closeSec=1690502999, self.tradeDate='20230728', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29209.8', self.close='29220'
2023-07-28 08:10:01,162:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690502999, self.tradeDate='20230728', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29209.8', self.close='29220'
2023-07-28 08:10:01,171:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230728   072000    072959  1690500599  29177.2  29185.2
12141  20230728   073000    073959  1690501199  29185.2  29190.5
12142  20230728   074000    074959  1690501799  29190.4  29192.5
12143  20230728   075000    075959  1690502399  29192.5  29209.7
12144  20230728   080000    080959  1690502999  29209.8    29220
2023-07-28 08:10:01,171:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10788 

self.closeSec=1690503599, self.tradeDate='20230728', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29220', self.close='29218.1'
127.0.0.1 - - [28/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-28 08:20:06,429:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690503599, self.tradeDate='20230728', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29220', self.close='29218.1'
2023-07-28 08:20:06,552:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230728   073000    073959  1690501199  29185.2  29190.5
12142  20230728   074000    074959  1690501799  29190.4  29192.5
12143  20230728   075000    075959  1690502399  29192.5  29209.7
12144  20230728   080000    080959  1690502999  29209.8    29220
12145  20230728   081000    081959  1690503599    29220  29218.1
2023-07-28 08:20:06,552:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=21568
self.closeSec=1690503599, self.tradeDate='20230728', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29222.0, self.close=29218.1, self.high=29222.0, self.low=29211.2, self.vol=286.446, self.amt=8368841.7137 
127.0.0.1 - - [28/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-28 08:20:05,007:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230728   075500    075959  ...         0.0        0.0       0
5856  20230728   080000    080459  ...         0.0        0.0       0
5857  20230728   080500    080959  ...         0.0        0.0       0
5858  20230728   081000    081459  ...         0.0        0.0       0
5859  20230728   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-28 08:20:05,027:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690503599, self.tradeDate='20230728', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29222.0, self.close=29218.1, self.high=29222.0, self.low=29211.2, self.vol=286.446, self.amt=8368841.7137, ukdf['pct'].iloc[-1]=-0.000133 , ukdf['amount'].iloc[-1]=8368841.7137, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '88176.4481', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29218.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=21569
self.closeSec=1690503899, self.tradeDate='20230728', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29218.1, self.close=29224.4, self.high=29248.8, self.low=29211.1, self.vol=1016.509, self.amt=29713872.5229 
127.0.0.1 - - [28/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-07-28 08:25:00,755:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230728   080000    080459  ...         0.0        0.0       0
5857  20230728   080500    080959  ...         0.0        0.0       0
5858  20230728   081000    081459  ...         0.0        0.0       0
5859  20230728   081500    081959  ...         0.0        0.0       0
5860  20230728   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-28 08:25:00,756:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690503899, self.tradeDate='20230728', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29218.1, self.close=29224.4, self.high=29248.8, self.low=29211.1, self.vol=1016.509, self.amt=29713872.5229, ukdf['pct'].iloc[-1]=0.000216 , ukdf['amount'].iloc[-1]=29713872.5229, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '88458.18183592312', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29225.68551832', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230727   200000    235959  1690473599  ...    719  0.644596  0.965451     1.0
720  20230728   000000    035959  1690487999  ...    720  0.702865  1.167903     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.821', 'enterprice': '29117.6', 'countrevence': '0', 'unrealprofit': '2066.7517', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29155.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1594659.6936504, self.flagDict['side']='buy', self.tradeCount=13, self.count=449
self.closeSec=1690502399, self.tradeDate='20230728', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29152.6, self.close=29209.7, self.high=29225.0, self.low=29117.7, self.vol=20489.076, self.amt=597804112.698 
127.0.0.1 - - [28/Jul/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-07-28 08:00:01,723:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1690502399, self.tradeDate='20230728', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=29152.6, self.close=29209.7, self.high=29225.0, self.low=29117.7, self.vol=20489.076, self.amt=597804112.698 
2023-07-28 08:00:01,751:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230727   120000    155959  ...  27656.693  8.140954e+08  0.000299
718  20230727   160000    195959  ...  34054.531  1.003948e+09  0.003300
719  20230727   200000    235959  ...  55283.047  1.623142e+09 -0.007320
720  20230728   000000    035959  ...  63642.422  1.857446e+09 -0.004283
721  20230728   040000    075959  ...  20489.076  5.978041e+08  0.001959

[5 rows x 11 columns]
2023-07-28 08:00:02,540:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230727   120000    155959  1690444799  ...    717  0.611399  0.866264     1.0
718  20230727   160000    195959  1690459199  ...    718  0.610258  0.847065     1.0
719  20230727   200000    235959  1690473599  ...    719  0.644596  0.965451     1.0
720  20230728   000000    035959  1690487999  ...    720  0.702865  1.167903     1.0
721  20230728   040000    075959  1690502399  ...    721  0.490120  0.346234     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.821', 'enterprice': '29117.6', 'countrevence': '0', 'unrealprofit': '5175.43812654505', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29212.00612405', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


