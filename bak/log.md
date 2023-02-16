# 20230216 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [16/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=23356
self.closeSec=1676535599, self.tradeDate='20230216', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=24629.4, self.close=24643.8, self.high=24655.3, self.low=24626.3, self.vol=1681.295, self.amt=41430849.2088 
2023-02-16 16:20:01,837:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230216   155500    155959  ...         0.0        0.0       0
5952  20230216   160000    160459  ...         0.0        0.0       0
5953  20230216   160500    160959  ...         0.0        0.0       0
5954  20230216   161000    161459  ...         0.0        0.0       0
5955  20230216   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-16 16:20:01,840:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676535599, self.tradeDate='20230216', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=24629.4, self.close=24643.8, self.high=24655.3, self.low=24626.3, self.vol=1681.295, self.amt=41430849.2088, ukdf['pct'].iloc[-1]=0.000585 , ukdf['amount'].iloc[-1]=41430849.2088, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-488298.152', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24643.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=23357
self.closeSec=1676535899, self.tradeDate='20230216', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=24643.8, self.close=24645.9, self.high=24648.2, self.low=24635.0, self.vol=559.53, self.amt=13788773.9804 
127.0.0.1 - - [16/Feb/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-02-16 16:25:01,721:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230216   160000    160459  ...         0.0        0.0       0
5953  20230216   160500    160959  ...         0.0        0.0       0
5954  20230216   161000    161459  ...         0.0        0.0       0
5955  20230216   161500    161959  ...         0.0        0.0       0
5956  20230216   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-16 16:25:01,722:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676535899, self.tradeDate='20230216', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=24643.8, self.close=24645.9, self.high=24648.2, self.low=24635.0, self.vol=559.53, self.amt=13788773.9804, ukdf['pct'].iloc[-1]=8.5e-05 , ukdf['amount'].iloc[-1]=13788773.9804, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-488355.02914746768', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24644.74517993', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1676535599, self.tradeDate='20230216', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=24629.4, self.close=24643.8, self.high=24655.3, self.low=24626.3 
2023-02-16 16:20:01,663:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676535599, self.tradeDate='20230216', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=24629.4, self.close=24643.8, self.high=24655.3, self.low=24626.3   
127.0.0.1 - - [16/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-02-16 16:20:01,688:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230216   155500    155959  1676534399  ...  24584.4  0.001427   1631    5
1632  20230216   160000    160459  1676534699  ...  24596.6 -0.001389   1632    0
1633  20230216   160500    160959  1676534999  ...  24584.3 -0.000094   1633    1
1634  20230216   161000    161459  1676535299  ...  24592.6  0.001427   1634    2
1635  20230216   161500    161959  1676535599  ...  24626.3  0.000585   1635    3

[5 rows x 11 columns]
2023-02-16 16:20:01,688:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [16/Feb/2023 16:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=71, self.factor=0.13625410353374373, self.count=23923 

self.closeSec=1676535899, self.tradeDate='20230216', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=24643.8, self.close=24645.9, self.high=24648.2, self.low=24635.0 
2023-02-16 16:25:01,603:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676535899, self.tradeDate='20230216', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=24643.8, self.close=24645.9, self.high=24648.2, self.low=24635.0   
2023-02-16 16:25:01,675:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230216   160000    160459  1676534699  ...  24596.6 -0.001389   1632    0
1633  20230216   160500    160959  1676534999  ...  24584.3 -0.000094   1633    1
1634  20230216   161000    161459  1676535299  ...  24592.6  0.001427   1634    2
1635  20230216   161500    161959  1676535599  ...  24626.3  0.000585   1635    3
1636  20230216   162000    162459  1676535899  ...  24635.0  0.000085   1636    4

[5 rows x 11 columns]
2023-02-16 16:25:01,683:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-16 16:00:32,906:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230216    132959  24647.9  ...  52.083333  0.764695  0.104819
5787  20230216    135959  24716.9  ...  52.083333  0.759578  0.103543
5788  20230216    142959  24694.4  ...  52.500000  0.762335  0.101474
5789  20230216    145959  24732.7  ...  52.500000  0.732233  0.102946
5790  20230216    152959  24597.9  ...  52.500000  0.732393  0.104307

[5 rows x 33 columns]
0.5202952029520295
acc is : 0.5202952029520295
2023-02-16 16:00:33,058:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.522571  0.477429       0  ...  1.160123   1.0    0.0  1.060574
538     0  0.503626  0.496374       1  ...  1.161927   1.0    0.0  1.062223
539     0  0.511875  0.488125       0  ...  1.155590   1.0    0.0  1.056429
540     1  0.471892  0.528108       1  ...  1.155684   1.0    0.0  1.056515
541     1  0.497151  0.502849       1  ...  1.157136   1.0    0.0  1.057842

[5 rows x 10 columns]
2023-02-16 16:00:33,079:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.522702  0.477298       0  ...  1.160123   1.0    0.0  1.055253
46     0  0.503318  0.496682       1  ...  1.161927   1.0    0.0  1.056163
47     0  0.511956  0.488044       0  ...  1.155590   1.0    0.0  1.054681
48     1  0.472405  0.527595       1  ...  1.118921   1.0    0.0  1.055192
49     1  0.497151  0.502849       1  ...  1.157136   1.0    0.0  1.057842

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '35.557', 'enterprice': '21695.5', 'countrevence': '0', 'unrealprofit': '103936.6667', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24618.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230216   155000    155959  1676534399  24567.8  24630.8  0.002524
2023-02-16 16:00:02,314:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [16/Feb/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11960 

self.closeSec=1676534999, self.tradeDate='20230216', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='24630.8', self.close='24594.3'
2023-02-16 16:10:01,747:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676534999, self.tradeDate='20230216', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='24630.8', self.close='24594.3'
2023-02-16 16:10:01,772:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230216   152000    152959  1676532599  24596.2  24599.9  0.000150
525  20230216   153000    153959  1676533199  24601.1  24570.5 -0.001195
526  20230216   154000    154959  1676533799  24570.5  24568.8 -0.000069
527  20230216   155000    155959  1676534399  24567.8  24630.8  0.002524
528  20230216   160000    160959  1676534999  24630.8  24594.3 -0.001482
2023-02-16 16:10:01,772:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11961 

self.closeSec=1676535599, self.tradeDate='20230216', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='24594.3', self.close='24643.8'
2023-02-16 16:20:01,769:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676535599, self.tradeDate='20230216', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='24594.3', self.close='24643.8'
127.0.0.1 - - [16/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-02-16 16:20:01,805:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230216   153000    153959  1676533199  24601.1  24570.5 -0.001195
526  20230216   154000    154959  1676533799  24570.5  24568.8 -0.000069
527  20230216   155000    155959  1676534399  24567.8  24630.8  0.002524
528  20230216   160000    160959  1676534999  24630.8  24594.3 -0.001482
529  20230216   161000    161959  1676535599  24594.3  24643.8  0.002013
2023-02-16 16:20:01,805:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/percentile_regression_step2/log.txt ----- -----

127.0.0.1 - - [16/Feb/2023 15:00:02] "POST / HTTP/1.1" 200 -
2023-02-16 15:00:02,950:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/16 12:30:00  123000  24647.9  ...     NaN     NaN       0
145  2023/02/16 13:00:00  130000  24717.0  ...     NaN     NaN       0
146  2023/02/16 13:30:00  133000  24694.4  ...     NaN     NaN       0
147  2023/02/16 14:00:00  140000  24732.8  ...     NaN     NaN       0
148  2023/02/16 14:30:00  143000  24597.9  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [16/Feb/2023 15:30:01] "POST / HTTP/1.1" 200 -
2023-02-16 15:30:02,707:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/16 13:00:00  130000  24717.0  ...     NaN     NaN       0
145  2023/02/16 13:30:00  133000  24694.4  ...     NaN     NaN       0
146  2023/02/16 14:00:00  140000  24732.8  ...     NaN     NaN       0
147  2023/02/16 14:30:00  143000  24597.9  ...     NaN     NaN       0
148  2023/02/16 15:00:00  150000  24599.9  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [16/Feb/2023 16:00:02] "POST / HTTP/1.1" 200 -
2023-02-16 16:00:03,305:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/16 13:30:00  133000  24694.4  ...     NaN     NaN       0
145  2023/02/16 14:00:00  140000  24732.8  ...     NaN     NaN       0
146  2023/02/16 14:30:00  143000  24597.9  ...     NaN     NaN       0
147  2023/02/16 15:00:00  150000  24599.9  ...     NaN     NaN       0
148  2023/02/16 15:30:00  153000  24630.8  ...     NaN     NaN       0

[5 rows x 10 columns]


## /root/FIL/strategy/pyemd/log.txt ----- -----

17519  20230216   155000    155959  1676534399  24567.8  24630.8
2023-02-16 16:00:02,332:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [16/Feb/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11961 

self.closeSec=1676534999, self.tradeDate='20230216', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='24630.8', self.close='24594.3'
2023-02-16 16:10:01,789:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676534999, self.tradeDate='20230216', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='24630.8', self.close='24594.3'
2023-02-16 16:10:01,808:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230216   152000    152959  1676532599  24596.2  24599.9
17517  20230216   153000    153959  1676533199  24601.1  24570.5
17518  20230216   154000    154959  1676533799  24570.5  24568.8
17519  20230216   155000    155959  1676534399  24567.8  24630.8
17520  20230216   160000    160959  1676534999  24630.8  24594.3
2023-02-16 16:10:01,809:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11962 

self.closeSec=1676535599, self.tradeDate='20230216', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='24594.3', self.close='24643.8'
2023-02-16 16:20:01,780:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676535599, self.tradeDate='20230216', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='24594.3', self.close='24643.8'
127.0.0.1 - - [16/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-02-16 16:20:01,816:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230216   153000    153959  1676533199  24601.1  24570.5
17518  20230216   154000    154959  1676533799  24570.5  24568.8
17519  20230216   155000    155959  1676534399  24567.8  24630.8
17520  20230216   160000    160959  1676534999  24630.8  24594.3
17521  20230216   161000    161959  1676535599  24594.3  24643.8
2023-02-16 16:20:01,824:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230216   155000    155959  1676534399  24567.8  24630.8
2023-02-16 16:00:02,309:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11961 

self.closeSec=1676534999, self.tradeDate='20230216', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='24630.8', self.close='24594.3'
2023-02-16 16:10:01,759:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676534999, self.tradeDate='20230216', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='24630.8', self.close='24594.3'
127.0.0.1 - - [16/Feb/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-02-16 16:10:01,776:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230216   152000    152959  1676532599  24596.2  24599.9
12189  20230216   153000    153959  1676533199  24601.1  24570.5
12190  20230216   154000    154959  1676533799  24570.5  24568.8
12191  20230216   155000    155959  1676534399  24567.8  24630.8
12192  20230216   160000    160959  1676534999  24630.8  24594.3
2023-02-16 16:10:01,776:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [16/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11962 

self.closeSec=1676535599, self.tradeDate='20230216', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='24594.3', self.close='24643.8'
2023-02-16 16:20:01,752:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676535599, self.tradeDate='20230216', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='24594.3', self.close='24643.8'
2023-02-16 16:20:01,804:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230216   153000    153959  1676533199  24601.1  24570.5
12190  20230216   154000    154959  1676533799  24570.5  24568.8
12191  20230216   155000    155959  1676534399  24567.8  24630.8
12192  20230216   160000    160959  1676534999  24630.8  24594.3
12193  20230216   161000    161959  1676535599  24594.3  24643.8
2023-02-16 16:20:01,804:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [16/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=19354
self.closeSec=1676535599, self.tradeDate='20230216', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=24629.4, self.close=24643.8, self.high=24655.3, self.low=24626.3, self.vol=1681.295, self.amt=41430849.2088 
2023-02-16 16:20:01,830:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230216   155500    155959  ...         0.0        0.0       0
5952  20230216   160000    160459  ...         0.0        0.0       0
5953  20230216   160500    160959  ...         0.0        0.0       0
5954  20230216   161000    161459  ...         0.0        0.0       0
5955  20230216   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-16 16:20:01,830:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676535599, self.tradeDate='20230216', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=24629.4, self.close=24643.8, self.high=24655.3, self.low=24626.3, self.vol=1681.295, self.amt=41430849.2088, ukdf['pct'].iloc[-1]=0.000585 , ukdf['amount'].iloc[-1]=41430849.2088, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=19355
self.closeSec=1676535899, self.tradeDate='20230216', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=24643.8, self.close=24645.9, self.high=24648.2, self.low=24635.0, self.vol=559.53, self.amt=13788773.9804 
127.0.0.1 - - [16/Feb/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-02-16 16:25:01,738:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230216   160000    160459  ...         0.0        0.0       0
5953  20230216   160500    160959  ...         0.0        0.0       0
5954  20230216   161000    161459  ...         0.0        0.0       0
5955  20230216   161500    161959  ...         0.0        0.0       0
5956  20230216   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-16 16:25:01,740:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676535899, self.tradeDate='20230216', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=24643.8, self.close=24645.9, self.high=24648.2, self.low=24635.0, self.vol=559.53, self.amt=13788773.9804, ukdf['pct'].iloc[-1]=8.5e-05 , ukdf['amount'].iloc[-1]=13788773.9804, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230216   040000    075959  1676505599  ...    721  1.530634  3.435158     1.0
722  20230216   080000    115959  1676519999  ...    722  1.379617  2.733619     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.518', 'enterprice': '23318.2', 'countrevence': '0', 'unrealprofit': '52116.9060389257', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24745.35663615', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=850682.4935724001, self.flagDict['side']='buy', self.tradeCount=20, self.count=498
self.closeSec=1676534399, self.tradeDate='20230216', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=24741.0, self.close=24630.8, self.high=24764.6, self.low=24427.0, self.vol=85116.457, self.amt=2096380834.9139 
127.0.0.1 - - [16/Feb/2023 16:00:02] "POST / HTTP/1.1" 200 -
2023-02-16 16:00:02,102:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1676534399, self.tradeDate='20230216', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=24741.0, self.close=24630.8, self.high=24764.6, self.low=24427.0, self.vol=85116.457, self.amt=2096380834.9139 
2023-02-16 16:00:02,132:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230215   200000    235959  ...  207159.107  4.704555e+09  0.016275
720  20230216   000000    035959  ...  165009.408  3.797764e+09  0.022620
721  20230216   040000    075959  ...  306935.488  7.368613e+09  0.043699
722  20230216   080000    115959  ...  149506.526  3.687049e+09  0.016784
723  20230216   120000    155959  ...   85116.457  2.096381e+09 -0.004454

[5 rows x 11 columns]
2023-02-16 16:00:04,748:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230215   200000    235959  1676476799  ...    719  0.558057 -0.052169     NaN
720  20230216   000000    035959  1676491199  ...    720  0.933373  1.400510     1.0
721  20230216   040000    075959  1676505599  ...    721  1.530634  3.435158     1.0
722  20230216   080000    115959  1676519999  ...    722  1.379617  2.733619     1.0
723  20230216   120000    155959  1676534399  ...    723  1.216220  2.090231     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.518', 'enterprice': '23318.2', 'countrevence': '0', 'unrealprofit': '47754.05079539702', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24625.88527289', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


