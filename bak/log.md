# 20230329 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=35164
self.closeSec=1680077999, self.tradeDate='20230329', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28338.0, self.close=28299.2, self.high=28400.0, self.low=28259.0, self.vol=8291.332, self.amt=234896384.2453 
127.0.0.1 - - [29/Mar/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-03-29 16:20:08,297:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230329   155500    155959  ...         0.0        0.0       0
5952  20230329   160000    160459  ...         0.0        0.0       0
5953  20230329   160500    160959  ...         0.0        0.0       0
5954  20230329   161000    161459  ...         0.0        0.0       0
5955  20230329   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-29 16:20:08,318:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680077999, self.tradeDate='20230329', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28338.0, self.close=28299.2, self.high=28400.0, self.low=28259.0, self.vol=8291.332, self.amt=234896384.2453, ukdf['pct'].iloc[-1]=-0.001373 , ukdf['amount'].iloc[-1]=234896384.2453, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-708360.38685830416', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28300.77678241', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [29/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=35165
self.closeSec=1680078299, self.tradeDate='20230329', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28295.5, self.close=28457.8, self.high=28480.0, self.low=28290.0, self.vol=10203.227, self.amt=289838887.3221 
2023-03-29 16:25:01,610:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230329   160000    160459  ...         0.0        0.0       0
5953  20230329   160500    160959  ...         0.0        0.0       0
5954  20230329   161000    161459  ...         0.0        0.0       0
5955  20230329   161500    161959  ...         0.0        0.0       0
5956  20230329   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-29 16:25:01,610:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680078299, self.tradeDate='20230329', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28295.5, self.close=28457.8, self.high=28480.0, self.low=28290.0, self.vol=10203.227, self.amt=289838887.3221, ukdf['pct'].iloc[-1]=0.005604 , ukdf['amount'].iloc[-1]=289838887.3221, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-717707.1168', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28456.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1680077999, self.tradeDate='20230329', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28338.0, self.close=28299.2, self.high=28400.0, self.low=28259.0 
127.0.0.1 - - [29/Mar/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-03-29 16:20:05,977:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680077999, self.tradeDate='20230329', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28338.0, self.close=28299.2, self.high=28400.0, self.low=28259.0   
2023-03-29 16:20:06,976:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230329   155500    155959  1680076799  ...  28058.9 -0.000445   1631    5
1632  20230329   160000    160459  1680077099  ...  28025.5 -0.001531   1632    0
1633  20230329   160500    160959  1680077399  ...  28028.6  0.002286   1633    1
1634  20230329   161000    161459  1680077699  ...  28094.5  0.008516   1634    2
1635  20230329   161500    161959  1680077999  ...  28259.0 -0.001373   1635    3

[5 rows x 11 columns]
2023-03-29 16:20:06,976:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [29/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=25, self.factor=0.3878425823488823, self.count=35731 

self.closeSec=1680078299, self.tradeDate='20230329', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28295.5, self.close=28457.8, self.high=28480.0, self.low=28290.0 
2023-03-29 16:25:01,514:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680078299, self.tradeDate='20230329', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28295.5, self.close=28457.8, self.high=28480.0, self.low=28290.0   
2023-03-29 16:25:01,579:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230329   160000    160459  1680077099  ...  28025.5 -0.001531   1632    0
1633  20230329   160500    160959  1680077399  ...  28028.6  0.002286   1633    1
1634  20230329   161000    161459  1680077699  ...  28094.5  0.008516   1634    2
1635  20230329   161500    161959  1680077999  ...  28259.0 -0.001373   1635    3
1636  20230329   162000    162459  1680078299  ...  28290.0  0.005604   1636    4

[5 rows x 11 columns]
2023-03-29 16:25:01,579:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-29 16:00:36,058:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230329    132959  27552.5  ...  48.750000  0.547984  0.267983
5787  20230329    135959  27567.1  ...  48.333333  0.542138  0.258134
5788  20230329    142959  27532.7  ...  48.333333  0.599881  0.245789
5789  20230329    145959  27988.5  ...  48.750000  0.605744  0.236809
5790  20230329    152959  28044.2  ...  49.166667  0.605833  0.228429

[5 rows x 33 columns]
0.5055350553505535
acc is : 0.5055350553505535
2023-03-29 16:00:36,212:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.542737  0.457263       0  ...  0.943476   1.0    0.0  0.997074
538     0  0.530692  0.469308       1  ...  0.959195   1.0    0.0  1.013685
539     0  0.661959  0.338041       1  ...  0.961011   1.0    0.0  1.015605
540     0  0.578805  0.421195       1  ...  0.961038   1.0    0.0  1.015634
541     0  0.555583  0.444417       1  ...  0.962155   1.0    0.0  1.016814

[5 rows x 10 columns]
2023-03-29 16:00:36,248:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.542592  0.457408       0  ...  0.947100   1.0    0.0  1.000763
46     0  0.531339  0.468661       1  ...  0.943504   1.0    0.0  1.023074
47     0  0.661097  0.338903       1  ...  0.945290   1.0    0.0  1.024113
48     0  0.579233  0.420767       1  ...  0.945317   1.0    0.0  1.030623
49     0  0.555583  0.444417       1  ...  0.962155   1.0    0.0  1.016814

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230329   155000    155959  1680076799    28140  28077.7 -0.002214
2023-03-29 16:00:02,202:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17864 

self.closeSec=1680077399, self.tradeDate='20230329', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28077.8', self.close='28098.8'
2023-03-29 16:10:01,613:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680077399, self.tradeDate='20230329', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='28077.8', self.close='28098.8'
127.0.0.1 - - [29/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-03-29 16:10:01,641:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230329   152000    152959  1680074999  28072.9  28045.1 -0.001097
525  20230329   153000    153959  1680075599  28045.1    28083  0.001351
526  20230329   154000    154959  1680076199  28084.5    28140  0.002030
527  20230329   155000    155959  1680076799    28140  28077.7 -0.002214
528  20230329   160000    160959  1680077399  28077.8  28098.8  0.000751
2023-03-29 16:10:01,641:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17865 

self.closeSec=1680077999, self.tradeDate='20230329', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28098.7', self.close='28299.2'
127.0.0.1 - - [29/Mar/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-03-29 16:20:07,226:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680077999, self.tradeDate='20230329', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='28098.7', self.close='28299.2'
2023-03-29 16:20:07,937:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230329   153000    153959  1680075599  28045.1    28083  0.001351
526  20230329   154000    154959  1680076199  28084.5    28140  0.002030
527  20230329   155000    155959  1680076799    28140  28077.7 -0.002214
528  20230329   160000    160959  1680077399  28077.8  28098.8  0.000751
529  20230329   161000    161959  1680077999  28098.7  28299.2  0.007132
2023-03-29 16:20:07,937:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230329   155000    155959  1680076799    28140  28077.7
2023-03-29 16:00:02,240:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17865 

self.closeSec=1680077399, self.tradeDate='20230329', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28077.8', self.close='28098.8'
2023-03-29 16:10:01,635:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680077399, self.tradeDate='20230329', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='28077.8', self.close='28098.8'
127.0.0.1 - - [29/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-03-29 16:10:01,651:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230329   152000    152959  1680074999  28072.9  28045.1
17517  20230329   153000    153959  1680075599  28045.1    28083
17518  20230329   154000    154959  1680076199  28084.5    28140
17519  20230329   155000    155959  1680076799    28140  28077.7
17520  20230329   160000    160959  1680077399  28077.8  28098.8
2023-03-29 16:10:01,651:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17866 

self.closeSec=1680077999, self.tradeDate='20230329', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28098.7', self.close='28299.2'
127.0.0.1 - - [29/Mar/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-03-29 16:20:10,081:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680077999, self.tradeDate='20230329', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='28098.7', self.close='28299.2'
2023-03-29 16:20:10,389:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230329   153000    153959  1680075599  28045.1    28083
17518  20230329   154000    154959  1680076199  28084.5    28140
17519  20230329   155000    155959  1680076799    28140  28077.7
17520  20230329   160000    160959  1680077399  28077.8  28098.8
17521  20230329   161000    161959  1680077999  28098.7  28299.2
2023-03-29 16:20:10,390:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230329   155000    155959  1680076799    28140  28077.7
2023-03-29 16:00:02,208:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17865 

self.closeSec=1680077399, self.tradeDate='20230329', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28077.8', self.close='28098.8'
2023-03-29 16:10:01,586:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680077399, self.tradeDate='20230329', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='28077.8', self.close='28098.8'
127.0.0.1 - - [29/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-03-29 16:10:01,595:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230329   152000    152959  1680074999  28072.9  28045.1
12189  20230329   153000    153959  1680075599  28045.1    28083
12190  20230329   154000    154959  1680076199  28084.5    28140
12191  20230329   155000    155959  1680076799    28140  28077.7
12192  20230329   160000    160959  1680077399  28077.8  28098.8
2023-03-29 16:10:01,595:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17866 

self.closeSec=1680077999, self.tradeDate='20230329', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28098.7', self.close='28299.2'
127.0.0.1 - - [29/Mar/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-03-29 16:20:09,547:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680077999, self.tradeDate='20230329', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='28098.7', self.close='28299.2'
2023-03-29 16:20:09,841:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230329   153000    153959  1680075599  28045.1    28083
12190  20230329   154000    154959  1680076199  28084.5    28140
12191  20230329   155000    155959  1680076799    28140  28077.7
12192  20230329   160000    160959  1680077399  28077.8  28098.8
12193  20230329   161000    161959  1680077999  28098.7  28299.2
2023-03-29 16:20:09,846:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=31162
self.closeSec=1680077999, self.tradeDate='20230329', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28338.0, self.close=28299.2, self.high=28400.0, self.low=28259.0, self.vol=8291.332, self.amt=234896384.2453 
127.0.0.1 - - [29/Mar/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-03-29 16:20:06,132:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230329   155500    155959  ...         0.0        0.0       0
5952  20230329   160000    160459  ...         0.0        0.0       0
5953  20230329   160500    160959  ...         0.0        0.0       0
5954  20230329   161000    161459  ...         0.0        0.0       0
5955  20230329   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-29 16:20:06,168:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680077999, self.tradeDate='20230329', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28338.0, self.close=28299.2, self.high=28400.0, self.low=28259.0, self.vol=8291.332, self.amt=234896384.2453, ukdf['pct'].iloc[-1]=-0.001373 , ukdf['amount'].iloc[-1]=234896384.2453, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=31163
self.closeSec=1680078299, self.tradeDate='20230329', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28295.5, self.close=28457.8, self.high=28480.0, self.low=28290.0, self.vol=10203.227, self.amt=289838887.3221 
127.0.0.1 - - [29/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-03-29 16:25:01,613:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230329   160000    160459  ...         0.0        0.0       0
5953  20230329   160500    160959  ...         0.0        0.0       0
5954  20230329   161000    161459  ...         0.0        0.0       0
5955  20230329   161500    161959  ...         0.0        0.0       0
5956  20230329   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-29 16:25:01,613:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680078299, self.tradeDate='20230329', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28295.5, self.close=28457.8, self.high=28480.0, self.low=28290.0, self.vol=10203.227, self.amt=289838887.3221, ukdf['pct'].iloc[-1]=0.005604 , ukdf['amount'].iloc[-1]=289838887.3221, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230329   040000    075959  1680047999  ...    721  0.185511 -0.789420    -1.0
722  20230329   080000    115959  1680062399  ...    722  0.216890 -0.698211    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '39513.5810808378', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27355.3613287', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1507151.9559834, self.flagDict['side']='sell', self.tradeCount=27, self.count=744127.0.0.1 - - [29/Mar/2023 16:00:01] "POST / HTTP/1.1" 200 -

self.closeSec=1680076799, self.tradeDate='20230329', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27354.1, self.close=28077.7, self.high=28210.7, self.low=27333.7, self.vol=154440.639, self.amt=4298771621.91433 
2023-03-29 16:00:01,923:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1680076799, self.tradeDate='20230329', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=27354.1, self.close=28077.7, self.high=28210.7, self.low=27333.7, self.vol=154440.639, self.amt=4298771621.91433 
2023-03-29 16:00:01,980:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230328   200000    235959  ...  123639.089  3.334585e+09 -0.002244
720  20230329   000000    035959  ...  151133.821  4.096441e+09  0.015831
721  20230329   040000    075959  ...   58236.084  1.587364e+09 -0.005924
722  20230329   080000    115959  ...   46690.555  1.276502e+09  0.003831
723  20230329   120000    155959  ...  154440.639  4.298772e+09  0.026453

[5 rows x 11 columns]
2023-03-29 16:00:05,275:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230328   200000    235959  1680019199  ...    719  0.235390 -0.710596    -1.0
720  20230329   000000    035959  1680033599  ...    720  0.197143 -0.780871    -1.0
721  20230329   040000    075959  1680047999  ...    721  0.185511 -0.789420    -1.0
722  20230329   080000    115959  1680062399  ...    722  0.216890 -0.698211    -1.0
723  20230329   120000    155959  1680076799  ...    723  0.220758 -0.671756    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '714.2898', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28077.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


