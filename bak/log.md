# 20230607 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [07/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=6880
self.closeSec=1686097199, self.tradeDate='20230607', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27221.3, self.close=27163.8, self.high=27232.4, self.low=27152.5, self.vol=1877.906, self.amt=51053552.9415 
2023-06-07 08:20:03,168:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230607   075500    075959  ...         0.0        0.0       0
5856  20230607   080000    080459  ...         0.0        0.0       0
5857  20230607   080500    080959  ...         0.0        0.0       0
5858  20230607   081000    081459  ...         0.0        0.0       0
5859  20230607   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-07 08:20:03,179:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686097199, self.tradeDate='20230607', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27221.3, self.close=27163.8, self.high=27232.4, self.low=27152.5, self.vol=1877.906, self.amt=51053552.9415, ukdf['pct'].iloc[-1]=-0.002116 , ukdf['amount'].iloc[-1]=51053552.9415, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-4177.8', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27164.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=6881
self.closeSec=1686097499, self.tradeDate='20230607', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27159.1, self.close=27206.3, self.high=27216.0, self.low=27155.6, self.vol=1524.982, self.amt=41459839.5092 
127.0.0.1 - - [07/Jun/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-06-07 08:25:04,322:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230607   080000    080459  ...         0.0        0.0       0
5857  20230607   080500    080959  ...         0.0        0.0       0
5858  20230607   081000    081459  ...         0.0        0.0       0
5859  20230607   081500    081959  ...         0.0        0.0       0
5860  20230607   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-07 08:25:04,335:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686097499, self.tradeDate='20230607', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27159.1, self.close=27206.3, self.high=27216.0, self.low=27155.6, self.vol=1524.982, self.amt=41459839.5092, ukdf['pct'].iloc[-1]=0.001565 , ukdf['amount'].iloc[-1]=41459839.5092, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-4774.15247912856', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27207.72295556', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1686097199, self.tradeDate='20230607', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27221.3, self.close=27163.8, self.high=27232.4, self.low=27152.5 
127.0.0.1 - - [07/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-07 08:20:01,887:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686097199, self.tradeDate='20230607', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27221.3, self.close=27163.8, self.high=27232.4, self.low=27152.5   
2023-06-07 08:20:02,978:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230607   075500    075959  1686095999  ...  27188.2  0.001085   1535    5
1536  20230607   080000    080459  1686096299  ...  27162.3 -0.001363   1536    0
1537  20230607   080500    080959  1686096599  ...  27182.5  0.002075   1537    1
1538  20230607   081000    081459  1686096899  ...  27189.4 -0.000712   1538    2
1539  20230607   081500    081959  1686097199  ...  27152.5 -0.002116   1539    3

[5 rows x 11 columns]
2023-06-07 08:20:02,978:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=12, self.factor=0.46644033220082454, self.count=6883 

self.closeSec=1686097499, self.tradeDate='20230607', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27159.1, self.close=27206.3, self.high=27216.0, self.low=27155.6 
127.0.0.1 - - [07/Jun/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-06-07 08:25:03,184:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686097499, self.tradeDate='20230607', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27159.1, self.close=27206.3, self.high=27216.0, self.low=27155.6   
2023-06-07 08:25:03,902:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230607   080000    080459  1686096299  ...  27162.3 -0.001363   1536    0
1537  20230607   080500    080959  1686096599  ...  27182.5  0.002075   1537    1
1538  20230607   081000    081459  1686096899  ...  27189.4 -0.000712   1538    2
1539  20230607   081500    081959  1686097199  ...  27152.5 -0.002116   1539    3
1540  20230607   082000    082459  1686097499  ...  27155.6  0.001565   1540    4

[5 rows x 11 columns]
2023-06-07 08:25:03,903:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-07 08:00:41,403:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230607    052959  26939.0  ...  47.916667  0.604634  0.308132
5771  20230607    055959  26999.9  ...  48.333333  0.610966  0.294022
5772  20230607    062959  27054.0  ...  48.333333  0.609820  0.281069
5773  20230607    065959  27047.7  ...  48.750000  0.620486  0.265815
5774  20230607    072959  27138.8  ...  49.166667  0.636561  0.250553

[5 rows x 33 columns]
0.5194085027726433
acc is : 0.5194085027726433
2023-06-07 08:00:41,628:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.526020  0.473980       1  ...  1.107224   1.0    0.0  1.010715
537     0  0.508713  0.491287       0  ...  1.106970   1.0    0.0  1.010483
538     1  0.482469  0.517531       1  ...  1.110694   1.0    0.0  1.013883
539     0  0.512046  0.487954       1  ...  1.116600   1.0    0.0  1.019274
540     0  0.536116  0.463884       0  ...  1.114083   1.0    0.0  1.016976

[5 rows x 10 columns]
2023-06-07 08:00:41,672:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.526338  0.473662       1  ...  1.107224   1.0    0.0  1.011837
46     0  0.508696  0.491304       0  ...  1.106970   1.0    0.0  1.008938
47     1  0.482584  0.517416       1  ...  1.110694   1.0    0.0  1.013466
48     0  0.512600  0.487400       1  ...  1.116600   1.0    0.0  1.019274
49     0  0.536116  0.463884       0  ...  1.114083   1.0    0.0  1.016976

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.054', 'enterprice': '25722.1', 'countrevence': '0', 'unrealprofit': '42406.4264', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27233.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230607   075000    075959  1686095999  27176.7  27221.5  0.001648
2023-06-07 08:00:02,339:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3440 

self.closeSec=1686096599, self.tradeDate='20230607', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27221.5', self.close='27240.8'
2023-06-07 08:10:01,105:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686096599, self.tradeDate='20230607', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27221.5', self.close='27240.8'
127.0.0.1 - - [07/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-06-07 08:10:01,112:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230607   072000    072959  1686094199  27142.9  27285.3  0.005246
621  20230607   073000    073959  1686094799  27285.3  27155.1 -0.004772
622  20230607   074000    074959  1686095399  27155.2  27176.7  0.000795
623  20230607   075000    075959  1686095999  27176.7  27221.5  0.001648
624  20230607   080000    080959  1686096599  27221.5  27240.8  0.000709
2023-06-07 08:10:01,116:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3441 

self.closeSec=1686097199, self.tradeDate='20230607', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27240.8', self.close='27159.1'
127.0.0.1 - - [07/Jun/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-06-07 08:20:05,370:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686097199, self.tradeDate='20230607', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27240.8', self.close='27159.1'
2023-06-07 08:20:05,788:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230607   073000    073959  1686094799  27285.3  27155.1 -0.004772
622  20230607   074000    074959  1686095399  27155.2  27176.7  0.000795
623  20230607   075000    075959  1686095999  27176.7  27221.5  0.001648
624  20230607   080000    080959  1686096599  27221.5  27240.8  0.000709
625  20230607   081000    081959  1686097199  27240.8  27159.1 -0.002999
2023-06-07 08:20:05,788:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230607   075000    075959  1686095999  27176.7  27221.5
2023-06-07 08:00:02,296:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3443 

self.closeSec=1686096599, self.tradeDate='20230607', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27221.5', self.close='27240.8'
2023-06-07 08:10:01,141:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686096599, self.tradeDate='20230607', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27221.5', self.close='27240.8'
127.0.0.1 - - [07/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-06-07 08:10:01,163:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230607   072000    072959  1686094199  27142.9  27285.3
17469  20230607   073000    073959  1686094799  27285.3  27155.1
17470  20230607   074000    074959  1686095399  27155.2  27176.7
17471  20230607   075000    075959  1686095999  27176.7  27221.5
17472  20230607   080000    080959  1686096599  27221.5  27240.8
2023-06-07 08:10:01,163:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3444 

self.closeSec=1686097199, self.tradeDate='20230607', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27240.8', self.close='27159.1'
127.0.0.1 - - [07/Jun/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-06-07 08:20:06,468:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686097199, self.tradeDate='20230607', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27240.8', self.close='27159.1'
2023-06-07 08:20:06,573:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230607   073000    073959  1686094799  27285.3  27155.1
17470  20230607   074000    074959  1686095399  27155.2  27176.7
17471  20230607   075000    075959  1686095999  27176.7  27221.5
17472  20230607   080000    080959  1686096599  27221.5  27240.8
17473  20230607   081000    081959  1686097199  27240.8  27159.1
2023-06-07 08:20:06,574:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230607   075000    075959  1686095999  27176.7  27221.5
2023-06-07 08:00:02,338:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [07/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3443 

self.closeSec=1686096599, self.tradeDate='20230607', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27221.5', self.close='27240.8'
2023-06-07 08:10:01,126:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686096599, self.tradeDate='20230607', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27221.5', self.close='27240.8'
2023-06-07 08:10:01,179:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230607   072000    072959  1686094199  27142.9  27285.3
12141  20230607   073000    073959  1686094799  27285.3  27155.1
12142  20230607   074000    074959  1686095399  27155.2  27176.7
12143  20230607   075000    075959  1686095999  27176.7  27221.5
12144  20230607   080000    080959  1686096599  27221.5  27240.8
2023-06-07 08:10:01,179:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3444 

self.closeSec=1686097199, self.tradeDate='20230607', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27240.8', self.close='27159.1'
127.0.0.1 - - [07/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-07 08:20:06,241:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686097199, self.tradeDate='20230607', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27240.8', self.close='27159.1'
2023-06-07 08:20:06,428:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230607   073000    073959  1686094799  27285.3  27155.1
12142  20230607   074000    074959  1686095399  27155.2  27176.7
12143  20230607   075000    075959  1686095999  27176.7  27221.5
12144  20230607   080000    080959  1686096599  27221.5  27240.8
12145  20230607   081000    081959  1686097199  27240.8  27159.1
2023-06-07 08:20:06,428:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=6880
self.closeSec=1686097199, self.tradeDate='20230607', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27221.3, self.close=27163.8, self.high=27232.4, self.low=27152.5, self.vol=1877.906, self.amt=51053552.9415 
127.0.0.1 - - [07/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-07 08:20:03,222:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230607   075500    075959  ...         0.0        0.0       0
5856  20230607   080000    080459  ...         0.0        0.0       0
5857  20230607   080500    080959  ...         0.0        0.0       0
5858  20230607   081000    081459  ...         0.0        0.0       0
5859  20230607   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-07 08:20:03,228:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686097199, self.tradeDate='20230607', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27221.3, self.close=27163.8, self.high=27232.4, self.low=27152.5, self.vol=1877.906, self.amt=51053552.9415, ukdf['pct'].iloc[-1]=-0.002116 , ukdf['amount'].iloc[-1]=51053552.9415, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '11747.6983', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27160.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=6881
self.closeSec=1686097499, self.tradeDate='20230607', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27159.1, self.close=27206.3, self.high=27216.0, self.low=27155.6, self.vol=1524.982, self.amt=41459839.5092 
127.0.0.1 - - [07/Jun/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-06-07 08:25:04,248:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230607   080000    080459  ...         0.0        0.0       0
5857  20230607   080500    080959  ...         0.0        0.0       0
5858  20230607   081000    081459  ...         0.0        0.0       0
5859  20230607   081500    081959  ...         0.0        0.0       0
5860  20230607   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-07 08:25:04,256:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686097499, self.tradeDate='20230607', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27159.1, self.close=27206.3, self.high=27216.0, self.low=27155.6, self.vol=1524.982, self.amt=41459839.5092, ukdf['pct'].iloc[-1]=0.001565 , ukdf['amount'].iloc[-1]=41459839.5092, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '13509.03429245396', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27207.72295556', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230606   200000    235959  1686067199  ...    719  0.604946  0.090038     NaN
720  20230607   000000    035959  1686081599  ...    720  0.498911 -0.255792     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '-1329.5006', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27102.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [07/Jun/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1492324.2295523998, self.flagDict['side']='sell', self.tradeCount=4, self.count=143
self.closeSec=1686095999, self.tradeDate='20230607', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27073.3, self.close=27221.5, self.high=27358.1, self.low=26884.0, self.vol=113750.962, self.amt=3081162920.06402 
2023-06-07 08:00:01,841:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1686095999, self.tradeDate='20230607', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27073.3, self.close=27221.5, self.high=27358.1, self.low=26884.0, self.vol=113750.962, self.amt=3081162920.06402 
2023-06-07 08:00:01,918:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230606   120000    155959  ...   32812.859  8.451787e+08 -0.000521
718  20230606   160000    195959  ...   37440.876  9.624731e+08 -0.001183
719  20230606   200000    235959  ...  252404.577  6.498559e+09  0.014613
720  20230607   000000    035959  ...  249451.290  6.638496e+09  0.039230
721  20230607   040000    075959  ...  113750.962  3.081163e+09  0.005478

[5 rows x 11 columns]
2023-06-07 08:00:04,226:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230606   120000    155959  1686038399  ...    717  0.625418  0.187076     NaN
718  20230606   160000    195959  1686052799  ...    718  0.677037  0.325372     NaN
719  20230606   200000    235959  1686067199  ...    719  0.604946  0.090038     NaN
720  20230607   000000    035959  1686081599  ...    720  0.498911 -0.255792     NaN
721  20230607   040000    075959  1686095999  ...    721  0.501330 -0.266944     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '-7888.738', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27221.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


