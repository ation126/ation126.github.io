# 20230730 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=22240
self.closeSec=1690705199, self.tradeDate='20230730', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29281.2, self.close=29289.8, self.high=29289.9, self.low=29281.1, self.vol=452.587, self.amt=13254822.4524 
127.0.0.1 - - [30/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-30 16:20:05,831:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230730   155500    155959  ...         0.0        0.0       0
5952  20230730   160000    160459  ...         0.0        0.0       0
5953  20230730   160500    160959  ...         0.0        0.0       0
5954  20230730   161000    161459  ...         0.0        0.0       0
5955  20230730   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-30 16:20:05,845:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690705199, self.tradeDate='20230730', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29281.2, self.close=29289.8, self.high=29289.9, self.low=29281.1, self.vol=452.587, self.amt=13254822.4524, ukdf['pct'].iloc[-1]=0.000297 , ukdf['amount'].iloc[-1]=13254822.4524, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-33826.254', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29293.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [30/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=22241
self.closeSec=1690705499, self.tradeDate='20230730', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29289.9, self.close=29296.3, self.high=29298.2, self.low=29289.8, self.vol=523.462, self.amt=15334263.5605 
2023-07-30 16:25:00,839:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230730   160000    160459  ...         0.0        0.0       0
5953  20230730   160500    160959  ...         0.0        0.0       0
5954  20230730   161000    161459  ...         0.0        0.0       0
5955  20230730   161500    161959  ...         0.0        0.0       0
5956  20230730   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-30 16:25:00,839:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690705499, self.tradeDate='20230730', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29289.9, self.close=29296.3, self.high=29298.2, self.low=29289.8, self.vol=523.462, self.amt=15334263.5605, ukdf['pct'].iloc[-1]=0.000222 , ukdf['amount'].iloc[-1]=15334263.5605, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-33859.6764', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29296.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1690705199, self.tradeDate='20230730', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29281.2, self.close=29289.8, self.high=29289.9, self.low=29281.1 
127.0.0.1 - - [30/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-30 16:20:04,102:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690705199, self.tradeDate='20230730', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29281.2, self.close=29289.8, self.high=29289.9, self.low=29281.1   
2023-07-30 16:20:05,282:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230730   155500    155959  1690703999  ...  29280.0 -0.000065   1631    5
1632  20230730   160000    160459  1690704299  ...  29278.4 -0.000014   1632    0
1633  20230730   160500    160959  1690704599  ...  29278.0  0.000031   1633    1
1634  20230730   161000    161459  1690704899  ...  29280.6  0.000017   1634    2
1635  20230730   161500    161959  1690705199  ...  29281.1  0.000297   1635    3

[5 rows x 11 columns]
2023-07-30 16:20:05,291:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=25, self.factor=0.5745932867469823, self.count=22243 

self.closeSec=1690705499, self.tradeDate='20230730', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29289.9, self.close=29296.3, self.high=29298.2, self.low=29289.8 
127.0.0.1 - - [30/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-07-30 16:25:00,803:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690705499, self.tradeDate='20230730', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29289.9, self.close=29296.3, self.high=29298.2, self.low=29289.8   
2023-07-30 16:25:00,819:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230730   160000    160459  1690704299  ...  29278.4 -0.000014   1632    0
1633  20230730   160500    160959  1690704599  ...  29278.0  0.000031   1633    1
1634  20230730   161000    161459  1690704899  ...  29280.6  0.000017   1634    2
1635  20230730   161500    161959  1690705199  ...  29281.1  0.000297   1635    3
1636  20230730   162000    162459  1690705499  ...  29289.8  0.000222   1636    4

[5 rows x 11 columns]
2023-07-30 16:25:00,820:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-30 16:00:16,758:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230730    132959  29309.6  ...  47.500000  0.501679  0.477018
5787  20230730    135959  29308.9  ...  47.083333  0.494367  0.484422
5788  20230730    142959  29296.8  ...  46.666667  0.473197  0.511290
5789  20230730    145959  29260.1  ...  47.083333  0.481166  0.529352
5790  20230730    152959  29272.9  ...  46.666667  0.475927  0.551213

[5 rows x 33 columns]
0.577490774907749
acc is : 0.577490774907749
2023-07-30 16:00:16,816:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.502308  0.497692       0  ...  0.919711   1.0    0.0  0.975162
538     1  0.497889  0.502111       0  ...  0.918559   1.0    0.0  0.973941
539     1  0.489313  0.510687       1  ...  0.918964   1.0    0.0  0.974370
540     0  0.500610  0.499390       0  ...  0.918675   1.0    0.0  0.974064
541     1  0.494871  0.505129       1  ...  0.919187   1.0    0.0  0.974606

[5 rows x 10 columns]
2023-07-30 16:00:16,827:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.502346  0.497654       0  ...  0.919711   1.0    0.0  0.982827
46     1  0.498003  0.501997       0  ...  0.918559   1.0    0.0  0.980994
47     1  0.489284  0.510716       1  ...  0.918964   1.0    0.0  0.980811
48     0  0.500775  0.499225       0  ...  0.918675   1.0    0.0  0.978251
49     1  0.494871  0.505129       1  ...  0.919187   1.0    0.0  0.974606

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.818', 'enterprice': '29478', 'countrevence': '0', 'unrealprofit': '-4648.741708333', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29282.8223315', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230730   155000    155959  1690703999  29279.9    29280  0.000000
2023-07-30 16:00:02,246:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11120 

self.closeSec=1690704599, self.tradeDate='20230730', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29280.1', self.close='29280.7'
127.0.0.1 - - [30/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-07-30 16:10:01,175:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690704599, self.tradeDate='20230730', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29280.1', self.close='29280.7'
2023-07-30 16:10:01,187:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230730   152000    152959  1690702199  29271.1  29263.7 -0.000249
525  20230730   153000    153959  1690702799  29263.8  29270.9  0.000246
526  20230730   154000    154959  1690703399  29270.9    29280  0.000311
527  20230730   155000    155959  1690703999  29279.9    29280  0.000000
528  20230730   160000    160959  1690704599  29280.1  29280.7  0.000024
2023-07-30 16:10:01,187:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11121 

self.closeSec=1690705199, self.tradeDate='20230730', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29280.6', self.close='29289.8'
127.0.0.1 - - [30/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-30 16:20:06,242:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690705199, self.tradeDate='20230730', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29280.6', self.close='29289.8'
2023-07-30 16:20:06,801:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230730   153000    153959  1690702799  29263.8  29270.9  0.000246
526  20230730   154000    154959  1690703399  29270.9    29280  0.000311
527  20230730   155000    155959  1690703999  29279.9    29280  0.000000
528  20230730   160000    160959  1690704599  29280.1  29280.7  0.000024
529  20230730   161000    161959  1690705199  29280.6  29289.8  0.000311
2023-07-30 16:20:06,802:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230730   155000    155959  1690703999  29279.9    29280
2023-07-30 16:00:02,252:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [30/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11123 

self.closeSec=1690704599, self.tradeDate='20230730', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29280.1', self.close='29280.7'
2023-07-30 16:10:01,168:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690704599, self.tradeDate='20230730', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29280.1', self.close='29280.7'
2023-07-30 16:10:01,176:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230730   152000    152959  1690702199  29271.1  29263.7
17517  20230730   153000    153959  1690702799  29263.8  29270.9
17518  20230730   154000    154959  1690703399  29270.9    29280
17519  20230730   155000    155959  1690703999  29279.9    29280
17520  20230730   160000    160959  1690704599  29280.1  29280.7
2023-07-30 16:10:01,177:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11124 

self.closeSec=1690705199, self.tradeDate='20230730', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29280.6', self.close='29289.8'
127.0.0.1 - - [30/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-30 16:20:07,746:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690705199, self.tradeDate='20230730', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29280.6', self.close='29289.8'
2023-07-30 16:20:07,848:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230730   153000    153959  1690702799  29263.8  29270.9
17518  20230730   154000    154959  1690703399  29270.9    29280
17519  20230730   155000    155959  1690703999  29279.9    29280
17520  20230730   160000    160959  1690704599  29280.1  29280.7
17521  20230730   161000    161959  1690705199  29280.6  29289.8
2023-07-30 16:20:07,849:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230730   155000    155959  1690703999  29279.9    29280
2023-07-30 16:00:02,242:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [30/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11123 

self.closeSec=1690704599, self.tradeDate='20230730', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29280.1', self.close='29280.7'
2023-07-30 16:10:01,180:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690704599, self.tradeDate='20230730', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29280.1', self.close='29280.7'
2023-07-30 16:10:01,192:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230730   152000    152959  1690702199  29271.1  29263.7
12189  20230730   153000    153959  1690702799  29263.8  29270.9
12190  20230730   154000    154959  1690703399  29270.9    29280
12191  20230730   155000    155959  1690703999  29279.9    29280
12192  20230730   160000    160959  1690704599  29280.1  29280.7
2023-07-30 16:10:01,192:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11124 

self.closeSec=1690705199, self.tradeDate='20230730', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29280.6', self.close='29289.8'
127.0.0.1 - - [30/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-30 16:20:07,632:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690705199, self.tradeDate='20230730', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29280.6', self.close='29289.8'
2023-07-30 16:20:07,754:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230730   153000    153959  1690702799  29263.8  29270.9
12190  20230730   154000    154959  1690703399  29270.9    29280
12191  20230730   155000    155959  1690703999  29279.9    29280
12192  20230730   160000    160959  1690704599  29280.1  29280.7
12193  20230730   161000    161959  1690705199  29280.6  29289.8
2023-07-30 16:20:07,754:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=22240
self.closeSec=1690705199, self.tradeDate='20230730', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29281.2, self.close=29289.8, self.high=29289.9, self.low=29281.1, self.vol=452.587, self.amt=13254822.4524 
127.0.0.1 - - [30/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-30 16:20:05,843:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230730   155500    155959  ...         0.0        0.0       0
5952  20230730   160000    160459  ...         0.0        0.0       0
5953  20230730   160500    160959  ...         0.0        0.0       0
5954  20230730   161000    161459  ...         0.0        0.0       0
5955  20230730   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-30 16:20:05,863:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690705199, self.tradeDate='20230730', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29281.2, self.close=29289.8, self.high=29289.9, self.low=29281.1, self.vol=452.587, self.amt=13254822.4524, ukdf['pct'].iloc[-1]=0.000297 , ukdf['amount'].iloc[-1]=13254822.4524, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '90991.7359', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29293.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=22241
self.closeSec=1690705499, self.tradeDate='20230730', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29289.9, self.close=29296.3, self.high=29298.2, self.low=29289.8, self.vol=523.462, self.amt=15334263.5605 
127.0.0.1 - - [30/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-07-30 16:25:00,830:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230730   160000    160459  ...         0.0        0.0       0
5953  20230730   160500    160959  ...         0.0        0.0       0
5954  20230730   161000    161459  ...         0.0        0.0       0
5955  20230730   161500    161959  ...         0.0        0.0       0
5956  20230730   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-30 16:25:00,830:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690705499, self.tradeDate='20230730', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29289.9, self.close=29296.3, self.high=29298.2, self.low=29289.8, self.vol=523.462, self.amt=15334263.5605, ukdf['pct'].iloc[-1]=0.000222 , ukdf['amount'].iloc[-1]=15334263.5605, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '91080.8743', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29296.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230730   040000    075959  1690675199  ...    721  0.116313 -1.023235    -1.0
722  20230730   080000    115959  1690689599  ...    722  0.085739 -1.129026    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.024', 'enterprice': '29248', 'countrevence': '0', 'unrealprofit': '-2836.26976051608', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29300.50018067', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1578513.8580480001, self.flagDict['side']='sell', self.tradeCount=16, self.count=463
self.closeSec=1690703999, self.tradeDate='20230730', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29300.1, self.close=29280.0, self.high=29317.5, self.low=29251.9, self.vol=11221.774, self.amt=328613036.7025 
127.0.0.1 - - [30/Jul/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-07-30 16:00:01,763:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1690703999, self.tradeDate='20230730', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=29300.1, self.close=29280.0, self.high=29317.5, self.low=29251.9, self.vol=11221.774, self.amt=328613036.7025 
2023-07-30 16:00:01,781:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230729   200000    235959  ...  18876.177  5.528415e+08  0.001080
720  20230730   000000    035959  ...  12008.201  3.518909e+08  0.001475
721  20230730   040000    075959  ...   9865.259  2.895167e+08  0.000378
722  20230730   080000    115959  ...   9189.052  2.693709e+08 -0.001326
723  20230730   120000    155959  ...  11221.774  3.286130e+08 -0.000689

[5 rows x 11 columns]
2023-07-30 16:00:02,556:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230729   200000    235959  1690646399  ...    719  0.164504 -0.841976    -1.0
720  20230730   000000    035959  1690660799  ...    720  0.153205 -0.881509    -1.0
721  20230730   040000    075959  1690675199  ...    721  0.116313 -1.023235    -1.0
722  20230730   080000    115959  1690689599  ...    722  0.085739 -1.129026    -1.0
723  20230730   120000    155959  1690703999  ...    723  0.121428 -0.957668    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.024', 'enterprice': '29248', 'countrevence': '0', 'unrealprofit': '-1891.83251758296', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29283.01837179', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


