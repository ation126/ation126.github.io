# 20230217 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [17/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=23644
self.closeSec=1676621999, self.tradeDate='20230217', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=23678.2, self.close=23661.9, self.high=23691.3, self.low=23646.3, self.vol=1250.336, self.amt=29596387.6488 
2023-02-17 16:20:01,627:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230217   155500    155959  ...         0.0        0.0       0
5952  20230217   160000    160459  ...         0.0        0.0       0
5953  20230217   160500    160959  ...         0.0        0.0       0
5954  20230217   161000    161459  ...         0.0        0.0       0
5955  20230217   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-17 16:20:01,629:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676621999, self.tradeDate='20230217', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=23678.2, self.close=23661.9, self.high=23691.3, self.low=23646.3, self.vol=1250.336, self.amt=29596387.6488, ukdf['pct'].iloc[-1]=-0.000473 , ukdf['amount'].iloc[-1]=29596387.6488, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-429130.20852561072', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23660.55180347', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=23645
self.closeSec=1676622299, self.tradeDate='20230217', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=23661.8, self.close=23666.1, self.high=23666.1, self.low=23649.9, self.vol=490.176, self.amt=11595797.3703 
127.0.0.1 - - [17/Feb/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-02-17 16:25:01,732:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230217   160000    160459  ...         0.0        0.0       0
5953  20230217   160500    160959  ...         0.0        0.0       0
5954  20230217   161000    161459  ...         0.0        0.0       0
5955  20230217   161500    161959  ...         0.0        0.0       0
5956  20230217   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-17 16:25:01,733:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676622299, self.tradeDate='20230217', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=23661.8, self.close=23666.1, self.high=23666.1, self.low=23649.9, self.vol=490.176, self.amt=11595797.3703, ukdf['pct'].iloc[-1]=0.000178 , ukdf['amount'].iloc[-1]=11595797.3703, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-429458.0592', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23666', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=119, self.factor=0.4757652041067315, self.count=24210 

self.closeSec=1676621999, self.tradeDate='20230217', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=23678.2, self.close=23661.9, self.high=23691.3, self.low=23646.3 
2023-02-17 16:20:01,552:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676621999, self.tradeDate='20230217', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=23678.2, self.close=23661.9, self.high=23691.3, self.low=23646.3   
2023-02-17 16:20:01,607:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230217   155500    155959  1676620799  ...  23629.2 -0.001010   1631    5
1632  20230217   160000    160459  1676621099  ...  23591.0 -0.000305   1632    0
1633  20230217   160500    160959  1676621399  ...  23628.7  0.000813   1633    1
1634  20230217   161000    161459  1676621699  ...  23638.1  0.001061   1634    2
1635  20230217   161500    161959  1676621999  ...  23646.3 -0.000473   1635    3

[5 rows x 11 columns]
2023-02-17 16:20:01,607:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [17/Feb/2023 16:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=119, self.factor=0.4757652041067315, self.count=24211 

self.closeSec=1676622299, self.tradeDate='20230217', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=23661.8, self.close=23666.1, self.high=23666.1, self.low=23649.9 
2023-02-17 16:25:01,623:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676622299, self.tradeDate='20230217', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=23661.8, self.close=23666.1, self.high=23666.1, self.low=23649.9   
2023-02-17 16:25:01,685:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230217   160000    160459  1676621099  ...  23591.0 -0.000305   1632    0
1633  20230217   160500    160959  1676621399  ...  23628.7  0.000813   1633    1
1634  20230217   161000    161459  1676621699  ...  23638.1  0.001061   1634    2
1635  20230217   161500    161959  1676621999  ...  23646.3 -0.000473   1635    3
1636  20230217   162000    162459  1676622299  ...  23649.9  0.000178   1636    4

[5 rows x 11 columns]
2023-02-17 16:25:01,685:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-17 16:00:30,864:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230217    132959  23804.9  ...  52.500000  0.492263  0.650196
5787  20230217    135959  23730.5  ...  52.083333  0.489833  0.661163
5788  20230217    142959  23709.5  ...  52.083333  0.492038  0.670776
5789  20230217    145959  23727.5  ...  51.666667  0.485589  0.681621
5790  20230217    152959  23673.0  ...  52.083333  0.497224  0.688503

[5 rows x 33 columns]
0.522140221402214
acc is : 0.522140221402214
2023-02-17 16:00:30,974:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.473419  0.526581       0  ...  1.124372  -1.0    0.0  1.028612
538     1  0.473181  0.526819       1  ...  1.123513  -1.0    0.0  1.029397
539     1  0.489229  0.510771       0  ...  1.126094  -1.0    0.0  1.027033
540     1  0.466162  0.533838       1  ...  1.121608  -1.0    0.0  1.031124
541     0  0.504526  0.495474       0  ...  1.127809  -1.0    0.0  1.025423

[5 rows x 10 columns]
2023-02-17 16:00:30,998:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.473394  0.526606       0  ...  1.124372  -1.0    0.0  1.031862
46     1  0.474774  0.525226       1  ...  1.067667  -1.0    0.0  1.034811
47     1  0.490727  0.509273       0  ...  1.070119  -1.0    0.0  1.032443
48     1  0.466875  0.533125       1  ...  1.065857  -1.0    0.0  1.031159
49     0  0.504526  0.495474       0  ...  1.127809  -1.0    0.0  1.025423

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '34.282', 'enterprice': '24560.5', 'countrevence': '0', 'unrealprofit': '31676.568', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23636.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230217   155000    155959  1676620799  23688.6    23636 -0.002216
2023-02-17 16:00:02,359:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12104 

self.closeSec=1676621399, self.tradeDate='20230217', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='23635.9', self.close='23648'
2023-02-17 16:10:01,620:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676621399, self.tradeDate='20230217', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='23635.9', self.close='23648'
127.0.0.1 - - [17/Feb/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-02-17 16:10:01,630:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230217   152000    152959  1676618999    23752  23767.4  0.000648
525  20230217   153000    153959  1676619599  23767.4    23730 -0.001574
526  20230217   154000    154959  1676620199    23730  23688.5 -0.001749
527  20230217   155000    155959  1676620799  23688.6    23636 -0.002216
528  20230217   160000    160959  1676621399  23635.9    23648  0.000508
2023-02-17 16:10:01,631:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [17/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12105 

self.closeSec=1676621999, self.tradeDate='20230217', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='23647.9', self.close='23661.9'
2023-02-17 16:20:01,765:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676621999, self.tradeDate='20230217', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='23647.9', self.close='23661.9'
2023-02-17 16:20:01,796:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230217   153000    153959  1676619599  23767.4    23730 -0.001574
526  20230217   154000    154959  1676620199    23730  23688.5 -0.001749
527  20230217   155000    155959  1676620799  23688.6    23636 -0.002216
528  20230217   160000    160959  1676621399  23635.9    23648  0.000508
529  20230217   161000    161959  1676621999  23647.9  23661.9  0.000588
2023-02-17 16:20:01,797:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/percentile_regression_step2/log.txt ----- -----

127.0.0.1 - - [17/Feb/2023 15:00:01] "POST / HTTP/1.1" 200 -
2023-02-17 15:00:03,150:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/17 12:30:00  123000  23804.8  ...     NaN     NaN       0
145  2023/02/17 13:00:00  130000  23730.5  ...     NaN     NaN       0
146  2023/02/17 13:30:00  133000  23709.5  ...     NaN     NaN       0
147  2023/02/17 14:00:00  140000  23727.6  ...     NaN     NaN       0
148  2023/02/17 14:30:00  143000  23673.1  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [17/Feb/2023 15:30:01] "POST / HTTP/1.1" 200 -
2023-02-17 15:30:03,225:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/17 13:00:00  130000  23730.5  ...     NaN     NaN       0
145  2023/02/17 13:30:00  133000  23709.5  ...     NaN     NaN       0
146  2023/02/17 14:00:00  140000  23727.6  ...     NaN     NaN       0
147  2023/02/17 14:30:00  143000  23673.1  ...     NaN     NaN       0
148  2023/02/17 15:00:00  150000  23767.4  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [17/Feb/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-02-17 16:00:03,367:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/17 13:30:00  133000  23709.5  ...     NaN     NaN       0
145  2023/02/17 14:00:00  140000  23727.6  ...     NaN     NaN       0
146  2023/02/17 14:30:00  143000  23673.1  ...     NaN     NaN       0
147  2023/02/17 15:00:00  150000  23767.4  ...     NaN     NaN       0
148  2023/02/17 15:30:00  153000  23636.0  ...     NaN     NaN       0

[5 rows x 10 columns]


## /root/FIL/strategy/pyemd/log.txt ----- -----

17519  20230217   155000    155959  1676620799  23688.6    23636
2023-02-17 16:00:02,411:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12105 

self.closeSec=1676621399, self.tradeDate='20230217', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='23635.9', self.close='23648'
2023-02-17 16:10:01,642:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676621399, self.tradeDate='20230217', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='23635.9', self.close='23648'
127.0.0.1 - - [17/Feb/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-02-17 16:10:01,652:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230217   152000    152959  1676618999    23752  23767.4
17517  20230217   153000    153959  1676619599  23767.4    23730
17518  20230217   154000    154959  1676620199    23730  23688.5
17519  20230217   155000    155959  1676620799  23688.6    23636
17520  20230217   160000    160959  1676621399  23635.9    23648
2023-02-17 16:10:01,652:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [17/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12106 

self.closeSec=1676621999, self.tradeDate='20230217', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='23647.9', self.close='23661.9'
2023-02-17 16:20:01,779:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676621999, self.tradeDate='20230217', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='23647.9', self.close='23661.9'
2023-02-17 16:20:01,802:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230217   153000    153959  1676619599  23767.4    23730
17518  20230217   154000    154959  1676620199    23730  23688.5
17519  20230217   155000    155959  1676620799  23688.6    23636
17520  20230217   160000    160959  1676621399  23635.9    23648
17521  20230217   161000    161959  1676621999  23647.9  23661.9
2023-02-17 16:20:01,802:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230217   155000    155959  1676620799  23688.6    23636
2023-02-17 16:00:02,404:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12105 

self.closeSec=1676621399, self.tradeDate='20230217', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='23635.9', self.close='23648'
2023-02-17 16:10:01,645:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676621399, self.tradeDate='20230217', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='23635.9', self.close='23648'
127.0.0.1 - - [17/Feb/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-02-17 16:10:01,664:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230217   152000    152959  1676618999    23752  23767.4
12189  20230217   153000    153959  1676619599  23767.4    23730
12190  20230217   154000    154959  1676620199    23730  23688.5
12191  20230217   155000    155959  1676620799  23688.6    23636
12192  20230217   160000    160959  1676621399  23635.9    23648
2023-02-17 16:10:01,664:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [17/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12106 

self.closeSec=1676621999, self.tradeDate='20230217', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='23647.9', self.close='23661.9'
2023-02-17 16:20:01,776:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676621999, self.tradeDate='20230217', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='23647.9', self.close='23661.9'
2023-02-17 16:20:01,797:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230217   153000    153959  1676619599  23767.4    23730
12190  20230217   154000    154959  1676620199    23730  23688.5
12191  20230217   155000    155959  1676620799  23688.6    23636
12192  20230217   160000    160959  1676621399  23635.9    23648
12193  20230217   161000    161959  1676621999  23647.9  23661.9
2023-02-17 16:20:01,797:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=19642
self.closeSec=1676621999, self.tradeDate='20230217', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=23678.2, self.close=23661.9, self.high=23691.3, self.low=23646.3, self.vol=1250.336, self.amt=29596387.6488 
127.0.0.1 - - [17/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-02-17 16:20:01,600:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230217   155500    155959  ...         0.0        0.0       0
5952  20230217   160000    160459  ...         0.0        0.0       0
5953  20230217   160500    160959  ...         0.0        0.0       0
5954  20230217   161000    161459  ...         0.0        0.0       0
5955  20230217   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-17 16:20:01,606:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676621999, self.tradeDate='20230217', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=23678.2, self.close=23661.9, self.high=23691.3, self.low=23646.3, self.vol=1250.336, self.amt=29596387.6488, ukdf['pct'].iloc[-1]=-0.000473 , ukdf['amount'].iloc[-1]=29596387.6488, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=19643
self.closeSec=1676622299, self.tradeDate='20230217', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=23661.8, self.close=23666.1, self.high=23666.1, self.low=23649.9, self.vol=490.176, self.amt=11595797.3703 
127.0.0.1 - - [17/Feb/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-02-17 16:25:01,713:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230217   160000    160459  ...         0.0        0.0       0
5953  20230217   160500    160959  ...         0.0        0.0       0
5954  20230217   161000    161459  ...         0.0        0.0       0
5955  20230217   161500    161959  ...         0.0        0.0       0
5956  20230217   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-17 16:25:01,713:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676622299, self.tradeDate='20230217', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=23661.8, self.close=23666.1, self.high=23666.1, self.low=23649.9, self.vol=490.176, self.amt=11595797.3703, ukdf['pct'].iloc[-1]=0.000178 , ukdf['amount'].iloc[-1]=11595797.3703, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230217   040000    075959  1676591999  ...    721  1.208527  1.844319     1.0
722  20230217   080000    115959  1676606399  ...    722  1.216225  1.815670     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.518', 'enterprice': '23318.2', 'countrevence': '0', 'unrealprofit': '19130.32628476412', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23842.06018634', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [17/Feb/2023 16:00:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=850682.4935724001, self.flagDict['side']='buy', self.tradeCount=20, self.count=504
self.closeSec=1676620799, self.tradeDate='20230217', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=23839.0, self.close=23636.0, self.high=23885.7, self.low=23612.0, self.vol=59676.035, self.amt=1416529597.3011 
2023-02-17 16:00:02,182:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1676620799, self.tradeDate='20230217', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=23839.0, self.close=23636.0, self.high=23885.7, self.low=23612.0, self.vol=59676.035, self.amt=1416529597.3011 
2023-02-17 16:00:02,222:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230216   200000    235959  ...  214136.439  5.270860e+09  0.021009
720  20230217   000000    035959  ...  224316.013  5.591111e+09 -0.008663
721  20230217   040000    075959  ...  237702.696  5.751313e+09 -0.054359
722  20230217   080000    115959  ...  125666.630  2.975857e+09  0.013283
723  20230217   120000    155959  ...   59676.035  1.416530e+09 -0.008520

[5 rows x 11 columns]
2023-02-17 16:00:04,107:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230216   200000    235959  1676563199  ...    719  1.148644  1.765325     1.0
720  20230217   000000    035959  1676577599  ...    720  1.167381  1.771426     1.0
721  20230217   040000    075959  1676591999  ...    721  1.208527  1.844319     1.0
722  20230217   080000    115959  1676606399  ...    722  1.216225  1.815670     1.0
723  20230217   120000    155959  1676620799  ...    723  1.188773  1.686635     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.518', 'enterprice': '23318.2', 'countrevence': '0', 'unrealprofit': '11632.78999609212', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23636.74948234', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


