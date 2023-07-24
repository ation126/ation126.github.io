# 20230724 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=20416
self.closeSec=1690157999, self.tradeDate='20230724', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30057.0, self.close=30077.7, self.high=30086.4, self.low=30053.2, self.vol=461.72, self.amt=13885375.2362 
127.0.0.1 - - [24/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-24 08:20:05,051:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230724   075500    075959  ...         0.0        0.0       0
5856  20230724   080000    080459  ...         0.0        0.0       0
5857  20230724   080500    080959  ...         0.0        0.0       0
5858  20230724   081000    081459  ...         0.0        0.0       0
5859  20230724   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-24 08:20:05,081:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690157999, self.tradeDate='20230724', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30057.0, self.close=30077.7, self.high=30086.4, self.low=30053.2, self.vol=461.72, self.amt=13885375.2362, ukdf['pct'].iloc[-1]=0.000685 , ukdf['amount'].iloc[-1]=13885375.2362, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-44741.4528', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30077.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=20417
self.closeSec=1690158299, self.tradeDate='20230724', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30077.7, self.close=30083.9, self.high=30089.7, self.low=30071.8, self.vol=351.31, self.amt=10567142.6737 
127.0.0.1 - - [24/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-07-24 08:25:00,755:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230724   080000    080459  ...         0.0        0.0       0
5857  20230724   080500    080959  ...         0.0        0.0       0
5858  20230724   081000    081459  ...         0.0        0.0       0
5859  20230724   081500    081959  ...         0.0        0.0       0
5860  20230724   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-24 08:25:00,755:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690158299, self.tradeDate='20230724', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30077.7, self.close=30083.9, self.high=30089.7, self.low=30071.8, self.vol=351.31, self.amt=10567142.6737, ukdf['pct'].iloc[-1]=0.000206 , ukdf['amount'].iloc[-1]=10567142.6737, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-44826.4014', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30083.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1690157999, self.tradeDate='20230724', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30057.0, self.close=30077.7, self.high=30086.4, self.low=30053.2 
127.0.0.1 - - [24/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-24 08:20:03,391:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690157999, self.tradeDate='20230724', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30057.0, self.close=30077.7, self.high=30086.4, self.low=30053.2   
2023-07-24 08:20:04,301:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230724   075500    075959  1690156799  ...  30053.9  0.000559   1535    5
1536  20230724   080000    080459  1690157099  ...  30057.8 -0.000106   1536    0
1537  20230724   080500    080959  1690157399  ...  30051.9 -0.000253   1537    1
1538  20230724   081000    081459  1690157699  ...  30048.2 -0.000096   1538    2
1539  20230724   081500    081959  1690157999  ...  30053.2  0.000685   1539    3

[5 rows x 11 columns]
2023-07-24 08:20:04,302:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=45, self.factor=0.3924435182620156, self.count=20419 

self.closeSec=1690158299, self.tradeDate='20230724', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30077.7, self.close=30083.9, self.high=30089.7, self.low=30071.8 
127.0.0.1 - - [24/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-07-24 08:25:00,739:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690158299, self.tradeDate='20230724', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30077.7, self.close=30083.9, self.high=30089.7, self.low=30071.8   
2023-07-24 08:25:00,763:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230724   080000    080459  1690157099  ...  30057.8 -0.000106   1536    0
1537  20230724   080500    080959  1690157399  ...  30051.9 -0.000253   1537    1
1538  20230724   081000    081459  1690157699  ...  30048.2 -0.000096   1538    2
1539  20230724   081500    081959  1690157999  ...  30053.2  0.000685   1539    3
1540  20230724   082000    082459  1690158299  ...  30071.8  0.000206   1540    4

[5 rows x 11 columns]
2023-07-24 08:25:00,763:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-24 08:00:18,856:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230724    052959  30131.2  ...  52.500000  0.537664  0.285885
5771  20230724    055959  30032.0  ...  52.500000  0.508110  0.316440
5772  20230724    062959  29940.9  ...  52.916667  0.525531  0.340613
5773  20230724    065959  30000.5  ...  52.916667  0.526648  0.362695
5774  20230724    072959  30004.4  ...  52.916667  0.540770  0.377161

[5 rows x 33 columns]
0.5397412199630314
acc is : 0.5397412199630314
2023-07-24 08:00:18,927:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.460909  0.539091       0  ...  0.951945   1.0    0.0  0.983775
537     1  0.458001  0.541999       1  ...  0.953843   1.0    0.0  0.985737
538     0  0.507763  0.492237       1  ...  0.953967   1.0    0.0  0.985865
539     1  0.494304  0.505696       1  ...  0.955554   1.0    0.0  0.987504
540     0  0.507476  0.492524       1  ...  0.956078   1.0    0.0  0.988046

[5 rows x 10 columns]
2023-07-24 08:00:18,941:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.460916  0.539084       0  ...  0.951945   1.0    0.0  0.981341
46     1  0.458430  0.541570       1  ...  0.969224   1.0    0.0  0.984582
47     0  0.507480  0.492520       1  ...  0.953967   1.0    0.0  0.984587
48     1  0.494840  0.505160       1  ...  0.970962   1.0    0.0  0.987504
49     0  0.507476  0.492524       1  ...  0.956078   1.0    0.0  0.988046

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.444', 'enterprice': '29839.3', 'countrevence': '0', 'unrealprofit': '5483.555421372', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30073.200163', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230724   075000    075959  1690156799  30060.5  30070.8  0.000343
2023-07-24 08:00:02,059:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [24/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10208 

self.closeSec=1690157399, self.tradeDate='20230724', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30070.9', self.close='30059.9'
2023-07-24 08:10:01,099:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690157399, self.tradeDate='20230724', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30070.9', self.close='30059.9'
2023-07-24 08:10:01,105:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230724   072000    072959  1690154999  30054.2  30054.3  0.000000
621  20230724   073000    073959  1690155599  30054.3  30054.6  0.000010
622  20230724   074000    074959  1690156199  30054.6  30060.5  0.000196
623  20230724   075000    075959  1690156799  30060.5  30070.8  0.000343
624  20230724   080000    080959  1690157399  30070.9  30059.9 -0.000362
2023-07-24 08:10:01,105:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10209 

self.closeSec=1690157999, self.tradeDate='20230724', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30059.9', self.close='30077.7'
127.0.0.1 - - [24/Jul/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-07-24 08:20:05,736:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690157999, self.tradeDate='20230724', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30059.9', self.close='30077.7'
2023-07-24 08:20:06,186:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230724   073000    073959  1690155599  30054.3  30054.6  0.000010
622  20230724   074000    074959  1690156199  30054.6  30060.5  0.000196
623  20230724   075000    075959  1690156799  30060.5  30070.8  0.000343
624  20230724   080000    080959  1690157399  30070.9  30059.9 -0.000362
625  20230724   081000    081959  1690157999  30059.9  30077.7  0.000592
2023-07-24 08:20:06,187:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230724   075000    075959  1690156799  30060.5  30070.8
2023-07-24 08:00:02,063:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10211 

self.closeSec=1690157399, self.tradeDate='20230724', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30070.9', self.close='30059.9'
2023-07-24 08:10:01,091:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690157399, self.tradeDate='20230724', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30070.9', self.close='30059.9'
127.0.0.1 - - [24/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-07-24 08:10:01,103:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230724   072000    072959  1690154999  30054.2  30054.3
17469  20230724   073000    073959  1690155599  30054.3  30054.6
17470  20230724   074000    074959  1690156199  30054.6  30060.5
17471  20230724   075000    075959  1690156799  30060.5  30070.8
17472  20230724   080000    080959  1690157399  30070.9  30059.9
2023-07-24 08:10:01,103:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10212 

self.closeSec=1690157999, self.tradeDate='20230724', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30059.9', self.close='30077.7'
127.0.0.1 - - [24/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-24 08:20:06,950:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690157999, self.tradeDate='20230724', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30059.9', self.close='30077.7'
2023-07-24 08:20:07,073:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230724   073000    073959  1690155599  30054.3  30054.6
17470  20230724   074000    074959  1690156199  30054.6  30060.5
17471  20230724   075000    075959  1690156799  30060.5  30070.8
17472  20230724   080000    080959  1690157399  30070.9  30059.9
17473  20230724   081000    081959  1690157999  30059.9  30077.7
2023-07-24 08:20:07,074:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230724   075000    075959  1690156799  30060.5  30070.8
2023-07-24 08:00:02,050:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10211 

self.closeSec=1690157399, self.tradeDate='20230724', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30070.9', self.close='30059.9'
2023-07-24 08:10:01,089:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690157399, self.tradeDate='20230724', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30070.9', self.close='30059.9'
127.0.0.1 - - [24/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-07-24 08:10:01,097:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230724   072000    072959  1690154999  30054.2  30054.3
12141  20230724   073000    073959  1690155599  30054.3  30054.6
12142  20230724   074000    074959  1690156199  30054.6  30060.5
12143  20230724   075000    075959  1690156799  30060.5  30070.8
12144  20230724   080000    080959  1690157399  30070.9  30059.9
2023-07-24 08:10:01,097:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10212 

self.closeSec=1690157999, self.tradeDate='20230724', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30059.9', self.close='30077.7'
127.0.0.1 - - [24/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-24 08:20:06,778:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690157999, self.tradeDate='20230724', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30059.9', self.close='30077.7'
2023-07-24 08:20:06,987:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230724   073000    073959  1690155599  30054.3  30054.6
12142  20230724   074000    074959  1690156199  30054.6  30060.5
12143  20230724   075000    075959  1690156799  30060.5  30070.8
12144  20230724   080000    080959  1690157399  30070.9  30059.9
12145  20230724   081000    081959  1690157999  30059.9  30077.7
2023-07-24 08:20:06,988:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=20416
self.closeSec=1690157999, self.tradeDate='20230724', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30057.0, self.close=30077.7, self.high=30086.4, self.low=30053.2, self.vol=461.72, self.amt=13885375.2362 
127.0.0.1 - - [24/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-24 08:20:05,041:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230724   075500    075959  ...         0.0        0.0       0
5856  20230724   080000    080459  ...         0.0        0.0       0
5857  20230724   080500    080959  ...         0.0        0.0       0
5858  20230724   081000    081459  ...         0.0        0.0       0
5859  20230724   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-24 08:20:05,061:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690157999, self.tradeDate='20230724', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30057.0, self.close=30077.7, self.high=30086.4, self.low=30053.2, self.vol=461.72, self.amt=13885375.2362, ukdf['pct'].iloc[-1]=0.000685 , ukdf['amount'].iloc[-1]=13885375.2362, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '120102.8517', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30077.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [24/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=20417
self.closeSec=1690158299, self.tradeDate='20230724', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30077.7, self.close=30083.9, self.high=30089.7, self.low=30071.8, self.vol=351.31, self.amt=10567142.6737 
2023-07-24 08:25:00,773:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230724   080000    080459  ...         0.0        0.0       0
5857  20230724   080500    080959  ...         0.0        0.0       0
5858  20230724   081000    081459  ...         0.0        0.0       0
5859  20230724   081500    081959  ...         0.0        0.0       0
5860  20230724   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-24 08:25:00,773:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690158299, self.tradeDate='20230724', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30077.7, self.close=30083.9, self.high=30089.7, self.low=30071.8, self.vol=351.31, self.amt=10567142.6737, ukdf['pct'].iloc[-1]=0.000206 , ukdf['amount'].iloc[-1]=10567142.6737, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '120329.4118', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30083.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230723   200000    235959  1690127999  ...    719  0.096704 -1.012718    -1.0
720  20230724   000000    035959  1690142399  ...    720  0.142670 -0.812779    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.176', 'enterprice': '29870.6', 'countrevence': '0', 'unrealprofit': '-11306.5392', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30087.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [24/Jul/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1556969.8971744, self.flagDict['side']='sell', self.tradeCount=12, self.count=425
self.closeSec=1690156799, self.tradeDate='20230724', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=30083.1, self.close=30070.8, self.high=30135.0, self.low=29909.0, self.vol=37643.416, self.amt=1130502254.44484 
2023-07-24 08:00:01,637:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1690156799, self.tradeDate='20230724', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=30083.1, self.close=30070.8, self.high=30135.0, self.low=29909.0, self.vol=37643.416, self.amt=1130502254.44484 
2023-07-24 08:00:01,653:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230723   120000    155959  ...  34347.504  1.027396e+09  0.002293
718  20230723   160000    195959  ...  15675.657  4.687871e+08 -0.000649
719  20230723   200000    235959  ...  14726.508  4.400262e+08  0.000151
720  20230724   000000    035959  ...  92494.175  2.786594e+09  0.006595
721  20230724   040000    075959  ...  37643.416  1.130502e+09 -0.000409

[5 rows x 11 columns]
2023-07-24 08:00:02,420:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230723   120000    155959  1690099199  ...    717  0.148149 -0.843344    -1.0
718  20230723   160000    195959  1690113599  ...    718  0.107702 -0.988349    -1.0
719  20230723   200000    235959  1690127999  ...    719  0.096704 -1.012718    -1.0
720  20230724   000000    035959  1690142399  ...    720  0.142670 -0.812779    -1.0
721  20230724   040000    075959  1690156799  ...    721  0.150437 -0.769752    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.176', 'enterprice': '29870.6', 'countrevence': '0', 'unrealprofit': '-10547.55203337984', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30072.75332784', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


