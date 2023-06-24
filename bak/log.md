# 20230624 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=11776
self.closeSec=1687565999, self.tradeDate='20230624', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30640.0, self.close=30601.2, self.high=30640.0, self.low=30589.5, self.vol=1010.105, self.amt=30920851.9791 
127.0.0.1 - - [24/Jun/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-06-24 08:20:07,709:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230624   075500    075959  ...         0.0        0.0       0
5856  20230624   080000    080459  ...         0.0        0.0       0
5857  20230624   080500    080959  ...         0.0        0.0       0
5858  20230624   081000    081459  ...         0.0        0.0       0
5859  20230624   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-24 08:20:07,730:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687565999, self.tradeDate='20230624', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30640.0, self.close=30601.2, self.high=30640.0, self.low=30589.5, self.vol=1010.105, self.amt=30920851.9791, ukdf['pct'].iloc[-1]=-0.001266 , ukdf['amount'].iloc[-1]=30920851.9791, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-52033.1064', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30601.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=11777
self.closeSec=1687566299, self.tradeDate='20230624', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30601.2, self.close=30601.4, self.high=30619.5, self.low=30582.8, self.vol=543.227, self.amt=16624324.9847 
127.0.0.1 - - [24/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-06-24 08:25:00,816:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230624   080000    080459  ...         0.0        0.0       0
5857  20230624   080500    080959  ...         0.0        0.0       0
5858  20230624   081000    081459  ...         0.0        0.0       0
5859  20230624   081500    081959  ...         0.0        0.0       0
5860  20230624   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-24 08:25:00,818:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687566299, self.tradeDate='20230624', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30601.2, self.close=30601.4, self.high=30619.5, self.low=30582.8, self.vol=543.227, self.amt=16624324.9847, ukdf['pct'].iloc[-1]=7e-06 , ukdf['amount'].iloc[-1]=16624324.9847, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-52015.0026', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30600', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1687565999, self.tradeDate='20230624', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30640.0, self.close=30601.2, self.high=30640.0, self.low=30589.5 
127.0.0.1 - - [24/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-24 08:20:05,099:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687565999, self.tradeDate='20230624', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30640.0, self.close=30601.2, self.high=30640.0, self.low=30589.5   
2023-06-24 08:20:06,679:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230624   075500    075959  1687564799  ...  30603.2  0.002189   1535    5
1536  20230624   080000    080459  1687565099  ...  30617.5 -0.001695   1536    0
1537  20230624   080500    080959  1687565399  ...  30595.2  0.000973   1537    1
1538  20230624   081000    081459  1687565699  ...  30626.0 -0.000418   1538    2
1539  20230624   081500    081959  1687565999  ...  30589.5 -0.001266   1539    3

[5 rows x 11 columns]
2023-06-24 08:20:06,689:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [24/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=341, self.factor=0.38381732970801075, self.count=11779 

self.closeSec=1687566299, self.tradeDate='20230624', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30601.2, self.close=30601.4, self.high=30619.5, self.low=30582.8 
2023-06-24 08:25:00,783:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687566299, self.tradeDate='20230624', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30601.2, self.close=30601.4, self.high=30619.5, self.low=30582.8   
2023-06-24 08:25:00,811:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230624   080000    080459  1687565099  ...  30617.5 -0.001695   1536    0
1537  20230624   080500    080959  1687565399  ...  30595.2  0.000973   1537    1
1538  20230624   081000    081459  1687565699  ...  30626.0 -0.000418   1538    2
1539  20230624   081500    081959  1687565999  ...  30589.5 -0.001266   1539    3
1540  20230624   082000    082459  1687566299  ...  30582.8  0.000007   1540    4

[5 rows x 11 columns]
2023-06-24 08:25:00,812:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-24 08:00:17,899:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230624    052959  30892.5  ...  54.583333  0.591782  0.334034
5771  20230624    055959  30868.5  ...  54.583333  0.564917  0.344958
5772  20230624    062959  30649.6  ...  54.166667  0.551034  0.362350
5773  20230624    065959  30530.7  ...  54.583333  0.560426  0.374358
5774  20230624    072959  30632.0  ...  54.583333  0.552757  0.388311

[5 rows x 33 columns]
0.5656192236598891
acc is : 0.5656192236598891
2023-06-24 08:00:17,985:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.477338  0.522662       0  ...  1.144686  -1.0    0.0  1.190271
537     1  0.438954  0.561046       0  ...  1.149130  -1.0    0.0  1.185650
538     1  0.441664  0.558336       1  ...  1.145314  -1.0    0.0  1.189588
539     1  0.480142  0.519858       0  ...  1.147778  -1.0    0.0  1.187028
540     1  0.450842  0.549158       1  ...  1.143688  -1.0    0.0  1.191258

[5 rows x 10 columns]
2023-06-24 08:00:17,997:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.477358  0.522642       0  ...  1.144686  -1.0    0.0  1.187541
46     1  0.439545  0.560455       0  ...  1.186803  -1.0    0.0  1.179694
47     1  0.442167  0.557833       1  ...  1.182862  -1.0    0.0  1.186638
48     1  0.481326  0.518674       0  ...  1.185406  -1.0    0.0  1.187028
49     1  0.450842  0.549158       1  ...  1.143688  -1.0    0.0  1.191258

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.697', 'enterprice': '30938.2', 'countrevence': '0', 'unrealprofit': '7079.9795156112', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30673.0024304', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230624   075000    075959  1687564799  30592.4  30673.4  0.002648
2023-06-24 08:00:02,155:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5888 

self.closeSec=1687565399, self.tradeDate='20230624', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30673.5', self.close='30652.8'
2023-06-24 08:10:01,111:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687565399, self.tradeDate='20230624', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30673.5', self.close='30652.8'
127.0.0.1 - - [24/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-06-24 08:10:01,132:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230624   072000    072959  1687562999  30604.5  30566.1 -0.001255
621  20230624   073000    073959  1687563599    30566  30611.1  0.001472
622  20230624   074000    074959  1687564199  30611.1  30592.4 -0.000611
623  20230624   075000    075959  1687564799  30592.4  30673.4  0.002648
624  20230624   080000    080959  1687565399  30673.5  30652.8 -0.000672
2023-06-24 08:10:01,133:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5889 

self.closeSec=1687565999, self.tradeDate='20230624', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30652.8', self.close='30601.2'
127.0.0.1 - - [24/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-24 08:20:07,439:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687565999, self.tradeDate='20230624', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30652.8', self.close='30601.2'
2023-06-24 08:20:08,310:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230624   073000    073959  1687563599    30566  30611.1  0.001472
622  20230624   074000    074959  1687564199  30611.1  30592.4 -0.000611
623  20230624   075000    075959  1687564799  30592.4  30673.4  0.002648
624  20230624   080000    080959  1687565399  30673.5  30652.8 -0.000672
625  20230624   081000    081959  1687565999  30652.8  30601.2 -0.001683
2023-06-24 08:20:08,319:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230624   075000    075959  1687564799  30592.4  30673.4
2023-06-24 08:00:02,095:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5891 

self.closeSec=1687565399, self.tradeDate='20230624', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30673.5', self.close='30652.8'
2023-06-24 08:10:01,115:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687565399, self.tradeDate='20230624', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30673.5', self.close='30652.8'
127.0.0.1 - - [24/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-06-24 08:10:01,148:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230624   072000    072959  1687562999  30604.5  30566.1
17469  20230624   073000    073959  1687563599    30566  30611.1
17470  20230624   074000    074959  1687564199  30611.1  30592.4
17471  20230624   075000    075959  1687564799  30592.4  30673.4
17472  20230624   080000    080959  1687565399  30673.5  30652.8
2023-06-24 08:10:01,148:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5892 

self.closeSec=1687565999, self.tradeDate='20230624', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30652.8', self.close='30601.2'
127.0.0.1 - - [24/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-24 08:20:09,606:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687565999, self.tradeDate='20230624', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30652.8', self.close='30601.2'
2023-06-24 08:20:09,755:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230624   073000    073959  1687563599    30566  30611.1
17470  20230624   074000    074959  1687564199  30611.1  30592.4
17471  20230624   075000    075959  1687564799  30592.4  30673.4
17472  20230624   080000    080959  1687565399  30673.5  30652.8
17473  20230624   081000    081959  1687565999  30652.8  30601.2
2023-06-24 08:20:09,755:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230624   075000    075959  1687564799  30592.4  30673.4
2023-06-24 08:00:02,163:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [24/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5891 

self.closeSec=1687565399, self.tradeDate='20230624', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30673.5', self.close='30652.8'
2023-06-24 08:10:01,105:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687565399, self.tradeDate='20230624', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30673.5', self.close='30652.8'
2023-06-24 08:10:01,145:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230624   072000    072959  1687562999  30604.5  30566.1
12141  20230624   073000    073959  1687563599    30566  30611.1
12142  20230624   074000    074959  1687564199  30611.1  30592.4
12143  20230624   075000    075959  1687564799  30592.4  30673.4
12144  20230624   080000    080959  1687565399  30673.5  30652.8
2023-06-24 08:10:01,146:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5892 

self.closeSec=1687565999, self.tradeDate='20230624', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30652.8', self.close='30601.2'
127.0.0.1 - - [24/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-24 08:20:09,111:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687565999, self.tradeDate='20230624', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30652.8', self.close='30601.2'
2023-06-24 08:20:09,439:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230624   073000    073959  1687563599    30566  30611.1
12142  20230624   074000    074959  1687564199  30611.1  30592.4
12143  20230624   075000    075959  1687564799  30592.4  30673.4
12144  20230624   080000    080959  1687565399  30673.5  30652.8
12145  20230624   081000    081959  1687565999  30652.8  30601.2
2023-06-24 08:20:09,440:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=11776
self.closeSec=1687565999, self.tradeDate='20230624', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30640.0, self.close=30601.2, self.high=30640.0, self.low=30589.5, self.vol=1010.105, self.amt=30920851.9791 
127.0.0.1 - - [24/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-24 08:20:07,720:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230624   075500    075959  ...         0.0        0.0       0
5856  20230624   080000    080459  ...         0.0        0.0       0
5857  20230624   080500    080959  ...         0.0        0.0       0
5858  20230624   081000    081459  ...         0.0        0.0       0
5859  20230624   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-24 08:20:07,750:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687565999, self.tradeDate='20230624', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30640.0, self.close=30601.2, self.high=30640.0, self.low=30589.5, self.vol=1010.105, self.amt=30920851.9791, ukdf['pct'].iloc[-1]=-0.001266 , ukdf['amount'].iloc[-1]=30920851.9791, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '139546.1652', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30601.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [24/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=11777
self.closeSec=1687566299, self.tradeDate='20230624', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30601.2, self.close=30601.4, self.high=30619.5, self.low=30582.8, self.vol=543.227, self.amt=16624324.9847 
2023-06-24 08:25:00,816:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230624   080000    080459  ...         0.0        0.0       0
5857  20230624   080500    080959  ...         0.0        0.0       0
5858  20230624   081000    081459  ...         0.0        0.0       0
5859  20230624   081500    081959  ...         0.0        0.0       0
5860  20230624   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-24 08:25:00,816:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687566299, self.tradeDate='20230624', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30601.2, self.close=30601.4, self.high=30619.5, self.low=30582.8, self.vol=543.227, self.amt=16624324.9847, ukdf['pct'].iloc[-1]=7e-06 , ukdf['amount'].iloc[-1]=16624324.9847, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '139501.596', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30600', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230623   200000    235959  1687535999  ...    719  1.006118  1.272443     1.0
720  20230624   000000    035959  1687550399  ...    720  0.997185  1.221229     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.344', 'enterprice': '27977.7', 'countrevence': '0', 'unrealprofit': '154350.864', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30871.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1490949.9863712, self.flagDict['side']='buy', self.tradeCount=7, self.count=245
self.closeSec=1687564799, self.tradeDate='20230624', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=30873.7, self.close=30673.4, self.high=30943.4, self.low=30441.1, self.vol=66965.089, self.amt=2054059002.03698 
127.0.0.1 - - [24/Jun/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-06-24 08:00:01,682:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1687564799, self.tradeDate='20230624', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=30873.7, self.close=30673.4, self.high=30943.4, self.low=30441.1, self.vol=66965.089, self.amt=2054059002.03698 
2023-06-24 08:00:01,707:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230623   120000    155959  ...   29527.682  8.858129e+08 -0.002513
718  20230623   160000    195959  ...   57808.102  1.737403e+09  0.006626
719  20230623   200000    235959  ...  269745.999  8.259525e+09  0.036939
720  20230624   000000    035959  ...  228949.781  7.104221e+09 -0.011665
721  20230624   040000    075959  ...   66965.089  2.054059e+09 -0.006488

[5 rows x 11 columns]
2023-06-24 08:00:03,171:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230623   120000    155959  1687507199  ...    717  1.037418  1.420951     1.0
718  20230623   160000    195959  1687521599  ...    718  0.997270  1.273535     1.0
719  20230623   200000    235959  1687535999  ...    719  1.006118  1.272443     1.0
720  20230624   000000    035959  1687550399  ...    720  0.997185  1.221229     1.0
721  20230624   040000    075959  1687564799  ...    721  1.016542  1.251985     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.344', 'enterprice': '27977.7', 'countrevence': '0', 'unrealprofit': '144168.08218740064', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30680.31101881', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


