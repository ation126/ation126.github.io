# 20230219 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=24220
self.closeSec=1676794799, self.tradeDate='20230219', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=24605.4, self.close=24612.2, self.high=24626.7, self.low=24605.4, self.vol=692.751, self.amt=17051918.9929 
127.0.0.1 - - [19/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-02-19 16:20:01,706:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230219   155500    155959  ...         0.0        0.0       0
5952  20230219   160000    160459  ...         0.0        0.0       0
5953  20230219   160500    160959  ...         0.0        0.0       0
5954  20230219   161000    161459  ...         0.0        0.0       0
5955  20230219   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-19 16:20:01,706:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676794799, self.tradeDate='20230219', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=24605.4, self.close=24612.2, self.high=24626.7, self.low=24605.4, self.vol=692.751, self.amt=17051918.9929, ukdf['pct'].iloc[-1]=0.000272 , ukdf['amount'].iloc[-1]=17051918.9929, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-486544.91296422112', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24614.66481262', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [19/Feb/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=24221
self.closeSec=1676795099, self.tradeDate='20230219', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=24612.2, self.close=24591.4, self.high=24615.1, self.low=24591.4, self.vol=448.278, self.amt=11029070.9526 
2023-02-19 16:25:01,554:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230219   160000    160459  ...         0.0        0.0       0
5953  20230219   160500    160959  ...         0.0        0.0       0
5954  20230219   161000    161459  ...         0.0        0.0       0
5955  20230219   161500    161959  ...         0.0        0.0       0
5956  20230219   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-19 16:25:01,555:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676795099, self.tradeDate='20230219', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=24612.2, self.close=24591.4, self.high=24615.1, self.low=24591.4, self.vol=448.278, self.amt=11029070.9526, ukdf['pct'].iloc[-1]=-0.000845 , ukdf['amount'].iloc[-1]=11029070.9526, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-485144.9296', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24591.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1676794799, self.tradeDate='20230219', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=24605.4, self.close=24612.2, self.high=24626.7, self.low=24605.4 
2023-02-19 16:20:01,650:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676794799, self.tradeDate='20230219', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=24605.4, self.close=24612.2, self.high=24626.7, self.low=24605.4   
127.0.0.1 - - [19/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-02-19 16:20:01,728:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230219   155500    155959  1676793599  ...  24553.6 -0.000541   1631    5
1632  20230219   160000    160459  1676793899  ...  24568.5  0.000728   1632    0
1633  20230219   160500    160959  1676794199  ...  24593.0  0.000146   1633    1
1634  20230219   161000    161459  1676794499  ...  24598.1  0.000297   1634    2
1635  20230219   161500    161959  1676794799  ...  24605.4  0.000272   1635    3

[5 rows x 11 columns]
2023-02-19 16:20:01,728:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=215, self.factor=0.40474167074926776, self.count=24787 

self.closeSec=1676795099, self.tradeDate='20230219', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=24612.2, self.close=24591.4, self.high=24615.1, self.low=24591.4 
127.0.0.1 - - [19/Feb/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-02-19 16:25:01,504:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676795099, self.tradeDate='20230219', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=24612.2, self.close=24591.4, self.high=24615.1, self.low=24591.4   
2023-02-19 16:25:01,538:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230219   160000    160459  1676793899  ...  24568.5  0.000728   1632    0
1633  20230219   160500    160959  1676794199  ...  24593.0  0.000146   1633    1
1634  20230219   161000    161459  1676794499  ...  24598.1  0.000297   1634    2
1635  20230219   161500    161959  1676794799  ...  24605.4  0.000272   1635    3
1636  20230219   162000    162459  1676795099  ...  24591.4 -0.000845   1636    4

[5 rows x 11 columns]
2023-02-19 16:25:01,538:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-19 16:00:34,098:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230219    132959  24720.3  ...  52.083333  0.574331  0.406796
5787  20230219    135959  24833.9  ...  51.666667  0.559613  0.397603
5788  20230219    142959  24766.2  ...  51.250000  0.543227  0.400564
5789  20230219    145959  24687.1  ...  51.250000  0.531395  0.411930
5790  20230219    152959  24629.9  ...  50.833333  0.529374  0.429851

[5 rows x 33 columns]
0.514760147601476
acc is : 0.514760147601476
2023-02-19 16:00:34,256:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.537487  0.462513       0  ...  1.117854   1.0    0.0  1.062015
538     1  0.497983  0.502017       0  ...  1.114329   1.0    0.0  1.058666
539     1  0.490687  0.509313       0  ...  1.111702   1.0    0.0  1.056171
540     1  0.487665  0.512335       0  ...  1.111251   1.0    0.0  1.055742
541     1  0.492389  0.507611       0  ...  1.109301   1.0    0.0  1.053889

[5 rows x 10 columns]
2023-02-19 16:00:34,290:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.538785  0.461215       0  ...  1.117854   1.0    0.0  1.066373
46     1  0.498598  0.501402       0  ...  1.114329   1.0    0.0  1.061146
47     1  0.491817  0.508183       0  ...  1.111702   1.0    0.0  1.059984
48     1  0.488190  0.511810       0  ...  1.111251   1.0    0.0  1.059021
49     1  0.492389  0.507611       0  ...  1.109301   1.0    0.0  1.053889

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '35.459', 'enterprice': '24163.6', 'countrevence': '0', 'unrealprofit': '14537.49024003794', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24573.58026566', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230219   155000    155959  1676793599    24593  24576.7 -0.000663
2023-02-19 16:00:02,247:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [19/Feb/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12392 

self.closeSec=1676794199, self.tradeDate='20230219', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='24576.6', self.close='24598.2'
2023-02-19 16:10:01,786:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676794199, self.tradeDate='20230219', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='24576.6', self.close='24598.2'
2023-02-19 16:10:01,816:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230219   152000    152959  1676791799  24611.3  24619.9  0.000349
525  20230219   153000    153959  1676792399  24619.8  24624.5  0.000187
526  20230219   154000    154959  1676792999  24624.5    24593 -0.001279
527  20230219   155000    155959  1676793599    24593  24576.7 -0.000663
528  20230219   160000    160959  1676794199  24576.6  24598.2  0.000875
2023-02-19 16:10:01,816:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12393 

self.closeSec=1676794799, self.tradeDate='20230219', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='24598.1', self.close='24612.2'
127.0.0.1 - - [19/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-02-19 16:20:01,866:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676794799, self.tradeDate='20230219', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='24598.1', self.close='24612.2'
2023-02-19 16:20:01,882:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230219   153000    153959  1676792399  24619.8  24624.5  0.000187
526  20230219   154000    154959  1676792999  24624.5    24593 -0.001279
527  20230219   155000    155959  1676793599    24593  24576.7 -0.000663
528  20230219   160000    160959  1676794199  24576.6  24598.2  0.000875
529  20230219   161000    161959  1676794799  24598.1  24612.2  0.000569
2023-02-19 16:20:01,882:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/percentile_regression_step2/log.txt ----- -----

127.0.0.1 - - [19/Feb/2023 15:00:01] "POST / HTTP/1.1" 200 -
2023-02-19 15:00:02,996:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/19 12:30:00  123000  24720.2  ...     NaN     NaN       0
145  2023/02/19 13:00:00  130000  24833.9  ...     NaN     NaN       0
146  2023/02/19 13:30:00  133000  24766.2  ...     NaN     NaN       0
147  2023/02/19 14:00:00  140000  24688.1  ...     NaN     NaN       0
148  2023/02/19 14:30:00  143000  24629.9  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [19/Feb/2023 15:30:01] "POST / HTTP/1.1" 200 -
2023-02-19 15:30:02,482:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/19 13:00:00  130000  24833.9  ...     NaN     NaN       0
145  2023/02/19 13:30:00  133000  24766.2  ...     NaN     NaN       0
146  2023/02/19 14:00:00  140000  24688.1  ...     NaN     NaN       0
147  2023/02/19 14:30:00  143000  24629.9  ...     NaN     NaN       0
148  2023/02/19 15:00:00  150000  24619.9  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [19/Feb/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-02-19 16:00:03,134:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/19 13:30:00  133000  24766.2  ...     NaN     NaN       0
145  2023/02/19 14:00:00  140000  24688.1  ...     NaN     NaN       0
146  2023/02/19 14:30:00  143000  24629.9  ...     NaN     NaN       0
147  2023/02/19 15:00:00  150000  24619.9  ...     NaN     NaN       0
148  2023/02/19 15:30:00  153000  24576.7  ...     NaN     NaN       0

[5 rows x 10 columns]


## /root/FIL/strategy/pyemd/log.txt ----- -----

17519  20230219   155000    155959  1676793599    24593  24576.7
2023-02-19 16:00:02,256:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [19/Feb/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12393 

self.closeSec=1676794199, self.tradeDate='20230219', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='24576.6', self.close='24598.2'
2023-02-19 16:10:01,791:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676794199, self.tradeDate='20230219', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='24576.6', self.close='24598.2'
2023-02-19 16:10:01,803:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230219   152000    152959  1676791799  24611.3  24619.9
17517  20230219   153000    153959  1676792399  24619.8  24624.5
17518  20230219   154000    154959  1676792999  24624.5    24593
17519  20230219   155000    155959  1676793599    24593  24576.7
17520  20230219   160000    160959  1676794199  24576.6  24598.2
2023-02-19 16:10:01,803:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [19/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12394 

self.closeSec=1676794799, self.tradeDate='20230219', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='24598.1', self.close='24612.2'
2023-02-19 16:20:01,900:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676794799, self.tradeDate='20230219', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='24598.1', self.close='24612.2'
2023-02-19 16:20:01,931:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230219   153000    153959  1676792399  24619.8  24624.5
17518  20230219   154000    154959  1676792999  24624.5    24593
17519  20230219   155000    155959  1676793599    24593  24576.7
17520  20230219   160000    160959  1676794199  24576.6  24598.2
17521  20230219   161000    161959  1676794799  24598.1  24612.2
2023-02-19 16:20:01,931:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230219   155000    155959  1676793599    24593  24576.7
2023-02-19 16:00:02,291:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12393 

self.closeSec=1676794199, self.tradeDate='20230219', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='24576.6', self.close='24598.2'
2023-02-19 16:10:01,779:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676794199, self.tradeDate='20230219', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='24576.6', self.close='24598.2'
127.0.0.1 - - [19/Feb/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-02-19 16:10:01,784:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230219   152000    152959  1676791799  24611.3  24619.9
12189  20230219   153000    153959  1676792399  24619.8  24624.5
12190  20230219   154000    154959  1676792999  24624.5    24593
12191  20230219   155000    155959  1676793599    24593  24576.7
12192  20230219   160000    160959  1676794199  24576.6  24598.2
2023-02-19 16:10:01,785:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [19/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12394 

self.closeSec=1676794799, self.tradeDate='20230219', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='24598.1', self.close='24612.2'
2023-02-19 16:20:01,862:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676794799, self.tradeDate='20230219', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='24598.1', self.close='24612.2'
2023-02-19 16:20:01,870:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230219   153000    153959  1676792399  24619.8  24624.5
12190  20230219   154000    154959  1676792999  24624.5    24593
12191  20230219   155000    155959  1676793599    24593  24576.7
12192  20230219   160000    160959  1676794199  24576.6  24598.2
12193  20230219   161000    161959  1676794799  24598.1  24612.2
2023-02-19 16:20:01,870:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [19/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=20218
self.closeSec=1676794799, self.tradeDate='20230219', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=24605.4, self.close=24612.2, self.high=24626.7, self.low=24605.4, self.vol=692.751, self.amt=17051918.9929 
2023-02-19 16:20:01,699:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230219   155500    155959  ...         0.0        0.0       0
5952  20230219   160000    160459  ...         0.0        0.0       0
5953  20230219   160500    160959  ...         0.0        0.0       0
5954  20230219   161000    161459  ...         0.0        0.0       0
5955  20230219   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-19 16:20:01,699:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676794799, self.tradeDate='20230219', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=24605.4, self.close=24612.2, self.high=24626.7, self.low=24605.4, self.vol=692.751, self.amt=17051918.9929, ukdf['pct'].iloc[-1]=0.000272 , ukdf['amount'].iloc[-1]=17051918.9929, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [19/Feb/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=20219
self.closeSec=1676795099, self.tradeDate='20230219', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=24612.2, self.close=24591.4, self.high=24615.1, self.low=24591.4, self.vol=448.278, self.amt=11029070.9526 
2023-02-19 16:25:01,620:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230219   160000    160459  ...         0.0        0.0       0
5953  20230219   160500    160959  ...         0.0        0.0       0
5954  20230219   161000    161459  ...         0.0        0.0       0
5955  20230219   161500    161959  ...         0.0        0.0       0
5956  20230219   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-19 16:25:01,620:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676795099, self.tradeDate='20230219', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=24612.2, self.close=24591.4, self.high=24615.1, self.low=24591.4, self.vol=448.278, self.amt=11029070.9526, ukdf['pct'].iloc[-1]=-0.000845 , ukdf['amount'].iloc[-1]=11029070.9526, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230219   040000    075959  1676764799  ...    721  0.922795  0.690896     1.0
722  20230219   080000    115959  1676779199  ...    722  0.831049  0.434007     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.518', 'enterprice': '23318.2', 'countrevence': '0', 'unrealprofit': '49909.70860526504', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24684.91528028', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [19/Feb/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=850682.4935724001, self.flagDict['side']='buy', self.tradeCount=20, self.count=516
self.closeSec=1676793599, self.tradeDate='20230219', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=24687.0, self.close=24576.7, self.high=24867.6, self.low=24553.6, self.vol=59061.967, self.amt=1459276010.1446 
2023-02-19 16:00:02,011:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1676793599, self.tradeDate='20230219', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=24687.0, self.close=24576.7, self.high=24867.6, self.low=24553.6, self.vol=59061.967, self.amt=1459276010.1446 
2023-02-19 16:00:02,065:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230218   200000    235959  ...  55533.683  1.368031e+09  0.005888
720  20230219   000000    035959  ...  61293.542  1.514293e+09 -0.002428
721  20230219   040000    075959  ...  22736.718  5.595636e+08  0.001089
722  20230219   080000    115959  ...  29006.051  7.166029e+08  0.002034
723  20230219   120000    155959  ...  59061.967  1.459276e+09 -0.004468

[5 rows x 11 columns]
2023-02-19 16:00:04,389:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230218   200000    235959  1676735999  ...    719  0.941629  0.757507     1.0
720  20230219   000000    035959  1676750399  ...    720  0.985311  0.869136     1.0
721  20230219   040000    075959  1676764799  ...    721  0.922795  0.690896     1.0
722  20230219   080000    115959  1676779199  ...    722  0.831049  0.434007     NaN
723  20230219   120000    155959  1676793599  ...    723  0.730658  0.154030     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.518', 'enterprice': '23318.2', 'countrevence': '0', 'unrealprofit': '45969.24053421186', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24577.01046427', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


