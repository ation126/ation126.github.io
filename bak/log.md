# 20230726 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=21088
self.closeSec=1690359599, self.tradeDate='20230726', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29214.9, self.close=29218.1, self.high=29220.1, self.low=29214.9, self.vol=159.683, self.amt=4665715.3983 
127.0.0.1 - - [26/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-26 16:20:06,027:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230726   155500    155959  ...         0.0        0.0       0
5952  20230726   160000    160459  ...         0.0        0.0       0
5953  20230726   160500    160959  ...         0.0        0.0       0
5954  20230726   161000    161459  ...         0.0        0.0       0
5955  20230726   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-26 16:20:06,046:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690359599, self.tradeDate='20230726', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29214.9, self.close=29218.1, self.high=29220.1, self.low=29214.9, self.vol=159.683, self.amt=4665715.3983, ukdf['pct'].iloc[-1]=0.000168 , ukdf['amount'].iloc[-1]=4665715.3983, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-32772.3308767965', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29218.21975275', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=21089
self.closeSec=1690359899, self.tradeDate='20230726', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29218.0, self.close=29211.8, self.high=29218.1, self.low=29202.7, self.vol=245.242, self.amt=7163259.3278 
127.0.0.1 - - [26/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-07-26 16:25:00,806:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230726   160000    160459  ...         0.0        0.0       0
5953  20230726   160500    160959  ...         0.0        0.0       0
5954  20230726   161000    161459  ...         0.0        0.0       0
5955  20230726   161500    161959  ...         0.0        0.0       0
5956  20230726   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-26 16:25:00,807:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690359899, self.tradeDate='20230726', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29218.0, self.close=29211.8, self.high=29218.1, self.low=29202.7, self.vol=245.242, self.amt=7163259.3278, ukdf['pct'].iloc[-1]=-0.000216 , ukdf['amount'].iloc[-1]=7163259.3278, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-32686.38610865628', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29212.04821978', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1690359599, self.tradeDate='20230726', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29214.9, self.close=29218.1, self.high=29220.1, self.low=29214.9 
127.0.0.1 - - [26/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-26 16:20:04,042:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690359599, self.tradeDate='20230726', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29214.9, self.close=29218.1, self.high=29220.1, self.low=29214.9   
2023-07-26 16:20:05,173:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230726   155500    155959  1690358399  ...  29198.8  0.000219   1631    5
1632  20230726   160000    160459  1690358699  ...  29205.3  0.000212   1632    0
1633  20230726   160500    160959  1690358999  ...  29211.4  0.000291   1633    1
1634  20230726   161000    161459  1690359299  ...  29207.5 -0.000233   1634    2
1635  20230726   161500    161959  1690359599  ...  29214.9  0.000168   1635    3

[5 rows x 11 columns]
2023-07-26 16:20:05,182:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [26/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=36, self.factor=0.4696468138677002, self.count=21091 

self.closeSec=1690359899, self.tradeDate='20230726', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29218.0, self.close=29211.8, self.high=29218.1, self.low=29202.7 
2023-07-26 16:25:00,778:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690359899, self.tradeDate='20230726', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29218.0, self.close=29211.8, self.high=29218.1, self.low=29202.7   
2023-07-26 16:25:00,790:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230726   160000    160459  1690358699  ...  29205.3  0.000212   1632    0
1633  20230726   160500    160959  1690358999  ...  29211.4  0.000291   1633    1
1634  20230726   161000    161459  1690359299  ...  29207.5 -0.000233   1634    2
1635  20230726   161500    161959  1690359599  ...  29214.9  0.000168   1635    3
1636  20230726   162000    162459  1690359899  ...  29202.7 -0.000216   1636    4

[5 rows x 11 columns]
2023-07-26 16:25:00,790:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-26 16:00:17,871:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230726    132959  29185.9  ...  50.000000  0.474714  0.530099
5787  20230726    135959  29219.7  ...  50.416667  0.488468  0.523513
5788  20230726    142959  29260.7  ...  50.000000  0.486035  0.518804
5789  20230726    145959  29253.1  ...  49.583333  0.469158  0.524599
5790  20230726    152959  29198.6  ...  50.000000  0.469813  0.529652

[5 rows x 33 columns]
0.5553505535055351
acc is : 0.5553505535055351
2023-07-26 16:00:17,936:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.507621  0.492379       1  ...  0.942504  -1.0    0.0  0.965225
538     0  0.517392  0.482608       0  ...  0.942752  -1.0    0.0  0.964971
539     0  0.506331  0.493669       0  ...  0.944508  -1.0    0.0  0.963173
540     1  0.492944  0.507056       1  ...  0.944447  -1.0    0.0  0.963236
541     0  0.509349  0.490651       1  ...  0.944292  -1.0    0.0  0.963394

[5 rows x 10 columns]
2023-07-26 16:00:17,948:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.507771  0.492229       1  ...  0.942504  -1.0    0.0  0.968644
46     0  0.517625  0.482375       0  ...  0.942752  -1.0    0.0  0.965806
47     0  0.506350  0.493650       0  ...  0.944508  -1.0    0.0  0.963863
48     1  0.493089  0.506911       1  ...  0.944447  -1.0    0.0  0.963872
49     0  0.509349  0.490651       1  ...  0.944292  -1.0    0.0  0.963394

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.403', 'enterprice': '29752', 'countrevence': '0', 'unrealprofit': '12792.0798', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29205.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230726   155000    155959  1690358399  29197.4  29205.3  0.000271
2023-07-26 16:00:02,087:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [26/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10544 

self.closeSec=1690358999, self.tradeDate='20230726', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29205.4', self.close='29220'
2023-07-26 16:10:01,130:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690358999, self.tradeDate='20230726', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29205.4', self.close='29220'
2023-07-26 16:10:01,146:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230726   152000    152959  1690356599  29194.1  29200.5  0.000216
525  20230726   153000    153959  1690357199  29200.5  29185.9 -0.000500
526  20230726   154000    154959  1690357799  29185.9  29197.4  0.000394
527  20230726   155000    155959  1690358399  29197.4  29205.3  0.000271
528  20230726   160000    160959  1690358999  29205.4    29220  0.000503
2023-07-26 16:10:01,149:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10545 

self.closeSec=1690359599, self.tradeDate='20230726', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29220', self.close='29218.1'
127.0.0.1 - - [26/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-26 16:20:06,717:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690359599, self.tradeDate='20230726', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29220', self.close='29218.1'
2023-07-26 16:20:07,186:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230726   153000    153959  1690357199  29200.5  29185.9 -0.000500
526  20230726   154000    154959  1690357799  29185.9  29197.4  0.000394
527  20230726   155000    155959  1690358399  29197.4  29205.3  0.000271
528  20230726   160000    160959  1690358999  29205.4    29220  0.000503
529  20230726   161000    161959  1690359599    29220  29218.1 -0.000065
2023-07-26 16:20:07,188:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230726   155000    155959  1690358399  29197.4  29205.3
2023-07-26 16:00:02,092:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [26/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10547 

self.closeSec=1690358999, self.tradeDate='20230726', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29205.4', self.close='29220'
2023-07-26 16:10:01,134:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690358999, self.tradeDate='20230726', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29205.4', self.close='29220'
2023-07-26 16:10:01,142:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230726   152000    152959  1690356599  29194.1  29200.5
17517  20230726   153000    153959  1690357199  29200.5  29185.9
17518  20230726   154000    154959  1690357799  29185.9  29197.4
17519  20230726   155000    155959  1690358399  29197.4  29205.3
17520  20230726   160000    160959  1690358999  29205.4    29220
2023-07-26 16:10:01,142:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10548 

self.closeSec=1690359599, self.tradeDate='20230726', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29220', self.close='29218.1'
127.0.0.1 - - [26/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-26 16:20:08,049:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690359599, self.tradeDate='20230726', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29220', self.close='29218.1'
2023-07-26 16:20:08,177:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230726   153000    153959  1690357199  29200.5  29185.9
17518  20230726   154000    154959  1690357799  29185.9  29197.4
17519  20230726   155000    155959  1690358399  29197.4  29205.3
17520  20230726   160000    160959  1690358999  29205.4    29220
17521  20230726   161000    161959  1690359599    29220  29218.1
2023-07-26 16:20:08,177:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230726   155000    155959  1690358399  29197.4  29205.3
2023-07-26 16:00:02,090:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10547 

self.closeSec=1690358999, self.tradeDate='20230726', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29205.4', self.close='29220'
127.0.0.1 - - [26/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-07-26 16:10:01,140:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690358999, self.tradeDate='20230726', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29205.4', self.close='29220'
2023-07-26 16:10:01,149:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230726   152000    152959  1690356599  29194.1  29200.5
12189  20230726   153000    153959  1690357199  29200.5  29185.9
12190  20230726   154000    154959  1690357799  29185.9  29197.4
12191  20230726   155000    155959  1690358399  29197.4  29205.3
12192  20230726   160000    160959  1690358999  29205.4    29220
2023-07-26 16:10:01,149:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10548 

self.closeSec=1690359599, self.tradeDate='20230726', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29220', self.close='29218.1'
127.0.0.1 - - [26/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-26 16:20:07,858:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690359599, self.tradeDate='20230726', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29220', self.close='29218.1'
2023-07-26 16:20:08,067:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230726   153000    153959  1690357199  29200.5  29185.9
12190  20230726   154000    154959  1690357799  29185.9  29197.4
12191  20230726   155000    155959  1690358399  29197.4  29205.3
12192  20230726   160000    160959  1690358999  29205.4    29220
12193  20230726   161000    161959  1690359599    29220  29218.1
2023-07-26 16:20:08,068:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=21088
self.closeSec=1690359599, self.tradeDate='20230726', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29214.9, self.close=29218.1, self.high=29220.1, self.low=29214.9, self.vol=159.683, self.amt=4665715.3983 
127.0.0.1 - - [26/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-26 16:20:06,037:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230726   155500    155959  ...         0.0        0.0       0
5952  20230726   160000    160459  ...         0.0        0.0       0
5953  20230726   160500    160959  ...         0.0        0.0       0
5954  20230726   161000    161459  ...         0.0        0.0       0
5955  20230726   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-26 16:20:06,046:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690359599, self.tradeDate='20230726', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29214.9, self.close=29218.1, self.high=29220.1, self.low=29214.9, self.vol=159.683, self.amt=4665715.3983, ukdf['pct'].iloc[-1]=0.000168 , ukdf['amount'].iloc[-1]=4665715.3983, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '88180.89583688775', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29218.21975275', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=21089
self.closeSec=1690359899, self.tradeDate='20230726', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29218.0, self.close=29211.8, self.high=29218.1, self.low=29202.7, self.vol=245.242, self.amt=7163259.3278 
127.0.0.1 - - [26/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-07-26 16:25:00,804:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230726   160000    160459  ...         0.0        0.0       0
5953  20230726   160500    160959  ...         0.0        0.0       0
5954  20230726   161000    161459  ...         0.0        0.0       0
5955  20230726   161500    161959  ...         0.0        0.0       0
5956  20230726   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-26 16:25:00,804:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690359899, self.tradeDate='20230726', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29218.0, self.close=29211.8, self.high=29218.1, self.low=29202.7, self.vol=245.242, self.amt=7163259.3278, ukdf['pct'].iloc[-1]=-0.000216 , ukdf['amount'].iloc[-1]=7163259.3278, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '87951.67893084898', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29212.04821978', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230726   040000    075959  1690329599  ...    721  0.565665  0.836485     1.0
722  20230726   080000    115959  1690343999  ...    722  0.564654  0.813558     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.821', 'enterprice': '29117.6', 'countrevence': '0', 'unrealprofit': '6195.77232871974', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29230.61822894', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1594659.6936504, self.flagDict['side']='buy', self.tradeCount=13, self.count=439
self.closeSec=1690358399, self.tradeDate='20230726', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29228.1, self.close=29205.3, self.high=29315.0, self.low=29100.0, self.vol=27037.859, self.amt=790056505.17822 
127.0.0.1 - - [26/Jul/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-07-26 16:00:01,699:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1690358399, self.tradeDate='20230726', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=29228.1, self.close=29205.3, self.high=29315.0, self.low=29100.0, self.vol=27037.859, self.amt=790056505.17822 
2023-07-26 16:00:01,717:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230725   200000    235959  ...  65595.464  1.916336e+09  0.001697
720  20230726   000000    035959  ...  36685.898  1.073156e+09  0.000754
721  20230726   040000    075959  ...  13574.242  3.965229e+08  0.000935
722  20230726   080000    115959  ...  47519.046  1.388819e+09  0.000400
723  20230726   120000    155959  ...  27037.859  7.900565e+08 -0.000777

[5 rows x 11 columns]
2023-07-26 16:00:02,500:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230725   200000    235959  1690300799  ...    719  0.534944  0.754108     1.0
720  20230726   000000    035959  1690315199  ...    720  0.552748  0.804980     1.0
721  20230726   040000    075959  1690329599  ...    721  0.565665  0.836485     1.0
722  20230726   080000    115959  1690343999  ...    722  0.564654  0.813558     1.0
723  20230726   120000    155959  1690358399  ...    723  0.582017  0.862747     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.821', 'enterprice': '29117.6', 'countrevence': '0', 'unrealprofit': '4826.63291414486', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29205.64350366', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


