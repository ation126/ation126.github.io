# 20230701 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=13792
self.closeSec=1688170799, self.tradeDate='20230701', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30438.7, self.close=30471.4, self.high=30478.9, self.low=30436.5, self.vol=786.604, self.amt=23959456.7746 
127.0.0.1 - - [01/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-01 08:20:08,185:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230701   075500    075959  ...         0.0        0.0       0
5856  20230701   080000    080459  ...         0.0        0.0       0
5857  20230701   080500    080959  ...         0.0        0.0       0
5858  20230701   081000    081459  ...         0.0        0.0       0
5859  20230701   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-01 08:20:08,215:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688170799, self.tradeDate='20230701', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30438.7, self.close=30471.4, self.high=30478.9, self.low=30436.5, self.vol=786.604, self.amt=23959456.7746, ukdf['pct'].iloc[-1]=0.001216 , ukdf['amount'].iloc[-1]=23959456.7746, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-50212.5834661374', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30470.5716549', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [01/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=13793
self.closeSec=1688171099, self.tradeDate='20230701', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30471.3, self.close=30480.8, self.high=30488.0, self.low=30452.8, self.vol=423.075, self.amt=12893314.2895 
2023-07-01 08:25:00,779:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230701   080000    080459  ...         0.0        0.0       0
5857  20230701   080500    080959  ...         0.0        0.0       0
5858  20230701   081000    081459  ...         0.0        0.0       0
5859  20230701   081500    081959  ...         0.0        0.0       0
5860  20230701   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-01 08:25:00,780:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688171099, self.tradeDate='20230701', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30471.3, self.close=30480.8, self.high=30488.0, self.low=30452.8, self.vol=423.075, self.amt=12893314.2895, ukdf['pct'].iloc[-1]=0.000308 , ukdf['amount'].iloc[-1]=12893314.2895, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-50408.3815841001', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30484.63155135', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1688170799, self.tradeDate='20230701', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30438.7, self.close=30471.4, self.high=30478.9, self.low=30436.5 
127.0.0.1 - - [01/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-01 08:20:05,420:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688170799, self.tradeDate='20230701', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30438.7, self.close=30471.4, self.high=30478.9, self.low=30436.5   
2023-07-01 08:20:07,075:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230701   075500    075959  1688169599  ...  30456.1 -0.000692   1535    5
1536  20230701   080000    080459  1688169899  ...  30446.3  0.000729   1536    0
1537  20230701   080500    080959  1688170199  ...  30467.7  0.000512   1537    1
1538  20230701   081000    081459  1688170499  ...  30405.6 -0.002085   1538    2
1539  20230701   081500    081959  1688170799  ...  30436.5  0.001216   1539    3

[5 rows x 11 columns]
2023-07-01 08:20:07,094:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [01/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=30, self.factor=0.49066307147428256, self.count=13795 

self.closeSec=1688171099, self.tradeDate='20230701', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30471.3, self.close=30480.8, self.high=30488.0, self.low=30452.8 
2023-07-01 08:25:00,721:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688171099, self.tradeDate='20230701', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30471.3, self.close=30480.8, self.high=30488.0, self.low=30452.8   
2023-07-01 08:25:00,763:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230701   080000    080459  1688169899  ...  30446.3  0.000729   1536    0
1537  20230701   080500    080959  1688170199  ...  30467.7  0.000512   1537    1
1538  20230701   081000    081459  1688170499  ...  30405.6 -0.002085   1538    2
1539  20230701   081500    081959  1688170799  ...  30436.5  0.001216   1539    3
1540  20230701   082000    082459  1688171099  ...  30452.8  0.000308   1540    4

[5 rows x 11 columns]
2023-07-01 08:25:00,763:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-01 08:00:17,865:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230701    052959  30391.3  ...  52.083333  0.492032  0.495911
5771  20230701    055959  30422.4  ...  52.500000  0.498655  0.493491
5772  20230701    062959  30472.8  ...  52.500000  0.502766  0.490077
5773  20230701    065959  30503.9  ...  52.500000  0.498051  0.488197
5774  20230701    072959  30468.6  ...  52.916667  0.501779  0.485421

[5 rows x 33 columns]
0.5046210720887245
acc is : 0.5046210720887245
2023-07-01 08:00:17,952:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.531156  0.468844       1  ...  1.036093   1.0    0.0  1.145642
537     0  0.535080  0.464920       1  ...  1.037154   1.0    0.0  1.146815
538     0  0.538394  0.461606       0  ...  1.035954   1.0    0.0  1.145488
539     0  0.517368  0.482632       1  ...  1.036892   1.0    0.0  1.146525
540     0  0.534799  0.465201       0  ...  1.035668   1.0    0.0  1.145172

[5 rows x 10 columns]
2023-07-01 08:00:17,963:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.530744  0.469256       1  ...  1.036093   1.0    0.0  1.152911
46     0  0.534714  0.465286       1  ...  1.037154   1.0    0.0  1.153991
47     0  0.537908  0.462092       0  ...  1.035954   1.0    0.0  1.150206
48     0  0.517368  0.482632       1  ...  1.036892   1.0    0.0  1.146525
49     0  0.534799  0.465201       0  ...  1.035668   1.0    0.0  1.145172

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.53', 'enterprice': '30560', 'countrevence': '0', 'unrealprofit': '-2475.3761350776', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30463.04049608', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230701   075000    075959  1688169599  30463.9  30460.2 -0.000121
2023-07-01 08:00:02,120:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6896 

self.closeSec=1688170199, self.tradeDate='20230701', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30460.2', self.close='30498'
2023-07-01 08:10:01,161:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688170199, self.tradeDate='20230701', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30460.2', self.close='30498'
127.0.0.1 - - [01/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-07-01 08:10:01,193:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230701   072000    072959  1688167799  30469.5  30496.2  0.000873
621  20230701   073000    073959  1688168399  30495.4  30474.5 -0.000712
622  20230701   074000    074959  1688168999  30474.5  30463.9 -0.000348
623  20230701   075000    075959  1688169599  30463.9  30460.2 -0.000121
624  20230701   080000    080959  1688170199  30460.2    30498  0.001241
2023-07-01 08:10:01,194:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6897 

self.closeSec=1688170799, self.tradeDate='20230701', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30498', self.close='30471.3'
127.0.0.1 - - [01/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-01 08:20:07,915:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688170799, self.tradeDate='20230701', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30498', self.close='30471.3'
2023-07-01 08:20:08,795:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230701   073000    073959  1688168399  30495.4  30474.5 -0.000712
622  20230701   074000    074959  1688168999  30474.5  30463.9 -0.000348
623  20230701   075000    075959  1688169599  30463.9  30460.2 -0.000121
624  20230701   080000    080959  1688170199  30460.2    30498  0.001241
625  20230701   081000    081959  1688170799    30498  30471.3 -0.000875
2023-07-01 08:20:08,806:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230701   075000    075959  1688169599  30463.9  30460.2
2023-07-01 08:00:02,117:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [01/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6899 

self.closeSec=1688170199, self.tradeDate='20230701', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30460.2', self.close='30498'
2023-07-01 08:10:01,174:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688170199, self.tradeDate='20230701', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30460.2', self.close='30498'
2023-07-01 08:10:01,197:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230701   072000    072959  1688167799  30469.5  30496.2
17469  20230701   073000    073959  1688168399  30495.4  30474.5
17470  20230701   074000    074959  1688168999  30474.5  30463.9
17471  20230701   075000    075959  1688169599  30463.9  30460.2
17472  20230701   080000    080959  1688170199  30460.2    30498
2023-07-01 08:10:01,197:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6900 

self.closeSec=1688170799, self.tradeDate='20230701', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30498', self.close='30471.3'
127.0.0.1 - - [01/Jul/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-07-01 08:20:10,248:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688170799, self.tradeDate='20230701', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30498', self.close='30471.3'
2023-07-01 08:20:10,434:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230701   073000    073959  1688168399  30495.4  30474.5
17470  20230701   074000    074959  1688168999  30474.5  30463.9
17471  20230701   075000    075959  1688169599  30463.9  30460.2
17472  20230701   080000    080959  1688170199  30460.2    30498
17473  20230701   081000    081959  1688170799    30498  30471.3
2023-07-01 08:20:10,435:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230701   075000    075959  1688169599  30463.9  30460.2
2023-07-01 08:00:02,106:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6899 

self.closeSec=1688170199, self.tradeDate='20230701', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30460.2', self.close='30498'
2023-07-01 08:10:01,182:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688170199, self.tradeDate='20230701', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30460.2', self.close='30498'
127.0.0.1 - - [01/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-07-01 08:10:01,196:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230701   072000    072959  1688167799  30469.5  30496.2
12141  20230701   073000    073959  1688168399  30495.4  30474.5
12142  20230701   074000    074959  1688168999  30474.5  30463.9
12143  20230701   075000    075959  1688169599  30463.9  30460.2
12144  20230701   080000    080959  1688170199  30460.2    30498
2023-07-01 08:10:01,200:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6900 

self.closeSec=1688170799, self.tradeDate='20230701', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30498', self.close='30471.3'
127.0.0.1 - - [01/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-01 08:20:09,708:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688170799, self.tradeDate='20230701', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30498', self.close='30471.3'
2023-07-01 08:20:10,054:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230701   073000    073959  1688168399  30495.4  30474.5
12142  20230701   074000    074959  1688168999  30474.5  30463.9
12143  20230701   075000    075959  1688169599  30463.9  30460.2
12144  20230701   080000    080959  1688170199  30460.2    30498
12145  20230701   081000    081959  1688170799    30498  30471.3
2023-07-01 08:20:10,065:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=13792
self.closeSec=1688170799, self.tradeDate='20230701', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30438.7, self.close=30471.4, self.high=30478.9, self.low=30436.5, self.vol=786.604, self.amt=23959456.7746 
127.0.0.1 - - [01/Jul/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-07-01 08:20:08,195:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230701   075500    075959  ...         0.0        0.0       0
5856  20230701   080000    080459  ...         0.0        0.0       0
5857  20230701   080500    080959  ...         0.0        0.0       0
5858  20230701   081000    081459  ...         0.0        0.0       0
5859  20230701   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-01 08:20:08,234:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688170799, self.tradeDate='20230701', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30438.7, self.close=30471.4, self.high=30478.9, self.low=30436.5, self.vol=786.604, self.amt=23959456.7746, ukdf['pct'].iloc[-1]=0.001216 , ukdf['amount'].iloc[-1]=23959456.7746, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '134694.4978346409', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30470.5716549', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [01/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=13793
self.closeSec=1688171099, self.tradeDate='20230701', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30471.3, self.close=30480.8, self.high=30488.0, self.low=30452.8, self.vol=423.075, self.amt=12893314.2895 
2023-07-01 08:25:00,772:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230701   080000    080459  ...         0.0        0.0       0
5857  20230701   080500    080959  ...         0.0        0.0       0
5858  20230701   081000    081459  ...         0.0        0.0       0
5859  20230701   081500    081959  ...         0.0        0.0       0
5860  20230701   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-01 08:25:00,773:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688171099, self.tradeDate='20230701', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30471.3, self.close=30480.8, self.high=30488.0, self.low=30452.8, self.vol=423.075, self.amt=12893314.2895, ukdf['pct'].iloc[-1]=0.000308 , ukdf['amount'].iloc[-1]=12893314.2895, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '135216.69644869035', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30484.63155135', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230630   200000    235959  1688140799  ...    719  0.035999 -1.527750    -1.0
720  20230701   000000    035959  1688155199  ...    720  0.026872 -1.519883    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '17968.41105900132', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30369.67907451', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [01/Jul/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1634064.775524, self.flagDict['side']='sell', self.tradeCount=8, self.count=287
self.closeSec=1688169599, self.tradeDate='20230701', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=30360.2, self.close=30460.2, self.high=30537.3, self.low=30324.4, self.vol=35577.773, self.amt=1083165137.70996 
2023-07-01 08:00:01,643:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1688169599, self.tradeDate='20230701', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=30360.2, self.close=30460.2, self.high=30537.3, self.low=30324.4, self.vol=35577.773, self.amt=1083165137.70996 
2023-07-01 08:00:01,682:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230630   120000    155959  ...  144771.236  4.472121e+09  0.000807
718  20230630   160000    195959  ...   52591.102  1.620298e+09  0.004506
719  20230630   200000    235959  ...  346709.184  1.049024e+10 -0.027371
720  20230701   000000    035959  ...  155211.239  4.717005e+09  0.010259
721  20230701   040000    075959  ...   35577.773  1.083165e+09  0.003290

[5 rows x 11 columns]
2023-07-01 08:00:03,158:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230630   120000    155959  1688111999  ...    717  0.725928  0.394365     NaN
718  20230630   160000    195959  1688126399  ...    718  0.635276  0.131462     NaN
719  20230630   200000    235959  1688140799  ...    719  0.035999 -1.527750    -1.0
720  20230701   000000    035959  1688155199  ...    720  0.026872 -1.519883    -1.0
721  20230701   040000    075959  1688169599  ...    721  0.019349 -1.508678    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '13045.69699433868', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30462.09317049', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


