# 20230712 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=16960
self.closeSec=1689121199, self.tradeDate='20230712', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30586.5, self.close=30563.2, self.high=30586.6, self.low=30563.2, self.vol=492.591, self.amt=15060234.0709 
127.0.0.1 - - [12/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-12 08:20:07,528:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230712   075500    075959  ...         0.0        0.0       0
5856  20230712   080000    080459  ...         0.0        0.0       0
5857  20230712   080500    080959  ...         0.0        0.0       0
5858  20230712   081000    081459  ...         0.0        0.0       0
5859  20230712   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-12 08:20:07,549:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689121199, self.tradeDate='20230712', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30586.5, self.close=30563.2, self.high=30586.6, self.low=30563.2, self.vol=492.591, self.amt=15060234.0709, ukdf['pct'].iloc[-1]=-0.000762 , ukdf['amount'].iloc[-1]=15060234.0709, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-51485.8146', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30562', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [12/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=16961
self.closeSec=1689121499, self.tradeDate='20230712', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30554.4, self.close=30543.1, self.high=30566.3, self.low=30540.6, self.vol=1019.825, self.amt=31158460.2755 
2023-07-12 08:25:00,826:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230712   080000    080459  ...         0.0        0.0       0
5857  20230712   080500    080959  ...         0.0        0.0       0
5858  20230712   081000    081459  ...         0.0        0.0       0
5859  20230712   081500    081959  ...         0.0        0.0       0
5860  20230712   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-12 08:25:00,826:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689121499, self.tradeDate='20230712', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30554.4, self.close=30543.1, self.high=30566.3, self.low=30540.6, self.vol=1019.825, self.amt=31158460.2755, ukdf['pct'].iloc[-1]=-0.000658 , ukdf['amount'].iloc[-1]=31158460.2755, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-51222.6132', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30543.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1689121199, self.tradeDate='20230712', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30586.5, self.close=30563.2, self.high=30586.6, self.low=30563.2 
127.0.0.1 - - [12/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-12 08:20:04,988:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689121199, self.tradeDate='20230712', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30586.5, self.close=30563.2, self.high=30586.6, self.low=30563.2   
2023-07-12 08:20:06,658:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230712   075500    075959  1689119999  ...  30603.5  0.000042   1535    5
1536  20230712   080000    080459  1689120299  ...  30596.4 -0.000317   1536    0
1537  20230712   080500    080959  1689120599  ...  30587.6 -0.000278   1537    1
1538  20230712   081000    081459  1689120899  ...  30575.0 -0.000118   1538    2
1539  20230712   081500    081959  1689121199  ...  30563.2 -0.000762   1539    3

[5 rows x 11 columns]
2023-07-12 08:20:06,668:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=159, self.factor=0.4357061470974487, self.count=16963 

self.closeSec=1689121499, self.tradeDate='20230712', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30554.4, self.close=30543.1, self.high=30566.3, self.low=30540.6 
127.0.0.1 - - [12/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-07-12 08:25:00,761:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689121499, self.tradeDate='20230712', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30554.4, self.close=30543.1, self.high=30566.3, self.low=30540.6   
2023-07-12 08:25:00,789:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230712   080000    080459  1689120299  ...  30596.4 -0.000317   1536    0
1537  20230712   080500    080959  1689120599  ...  30587.6 -0.000278   1537    1
1538  20230712   081000    081459  1689120899  ...  30575.0 -0.000118   1538    2
1539  20230712   081500    081959  1689121199  ...  30563.2 -0.000762   1539    3
1540  20230712   082000    082459  1689121499  ...  30540.6 -0.000658   1540    4

[5 rows x 11 columns]
2023-07-12 08:25:00,789:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-12 08:00:17,325:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230712    052959  30561.0  ...  49.166667  0.525122  0.513723
5771  20230712    055959  30512.9  ...  49.583333  0.534462  0.509956
5772  20230712    062959  30556.5  ...  49.166667  0.529430  0.508967
5773  20230712    065959  30535.8  ...  49.583333  0.537221  0.503616
5774  20230712    072959  30571.9  ...  50.000000  0.549472  0.491495

[5 rows x 33 columns]
0.5785582255083179
acc is : 0.5785582255083179
2023-07-12 08:00:17,425:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.503442  0.496558       1  ...  1.015415   1.0    0.0  1.000707
537     0  0.523038  0.476962       0  ...  1.014730   1.0    0.0  1.000033
538     0  0.502581  0.497419       1  ...  1.015930   1.0    0.0  1.001215
539     0  0.517047  0.482953       1  ...  1.017860   1.0    0.0  1.003118
540     0  0.530367  0.469633       0  ...  1.017143   1.0    0.0  1.002410

[5 rows x 10 columns]
2023-07-12 08:00:17,447:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.504335  0.495665       1  ...  1.008128   1.0    0.0  1.016788
46     0  0.523882  0.476118       0  ...  1.020353   1.0    0.0  1.013812
47     0  0.502858  0.497142       1  ...  1.020935   1.0    0.0  1.006135
48     0  0.517047  0.482953       1  ...  1.017860   1.0    0.0  1.003118
49     0  0.530367  0.469633       0  ...  1.017143   1.0    0.0  1.002410

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.383', 'enterprice': '30486.7', 'countrevence': '0', 'unrealprofit': '3201.4879', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30618', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230712   075000    075959  1689119999  30592.1  30608.4  0.000536
2023-07-12 08:00:02,101:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [12/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8480 

self.closeSec=1689120599, self.tradeDate='20230712', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30608.3', self.close='30590.1'
2023-07-12 08:10:01,156:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689120599, self.tradeDate='20230712', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30608.3', self.close='30590.1'
2023-07-12 08:10:01,168:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230712   072000    072959  1689118199  30605.5    30630  0.000801
621  20230712   073000    073959  1689118799    30630  30592.7 -0.001218
622  20230712   074000    074959  1689119399  30592.7    30592 -0.000023
623  20230712   075000    075959  1689119999  30592.1  30608.4  0.000536
624  20230712   080000    080959  1689120599  30608.3  30590.1 -0.000598
2023-07-12 08:10:01,168:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8481 

self.closeSec=1689121199, self.tradeDate='20230712', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30590', self.close='30563.2'
127.0.0.1 - - [12/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-12 08:20:07,598:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689121199, self.tradeDate='20230712', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30590', self.close='30563.2'
2023-07-12 08:20:08,558:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230712   073000    073959  1689118799    30630  30592.7 -0.001218
622  20230712   074000    074959  1689119399  30592.7    30592 -0.000023
623  20230712   075000    075959  1689119999  30592.1  30608.4  0.000536
624  20230712   080000    080959  1689120599  30608.3  30590.1 -0.000598
625  20230712   081000    081959  1689121199    30590  30563.2 -0.000879
2023-07-12 08:20:08,558:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230712   075000    075959  1689119999  30592.1  30608.4
2023-07-12 08:00:02,133:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [12/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8483 

self.closeSec=1689120599, self.tradeDate='20230712', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30608.3', self.close='30590.1'
2023-07-12 08:10:01,154:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689120599, self.tradeDate='20230712', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30608.3', self.close='30590.1'
2023-07-12 08:10:01,188:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230712   072000    072959  1689118199  30605.5    30630
17469  20230712   073000    073959  1689118799    30630  30592.7
17470  20230712   074000    074959  1689119399  30592.7    30592
17471  20230712   075000    075959  1689119999  30592.1  30608.4
17472  20230712   080000    080959  1689120599  30608.3  30590.1
2023-07-12 08:10:01,188:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8484 

self.closeSec=1689121199, self.tradeDate='20230712', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30590', self.close='30563.2'
127.0.0.1 - - [12/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-12 08:20:09,500:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689121199, self.tradeDate='20230712', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30590', self.close='30563.2'
2023-07-12 08:20:09,721:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230712   073000    073959  1689118799    30630  30592.7
17470  20230712   074000    074959  1689119399  30592.7    30592
17471  20230712   075000    075959  1689119999  30592.1  30608.4
17472  20230712   080000    080959  1689120599  30608.3  30590.1
17473  20230712   081000    081959  1689121199    30590  30563.2
2023-07-12 08:20:09,722:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230712   075000    075959  1689119999  30592.1  30608.4
2023-07-12 08:00:02,124:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8483 

self.closeSec=1689120599, self.tradeDate='20230712', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30608.3', self.close='30590.1'
2023-07-12 08:10:01,167:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689120599, self.tradeDate='20230712', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30608.3', self.close='30590.1'
127.0.0.1 - - [12/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-07-12 08:10:01,174:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230712   072000    072959  1689118199  30605.5    30630
12141  20230712   073000    073959  1689118799    30630  30592.7
12142  20230712   074000    074959  1689119399  30592.7    30592
12143  20230712   075000    075959  1689119999  30592.1  30608.4
12144  20230712   080000    080959  1689120599  30608.3  30590.1
2023-07-12 08:10:01,175:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8484 

self.closeSec=1689121199, self.tradeDate='20230712', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30590', self.close='30563.2'
127.0.0.1 - - [12/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-12 08:20:09,281:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689121199, self.tradeDate='20230712', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30590', self.close='30563.2'
2023-07-12 08:20:09,571:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230712   073000    073959  1689118799    30630  30592.7
12142  20230712   074000    074959  1689119399  30592.7    30592
12143  20230712   075000    075959  1689119999  30592.1  30608.4
12144  20230712   080000    080959  1689120599  30608.3  30590.1
12145  20230712   081000    081959  1689121199    30590  30563.2
2023-07-12 08:20:09,578:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=16960
self.closeSec=1689121199, self.tradeDate='20230712', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30586.5, self.close=30563.2, self.high=30586.6, self.low=30563.2, self.vol=492.591, self.amt=15060234.0709 
127.0.0.1 - - [12/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-12 08:20:07,467:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230712   075500    075959  ...         0.0        0.0       0
5856  20230712   080000    080459  ...         0.0        0.0       0
5857  20230712   080500    080959  ...         0.0        0.0       0
5858  20230712   081000    081459  ...         0.0        0.0       0
5859  20230712   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-12 08:20:07,497:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689121199, self.tradeDate='20230712', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30586.5, self.close=30563.2, self.high=30586.6, self.low=30563.2, self.vol=492.591, self.amt=15060234.0709, ukdf['pct'].iloc[-1]=-0.000762 , ukdf['amount'].iloc[-1]=15060234.0709, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '138093.9521', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30562.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [12/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=16961
self.closeSec=1689121499, self.tradeDate='20230712', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30554.4, self.close=30543.1, self.high=30566.3, self.low=30540.6, self.vol=1019.825, self.amt=31158460.2755 
2023-07-12 08:25:00,811:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230712   080000    080459  ...         0.0        0.0       0
5857  20230712   080500    080959  ...         0.0        0.0       0
5858  20230712   081000    081459  ...         0.0        0.0       0
5859  20230712   081500    081959  ...         0.0        0.0       0
5860  20230712   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-12 08:25:00,812:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689121499, self.tradeDate='20230712', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30554.4, self.close=30543.1, self.high=30566.3, self.low=30540.6, self.vol=1019.825, self.amt=31158460.2755, ukdf['pct'].iloc[-1]=-0.000658 , ukdf['amount'].iloc[-1]=31158460.2755, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '137388.2731', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30543.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230711   200000    235959  1689091199  ...    719  0.168446 -0.433802     NaN
720  20230712   000000    035959  1689105599  ...    720  0.258325 -0.037801     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.015', 'enterprice': '30303.5', 'countrevence': '0', 'unrealprofit': '-14658.6475', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30580', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [12/Jul/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1604933.5124475, self.flagDict['side']='sell', self.tradeCount=10, self.count=353
self.closeSec=1689119999, self.tradeDate='20230712', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=30565.5, self.close=30608.4, self.high=30640.0, self.low=30492.8, self.vol=26843.465, self.amt=820493886.005 
2023-07-12 08:00:01,725:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1689119999, self.tradeDate='20230712', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=30565.5, self.close=30608.4, self.high=30640.0, self.low=30492.8, self.vol=26843.465, self.amt=820493886.005 
2023-07-12 08:00:01,789:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230711   120000    155959  ...  37038.603  1.130975e+09  0.002216
718  20230711   160000    195959  ...  38953.602  1.185001e+09 -0.004494
719  20230711   200000    235959  ...  98194.832  2.997190e+09  0.006390
720  20230712   000000    035959  ...  52691.726  1.609284e+09 -0.000654
721  20230712   040000    075959  ...  26843.465  8.204939e+08  0.001404

[5 rows x 11 columns]
2023-07-12 08:00:03,176:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230711   120000    155959  1689062399  ...    717  0.112018 -0.687766    -1.0
718  20230711   160000    195959  1689076799  ...    718  0.144841 -0.538874     NaN
719  20230711   200000    235959  1689091199  ...    719  0.168446 -0.433802     NaN
720  20230712   000000    035959  1689105599  ...    720  0.258325 -0.037801     NaN
721  20230712   040000    075959  1689119999  ...    721  0.249948 -0.076812     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.015', 'enterprice': '30303.5', 'countrevence': '0', 'unrealprofit': '-16169.89142691945', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30608.50596863', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


