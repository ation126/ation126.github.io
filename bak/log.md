# 20230726 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=20992
self.closeSec=1690330799, self.tradeDate='20230726', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29193.6, self.close=29181.8, self.high=29206.0, self.low=29178.3, self.vol=608.433, self.amt=17761464.4399 
127.0.0.1 - - [26/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-26 08:20:05,375:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230726   075500    075959  ...         0.0        0.0       0
5856  20230726   080000    080459  ...         0.0        0.0       0
5857  20230726   080500    080959  ...         0.0        0.0       0
5858  20230726   081000    081459  ...         0.0        0.0       0
5859  20230726   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-26 08:20:05,394:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690330799, self.tradeDate='20230726', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29193.6, self.close=29181.8, self.high=29206.0, self.low=29178.3, self.vol=608.433, self.amt=17761464.4399, ukdf['pct'].iloc[-1]=-0.000401 , ukdf['amount'].iloc[-1]=17761464.4399, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-32320.8534', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29185.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [26/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=20993
self.closeSec=1690331099, self.tradeDate='20230726', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29181.7, self.close=29168.8, self.high=29186.1, self.low=29157.3, self.vol=1097.43, self.amt=32012332.4519 
2023-07-26 08:25:00,764:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230726   080000    080459  ...         0.0        0.0       0
5857  20230726   080500    080959  ...         0.0        0.0       0
5858  20230726   081000    081459  ...         0.0        0.0       0
5859  20230726   081500    081959  ...         0.0        0.0       0
5860  20230726   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-26 08:25:00,764:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690331099, self.tradeDate='20230726', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29181.7, self.close=29168.8, self.high=29186.1, self.low=29157.3, self.vol=1097.43, self.amt=32012332.4519, ukdf['pct'].iloc[-1]=-0.000445 , ukdf['amount'].iloc[-1]=32012332.4519, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-32085.504', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29168.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1690330799, self.tradeDate='20230726', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29193.6, self.close=29181.8, self.high=29206.0, self.low=29178.3 
127.0.0.1 - - [26/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-26 08:20:03,855:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690330799, self.tradeDate='20230726', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29193.6, self.close=29181.8, self.high=29206.0, self.low=29178.3   
2023-07-26 08:20:04,865:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230726   075500    075959  1690329599  ...  29212.6 -0.000274   1535    5
1536  20230726   080000    080459  1690329899  ...  29203.4 -0.000356   1536    0
1537  20230726   080500    080959  1690330199  ...  29205.9  0.000445   1537    1
1538  20230726   081000    081459  1690330499  ...  29192.0 -0.000869   1538    2
1539  20230726   081500    081959  1690330799  ...  29178.3 -0.000401   1539    3

[5 rows x 11 columns]
2023-07-26 08:20:04,874:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [26/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=20, self.factor=0.48035433818004014, self.count=20995 

self.closeSec=1690331099, self.tradeDate='20230726', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29181.7, self.close=29168.8, self.high=29186.1, self.low=29157.3 
2023-07-26 08:25:00,736:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690331099, self.tradeDate='20230726', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29181.7, self.close=29168.8, self.high=29186.1, self.low=29157.3   
2023-07-26 08:25:00,757:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230726   080000    080459  1690329899  ...  29203.4 -0.000356   1536    0
1537  20230726   080500    080959  1690330199  ...  29205.9  0.000445   1537    1
1538  20230726   081000    081459  1690330499  ...  29192.0 -0.000869   1538    2
1539  20230726   081500    081959  1690330799  ...  29178.3 -0.000401   1539    3
1540  20230726   082000    082459  1690331099  ...  29157.3 -0.000445   1540    4

[5 rows x 11 columns]
2023-07-26 08:25:00,757:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-26 08:00:17,296:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230726    052959  29219.9  ...  50.416667  0.468131  0.429689
5771  20230726    055959  29235.3  ...  50.000000  0.462937  0.433919
5772  20230726    062959  29217.9  ...  50.000000  0.460346  0.440304
5773  20230726    065959  29209.2  ...  50.000000  0.454380  0.450412
5774  20230726    072959  29189.1  ...  50.000000  0.457964  0.457771

[5 rows x 33 columns]
0.5526802218114603
acc is : 0.5526802218114603
2023-07-26 08:00:17,352:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.509346  0.490654       0  ...  0.979244  -1.0    0.0  0.945083
537     0  0.501354  0.498646       0  ...  0.979535  -1.0    0.0  0.944802
538     0  0.507923  0.492077       0  ...  0.980206  -1.0    0.0  0.944155
539     1  0.498983  0.501017       1  ...  0.979870  -1.0    0.0  0.944478
540     0  0.507102  0.492898       1  ...  0.979300  -1.0    0.0  0.945028

[5 rows x 10 columns]
2023-07-26 08:00:17,362:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.509671  0.490329       0  ...  0.979244  -1.0    0.0  0.935377
46     0  0.501865  0.498135       0  ...  0.979535  -1.0    0.0  0.936865
47     0  0.507700  0.492300       0  ...  0.980206  -1.0    0.0  0.935386
48     1  0.499381  0.500619       1  ...  0.979870  -1.0    0.0  0.944478
49     0  0.507102  0.492898       1  ...  0.979300  -1.0    0.0  0.945028

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.403', 'enterprice': '29752', 'countrevence': '0', 'unrealprofit': '12457.4169', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29219.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230726   075000    075959  1690329599  29223.4  29216.3 -0.000243
2023-07-26 08:00:02,182:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10496 

self.closeSec=1690330199, self.tradeDate='20230726', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29216.2', self.close='29218.9'
2023-07-26 08:10:01,081:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690330199, self.tradeDate='20230726', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29216.2', self.close='29218.9'
127.0.0.1 - - [26/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-07-26 08:10:01,087:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230726   072000    072959  1690327799  29199.7  29199.2 -0.000014
621  20230726   073000    073959  1690328399  29199.3  29211.8  0.000432
622  20230726   074000    074959  1690328999  29211.8  29223.4  0.000397
623  20230726   075000    075959  1690329599  29223.4  29216.3 -0.000243
624  20230726   080000    080959  1690330199  29216.2  29218.9  0.000089
2023-07-26 08:10:01,090:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10497 

self.closeSec=1690330799, self.tradeDate='20230726', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29219', self.close='29181.8'
127.0.0.1 - - [26/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-26 08:20:06,075:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690330799, self.tradeDate='20230726', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29219', self.close='29181.8'
2023-07-26 08:20:06,486:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230726   073000    073959  1690328399  29199.3  29211.8  0.000432
622  20230726   074000    074959  1690328999  29211.8  29223.4  0.000397
623  20230726   075000    075959  1690329599  29223.4  29216.3 -0.000243
624  20230726   080000    080959  1690330199  29216.2  29218.9  0.000089
625  20230726   081000    081959  1690330799    29219  29181.8 -0.001270
2023-07-26 08:20:06,494:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230726   075000    075959  1690329599  29223.4  29216.3
2023-07-26 08:00:02,192:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [26/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10499 

self.closeSec=1690330199, self.tradeDate='20230726', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29216.2', self.close='29218.9'
2023-07-26 08:10:01,075:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690330199, self.tradeDate='20230726', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29216.2', self.close='29218.9'
2023-07-26 08:10:01,093:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230726   072000    072959  1690327799  29199.7  29199.2
17469  20230726   073000    073959  1690328399  29199.3  29211.8
17470  20230726   074000    074959  1690328999  29211.8  29223.4
17471  20230726   075000    075959  1690329599  29223.4  29216.3
17472  20230726   080000    080959  1690330199  29216.2  29218.9
2023-07-26 08:10:01,093:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10500 

self.closeSec=1690330799, self.tradeDate='20230726', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29219', self.close='29181.8'
127.0.0.1 - - [26/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-26 08:20:07,237:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690330799, self.tradeDate='20230726', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29219', self.close='29181.8'
2023-07-26 08:20:07,371:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230726   073000    073959  1690328399  29199.3  29211.8
17470  20230726   074000    074959  1690328999  29211.8  29223.4
17471  20230726   075000    075959  1690329599  29223.4  29216.3
17472  20230726   080000    080959  1690330199  29216.2  29218.9
17473  20230726   081000    081959  1690330799    29219  29181.8
2023-07-26 08:20:07,371:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230726   075000    075959  1690329599  29223.4  29216.3
2023-07-26 08:00:02,176:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [26/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10499 

self.closeSec=1690330199, self.tradeDate='20230726', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29216.2', self.close='29218.9'
2023-07-26 08:10:01,083:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690330199, self.tradeDate='20230726', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29216.2', self.close='29218.9'
2023-07-26 08:10:01,089:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230726   072000    072959  1690327799  29199.7  29199.2
12141  20230726   073000    073959  1690328399  29199.3  29211.8
12142  20230726   074000    074959  1690328999  29211.8  29223.4
12143  20230726   075000    075959  1690329599  29223.4  29216.3
12144  20230726   080000    080959  1690330199  29216.2  29218.9
2023-07-26 08:10:01,089:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10500 

self.closeSec=1690330799, self.tradeDate='20230726', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29219', self.close='29181.8'
127.0.0.1 - - [26/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-26 08:20:07,086:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690330799, self.tradeDate='20230726', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29219', self.close='29181.8'
2023-07-26 08:20:07,264:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230726   073000    073959  1690328399  29199.3  29211.8
12142  20230726   074000    074959  1690328999  29211.8  29223.4
12143  20230726   075000    075959  1690329599  29223.4  29216.3
12144  20230726   080000    080959  1690330199  29216.2  29218.9
12145  20230726   081000    081959  1690330799    29219  29181.8
2023-07-26 08:20:07,265:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=20992
self.closeSec=1690330799, self.tradeDate='20230726', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29193.6, self.close=29181.8, self.high=29206.0, self.low=29178.3, self.vol=608.433, self.amt=17761464.4399 
127.0.0.1 - - [26/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-26 08:20:05,425:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230726   075500    075959  ...         0.0        0.0       0
5856  20230726   080000    080459  ...         0.0        0.0       0
5857  20230726   080500    080959  ...         0.0        0.0       0
5858  20230726   081000    081459  ...         0.0        0.0       0
5859  20230726   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-26 08:20:05,436:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690330799, self.tradeDate='20230726', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29193.6, self.close=29181.8, self.high=29206.0, self.low=29178.3, self.vol=608.433, self.amt=17761464.4399, ukdf['pct'].iloc[-1]=-0.000401 , ukdf['amount'].iloc[-1]=17761464.4399, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '86976.7938', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29185.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=20993
self.closeSec=1690331099, self.tradeDate='20230726', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29181.7, self.close=29168.8, self.high=29186.1, self.low=29157.3, self.vol=1097.43, self.amt=32012332.4519 
127.0.0.1 - - [26/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-07-26 08:25:00,754:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230726   080000    080459  ...         0.0        0.0       0
5857  20230726   080500    080959  ...         0.0        0.0       0
5858  20230726   081000    081459  ...         0.0        0.0       0
5859  20230726   081500    081959  ...         0.0        0.0       0
5860  20230726   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-26 08:25:00,754:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690331099, self.tradeDate='20230726', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29181.7, self.close=29168.8, self.high=29186.1, self.low=29157.3, self.vol=1097.43, self.amt=32012332.4519, ukdf['pct'].iloc[-1]=-0.000445 , ukdf['amount'].iloc[-1]=32012332.4519, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '86349.1109', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29168.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230725   200000    235959  1690300799  ...    719  0.534944  0.754108     1.0
720  20230726   000000    035959  1690315199  ...    720  0.552748  0.804980     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.821', 'enterprice': '29117.6', 'countrevence': '0', 'unrealprofit': '3919.7015', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29189.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [26/Jul/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1594659.6936504, self.flagDict['side']='buy', self.tradeCount=13, self.count=437
self.closeSec=1690329599, self.tradeDate='20230726', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29189.0, self.close=29216.3, self.high=29247.9, self.low=29171.3, self.vol=13574.242, self.amt=396522877.3607 
2023-07-26 08:00:01,735:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1690329599, self.tradeDate='20230726', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=29189.0, self.close=29216.3, self.high=29247.9, self.low=29171.3, self.vol=13574.242, self.amt=396522877.3607 
2023-07-26 08:00:01,748:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230725   120000    155959  ...  17709.951  5.155998e+08  0.001124
718  20230725   160000    195959  ...  35393.284  1.032527e+09 -0.000505
719  20230725   200000    235959  ...  65595.464  1.916336e+09  0.001697
720  20230726   000000    035959  ...  36685.898  1.073156e+09  0.000754
721  20230726   040000    075959  ...  13574.242  3.965229e+08  0.000935

[5 rows x 11 columns]
2023-07-26 08:00:02,382:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230725   120000    155959  1690271999  ...    717  0.479340  0.567308     NaN
718  20230725   160000    195959  1690286399  ...    718  0.515390  0.696247     1.0
719  20230725   200000    235959  1690300799  ...    719  0.534944  0.754108     1.0
720  20230726   000000    035959  1690315199  ...    720  0.552748  0.804980     1.0
721  20230726   040000    075959  1690329599  ...    721  0.565665  0.836485     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.821', 'enterprice': '29117.6', 'countrevence': '0', 'unrealprofit': '5410.8327', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29216.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


