# 20230317 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=31708
self.closeSec=1679041199, self.tradeDate='20230317', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26118.6, self.close=26043.4, self.high=26118.8, self.low=26008.6, self.vol=5539.912, self.amt=144356617.6816 
127.0.0.1 - - [17/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-17 16:20:03,502:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230317   155500    155959  ...         0.0        0.0       0
5952  20230317   160000    160459  ...         0.0        0.0       0
5953  20230317   160500    160959  ...         0.0        0.0       0
5954  20230317   161000    161459  ...         0.0        0.0       0
5955  20230317   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-17 16:20:03,513:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679041199, self.tradeDate='20230317', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26118.6, self.close=26043.4, self.high=26118.8, self.low=26008.6, self.vol=5539.912, self.amt=144356617.6816, ukdf['pct'].iloc[-1]=-0.002891 , ukdf['amount'].iloc[-1]=144356617.6816, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-572339.3456930216', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26040.38989785', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [17/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=31709
self.closeSec=1679041499, self.tradeDate='20230317', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26041.3, self.close=26075.3, self.high=26114.5, self.low=26031.6, self.vol=2383.426, self.amt=62174492.4025 
2023-03-17 16:25:01,627:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230317   160000    160459  ...         0.0        0.0       0
5953  20230317   160500    160959  ...         0.0        0.0       0
5954  20230317   161000    161459  ...         0.0        0.0       0
5955  20230317   161500    161959  ...         0.0        0.0       0
5956  20230317   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-17 16:25:01,628:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679041499, self.tradeDate='20230317', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26041.3, self.close=26075.3, self.high=26114.5, self.low=26031.6, self.vol=2383.426, self.amt=62174492.4025, ukdf['pct'].iloc[-1]=0.001225 , ukdf['amount'].iloc[-1]=62174492.4025, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-574355.8496', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26073.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=45, self.factor=0.3087028505762341, self.count=32274 

self.closeSec=1679041199, self.tradeDate='20230317', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26118.6, self.close=26043.4, self.high=26118.8, self.low=26008.6 
2023-03-17 16:20:02,353:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679041199, self.tradeDate='20230317', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26118.6, self.close=26043.4, self.high=26118.8, self.low=26008.6   
2023-03-17 16:20:02,893:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230317   155500    155959  1679039999  ...  25982.0  0.001519   1631    5
1632  20230317   160000    160459  1679040299  ...  25998.3  0.000065   1632    0
1633  20230317   160500    160959  1679040599  ...  26048.5  0.002227   1633    1
1634  20230317   161000    161459  1679040899  ...  26082.0  0.000471   1634    2
1635  20230317   161500    161959  1679041199  ...  26008.6 -0.002891   1635    3

[5 rows x 11 columns]
2023-03-17 16:20:02,902:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [17/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=45, self.factor=0.3087028505762341, self.count=32275 

self.closeSec=1679041499, self.tradeDate='20230317', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26041.3, self.close=26075.3, self.high=26114.5, self.low=26031.6 
2023-03-17 16:25:01,527:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679041499, self.tradeDate='20230317', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26041.3, self.close=26075.3, self.high=26114.5, self.low=26031.6   
2023-03-17 16:25:01,593:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230317   160000    160459  1679040299  ...  25998.3  0.000065   1632    0
1633  20230317   160500    160959  1679040599  ...  26048.5  0.002227   1633    1
1634  20230317   161000    161459  1679040899  ...  26082.0  0.000471   1634    2
1635  20230317   161500    161959  1679041199  ...  26008.6 -0.002891   1635    3
1636  20230317   162000    162459  1679041499  ...  26031.6  0.001225   1636    4

[5 rows x 11 columns]
2023-03-17 16:25:01,593:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-17 16:00:32,644:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230317    132959  25710.1  ...  52.083333  0.598414  0.213136
5787  20230317    135959  25704.6  ...  52.500000  0.602540  0.205779
5788  20230317    142959  25754.6  ...  52.500000  0.609967  0.198997
5789  20230317    145959  25845.7  ...  52.916667  0.632244  0.188316
5790  20230317    152959  26134.7  ...  52.500000  0.607611  0.186308

[5 rows x 33 columns]
0.5571955719557196
acc is : 0.5571955719557196
2023-03-17 16:00:32,863:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.512113  0.487887       1  ...  1.122223   1.0    0.0  1.147965
538     0  0.518481  0.481519       1  ...  1.126189   1.0    0.0  1.152021
539     0  0.537813  0.462187       1  ...  1.138786   1.0    0.0  1.164908
540     0  0.630810  0.369190       0  ...  1.130023   1.0    0.0  1.155944
541     1  0.453682  0.546318       1  ...  1.134960   1.0    0.0  1.160994

[5 rows x 10 columns]
2023-03-17 16:00:32,901:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.511683  0.488317       1  ...  1.122223   1.0    0.0  1.148615
46     0  0.518714  0.481286       1  ...  1.126189   1.0    0.0  1.154326
47     0  0.537150  0.462850       1  ...  1.138786   1.0    0.0  1.165718
48     0  0.630414  0.369586       0  ...  1.130023   1.0    0.0  1.155794
49     1  0.453682  0.546318       1  ...  1.134960   1.0    0.0  1.160994

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230317   155000    155959  1679039999  25997.8  26046.9  0.001892
2023-03-17 16:00:02,228:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16136 

self.closeSec=1679040599, self.tradeDate='20230317', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26046.9', self.close='26106.6'
2023-03-17 16:10:01,626:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679040599, self.tradeDate='20230317', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26046.9', self.close='26106.6'
2023-03-17 16:10:01,632:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230317   152000    152959  1679038199  25913.1  25933.6  0.000926
525  20230317   153000    153959  1679038799  25933.5  26019.9  0.003328
526  20230317   154000    154959  1679039399  26019.9  25997.7 -0.000853
527  20230317   155000    155959  1679039999  25997.8  26046.9  0.001892
528  20230317   160000    160959  1679040599  26046.9  26106.6  0.002292
2023-03-17 16:10:01,632:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [17/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16137 

self.closeSec=1679041199, self.tradeDate='20230317', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26104.5', self.close='26043.4'
127.0.0.1 - - [17/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-17 16:20:03,083:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679041199, self.tradeDate='20230317', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26104.5', self.close='26043.4'
2023-03-17 16:20:03,422:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230317   153000    153959  1679038799  25933.5  26019.9  0.003328
526  20230317   154000    154959  1679039399  26019.9  25997.7 -0.000853
527  20230317   155000    155959  1679039999  25997.8  26046.9  0.001892
528  20230317   160000    160959  1679040599  26046.9  26106.6  0.002292
529  20230317   161000    161959  1679041199  26104.5  26043.4 -0.002421
2023-03-17 16:20:03,423:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230317   155000    155959  1679039999  25997.8  26046.9
2023-03-17 16:00:02,327:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [17/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16137 

self.closeSec=1679040599, self.tradeDate='20230317', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26046.9', self.close='26106.6'
2023-03-17 16:10:01,602:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679040599, self.tradeDate='20230317', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26046.9', self.close='26106.6'
2023-03-17 16:10:01,640:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230317   152000    152959  1679038199  25913.1  25933.6
17517  20230317   153000    153959  1679038799  25933.5  26019.9
17518  20230317   154000    154959  1679039399  26019.9  25997.7
17519  20230317   155000    155959  1679039999  25997.8  26046.9
17520  20230317   160000    160959  1679040599  26046.9  26106.6
2023-03-17 16:10:01,641:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16138 

self.closeSec=1679041199, self.tradeDate='20230317', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26104.5', self.close='26043.4'
127.0.0.1 - - [17/Mar/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-03-17 16:20:04,613:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679041199, self.tradeDate='20230317', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26104.5', self.close='26043.4'
2023-03-17 16:20:04,748:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230317   153000    153959  1679038799  25933.5  26019.9
17518  20230317   154000    154959  1679039399  26019.9  25997.7
17519  20230317   155000    155959  1679039999  25997.8  26046.9
17520  20230317   160000    160959  1679040599  26046.9  26106.6
17521  20230317   161000    161959  1679041199  26104.5  26043.4
2023-03-17 16:20:04,749:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230317   155000    155959  1679039999  25997.8  26046.9
2023-03-17 16:00:02,314:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16137 

self.closeSec=1679040599, self.tradeDate='20230317', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26046.9', self.close='26106.6'
2023-03-17 16:10:01,626:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679040599, self.tradeDate='20230317', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26046.9', self.close='26106.6'
127.0.0.1 - - [17/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-03-17 16:10:01,674:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230317   152000    152959  1679038199  25913.1  25933.6
12189  20230317   153000    153959  1679038799  25933.5  26019.9
12190  20230317   154000    154959  1679039399  26019.9  25997.7
12191  20230317   155000    155959  1679039999  25997.8  26046.9
12192  20230317   160000    160959  1679040599  26046.9  26106.6
2023-03-17 16:10:01,674:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16138 

self.closeSec=1679041199, self.tradeDate='20230317', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26104.5', self.close='26043.4'
127.0.0.1 - - [17/Mar/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-03-17 16:20:04,245:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679041199, self.tradeDate='20230317', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26104.5', self.close='26043.4'
2023-03-17 16:20:04,458:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230317   153000    153959  1679038799  25933.5  26019.9
12190  20230317   154000    154959  1679039399  26019.9  25997.7
12191  20230317   155000    155959  1679039999  25997.8  26046.9
12192  20230317   160000    160959  1679040599  26046.9  26106.6
12193  20230317   161000    161959  1679041199  26104.5  26043.4
2023-03-17 16:20:04,458:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [17/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=27706
self.closeSec=1679041199, self.tradeDate='20230317', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26118.6, self.close=26043.4, self.high=26118.8, self.low=26008.6, self.vol=5539.912, self.amt=144356617.6816 
2023-03-17 16:20:01,624:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230317   155500    155959  ...         0.0        0.0       0
5952  20230317   160000    160459  ...         0.0        0.0       0
5953  20230317   160500    160959  ...         0.0        0.0       0
5954  20230317   161000    161459  ...         0.0        0.0       0
5955  20230317   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-17 16:20:01,626:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679041199, self.tradeDate='20230317', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26118.6, self.close=26043.4, self.high=26118.8, self.low=26008.6, self.vol=5539.912, self.amt=144356617.6816, ukdf['pct'].iloc[-1]=-0.002891 , ukdf['amount'].iloc[-1]=144356617.6816, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=27707
self.closeSec=1679041499, self.tradeDate='20230317', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26041.3, self.close=26075.3, self.high=26114.5, self.low=26031.6, self.vol=2383.426, self.amt=62174492.4025 
127.0.0.1 - - [17/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-03-17 16:25:01,551:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230317   160000    160459  ...         0.0        0.0       0
5953  20230317   160500    160959  ...         0.0        0.0       0
5954  20230317   161000    161459  ...         0.0        0.0       0
5955  20230317   161500    161959  ...         0.0        0.0       0
5956  20230317   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-17 16:25:01,552:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679041499, self.tradeDate='20230317', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26041.3, self.close=26075.3, self.high=26114.5, self.low=26031.6, self.vol=2383.426, self.amt=62174492.4025, ukdf['pct'].iloc[-1]=0.001225 , ukdf['amount'].iloc[-1]=62174492.4025, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230317   040000    075959  1679011199  ...    721  0.510269 -0.305711     NaN
722  20230317   080000    115959  1679025599  ...    722  0.513413 -0.289174     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.825', 'enterprice': '20070', 'countrevence': '0', 'unrealprofit': '318275.0725', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25771.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1119287.34225, self.flagDict['side']='buy', self.tradeCount=24, self.count=672
self.closeSec=1679039999, self.tradeDate='20230317', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=25769.9, self.close=26046.9, self.high=26200.0, self.low=25638.8, self.vol=159158.385, self.amt=4126134831.90518 
127.0.0.1 - - [17/Mar/2023 16:00:02] "POST / HTTP/1.1" 200 -
2023-03-17 16:00:02,108:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1679039999, self.tradeDate='20230317', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=25769.9, self.close=26046.9, self.high=26200.0, self.low=25638.8, self.vol=159158.385, self.amt=4126134831.90518 
2023-03-17 16:00:02,142:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230316   200000    235959  ...  182794.492  4.529335e+09  0.002385
720  20230317   000000    035959  ...  128630.721  3.194127e+09  0.002625
721  20230317   040000    075959  ...   91673.471  2.279733e+09  0.001784
722  20230317   080000    115959  ...  202957.831  5.176549e+09  0.031192
723  20230317   120000    155959  ...  159158.385  4.126135e+09  0.010749

[5 rows x 11 columns]
2023-03-17 16:00:04,657:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230316   200000    235959  1678982399  ...    719  0.754877  0.400662     NaN
720  20230317   000000    035959  1678996799  ...    720  0.608782 -0.022024     NaN
721  20230317   040000    075959  1679011199  ...    721  0.510269 -0.305711     NaN
722  20230317   080000    115959  1679025599  ...    722  0.513413 -0.289174     NaN
723  20230317   120000    155959  1679039999  ...    723  0.437985 -0.501484     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.825', 'enterprice': '20070', 'countrevence': '0', 'unrealprofit': '333785.961051158', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26049.14842904', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


