# 20230621 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=10912
self.closeSec=1687306799, self.tradeDate='20230621', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28284.4, self.close=28249.6, self.high=28367.5, self.low=28236.4, self.vol=4575.651, self.amt=129505100.9184 
127.0.0.1 - - [21/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-21 08:20:07,428:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230621   075500    075959  ...         0.0        0.0       0
5856  20230621   080000    080459  ...         0.0        0.0       0
5857  20230621   080500    080959  ...         0.0        0.0       0
5858  20230621   081000    081459  ...         0.0        0.0       0
5859  20230621   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-21 08:20:07,448:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687306799, self.tradeDate='20230621', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28284.4, self.close=28249.6, self.high=28367.5, self.low=28236.4, self.vol=4575.651, self.amt=129505100.9184, ukdf['pct'].iloc[-1]=-0.00123 , ukdf['amount'].iloc[-1]=129505100.9184, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-19371.066', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28255.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [21/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=10913
self.closeSec=1687307099, self.tradeDate='20230621', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28249.6, self.close=28363.1, self.high=28500.0, self.low=28245.7, self.vol=12490.247, self.amt=354745715.34371 
2023-06-21 08:25:00,836:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230621   080000    080459  ...         0.0        0.0       0
5857  20230621   080500    080959  ...         0.0        0.0       0
5858  20230621   081000    081459  ...         0.0        0.0       0
5859  20230621   081500    081959  ...         0.0        0.0       0
5860  20230621   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-21 08:25:00,837:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687307099, self.tradeDate='20230621', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28249.6, self.close=28363.1, self.high=28500.0, self.low=28245.7, self.vol=12490.247, self.amt=354745715.34371, ukdf['pct'].iloc[-1]=0.004018 , ukdf['amount'].iloc[-1]=354745715.34371, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-21043.50032362512', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28375.99437912', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1687306799, self.tradeDate='20230621', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28284.4, self.close=28249.6, self.high=28367.5, self.low=28236.4 
127.0.0.1 - - [21/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-21 08:20:04,829:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687306799, self.tradeDate='20230621', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28284.4, self.close=28249.6, self.high=28367.5, self.low=28236.4   
2023-06-21 08:20:06,348:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230621   075500    075959  1687305599  ...  28276.0 -0.002380   1535    5
1536  20230621   080000    080459  1687305899  ...  28252.1 -0.001128   1536    0
1537  20230621   080500    080959  1687306199  ...  28251.8 -0.000042   1537    1
1538  20230621   081000    081459  1687306499  ...  28250.6  0.000948   1538    2
1539  20230621   081500    081959  1687306799  ...  28236.4 -0.001230   1539    3

[5 rows x 11 columns]
2023-06-21 08:20:06,358:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [21/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=197, self.factor=0.27532284949747426, self.count=10915 

self.closeSec=1687307099, self.tradeDate='20230621', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28249.6, self.close=28363.1, self.high=28500.0, self.low=28245.7 
2023-06-21 08:25:00,812:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687307099, self.tradeDate='20230621', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28249.6, self.close=28363.1, self.high=28500.0, self.low=28245.7   
2023-06-21 08:25:00,851:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230621   080000    080459  1687305899  ...  28252.1 -0.001128   1536    0
1537  20230621   080500    080959  1687306199  ...  28251.8 -0.000042   1537    1
1538  20230621   081000    081459  1687306499  ...  28250.6  0.000948   1538    2
1539  20230621   081500    081959  1687306799  ...  28236.4 -0.001230   1539    3
1540  20230621   082000    082459  1687307099  ...  28245.7  0.004018   1540    4

[5 rows x 11 columns]
2023-06-21 08:25:00,851:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-21 08:00:18,702:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230621    052959  28147.2  ...  56.250000  0.699922  0.248818
5771  20230621    055959  28187.2  ...  56.250000  0.686016  0.239384
5772  20230621    062959  28121.3  ...  56.250000  0.691156  0.228415
5773  20230621    065959  28175.3  ...  56.250000  0.693625  0.217133
5774  20230621    072959  28201.3  ...  56.666667  0.702812  0.203201

[5 rows x 33 columns]
0.5526802218114603
acc is : 0.5526802218114603
2023-06-21 08:00:18,788:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.512069  0.487931       0  ...  1.050322   1.0    0.0  1.062139
537     1  0.499806  0.500194       1  ...  1.052343   1.0    0.0  1.064183
538     0  0.518629  0.481371       1  ...  1.053318   1.0    0.0  1.065168
539     0  0.516678  0.483322       1  ...  1.057012   1.0    0.0  1.068904
540     0  0.517603  0.482397       0  ...  1.056649   1.0    0.0  1.068538

[5 rows x 10 columns]
2023-06-21 08:00:18,816:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.512135  0.487865       0  ...  1.050322   1.0    0.0  1.062577
46     1  0.499844  0.500156       1  ...  1.052343   1.0    0.0  1.063901
47     0  0.518716  0.481284       1  ...  1.053318   1.0    0.0  1.065209
48     0  0.516678  0.483322       1  ...  1.057012   1.0    0.0  1.068904
49     0  0.517603  0.482397       0  ...  1.056649   1.0    0.0  1.068538

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.893', 'enterprice': '27229', 'countrevence': '0', 'unrealprofit': '28732.4812', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28297.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230621   075000    075959  1687305599  28316.6  28290.6 -0.000918
2023-06-21 08:00:02,039:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [21/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5456 

self.closeSec=1687306199, self.tradeDate='20230621', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28290.7', self.close='28257.7'
2023-06-21 08:10:01,091:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687306199, self.tradeDate='20230621', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='28290.7', self.close='28257.7'
2023-06-21 08:10:01,113:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230621   072000    072959  1687303799  28150.3  28300.3  0.005325
621  20230621   073000    073959  1687304399  28326.8  28305.8  0.000194
622  20230621   074000    074959  1687304999  28305.8  28316.6  0.000382
623  20230621   075000    075959  1687305599  28316.6  28290.6 -0.000918
624  20230621   080000    080959  1687306199  28290.7  28257.7 -0.001163
2023-06-21 08:10:01,113:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5457 

self.closeSec=1687306799, self.tradeDate='20230621', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28257.6', self.close='28249.6'
127.0.0.1 - - [21/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-21 08:20:07,129:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687306799, self.tradeDate='20230621', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='28257.6', self.close='28249.6'
2023-06-21 08:20:07,818:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230621   073000    073959  1687304399  28326.8  28305.8  0.000194
622  20230621   074000    074959  1687304999  28305.8  28316.6  0.000382
623  20230621   075000    075959  1687305599  28316.6  28290.6 -0.000918
624  20230621   080000    080959  1687306199  28290.7  28257.7 -0.001163
625  20230621   081000    081959  1687306799  28257.6  28249.6 -0.000287
2023-06-21 08:20:07,819:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230621   075000    075959  1687305599  28316.6  28290.6
2023-06-21 08:00:02,046:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [21/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5459 

self.closeSec=1687306199, self.tradeDate='20230621', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28290.7', self.close='28257.7'
2023-06-21 08:10:01,106:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687306199, self.tradeDate='20230621', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='28290.7', self.close='28257.7'
2023-06-21 08:10:01,113:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230621   072000    072959  1687303799  28150.3  28300.3
17469  20230621   073000    073959  1687304399  28326.8  28305.8
17470  20230621   074000    074959  1687304999  28305.8  28316.6
17471  20230621   075000    075959  1687305599  28316.6  28290.6
17472  20230621   080000    080959  1687306199  28290.7  28257.7
2023-06-21 08:10:01,113:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5460 

self.closeSec=1687306799, self.tradeDate='20230621', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28257.6', self.close='28249.6'
127.0.0.1 - - [21/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-21 08:20:09,081:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687306799, self.tradeDate='20230621', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='28257.6', self.close='28249.6'
2023-06-21 08:20:09,223:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230621   073000    073959  1687304399  28326.8  28305.8
17470  20230621   074000    074959  1687304999  28305.8  28316.6
17471  20230621   075000    075959  1687305599  28316.6  28290.6
17472  20230621   080000    080959  1687306199  28290.7  28257.7
17473  20230621   081000    081959  1687306799  28257.6  28249.6
2023-06-21 08:20:09,224:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230621   075000    075959  1687305599  28316.6  28290.6
2023-06-21 08:00:02,041:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5459 

self.closeSec=1687306199, self.tradeDate='20230621', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28290.7', self.close='28257.7'
2023-06-21 08:10:01,075:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687306199, self.tradeDate='20230621', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='28290.7', self.close='28257.7'
2023-06-21 08:10:01,081:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230621   072000    072959  1687303799  28150.3  28300.3
12141  20230621   073000    073959  1687304399  28326.8  28305.8
12142  20230621   074000    074959  1687304999  28305.8  28316.6
12143  20230621   075000    075959  1687305599  28316.6  28290.6
12144  20230621   080000    080959  1687306199  28290.7  28257.7
2023-06-21 08:10:01,081:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [21/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5460 

self.closeSec=1687306799, self.tradeDate='20230621', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28257.6', self.close='28249.6'
127.0.0.1 - - [21/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-21 08:20:08,632:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687306799, self.tradeDate='20230621', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='28257.6', self.close='28249.6'
2023-06-21 08:20:08,950:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230621   073000    073959  1687304399  28326.8  28305.8
12142  20230621   074000    074959  1687304999  28305.8  28316.6
12143  20230621   075000    075959  1687305599  28316.6  28290.6
12144  20230621   080000    080959  1687306199  28290.7  28257.7
12145  20230621   081000    081959  1687306799  28257.6  28249.6
2023-06-21 08:20:08,958:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=10912
self.closeSec=1687306799, self.tradeDate='20230621', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28284.4, self.close=28249.6, self.high=28367.5, self.low=28236.4, self.vol=4575.651, self.amt=129505100.9184 
127.0.0.1 - - [21/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-21 08:20:07,458:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230621   075500    075959  ...         0.0        0.0       0
5856  20230621   080000    080459  ...         0.0        0.0       0
5857  20230621   080500    080959  ...         0.0        0.0       0
5858  20230621   081000    081459  ...         0.0        0.0       0
5859  20230621   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-21 08:20:07,478:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687306799, self.tradeDate='20230621', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28284.4, self.close=28249.6, self.high=28367.5, self.low=28236.4, self.vol=4575.651, self.amt=129505100.9184, ukdf['pct'].iloc[-1]=-0.00123 , ukdf['amount'].iloc[-1]=129505100.9184, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '52439.3779', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28255.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=10913
self.closeSec=1687307099, self.tradeDate='20230621', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28249.6, self.close=28363.1, self.high=28500.0, self.low=28245.7, self.vol=12490.247, self.amt=354745715.34371 
127.0.0.1 - - [21/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-06-21 08:25:00,831:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230621   080000    080459  ...         0.0        0.0       0
5857  20230621   080500    080959  ...         0.0        0.0       0
5858  20230621   081000    081459  ...         0.0        0.0       0
5859  20230621   081500    081959  ...         0.0        0.0       0
5860  20230621   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-21 08:25:00,832:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687307099, self.tradeDate='20230621', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28249.6, self.close=28363.1, self.high=28500.0, self.low=28245.7, self.vol=12490.247, self.amt=354745715.34371, ukdf['pct'].iloc[-1]=0.004018 , ukdf['amount'].iloc[-1]=354745715.34371, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '56899.80323489592', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28375.99437912', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

127.0.0.1 - - [21/Jun/2023 04:00:11] "POST / HTTP/1.1" 200 -
2023-06-21 04:00:11,399:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42430F1687291205725I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1687291206117495, 'quantity': '57.126', 'price': '27978', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1687291204829, 'updatetime': 1687291206117, 'tradetype': 'usdt', 'selfid': 42430, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1687291206117, 'clientorderid': '42430F1687291205725I0L65', 'price': '27978', 'quantity': '57.126', 'commission': '1598.271228', 'commissionasset': 'USDT', 'tradetime': 1687291206117, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1687291206117}], 'gatetype': 'simulator', 'handletime': 0}
2023-06-21 04:00:11,830:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42431F1687291211369I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1687291211776853, 'quantity': '53.344', 'price': '27977.7', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1687291210876, 'updatetime': 1687291211776, 'tradetype': 'usdt', 'selfid': 42431, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1687291211776, 'clientorderid': '42431F1687291211369I0L65', 'price': '27977.7', 'quantity': '53.344', 'commission': '1492.4424288', 'commissionasset': 'USDT', 'tradetime': 1687291211776, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1687291211776}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [21/Jun/2023 04:00:11] "POST / HTTP/1.1" 200 -
2023-06-21 04:00:12,014:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42431F1687291211369I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1687291211776853, 'quantity': '53.344', 'price': '27977.7', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1687291210876, 'updatetime': 1687291211776, 'tradetype': 'usdt', 'selfid': 42431, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1687291211776, 'clientorderid': '42431F1687291211369I0L65', 'price': '27977.7', 'quantity': '53.344', 'commission': '1492.4424288', 'commissionasset': 'USDT', 'tradetime': 1687291211776, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1687291211776}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [21/Jun/2023 04:00:12] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1490949.9863712, self.flagDict['side']='buy', self.tradeCount=7, self.count=227
self.closeSec=1687305599, self.tradeDate='20230621', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27973.7, self.close=28290.6, self.high=28397.8, self.low=27855.6, self.vol=124303.4, self.amt=3498796269.843 
2023-06-21 08:00:01,588:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1687305599, self.tradeDate='20230621', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27973.7, self.close=28290.6, self.high=28397.8, self.low=27855.6, self.vol=124303.4, self.amt=3498796269.843 
127.0.0.1 - - [21/Jun/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-06-21 08:00:01,617:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230620   120000    155959  ...   58296.884  1.565392e+09 -0.002243
718  20230620   160000    195959  ...   41628.652  1.114877e+09  0.002789
719  20230620   200000    235959  ...  114387.910  3.072620e+09  0.005912
720  20230621   000000    035959  ...  340070.821  9.391812e+09  0.033958
721  20230621   040000    075959  ...  124303.400  3.498796e+09  0.011357

[5 rows x 11 columns]
2023-06-21 08:00:03,225:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230620   120000    155959  1687247999  ...    717  0.454998  0.083055     NaN
718  20230620   160000    195959  1687262399  ...    718  0.349276 -0.573679     NaN
719  20230620   200000    235959  1687276799  ...    719  0.227191 -1.342353    -1.0
720  20230621   000000    035959  1687291199  ...    720  0.576821  0.801283     1.0
721  20230621   040000    075959  1687305599  ...    721  1.222639  4.235218     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.344', 'enterprice': '27977.7', 'countrevence': '0', 'unrealprofit': '16696.672', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28290.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


