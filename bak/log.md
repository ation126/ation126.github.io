# 20230801 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=22720
self.closeSec=1690849199, self.tradeDate='20230801', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29214.9, self.close=29227.9, self.high=29228.0, self.low=29211.9, self.vol=321.213, self.amt=9385432.8605 
127.0.0.1 - - [01/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-01 08:20:06,129:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230801   075500    075959  ...         0.0        0.0       0
5856  20230801   080000    080459  ...         0.0        0.0       0
5857  20230801   080500    080959  ...         0.0        0.0       0
5858  20230801   081000    081459  ...         0.0        0.0       0
5859  20230801   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-01 08:20:06,150:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690849199, self.tradeDate='20230801', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29214.9, self.close=29227.9, self.high=29228.0, self.low=29211.9, self.vol=321.213, self.amt=9385432.8605, ukdf['pct'].iloc[-1]=0.000459 , ukdf['amount'].iloc[-1]=9385432.8605, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-32905.7454', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29227.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=22721
self.closeSec=1690849499, self.tradeDate='20230801', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29227.9, self.close=29224.9, self.high=29241.3, self.low=29223.0, self.vol=524.843, self.amt=15342231.7904 
127.0.0.1 - - [01/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-08-01 08:25:00,805:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230801   080000    080459  ...         0.0        0.0       0
5857  20230801   080500    080959  ...         0.0        0.0       0
5858  20230801   081000    081459  ...         0.0        0.0       0
5859  20230801   081500    081959  ...         0.0        0.0       0
5860  20230801   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-01 08:25:00,805:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690849499, self.tradeDate='20230801', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29227.9, self.close=29224.9, self.high=29241.3, self.low=29223.0, self.vol=524.843, self.amt=15342231.7904, ukdf['pct'].iloc[-1]=-0.000103 , ukdf['amount'].iloc[-1]=15342231.7904, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-32873.1724107996', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29225.4609946', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1690849199, self.tradeDate='20230801', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29214.9, self.close=29227.9, self.high=29228.0, self.low=29211.9 
127.0.0.1 - - [01/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-01 08:20:03,969:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690849199, self.tradeDate='20230801', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29214.9, self.close=29227.9, self.high=29228.0, self.low=29211.9   
2023-08-01 08:20:05,313:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230801   075500    075959  1690847999  ...  29219.4 -0.000178   1535    5
1536  20230801   080000    080459  1690848299  ...  29213.8 -0.000003   1536    0
1537  20230801   080500    080959  1690848599  ...  29200.9 -0.000626   1537    1
1538  20230801   081000    081459  1690848899  ...  29202.0  0.000414   1538    2
1539  20230801   081500    081959  1690849199  ...  29211.9  0.000459   1539    3

[5 rows x 11 columns]
2023-08-01 08:20:05,314:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [01/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=22, self.factor=0.5130342097541302, self.count=22723 

self.closeSec=1690849499, self.tradeDate='20230801', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29227.9, self.close=29224.9, self.high=29241.3, self.low=29223.0 
2023-08-01 08:25:00,758:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690849499, self.tradeDate='20230801', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29227.9, self.close=29224.9, self.high=29241.3, self.low=29223.0   
2023-08-01 08:25:00,770:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230801   080000    080459  1690848299  ...  29213.8 -0.000003   1536    0
1537  20230801   080500    080959  1690848599  ...  29200.9 -0.000626   1537    1
1538  20230801   081000    081459  1690848899  ...  29202.0  0.000414   1538    2
1539  20230801   081500    081959  1690849199  ...  29211.9  0.000459   1539    3
1540  20230801   082000    082459  1690849499  ...  29223.0 -0.000103   1540    4

[5 rows x 11 columns]
2023-08-01 08:25:00,770:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-01 08:00:16,357:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230801    052959  29194.5  ...  44.166667  0.455470  0.582829
5771  20230801    055959  29187.8  ...  44.583333  0.472481  0.588084
5772  20230801    062959  29230.6  ...  44.583333  0.471040  0.593697
5773  20230801    065959  29226.4  ...  44.166667  0.461609  0.602411
5774  20230801    072959  29199.5  ...  44.166667  0.456307  0.613367

[5 rows x 33 columns]
0.5933456561922366
acc is : 0.5933456561922366
2023-08-01 08:00:16,414:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.501535  0.498465       1  ...  0.921625   1.0    0.0  0.984023
537     0  0.515882  0.484118       0  ...  0.921496   1.0    0.0  0.983885
538     0  0.509501  0.490499       0  ...  0.920648   1.0    0.0  0.982979
539     1  0.493956  0.506044       0  ...  0.920165   1.0    0.0  0.982464
540     1  0.498582  0.501418       1  ...  0.921316   1.0    0.0  0.983693

[5 rows x 10 columns]
2023-08-01 08:00:16,425:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.501208  0.498792       1  ...  0.921625   1.0    0.0  0.981130
46     0  0.515813  0.484187       0  ...  0.921496   1.0    0.0  0.982426
47     0  0.509404  0.490596       0  ...  0.920648   1.0    0.0  0.982979
48     1  0.494032  0.505968       0  ...  0.920165   1.0    0.0  0.982464
49     1  0.498582  0.501418       1  ...  0.921316   1.0    0.0  0.983693

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.818', 'enterprice': '29478', 'countrevence': '0', 'unrealprofit': '-6184.20545961346', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29218.35580403', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230801   075000    075959  1690847999  29229.5  29220.8 -0.000301
2023-08-01 08:00:02,081:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11360 

self.closeSec=1690848599, self.tradeDate='20230801', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29220.8', self.close='29202.4'
2023-08-01 08:10:01,159:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690848599, self.tradeDate='20230801', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29220.8', self.close='29202.4'
127.0.0.1 - - [01/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-08-01 08:10:01,166:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230801   072000    072959  1690846199  29193.8  29184.3 -0.000325
621  20230801   073000    073959  1690846799  29184.4  29201.5  0.000589
622  20230801   074000    074959  1690847399  29201.5  29229.6  0.000962
623  20230801   075000    075959  1690847999  29229.5  29220.8 -0.000301
624  20230801   080000    080959  1690848599  29220.8  29202.4 -0.000630
2023-08-01 08:10:01,173:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11361 

self.closeSec=1690849199, self.tradeDate='20230801', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29202.4', self.close='29227.9'
127.0.0.1 - - [01/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-08-01 08:20:06,799:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690849199, self.tradeDate='20230801', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29202.4', self.close='29227.9'
2023-08-01 08:20:07,360:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230801   073000    073959  1690846799  29184.4  29201.5  0.000589
622  20230801   074000    074959  1690847399  29201.5  29229.6  0.000962
623  20230801   075000    075959  1690847999  29229.5  29220.8 -0.000301
624  20230801   080000    080959  1690848599  29220.8  29202.4 -0.000630
625  20230801   081000    081959  1690849199  29202.4  29227.9  0.000873
2023-08-01 08:20:07,360:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230801   075000    075959  1690847999  29229.5  29220.8
2023-08-01 08:00:02,089:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11363 

self.closeSec=1690848599, self.tradeDate='20230801', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29220.8', self.close='29202.4'
127.0.0.1 - - [01/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-08-01 08:10:01,162:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690848599, self.tradeDate='20230801', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29220.8', self.close='29202.4'
2023-08-01 08:10:01,170:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230801   072000    072959  1690846199  29193.8  29184.3
17469  20230801   073000    073959  1690846799  29184.4  29201.5
17470  20230801   074000    074959  1690847399  29201.5  29229.6
17471  20230801   075000    075959  1690847999  29229.5  29220.8
17472  20230801   080000    080959  1690848599  29220.8  29202.4
2023-08-01 08:10:01,171:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11364 

self.closeSec=1690849199, self.tradeDate='20230801', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29202.4', self.close='29227.9'
127.0.0.1 - - [01/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-08-01 08:20:08,263:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690849199, self.tradeDate='20230801', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29202.4', self.close='29227.9'
2023-08-01 08:20:08,375:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230801   073000    073959  1690846799  29184.4  29201.5
17470  20230801   074000    074959  1690847399  29201.5  29229.6
17471  20230801   075000    075959  1690847999  29229.5  29220.8
17472  20230801   080000    080959  1690848599  29220.8  29202.4
17473  20230801   081000    081959  1690849199  29202.4  29227.9
2023-08-01 08:20:08,376:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230801   075000    075959  1690847999  29229.5  29220.8
2023-08-01 08:00:02,095:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [01/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11363 

self.closeSec=1690848599, self.tradeDate='20230801', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29220.8', self.close='29202.4'
2023-08-01 08:10:01,172:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690848599, self.tradeDate='20230801', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29220.8', self.close='29202.4'
2023-08-01 08:10:01,179:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230801   072000    072959  1690846199  29193.8  29184.3
12141  20230801   073000    073959  1690846799  29184.4  29201.5
12142  20230801   074000    074959  1690847399  29201.5  29229.6
12143  20230801   075000    075959  1690847999  29229.5  29220.8
12144  20230801   080000    080959  1690848599  29220.8  29202.4
2023-08-01 08:10:01,179:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11364 

self.closeSec=1690849199, self.tradeDate='20230801', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29202.4', self.close='29227.9'
127.0.0.1 - - [01/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-08-01 08:20:08,100:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690849199, self.tradeDate='20230801', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29202.4', self.close='29227.9'
2023-08-01 08:20:08,270:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230801   073000    073959  1690846799  29184.4  29201.5
12142  20230801   074000    074959  1690847399  29201.5  29229.6
12143  20230801   075000    075959  1690847999  29229.5  29220.8
12144  20230801   080000    080959  1690848599  29220.8  29202.4
12145  20230801   081000    081959  1690849199  29202.4  29227.9
2023-08-01 08:20:08,271:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=22720
self.closeSec=1690849199, self.tradeDate='20230801', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29214.9, self.close=29227.9, self.high=29228.0, self.low=29211.9, self.vol=321.213, self.amt=9385432.8605 
127.0.0.1 - - [01/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-01 08:20:06,110:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230801   075500    075959  ...         0.0        0.0       0
5856  20230801   080000    080459  ...         0.0        0.0       0
5857  20230801   080500    080959  ...         0.0        0.0       0
5858  20230801   081000    081459  ...         0.0        0.0       0
5859  20230801   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-01 08:20:06,139:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690849199, self.tradeDate='20230801', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29214.9, self.close=29227.9, self.high=29228.0, self.low=29211.9, self.vol=321.213, self.amt=9385432.8605, ukdf['pct'].iloc[-1]=0.000459 , ukdf['amount'].iloc[-1]=9385432.8605, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '88536.7158', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29227.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=22721
self.closeSec=1690849499, self.tradeDate='20230801', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29227.9, self.close=29224.9, self.high=29241.3, self.low=29223.0, self.vol=524.843, self.amt=15342231.7904 
127.0.0.1 - - [01/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-08-01 08:25:00,792:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230801   080000    080459  ...         0.0        0.0       0
5857  20230801   080500    080959  ...         0.0        0.0       0
5858  20230801   081000    081459  ...         0.0        0.0       0
5859  20230801   081500    081959  ...         0.0        0.0       0
5860  20230801   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-01 08:25:00,793:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690849499, self.tradeDate='20230801', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29227.9, self.close=29224.9, self.high=29241.3, self.low=29223.0, self.vol=524.843, self.amt=15342231.7904, ukdf['pct'].iloc[-1]=-0.000103 , ukdf['amount'].iloc[-1]=15342231.7904, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '88449.8428004386', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29225.4609946', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230731   200000    235959  1690819199  ...    719  0.033872 -1.156911    -1.0
720  20230801   000000    035959  1690833599  ...    720  0.048282 -1.075937    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.024', 'enterprice': '29248', 'countrevence': '0', 'unrealprofit': '5905.18702084632', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29138.69326557', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1578513.8580480001, self.flagDict['side']='sell', self.tradeCount=16, self.count=473
self.closeSec=1690847999, self.tradeDate='20230801', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29146.4, self.close=29220.8, self.high=29285.3, self.low=29102.3, self.vol=32949.344, self.amt=962100506.6241 
127.0.0.1 - - [01/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-08-01 08:00:01,668:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1690847999, self.tradeDate='20230801', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=29146.4, self.close=29220.8, self.high=29285.3, self.low=29102.3, self.vol=32949.344, self.amt=962100506.6241 
2023-08-01 08:00:01,680:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230731   120000    155959  ...  19913.294  5.852377e+08 -0.001632
718  20230731   160000    195959  ...  19231.234  5.647518e+08  0.001093
719  20230731   200000    235959  ...  58214.878  1.707882e+09 -0.005599
720  20230801   000000    035959  ...  50437.485  1.472438e+09 -0.002942
721  20230801   040000    075959  ...  32949.344  9.621005e+08  0.002590

[5 rows x 11 columns]
2023-08-01 08:00:02,396:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230731   120000    155959  1690790399  ...    717  0.097876 -0.926380    -1.0
718  20230731   160000    195959  1690804799  ...    718  0.078130 -0.989512    -1.0
719  20230731   200000    235959  1690819199  ...    719  0.033872 -1.156911    -1.0
720  20230801   000000    035959  1690833599  ...    720  0.048282 -1.075937    -1.0
721  20230801   040000    075959  1690847999  ...    721  0.062756 -0.996077    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.024', 'enterprice': '29248', 'countrevence': '0', 'unrealprofit': '1469.4528', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29220.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


