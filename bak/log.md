# 20230707 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=15520
self.closeSec=1688689199, self.tradeDate='20230707', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29979.9, self.close=29968.2, self.high=29993.6, self.low=29936.1, self.vol=2890.654, self.amt=86612782.8052 
127.0.0.1 - - [07/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-07 08:20:07,425:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230707   075500    075959  ...         0.0        0.0       0
5856  20230707   080000    080459  ...         0.0        0.0       0
5857  20230707   080500    080959  ...         0.0        0.0       0
5858  20230707   081000    081459  ...         0.0        0.0       0
5859  20230707   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-07 08:20:07,465:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688689199, self.tradeDate='20230707', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29979.9, self.close=29968.2, self.high=29993.6, self.low=29936.1, self.vol=2890.654, self.amt=86612782.8052, ukdf['pct'].iloc[-1]=-0.000227 , ukdf['amount'].iloc[-1]=86612782.8052, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-43066.57576280994', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29957.43021419', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=15521
self.closeSec=1688689499, self.tradeDate='20230707', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29969.9, self.close=29962.0, self.high=29982.5, self.low=29918.2, self.vol=1547.007, self.amt=46342477.4347 
127.0.0.1 - - [07/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-07-07 08:25:00,800:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230707   080000    080459  ...         0.0        0.0       0
5857  20230707   080500    080959  ...         0.0        0.0       0
5858  20230707   081000    081459  ...         0.0        0.0       0
5859  20230707   081500    081959  ...         0.0        0.0       0
5860  20230707   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-07 08:25:00,800:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688689499, self.tradeDate='20230707', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29969.9, self.close=29962.0, self.high=29982.5, self.low=29918.2, self.vol=1547.007, self.amt=46342477.4347, ukdf['pct'].iloc[-1]=-0.000207 , ukdf['amount'].iloc[-1]=46342477.4347, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-43130.2146', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29962', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1688689199, self.tradeDate='20230707', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29979.9, self.close=29968.2, self.high=29993.6, self.low=29936.1 
127.0.0.1 - - [07/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-07 08:20:04,993:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688689199, self.tradeDate='20230707', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29979.9, self.close=29968.2, self.high=29993.6, self.low=29936.1   
2023-07-07 08:20:06,554:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230707   075500    075959  1688687999  ...  29862.4 -0.002360   1535    5
1536  20230707   080000    080459  1688688299  ...  29680.0 -0.002634   1536    0
1537  20230707   080500    080959  1688688599  ...  29750.0  0.000936   1537    1
1538  20230707   081000    081459  1688688899  ...  29825.9  0.004841   1538    2
1539  20230707   081500    081959  1688689199  ...  29936.1 -0.000227   1539    3

[5 rows x 11 columns]
2023-07-07 08:20:06,573:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6632992831486878, self.count=15523 

self.closeSec=1688689499, self.tradeDate='20230707', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29969.9, self.close=29962.0, self.high=29982.5, self.low=29918.2 
127.0.0.1 - - [07/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-07-07 08:25:00,738:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688689499, self.tradeDate='20230707', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29969.9, self.close=29962.0, self.high=29982.5, self.low=29918.2   
2023-07-07 08:25:00,780:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230707   080000    080459  1688688299  ...  29680.0 -0.002634   1536    0
1537  20230707   080500    080959  1688688599  ...  29750.0  0.000936   1537    1
1538  20230707   081000    081459  1688688899  ...  29825.9  0.004841   1538    2
1539  20230707   081500    081959  1688689199  ...  29936.1 -0.000227   1539    3
1540  20230707   082000    082459  1688689499  ...  29918.2 -0.000207   1540    4

[5 rows x 11 columns]
2023-07-07 08:25:00,781:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-07 08:00:18,667:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230707    052959  30303.8  ...  47.916667  0.449614  0.661915
5771  20230707    055959  30239.4  ...  47.916667  0.445406  0.671054
5772  20230707    062959  30207.3  ...  47.916667  0.447576  0.679068
5773  20230707    065959  30220.5  ...  47.916667  0.437908  0.689404
5774  20230707    072959  30147.6  ...  47.916667  0.423510  0.701848

[5 rows x 33 columns]
0.5489833641404805
acc is : 0.5489833641404805
2023-07-07 08:00:18,786:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.495596  0.504404       0  ...  0.950902  -1.0    0.0  0.988656
537     0  0.507855  0.492145       1  ...  0.950487  -1.0    0.0  0.989088
538     0  0.517576  0.482424       0  ...  0.952783  -1.0    0.0  0.986699
539     1  0.495787  0.504213       0  ...  0.956341  -1.0    0.0  0.983014
540     1  0.472914  0.527086       0  ...  0.961229  -1.0    0.0  0.977990

[5 rows x 10 columns]
2023-07-07 08:00:18,806:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.495222  0.504778       0  ...  0.950902  -1.0    0.0  0.988003
46     0  0.508071  0.491929       1  ...  0.948601  -1.0    0.0  0.989895
47     0  0.517043  0.482957       0  ...  0.952783  -1.0    0.0  0.985718
48     1  0.495749  0.504251       0  ...  0.954444  -1.0    0.0  0.983014
49     1  0.472914  0.527086       0  ...  0.961229  -1.0    0.0  0.977990

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.821', 'enterprice': '30691.5', 'countrevence': '0', 'unrealprofit': '19568.9515', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29870', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230707   075000    075959  1688687999  29960.2  29881.4 -0.002627
2023-07-07 08:00:02,134:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7760 

self.closeSec=1688688599, self.tradeDate='20230707', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29874.3', self.close='29830.6'
2023-07-07 08:10:01,119:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688688599, self.tradeDate='20230707', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29874.3', self.close='29830.6'
127.0.0.1 - - [07/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-07-07 08:10:01,135:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230707   072000    072959  1688686199  29971.9  30034.9  0.002172
621  20230707   073000    073959  1688686799  30034.9  29937.4 -0.003246
622  20230707   074000    074959  1688687399  29940.9  29960.1  0.000758
623  20230707   075000    075959  1688687999  29960.2  29881.4 -0.002627
624  20230707   080000    080959  1688688599  29874.3  29830.6 -0.001700
2023-07-07 08:10:01,135:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7761 

self.closeSec=1688689199, self.tradeDate='20230707', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29830.6', self.close='29968.3'
127.0.0.1 - - [07/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-07 08:20:07,405:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688689199, self.tradeDate='20230707', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29830.6', self.close='29968.3'
2023-07-07 08:20:08,244:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230707   073000    073959  1688686799  30034.9  29937.4 -0.003246
622  20230707   074000    074959  1688687399  29940.9  29960.1  0.000758
623  20230707   075000    075959  1688687999  29960.2  29881.4 -0.002627
624  20230707   080000    080959  1688688599  29874.3  29830.6 -0.001700
625  20230707   081000    081959  1688689199  29830.6  29968.3  0.004616
2023-07-07 08:20:08,244:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230707   075000    075959  1688687999  29960.2  29881.4
2023-07-07 08:00:02,144:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [07/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7763 

self.closeSec=1688688599, self.tradeDate='20230707', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29874.3', self.close='29830.6'
2023-07-07 08:10:01,113:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688688599, self.tradeDate='20230707', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29874.3', self.close='29830.6'
2023-07-07 08:10:01,130:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230707   072000    072959  1688686199  29971.9  30034.9
17469  20230707   073000    073959  1688686799  30034.9  29937.4
17470  20230707   074000    074959  1688687399  29940.9  29960.1
17471  20230707   075000    075959  1688687999  29960.2  29881.4
17472  20230707   080000    080959  1688688599  29874.3  29830.6
2023-07-07 08:10:01,130:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7764 

self.closeSec=1688689199, self.tradeDate='20230707', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29830.6', self.close='29968.3'
127.0.0.1 - - [07/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-07 08:20:09,168:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688689199, self.tradeDate='20230707', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29830.6', self.close='29968.3'
2023-07-07 08:20:09,348:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230707   073000    073959  1688686799  30034.9  29937.4
17470  20230707   074000    074959  1688687399  29940.9  29960.1
17471  20230707   075000    075959  1688687999  29960.2  29881.4
17472  20230707   080000    080959  1688688599  29874.3  29830.6
17473  20230707   081000    081959  1688689199  29830.6  29968.3
2023-07-07 08:20:09,348:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230707   075000    075959  1688687999  29960.2  29881.4
2023-07-07 08:00:02,140:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7763 

self.closeSec=1688688599, self.tradeDate='20230707', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29874.3', self.close='29830.6'
127.0.0.1 - - [07/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-07-07 08:10:01,147:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688688599, self.tradeDate='20230707', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29874.3', self.close='29830.6'
2023-07-07 08:10:01,153:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230707   072000    072959  1688686199  29971.9  30034.9
12141  20230707   073000    073959  1688686799  30034.9  29937.4
12142  20230707   074000    074959  1688687399  29940.9  29960.1
12143  20230707   075000    075959  1688687999  29960.2  29881.4
12144  20230707   080000    080959  1688688599  29874.3  29830.6
2023-07-07 08:10:01,153:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7764 

self.closeSec=1688689199, self.tradeDate='20230707', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29830.6', self.close='29968.3'
127.0.0.1 - - [07/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-07 08:20:08,885:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688689199, self.tradeDate='20230707', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29830.6', self.close='29968.3'
2023-07-07 08:20:09,169:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230707   073000    073959  1688686799  30034.9  29937.4
12142  20230707   074000    074959  1688687399  29940.9  29960.1
12143  20230707   075000    075959  1688687999  29960.2  29881.4
12144  20230707   080000    080959  1688688599  29874.3  29830.6
12145  20230707   081000    081959  1688689199  29830.6  29968.3
2023-07-07 08:20:09,174:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=15520
self.closeSec=1688689199, self.tradeDate='20230707', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29979.9, self.close=29968.2, self.high=29993.6, self.low=29936.1, self.vol=2890.654, self.amt=86612782.8052 
127.0.0.1 - - [07/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-07 08:20:07,424:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230707   075500    075959  ...         0.0        0.0       0
5856  20230707   080000    080459  ...         0.0        0.0       0
5857  20230707   080500    080959  ...         0.0        0.0       0
5858  20230707   081000    081459  ...         0.0        0.0       0
5859  20230707   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-07 08:20:07,463:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688689199, self.tradeDate='20230707', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29979.9, self.close=29968.2, self.high=29993.6, self.low=29936.1, self.vol=2890.654, self.amt=86612782.8052, ukdf['pct'].iloc[-1]=-0.000227 , ukdf['amount'].iloc[-1]=86612782.8052, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '115635.91158523079', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29957.43021419', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=15521
self.closeSec=1688689499, self.tradeDate='20230707', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29969.9, self.close=29962.0, self.high=29982.5, self.low=29918.2, self.vol=1547.007, self.amt=46342477.4347 
127.0.0.1 - - [07/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-07-07 08:25:00,800:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230707   080000    080459  ...         0.0        0.0       0
5857  20230707   080500    080959  ...         0.0        0.0       0
5858  20230707   081000    081459  ...         0.0        0.0       0
5859  20230707   081500    081959  ...         0.0        0.0       0
5860  20230707   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-07 08:25:00,800:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688689499, self.tradeDate='20230707', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29969.9, self.close=29962.0, self.high=29982.5, self.low=29918.2, self.vol=1547.007, self.amt=46342477.4347, ukdf['pct'].iloc[-1]=-0.000207 , ukdf['amount'].iloc[-1]=46342477.4347, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '115805.638', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29962', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230706   200000    235959  1688659199  ...    719  0.249758 -0.418730     NaN
720  20230707   000000    035959  1688673599  ...    720  0.287269 -0.304465     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.05', 'enterprice': '30750.9', 'countrevence': '0', 'unrealprofit': '-24508.759112371', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30288.90642578', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [07/Jul/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1629703.909755, self.flagDict['side']='buy', self.tradeCount=9, self.count=323
self.closeSec=1688687999, self.tradeDate='20230707', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=30294.6, self.close=29881.4, self.high=30336.3, self.low=29818.0, self.vol=69574.823, self.amt=2092298668.4821 
2023-07-07 08:00:01,688:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1688687999, self.tradeDate='20230707', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=30294.6, self.close=29881.4, self.high=30336.3, self.low=29818.0, self.vol=69574.823, self.amt=2092298668.4821 
2023-07-07 08:00:01,718:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230706   120000    155959  ...   59326.951  1.819310e+09  0.010322
718  20230706   160000    195959  ...  227986.969  7.104595e+09  0.001257
719  20230706   200000    235959  ...  270998.539  8.221109e+09 -0.014294
720  20230707   000000    035959  ...   65824.541  1.993928e+09 -0.003146
721  20230707   040000    075959  ...   69574.823  2.092299e+09 -0.013643

[5 rows x 11 columns]
2023-07-07 08:00:02,971:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230706   120000    155959  1688630399  ...    717  0.604498  0.401745     NaN
718  20230706   160000    195959  1688644799  ...    718  0.571736  0.346347     NaN
719  20230706   200000    235959  1688659199  ...    719  0.249758 -0.418730     NaN
720  20230707   000000    035959  1688673599  ...    720  0.287269 -0.304465     NaN
721  20230707   040000    075959  1688687999  ...    721  0.320735 -0.195696     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.05', 'enterprice': '30750.9', 'countrevence': '0', 'unrealprofit': '-46385.172186053', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29876.53294654', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


