# 20230322 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=33148
self.closeSec=1679473199, self.tradeDate='20230322', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28153.0, self.close=28176.8, self.high=28185.8, self.low=28139.2, self.vol=934.156, self.amt=26308066.4177 
127.0.0.1 - - [22/Mar/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-03-22 16:20:07,278:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230322   155500    155959  ...         0.0        0.0       0
5952  20230322   160000    160459  ...         0.0        0.0       0
5953  20230322   160500    160959  ...         0.0        0.0       0
5954  20230322   161000    161459  ...         0.0        0.0       0
5955  20230322   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-22 16:20:07,297:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679473199, self.tradeDate='20230322', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28153.0, self.close=28176.8, self.high=28185.8, self.low=28139.2, self.vol=934.156, self.amt=26308066.4177, ukdf['pct'].iloc[-1]=0.000774 , ukdf['amount'].iloc[-1]=26308066.4177, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-700029.00481288496', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28162.32653571', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [22/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=33149
self.closeSec=1679473499, self.tradeDate='20230322', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28175.8, self.close=28147.1, self.high=28175.8, self.low=28139.2, self.vol=792.114, self.amt=22300413.8592 
2023-03-22 16:25:01,606:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230322   160000    160459  ...         0.0        0.0       0
5953  20230322   160500    160959  ...         0.0        0.0       0
5954  20230322   161000    161459  ...         0.0        0.0       0
5955  20230322   161500    161959  ...         0.0        0.0       0
5956  20230322   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-22 16:25:01,607:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679473499, self.tradeDate='20230322', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28175.8, self.close=28147.1, self.high=28175.8, self.low=28139.2, self.vol=792.114, self.amt=22300413.8592, ukdf['pct'].iloc[-1]=-0.001054 , ukdf['amount'].iloc[-1]=22300413.8592, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-699108.57325314848', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28147.03087698', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1679473199, self.tradeDate='20230322', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28153.0, self.close=28176.8, self.high=28185.8, self.low=28139.2 
127.0.0.1 - - [22/Mar/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-03-22 16:20:05,068:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679473199, self.tradeDate='20230322', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28153.0, self.close=28176.8, self.high=28185.8, self.low=28139.2   
2023-03-22 16:20:06,167:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230322   155500    155959  1679471999  ...  28056.6  0.000096   1631    5
1632  20230322   160000    160459  1679472299  ...  28055.4 -0.000741   1632    0
1633  20230322   160500    160959  1679472599  ...  28065.1  0.002205   1633    1
1634  20230322   161000    161459  1679472899  ...  28113.0  0.000914   1634    2
1635  20230322   161500    161959  1679473199  ...  28139.2  0.000774   1635    3

[5 rows x 11 columns]
2023-03-22 16:20:06,168:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=236, self.factor=0.36453120979009607, self.count=33715 

self.closeSec=1679473499, self.tradeDate='20230322', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28175.8, self.close=28147.1, self.high=28175.8, self.low=28139.2 
127.0.0.1 - - [22/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-03-22 16:25:01,491:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679473499, self.tradeDate='20230322', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28175.8, self.close=28147.1, self.high=28175.8, self.low=28139.2   
2023-03-22 16:25:01,511:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230322   160000    160459  1679472299  ...  28055.4 -0.000741   1632    0
1633  20230322   160500    160959  1679472599  ...  28065.1  0.002205   1633    1
1634  20230322   161000    161459  1679472899  ...  28113.0  0.000914   1634    2
1635  20230322   161500    161959  1679473199  ...  28139.2  0.000774   1635    3
1636  20230322   162000    162459  1679473499  ...  28139.2 -0.001054   1636    4

[5 rows x 11 columns]
2023-03-22 16:25:01,513:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-22 16:00:34,875:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230322    132959  28188.0  ...  52.500000  0.547376  0.329913
5787  20230322    135959  28241.1  ...  52.083333  0.539259  0.332322
5788  20230322    142959  28184.0  ...  51.666667  0.534885  0.337294
5789  20230322    145959  28153.2  ...  51.666667  0.539292  0.338786
5790  20230322    152959  28188.9  ...  52.083333  0.539317  0.340162

[5 rows x 33 columns]
0.5387453874538746
acc is : 0.5387453874538746
2023-03-22 16:00:35,037:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.562865  0.437135       0  ...  1.205179   1.0    0.0  1.394771
538     0  0.509009  0.490991       0  ...  1.203861   1.0    0.0  1.393247
539     0  0.519349  0.480651       1  ...  1.205384   1.0    0.0  1.395009
540     0  0.541156  0.458844       1  ...  1.205392   1.0    0.0  1.395019
541     0  0.525333  0.474667       0  ...  1.201082   1.0    0.0  1.390030

[5 rows x 10 columns]
2023-03-22 16:00:35,065:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.563683  0.436317       0  ...  1.211985   1.0    0.0  1.403104
46     0  0.509488  0.490512       0  ...  1.216051   1.0    0.0  1.398465
47     0  0.519795  0.480205       1  ...  1.217066   1.0    0.0  1.399622
48     0  0.541049  0.458951       1  ...  1.211006   1.0    0.0  1.392668
49     0  0.525333  0.474667       0  ...  1.201082   1.0    0.0  1.390030

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230322   155000    155959  1679471999  28100.4  28088.2 -0.000434
2023-03-22 16:00:02,069:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [22/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16856 

self.closeSec=1679472599, self.tradeDate='20230322', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28088.2', self.close='28129.3'
2023-03-22 16:10:01,611:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679472599, self.tradeDate='20230322', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='28088.2', self.close='28129.3'
2023-03-22 16:10:01,674:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230322   152000    152959  1679470199  28167.2    28189  0.000774
525  20230322   153000    153959  1679470799    28189  28081.4 -0.003817
526  20230322   154000    154959  1679471399  28081.4  28100.4  0.000677
527  20230322   155000    155959  1679471999  28100.4  28088.2 -0.000434
528  20230322   160000    160959  1679472599  28088.2  28129.3  0.001463
2023-03-22 16:10:01,674:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16857 

self.closeSec=1679473199, self.tradeDate='20230322', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28129.3', self.close='28176.8'
127.0.0.1 - - [22/Mar/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-03-22 16:20:05,957:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679473199, self.tradeDate='20230322', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='28129.3', self.close='28176.8'
2023-03-22 16:20:06,667:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230322   153000    153959  1679470799    28189  28081.4 -0.003817
526  20230322   154000    154959  1679471399  28081.4  28100.4  0.000677
527  20230322   155000    155959  1679471999  28100.4  28088.2 -0.000434
528  20230322   160000    160959  1679472599  28088.2  28129.3  0.001463
529  20230322   161000    161959  1679473199  28129.3  28176.8  0.001689
2023-03-22 16:20:06,668:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230322   155000    155959  1679471999  28100.4  28088.2
2023-03-22 16:00:02,136:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [22/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16857 

self.closeSec=1679472599, self.tradeDate='20230322', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28088.2', self.close='28129.3'
2023-03-22 16:10:01,632:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679472599, self.tradeDate='20230322', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='28088.2', self.close='28129.3'
2023-03-22 16:10:01,687:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230322   152000    152959  1679470199  28167.2    28189
17517  20230322   153000    153959  1679470799    28189  28081.4
17518  20230322   154000    154959  1679471399  28081.4  28100.4
17519  20230322   155000    155959  1679471999  28100.4  28088.2
17520  20230322   160000    160959  1679472599  28088.2  28129.3
2023-03-22 16:10:01,688:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16858 

self.closeSec=1679473199, self.tradeDate='20230322', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28129.3', self.close='28176.8'
127.0.0.1 - - [22/Mar/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-03-22 16:20:08,869:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679473199, self.tradeDate='20230322', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='28129.3', self.close='28176.8'
2023-03-22 16:20:08,993:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230322   153000    153959  1679470799    28189  28081.4
17518  20230322   154000    154959  1679471399  28081.4  28100.4
17519  20230322   155000    155959  1679471999  28100.4  28088.2
17520  20230322   160000    160959  1679472599  28088.2  28129.3
17521  20230322   161000    161959  1679473199  28129.3  28176.8
2023-03-22 16:20:08,994:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230322   155000    155959  1679471999  28100.4  28088.2
2023-03-22 16:00:02,111:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16857 

self.closeSec=1679472599, self.tradeDate='20230322', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28088.2', self.close='28129.3'
127.0.0.1 - - [22/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-03-22 16:10:01,587:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679472599, self.tradeDate='20230322', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='28088.2', self.close='28129.3'
2023-03-22 16:10:01,604:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230322   152000    152959  1679470199  28167.2    28189
12189  20230322   153000    153959  1679470799    28189  28081.4
12190  20230322   154000    154959  1679471399  28081.4  28100.4
12191  20230322   155000    155959  1679471999  28100.4  28088.2
12192  20230322   160000    160959  1679472599  28088.2  28129.3
2023-03-22 16:10:01,604:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16858 

self.closeSec=1679473199, self.tradeDate='20230322', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28129.3', self.close='28176.8'
127.0.0.1 - - [22/Mar/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-03-22 16:20:08,258:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679473199, self.tradeDate='20230322', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='28129.3', self.close='28176.8'
2023-03-22 16:20:08,640:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230322   153000    153959  1679470799    28189  28081.4
12190  20230322   154000    154959  1679471399  28081.4  28100.4
12191  20230322   155000    155959  1679471999  28100.4  28088.2
12192  20230322   160000    160959  1679472599  28088.2  28129.3
12193  20230322   161000    161959  1679473199  28129.3  28176.8
2023-03-22 16:20:08,641:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [22/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=29146
self.closeSec=1679473199, self.tradeDate='20230322', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28153.0, self.close=28176.8, self.high=28185.8, self.low=28139.2, self.vol=934.156, self.amt=26308066.4177 
2023-03-22 16:20:01,918:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230322   155500    155959  ...         0.0        0.0       0
5952  20230322   160000    160459  ...         0.0        0.0       0
5953  20230322   160500    160959  ...         0.0        0.0       0
5954  20230322   161000    161459  ...         0.0        0.0       0
5955  20230322   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-22 16:20:01,949:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679473199, self.tradeDate='20230322', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28153.0, self.close=28176.8, self.high=28185.8, self.low=28139.2, self.vol=934.156, self.amt=26308066.4177, ukdf['pct'].iloc[-1]=0.000774 , ukdf['amount'].iloc[-1]=26308066.4177, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [22/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=29147
self.closeSec=1679473499, self.tradeDate='20230322', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28175.8, self.close=28147.1, self.high=28175.8, self.low=28139.2, self.vol=792.114, self.amt=22300413.8592 
2023-03-22 16:25:01,607:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230322   160000    160459  ...         0.0        0.0       0
5953  20230322   160500    160959  ...         0.0        0.0       0
5954  20230322   161000    161459  ...         0.0        0.0       0
5955  20230322   161500    161959  ...         0.0        0.0       0
5956  20230322   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-22 16:25:01,607:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679473499, self.tradeDate='20230322', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28175.8, self.close=28147.1, self.high=28175.8, self.low=28139.2, self.vol=792.114, self.amt=22300413.8592, ukdf['pct'].iloc[-1]=-0.001054 , ukdf['amount'].iloc[-1]=22300413.8592, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230322   040000    075959  1679443199  ...    721  0.438918 -0.819217    -1.0
722  20230322   080000    115959  1679457599  ...    722  0.541432 -0.515098     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '-2785.31929767102', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28142.96234867', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [22/Mar/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1507151.9559834, self.flagDict['side']='sell', self.tradeCount=27, self.count=702
self.closeSec=1679471999, self.tradeDate='20230322', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=28137.6, self.close=28088.2, self.high=28280.0, self.low=28002.6, self.vol=54361.466, self.amt=1530369190.0588 
2023-03-22 16:00:01,961:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1679471999, self.tradeDate='20230322', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=28137.6, self.close=28088.2, self.high=28280.0, self.low=28002.6, self.vol=54361.466, self.amt=1530369190.0588 
2023-03-22 16:00:02,028:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230321   200000    235959  ...  166351.235  4.656915e+09  0.000068
720  20230322   000000    035959  ...  165390.923  4.661815e+09  0.002840
721  20230322   040000    075959  ...   50579.928  1.418130e+09 -0.000587
722  20230322   080000    115959  ...   62536.552  1.756711e+09  0.001659
723  20230322   120000    155959  ...   54361.466  1.530369e+09 -0.001759

[5 rows x 11 columns]
2023-03-22 16:00:04,098:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230321   200000    235959  1679414399  ...    719  0.607069 -0.285479     NaN
720  20230322   000000    035959  1679428799  ...    720  0.593629 -0.341142     NaN
721  20230322   040000    075959  1679443199  ...    721  0.438918 -0.819217    -1.0
722  20230322   080000    115959  1679457599  ...    722  0.541432 -0.515098     NaN
723  20230322   120000    155959  1679471999  ...    723  0.493981 -0.688068    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '175.76609828718', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28087.82725397', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


