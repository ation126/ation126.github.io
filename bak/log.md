# 20230713 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=17248
self.closeSec=1689207599, self.tradeDate='20230713', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30401.6, self.close=30407.5, self.high=30423.0, self.low=30401.5, self.vol=1098.186, self.amt=33398966.0298 
127.0.0.1 - - [13/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-13 08:20:07,276:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230713   075500    075959  ...         0.0        0.0       0
5856  20230713   080000    080459  ...         0.0        0.0       0
5857  20230713   080500    080959  ...         0.0        0.0       0
5858  20230713   081000    081459  ...         0.0        0.0       0
5859  20230713   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-13 08:20:07,298:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689207599, self.tradeDate='20230713', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30401.6, self.close=30407.5, self.high=30423.0, self.low=30401.5, self.vol=1098.186, self.amt=33398966.0298, ukdf['pct'].iloc[-1]=0.000194 , ukdf['amount'].iloc[-1]=33398966.0298, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-49332.855', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30407.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=17249
self.closeSec=1689207899, self.tradeDate='20230713', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30407.5, self.close=30390.3, self.high=30407.5, self.low=30383.3, self.vol=443.298, self.amt=13473737.2792 
127.0.0.1 - - [13/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-07-13 08:25:00,802:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230713   080000    080459  ...         0.0        0.0       0
5857  20230713   080500    080959  ...         0.0        0.0       0
5858  20230713   081000    081459  ...         0.0        0.0       0
5859  20230713   081500    081959  ...         0.0        0.0       0
5860  20230713   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-13 08:25:00,802:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689207899, self.tradeDate='20230713', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30407.5, self.close=30390.3, self.high=30407.5, self.low=30383.3, self.vol=443.298, self.amt=13473737.2792, ukdf['pct'].iloc[-1]=-0.000566 , ukdf['amount'].iloc[-1]=13473737.2792, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-49108.6464', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30391.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1689207599, self.tradeDate='20230713', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30401.6, self.close=30407.5, self.high=30423.0, self.low=30401.5 
127.0.0.1 - - [13/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-13 08:20:04,796:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689207599, self.tradeDate='20230713', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30401.6, self.close=30407.5, self.high=30423.0, self.low=30401.5   
2023-07-13 08:20:06,246:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230713   075500    075959  1689206399  ...  30361.5 -0.000089   1535    5
1536  20230713   080000    080459  1689206699  ...  30356.0  0.000165   1536    0
1537  20230713   080500    080959  1689206999  ...  30371.3  0.000731   1537    1
1538  20230713   081000    081459  1689207299  ...  30382.9  0.000178   1538    2
1539  20230713   081500    081959  1689207599  ...  30401.5  0.000194   1539    3

[5 rows x 11 columns]
2023-07-13 08:20:06,256:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [13/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=207, self.factor=0.5324907550393744, self.count=17251 

self.closeSec=1689207899, self.tradeDate='20230713', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30407.5, self.close=30390.3, self.high=30407.5, self.low=30383.3 
2023-07-13 08:25:00,745:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689207899, self.tradeDate='20230713', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30407.5, self.close=30390.3, self.high=30407.5, self.low=30383.3   
2023-07-13 08:25:00,789:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230713   080000    080459  1689206699  ...  30356.0  0.000165   1536    0
1537  20230713   080500    080959  1689206999  ...  30371.3  0.000731   1537    1
1538  20230713   081000    081459  1689207299  ...  30382.9  0.000178   1538    2
1539  20230713   081500    081959  1689207599  ...  30401.5  0.000194   1539    3
1540  20230713   082000    082459  1689207899  ...  30383.3 -0.000566   1540    4

[5 rows x 11 columns]
2023-07-13 08:25:00,789:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-13 08:00:20,561:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230713    052959  30330.0  ...  50.416667  0.456800  0.656943
5771  20230713    055959  30328.2  ...  50.833333  0.459463  0.667034
5772  20230713    062959  30338.3  ...  50.833333  0.462023  0.675638
5773  20230713    065959  30348.1  ...  51.250000  0.462585  0.683492
5774  20230713    072959  30350.1  ...  51.250000  0.465164  0.690026

[5 rows x 33 columns]
0.5526802218114603
acc is : 0.5526802218114603
2023-07-13 08:00:20,698:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.487872  0.512128       1  ...  0.962688   1.0    0.0  0.992317
537     0  0.506226  0.493774       1  ...  0.962996   1.0    0.0  0.992634
538     0  0.519266  0.480734       1  ...  0.963063   1.0    0.0  0.992703
539     0  0.512578  0.487422       1  ...  0.963364   1.0    0.0  0.993013
540     0  0.509917  0.490083       1  ...  0.963659   1.0    0.0  0.993318

[5 rows x 10 columns]
2023-07-13 08:00:20,726:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.488361  0.511639       1  ...  0.970356   1.0    0.0  0.992697
46     0  0.507117  0.492883       1  ...  0.970666   1.0    0.0  0.993355
47     0  0.519997  0.480003       1  ...  0.970733   1.0    0.0  0.992998
48     0  0.512578  0.487422       1  ...  0.963364   1.0    0.0  0.993013
49     0  0.509917  0.490083       1  ...  0.963659   1.0    0.0  0.993318

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.383', 'enterprice': '30486.7', 'countrevence': '0', 'unrealprofit': '-2967.74113341437', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30364.98646461', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230713   075000    075959  1689206399    30392  30368.9 -0.000763
2023-07-13 08:00:02,270:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8624 

self.closeSec=1689206999, self.tradeDate='20230713', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30368.9', self.close='30396.2'
2023-07-13 08:10:01,085:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689206999, self.tradeDate='20230713', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30368.9', self.close='30396.2'
127.0.0.1 - - [13/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-07-13 08:10:01,096:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230713   072000    072959  1689204599    30366  30359.6 -0.000207
621  20230713   073000    073959  1689205199  30359.6  30386.1  0.000873
622  20230713   074000    074959  1689205799  30386.1  30392.1  0.000197
623  20230713   075000    075959  1689206399    30392  30368.9 -0.000763
624  20230713   080000    080959  1689206999  30368.9  30396.2  0.000899
2023-07-13 08:10:01,097:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8625 

self.closeSec=1689207599, self.tradeDate='20230713', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30396.2', self.close='30407.5'
127.0.0.1 - - [13/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-13 08:20:07,226:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689207599, self.tradeDate='20230713', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30396.2', self.close='30407.5'
2023-07-13 08:20:08,036:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230713   073000    073959  1689205199  30359.6  30386.1  0.000873
622  20230713   074000    074959  1689205799  30386.1  30392.1  0.000197
623  20230713   075000    075959  1689206399    30392  30368.9 -0.000763
624  20230713   080000    080959  1689206999  30368.9  30396.2  0.000899
625  20230713   081000    081959  1689207599  30396.2  30407.5  0.000372
2023-07-13 08:20:08,046:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230713   075000    075959  1689206399    30392  30368.9
2023-07-13 08:00:02,272:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [13/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8627 

self.closeSec=1689206999, self.tradeDate='20230713', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30368.9', self.close='30396.2'
2023-07-13 08:10:01,110:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689206999, self.tradeDate='20230713', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30368.9', self.close='30396.2'
2023-07-13 08:10:01,116:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230713   072000    072959  1689204599    30366  30359.6
17469  20230713   073000    073959  1689205199  30359.6  30386.1
17470  20230713   074000    074959  1689205799  30386.1  30392.1
17471  20230713   075000    075959  1689206399    30392  30368.9
17472  20230713   080000    080959  1689206999  30368.9  30396.2
2023-07-13 08:10:01,116:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8628 

self.closeSec=1689207599, self.tradeDate='20230713', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30396.2', self.close='30407.5'
127.0.0.1 - - [13/Jul/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-07-13 08:20:09,018:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689207599, self.tradeDate='20230713', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30396.2', self.close='30407.5'
2023-07-13 08:20:09,247:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230713   073000    073959  1689205199  30359.6  30386.1
17470  20230713   074000    074959  1689205799  30386.1  30392.1
17471  20230713   075000    075959  1689206399    30392  30368.9
17472  20230713   080000    080959  1689206999  30368.9  30396.2
17473  20230713   081000    081959  1689207599  30396.2  30407.5
2023-07-13 08:20:09,247:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230713   075000    075959  1689206399    30392  30368.9
2023-07-13 08:00:02,280:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8627 

self.closeSec=1689206999, self.tradeDate='20230713', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30368.9', self.close='30396.2'
2023-07-13 08:10:01,078:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689206999, self.tradeDate='20230713', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30368.9', self.close='30396.2'
127.0.0.1 - - [13/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-07-13 08:10:01,095:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230713   072000    072959  1689204599    30366  30359.6
12141  20230713   073000    073959  1689205199  30359.6  30386.1
12142  20230713   074000    074959  1689205799  30386.1  30392.1
12143  20230713   075000    075959  1689206399    30392  30368.9
12144  20230713   080000    080959  1689206999  30368.9  30396.2
2023-07-13 08:10:01,095:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8628 

self.closeSec=1689207599, self.tradeDate='20230713', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30396.2', self.close='30407.5'
127.0.0.1 - - [13/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-13 08:20:08,848:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689207599, self.tradeDate='20230713', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30396.2', self.close='30407.5'
2023-07-13 08:20:09,117:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230713   073000    073959  1689205199  30359.6  30386.1
12142  20230713   074000    074959  1689205799  30386.1  30392.1
12143  20230713   075000    075959  1689206399    30392  30368.9
12144  20230713   080000    080959  1689206999  30368.9  30396.2
12145  20230713   081000    081959  1689207599  30396.2  30407.5
2023-07-13 08:20:09,117:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=17248
self.closeSec=1689207599, self.tradeDate='20230713', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30401.6, self.close=30407.5, self.high=30423.0, self.low=30401.5, self.vol=1098.186, self.amt=33398966.0298 
127.0.0.1 - - [13/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-13 08:20:07,286:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230713   075500    075959  ...         0.0        0.0       0
5856  20230713   080000    080459  ...         0.0        0.0       0
5857  20230713   080500    080959  ...         0.0        0.0       0
5858  20230713   081000    081459  ...         0.0        0.0       0
5859  20230713   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-13 08:20:07,298:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689207599, self.tradeDate='20230713', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30401.6, self.close=30407.5, self.high=30423.0, self.low=30401.5, self.vol=1098.186, self.amt=33398966.0298, ukdf['pct'].iloc[-1]=0.000194 , ukdf['amount'].iloc[-1]=33398966.0298, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '132348.2394', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30407.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [13/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=17249
self.closeSec=1689207899, self.tradeDate='20230713', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30407.5, self.close=30390.3, self.high=30407.5, self.low=30383.3, self.vol=443.298, self.amt=13473737.2792 
2023-07-13 08:25:00,798:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230713   080000    080459  ...         0.0        0.0       0
5857  20230713   080500    080959  ...         0.0        0.0       0
5858  20230713   081000    081459  ...         0.0        0.0       0
5859  20230713   081500    081959  ...         0.0        0.0       0
5860  20230713   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-13 08:25:00,798:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689207899, self.tradeDate='20230713', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30407.5, self.close=30390.3, self.high=30407.5, self.low=30383.3, self.vol=443.298, self.amt=13473737.2792, ukdf['pct'].iloc[-1]=-0.000566 , ukdf['amount'].iloc[-1]=13473737.2792, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '131750.2693', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30391.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230712   200000    235959  1689177599  ...    719  0.413594  0.605172     1.0
720  20230713   000000    035959  1689191999  ...    720  0.383637  0.473527     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.241', 'enterprice': '30511.1', 'countrevence': '0', 'unrealprofit': '-13355.96120494601', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30255.43948039', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1592336.4447248997, self.flagDict['side']='buy', self.tradeCount=11, self.count=359
self.closeSec=1689206399, self.tradeDate='20230713', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=30268.1, self.close=30368.9, self.high=30408.8, self.low=30220.5, self.vol=29246.963, self.amt=886732082.3149 
127.0.0.1 - - [13/Jul/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-07-13 08:00:01,746:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1689206399, self.tradeDate='20230713', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=30268.1, self.close=30368.9, self.high=30408.8, self.low=30220.5, self.vol=29246.963, self.amt=886732082.3149 
2023-07-13 08:00:01,787:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230712   120000    155959  ...   50264.091  1.543709e+09  0.004889
718  20230712   160000    195959  ...   33657.850  1.033479e+09  0.001123
719  20230712   200000    235959  ...  198941.331  6.108353e+09 -0.008295
720  20230713   000000    035959  ...   84461.464  2.566969e+09 -0.007932
721  20230713   040000    075959  ...   29246.963  8.867321e+08  0.003330

[5 rows x 11 columns]
2023-07-13 08:00:03,328:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230712   120000    155959  1689148799  ...    717  0.355324  0.374296     NaN
718  20230712   160000    195959  1689163199  ...    718  0.347269  0.325733     NaN
719  20230712   200000    235959  1689177599  ...    719  0.413594  0.605172     1.0
720  20230713   000000    035959  1689191999  ...    720  0.383637  0.473527     NaN
721  20230713   040000    075959  1689206399  ...    721  0.367737  0.396680     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.241', 'enterprice': '30511.1', 'countrevence': '0', 'unrealprofit': '-7418.33682780764', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30369.09780196', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


