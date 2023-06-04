# 20230604 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=6016
self.closeSec=1685837999, self.tradeDate='20230604', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27040.5, self.close=27054.0, self.high=27054.0, self.low=27027.0, self.vol=667.492, self.amt=18048952.9874 
127.0.0.1 - - [04/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-04 08:20:08,111:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230604   075500    075959  ...         0.0        0.0       0
5856  20230604   080000    080459  ...         0.0        0.0       0
5857  20230604   080500    080959  ...         0.0        0.0       0
5858  20230604   081000    081459  ...         0.0        0.0       0
5859  20230604   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-04 08:20:08,130:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685837999, self.tradeDate='20230604', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27040.5, self.close=27054.0, self.high=27054.0, self.low=27027.0, self.vol=667.492, self.amt=18048952.9874, ukdf['pct'].iloc[-1]=0.000496 , ukdf['amount'].iloc[-1]=18048952.9874, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-2566.5618', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27049.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [04/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=6017
self.closeSec=1685838299, self.tradeDate='20230604', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27054.0, self.close=27027.8, self.high=27054.0, self.low=27026.6, self.vol=317.521, self.amt=8586603.4029 
2023-06-04 08:25:00,834:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230604   080000    080459  ...         0.0        0.0       0
5857  20230604   080500    080959  ...         0.0        0.0       0
5858  20230604   081000    081459  ...         0.0        0.0       0
5859  20230604   081500    081959  ...         0.0        0.0       0
5860  20230604   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-04 08:25:00,834:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685838299, self.tradeDate='20230604', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27054.0, self.close=27027.8, self.high=27054.0, self.low=27026.6, self.vol=317.521, self.amt=8586603.4029, ukdf['pct'].iloc[-1]=-0.000968 , ukdf['amount'].iloc[-1]=8586603.4029, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-2269.938', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27027.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1685837999, self.tradeDate='20230604', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27040.5, self.close=27054.0, self.high=27054.0, self.low=27027.0 
127.0.0.1 - - [04/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-04 08:20:04,840:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685837999, self.tradeDate='20230604', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27040.5, self.close=27054.0, self.high=27054.0, self.low=27027.0   
2023-06-04 08:20:06,790:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230604   075500    075959  1685836799  ...  27039.0  0.000584   1535    5
1536  20230604   080000    080459  1685837099  ...  27037.0 -0.000189   1536    0
1537  20230604   080500    080959  1685837399  ...  27036.4 -0.000421   1537    1
1538  20230604   081000    081459  1685837699  ...  27037.4  0.000081   1538    2
1539  20230604   081500    081959  1685837999  ...  27027.0  0.000496   1539    3

[5 rows x 11 columns]
2023-06-04 08:20:06,800:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [04/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=35, self.factor=0.48989645961588635, self.count=6019 

self.closeSec=1685838299, self.tradeDate='20230604', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27054.0, self.close=27027.8, self.high=27054.0, self.low=27026.6 
2023-06-04 08:25:00,738:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685838299, self.tradeDate='20230604', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27054.0, self.close=27027.8, self.high=27054.0, self.low=27026.6   
2023-06-04 08:25:00,793:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230604   080000    080459  1685837099  ...  27037.0 -0.000189   1536    0
1537  20230604   080500    080959  1685837399  ...  27036.4 -0.000421   1537    1
1538  20230604   081000    081459  1685837699  ...  27037.4  0.000081   1538    2
1539  20230604   081500    081959  1685837999  ...  27027.0  0.000496   1539    3
1540  20230604   082000    082459  1685838299  ...  27026.6 -0.000968   1540    4

[5 rows x 11 columns]
2023-06-04 08:25:00,793:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-04 08:00:32,566:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230604    052959  27052.8  ...  47.083333  0.464332  0.533838
5771  20230604    055959  27002.7  ...  46.666667  0.460683  0.551285
5772  20230604    062959  26990.0  ...  47.083333  0.474928  0.561011
5773  20230604    065959  27033.3  ...  47.083333  0.483638  0.565985
5774  20230604    072959  27060.4  ...  47.083333  0.484475  0.570234

[5 rows x 33 columns]
0.5212569316081331
acc is : 0.5212569316081331
2023-06-04 08:00:32,720:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.479512  0.520488       0  ...  1.031556   1.0    0.0  0.992852
537     1  0.485319  0.514681       1  ...  1.033211   1.0    0.0  0.994445
538     0  0.503221  0.496779       1  ...  1.034246   1.0    0.0  0.995442
539     0  0.501609  0.498391       1  ...  1.034346   1.0    0.0  0.995538
540     0  0.501009  0.498991       0  ...  1.034036   1.0    0.0  0.995240

[5 rows x 10 columns]
2023-06-04 08:00:32,752:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.479530  0.520470       0  ...  1.031556   1.0    0.0  0.988257
46     1  0.485513  0.514487       1  ...  1.033211   1.0    0.0  0.991386
47     0  0.503397  0.496603       1  ...  1.034246   1.0    0.0  0.994162
48     0  0.501882  0.498118       1  ...  1.034346   1.0    0.0  0.995538
49     0  0.501009  0.498991       0  ...  1.034036   1.0    0.0  0.995240

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.623', 'enterprice': '26988.6', 'countrevence': '0', 'unrealprofit': '1806.5442', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27054', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230604   075000    075959  1685836799  27064.2  27054.9 -0.000344
2023-06-04 08:00:02,258:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [04/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3008 

self.closeSec=1685837399, self.tradeDate='20230604', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27054.9', self.close='27038.4'
2023-06-04 08:10:01,090:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685837399, self.tradeDate='20230604', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27054.9', self.close='27038.4'
2023-06-04 08:10:01,130:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230604   072000    072959  1685834999  27051.6    27063  0.000421
621  20230604   073000    073959  1685835599  27063.1  27060.8 -0.000081
622  20230604   074000    074959  1685836199  27060.7  27064.2  0.000126
623  20230604   075000    075959  1685836799  27064.2  27054.9 -0.000344
624  20230604   080000    080959  1685837399  27054.9  27038.4 -0.000610
2023-06-04 08:10:01,131:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3009 

self.closeSec=1685837999, self.tradeDate='20230604', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27038.5', self.close='27054'
127.0.0.1 - - [04/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-04 08:20:08,300:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685837999, self.tradeDate='20230604', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27038.5', self.close='27054'
2023-06-04 08:20:09,021:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230604   073000    073959  1685835599  27063.1  27060.8 -0.000081
622  20230604   074000    074959  1685836199  27060.7  27064.2  0.000126
623  20230604   075000    075959  1685836799  27064.2  27054.9 -0.000344
624  20230604   080000    080959  1685837399  27054.9  27038.4 -0.000610
625  20230604   081000    081959  1685837999  27038.5    27054  0.000577
2023-06-04 08:20:09,022:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230604   075000    075959  1685836799  27064.2  27054.9
2023-06-04 08:00:02,280:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [04/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3011 

self.closeSec=1685837399, self.tradeDate='20230604', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27054.9', self.close='27038.4'
2023-06-04 08:10:01,102:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685837399, self.tradeDate='20230604', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27054.9', self.close='27038.4'
2023-06-04 08:10:01,141:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230604   072000    072959  1685834999  27051.6    27063
17469  20230604   073000    073959  1685835599  27063.1  27060.8
17470  20230604   074000    074959  1685836199  27060.7  27064.2
17471  20230604   075000    075959  1685836799  27064.2  27054.9
17472  20230604   080000    080959  1685837399  27054.9  27038.4
2023-06-04 08:10:01,141:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3012 

self.closeSec=1685837999, self.tradeDate='20230604', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27038.5', self.close='27054'
127.0.0.1 - - [04/Jun/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-06-04 08:20:10,234:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685837999, self.tradeDate='20230604', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27038.5', self.close='27054'
2023-06-04 08:20:10,383:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230604   073000    073959  1685835599  27063.1  27060.8
17470  20230604   074000    074959  1685836199  27060.7  27064.2
17471  20230604   075000    075959  1685836799  27064.2  27054.9
17472  20230604   080000    080959  1685837399  27054.9  27038.4
17473  20230604   081000    081959  1685837999  27038.5    27054
2023-06-04 08:20:10,384:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230604   075000    075959  1685836799  27064.2  27054.9
2023-06-04 08:00:02,270:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [04/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3011 

self.closeSec=1685837399, self.tradeDate='20230604', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27054.9', self.close='27038.4'
2023-06-04 08:10:01,087:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685837399, self.tradeDate='20230604', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27054.9', self.close='27038.4'
2023-06-04 08:10:01,120:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230604   072000    072959  1685834999  27051.6    27063
12141  20230604   073000    073959  1685835599  27063.1  27060.8
12142  20230604   074000    074959  1685836199  27060.7  27064.2
12143  20230604   075000    075959  1685836799  27064.2  27054.9
12144  20230604   080000    080959  1685837399  27054.9  27038.4
2023-06-04 08:10:01,122:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3012 

self.closeSec=1685837999, self.tradeDate='20230604', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27038.5', self.close='27054'
127.0.0.1 - - [04/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-04 08:20:09,852:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685837999, self.tradeDate='20230604', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27038.5', self.close='27054'
2023-06-04 08:20:10,169:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230604   073000    073959  1685835599  27063.1  27060.8
12142  20230604   074000    074959  1685836199  27060.7  27064.2
12143  20230604   075000    075959  1685836799  27064.2  27054.9
12144  20230604   080000    080959  1685837399  27054.9  27038.4
12145  20230604   081000    081959  1685837999  27038.5    27054
2023-06-04 08:20:10,171:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=6016
self.closeSec=1685837999, self.tradeDate='20230604', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27040.5, self.close=27054.0, self.high=27054.0, self.low=27027.0, self.vol=667.492, self.amt=18048952.9874 
127.0.0.1 - - [04/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-04 08:20:08,050:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230604   075500    075959  ...         0.0        0.0       0
5856  20230604   080000    080459  ...         0.0        0.0       0
5857  20230604   080500    080959  ...         0.0        0.0       0
5858  20230604   081000    081459  ...         0.0        0.0       0
5859  20230604   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-04 08:20:08,070:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685837999, self.tradeDate='20230604', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27040.5, self.close=27054.0, self.high=27054.0, self.low=27027.0, self.vol=667.492, self.amt=18048952.9874, ukdf['pct'].iloc[-1]=0.000496 , ukdf['amount'].iloc[-1]=18048952.9874, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '7621.3332', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27049.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [04/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=6017
self.closeSec=1685838299, self.tradeDate='20230604', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27054.0, self.close=27027.8, self.high=27054.0, self.low=27026.6, self.vol=317.521, self.amt=8586603.4029 
2023-06-04 08:25:00,855:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230604   080000    080459  ...         0.0        0.0       0
5857  20230604   080500    080959  ...         0.0        0.0       0
5858  20230604   081000    081459  ...         0.0        0.0       0
5859  20230604   081500    081959  ...         0.0        0.0       0
5860  20230604   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-04 08:25:00,856:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685838299, self.tradeDate='20230604', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27054.0, self.close=27027.8, self.high=27054.0, self.low=27026.6, self.vol=317.521, self.amt=8586603.4029, ukdf['pct'].iloc[-1]=-0.000968 , ukdf['amount'].iloc[-1]=8586603.4029, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '6830.2299', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27027.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

127.0.0.1 - - [04/Jun/2023 04:00:12] "POST / HTTP/1.1" 200 -
2023-06-04 04:00:12,716:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42316F1685822406918I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1685822407353059, 'quantity': '55.249', 'price': '27083.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1685822405980, 'updatetime': 1685822407353, 'tradetype': 'usdt', 'selfid': 42316, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1685822407353, 'clientorderid': '42316F1685822406918I0L65', 'price': '27083.5', 'quantity': '55.249', 'commission': '1496.3362915', 'commissionasset': 'USDT', 'tradetime': 1685822407353, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1685822407353}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [04/Jun/2023 04:00:13] "POST / HTTP/1.1" 200 -
2023-06-04 04:00:13,079:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42317F1685822412683I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1685822413064002, 'quantity': '55.166', 'price': '27078.6', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1685822412085, 'updatetime': 1685822413064, 'tradetype': 'usdt', 'selfid': 42317, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1685822413064, 'clientorderid': '42317F1685822412683I0L65', 'price': '27078.6', 'quantity': '55.166', 'commission': '1493.8180476', 'commissionasset': 'USDT', 'tradetime': 1685822413064, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1685822413064}], 'gatetype': 'simulator', 'handletime': 0}
2023-06-04 04:00:13,329:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42317F1685822412683I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1685822413064002, 'quantity': '55.166', 'price': '27078.6', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1685822412085, 'updatetime': 1685822413064, 'tradetype': 'usdt', 'selfid': 42317, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1685822413064, 'clientorderid': '42317F1685822412683I0L65', 'price': '27078.6', 'quantity': '55.166', 'commission': '1493.8180476', 'commissionasset': 'USDT', 'tradetime': 1685822413064, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1685822413064}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [04/Jun/2023 04:00:13] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1492324.2295523998, self.flagDict['side']='sell', self.tradeCount=4, self.count=125
self.closeSec=1685836799, self.tradeDate='20230604', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27084.9, self.close=27054.9, self.high=27119.5, self.low=26900.0, self.vol=36463.54, self.amt=985188378.1748 
127.0.0.1 - - [04/Jun/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-06-04 08:00:01,836:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1685836799, self.tradeDate='20230604', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27084.9, self.close=27054.9, self.high=27119.5, self.low=26900.0, self.vol=36463.54, self.amt=985188378.1748 
2023-06-04 08:00:01,870:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230603   120000    155959  ...  17689.692  4.803177e+08  0.001120
718  20230603   160000    195959  ...  16660.540  4.521462e+08 -0.001484
719  20230603   200000    235959  ...  35777.121  9.731898e+08  0.006331
720  20230604   000000    035959  ...  50814.584  1.380421e+09 -0.007614
721  20230604   040000    075959  ...  36463.540  9.851884e+08 -0.001108

[5 rows x 11 columns]
2023-06-04 08:00:03,917:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230603   120000    155959  1685779199  ...    717  0.580259  0.077345     NaN
718  20230603   160000    195959  1685793599  ...    718  0.559322  0.006778     NaN
719  20230603   200000    235959  1685807999  ...    719  0.472565 -0.261938     NaN
720  20230604   000000    035959  1685822399  ...    720  0.361375 -0.602675    -1.0
721  20230604   040000    075959  1685836799  ...    721  0.276780 -0.862749    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '1191.94867392568', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27056.99341852', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


