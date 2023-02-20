# 20230220 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [20/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=24508
self.closeSec=1676881199, self.tradeDate='20230220', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=24510.9, self.close=24468.4, self.high=24570.0, self.low=24466.5, self.vol=3564.948, self.amt=87391353.9046 
2023-02-20 16:20:01,633:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230220   155500    155959  ...         0.0        0.0       0
5952  20230220   160000    160459  ...         0.0        0.0       0
5953  20230220   160500    160959  ...         0.0        0.0       0
5954  20230220   161000    161459  ...         0.0        0.0       0
5955  20230220   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-20 16:20:01,644:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676881199, self.tradeDate='20230220', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=24510.9, self.close=24468.4, self.high=24570.0, self.low=24466.5, self.vol=3564.948, self.amt=87391353.9046, ukdf['pct'].iloc[-1]=-0.001734 , ukdf['amount'].iloc[-1]=87391353.9046, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-478120.8711004224', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24474.6747524', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=24509
self.closeSec=1676881499, self.tradeDate='20230220', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=24468.5, self.close=24510.1, self.high=24519.8, self.low=24468.4, self.vol=1238.474, self.amt=30333412.449 
127.0.0.1 - - [20/Feb/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-02-20 16:25:01,617:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230220   160000    160459  ...         0.0        0.0       0
5953  20230220   160500    160959  ...         0.0        0.0       0
5954  20230220   161000    161459  ...         0.0        0.0       0
5955  20230220   161500    161959  ...         0.0        0.0       0
5956  20230220   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-20 16:25:01,618:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676881499, self.tradeDate='20230220', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=24468.5, self.close=24510.1, self.high=24519.8, self.low=24468.4, self.vol=1238.474, self.amt=30333412.449, ukdf['pct'].iloc[-1]=0.001704 , ukdf['amount'].iloc[-1]=30333412.449, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-480252.6208', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24510.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=263, self.factor=0.5903512573173919, self.count=25074 

self.closeSec=1676881199, self.tradeDate='20230220', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=24510.9, self.close=24468.4, self.high=24570.0, self.low=24466.5 
2023-02-20 16:20:01,553:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676881199, self.tradeDate='20230220', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=24510.9, self.close=24468.4, self.high=24570.0, self.low=24466.5   
2023-02-20 16:20:01,605:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230220   155500    155959  1676879999  ...  24500.0 -0.001215   1631    5
1632  20230220   160000    160459  1676880299  ...  24493.7  0.000400   1632    0
1633  20230220   160500    160959  1676880599  ...  24495.6  0.000273   1633    1
1634  20230220   161000    161459  1676880899  ...  24505.0 -0.000232   1634    2
1635  20230220   161500    161959  1676881199  ...  24466.5 -0.001734   1635    3

[5 rows x 11 columns]
2023-02-20 16:20:01,605:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [20/Feb/2023 16:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=263, self.factor=0.5903512573173919, self.count=25075 

self.closeSec=1676881499, self.tradeDate='20230220', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=24468.5, self.close=24510.1, self.high=24519.8, self.low=24468.4 
2023-02-20 16:25:01,569:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676881499, self.tradeDate='20230220', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=24468.5, self.close=24510.1, self.high=24519.8, self.low=24468.4   
2023-02-20 16:25:01,647:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230220   160000    160459  1676880299  ...  24493.7  0.000400   1632    0
1633  20230220   160500    160959  1676880599  ...  24495.6  0.000273   1633    1
1634  20230220   161000    161459  1676880899  ...  24505.0 -0.000232   1634    2
1635  20230220   161500    161959  1676881199  ...  24466.5 -0.001734   1635    3
1636  20230220   162000    162459  1676881499  ...  24468.4  0.001704   1636    4

[5 rows x 11 columns]
2023-02-20 16:25:01,647:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-20 16:00:34,817:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230220    132959  24482.3  ...  53.750000  0.494140  0.659556
5787  20230220    135959  24450.1  ...  53.750000  0.500578  0.649972
5788  20230220    142959  24491.8  ...  53.333333  0.496062  0.642450
5789  20230220    145959  24462.4  ...  53.750000  0.501945  0.633604
5790  20230220    152959  24500.2  ...  53.333333  0.496721  0.626960

[5 rows x 33 columns]
0.5018450184501845
acc is : 0.5018450184501845
2023-02-20 16:00:34,999:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.510845  0.489155       1  ...  1.058869  -1.0    0.0  1.066145
538     0  0.521421  0.478579       0  ...  1.060136  -1.0    0.0  1.064869
539     0  0.506730  0.493270       1  ...  1.058506  -1.0    0.0  1.066506
540     0  0.516190  0.483810       0  ...  1.059941  -1.0    0.0  1.065061
541     1  0.496019  0.503981       1  ...  1.058503  -1.0    0.0  1.066506

[5 rows x 10 columns]
2023-02-20 16:00:35,029:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.510853  0.489147       1  ...  1.058869  -1.0    0.0  1.068442
46     0  0.522041  0.477959       0  ...  1.060136  -1.0    0.0  1.067994
47     0  0.506741  0.493259       1  ...  1.058506  -1.0    0.0  1.067263
48     0  0.515649  0.484351       0  ...  1.059941  -1.0    0.0  1.064639
49     1  0.496019  0.503981       1  ...  1.058503  -1.0    0.0  1.066506

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '35.348', 'enterprice': '24430.6', 'countrevence': '0', 'unrealprofit': '-2651.1', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24505.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230220   155000    155959  1676879999  24503.3  24500.1 -0.000127
2023-02-20 16:00:02,135:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [20/Feb/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12536 

self.closeSec=1676880599, self.tradeDate='20230220', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='24500.1', self.close='24516.6'
2023-02-20 16:10:01,651:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676880599, self.tradeDate='20230220', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='24500.1', self.close='24516.6'
2023-02-20 16:10:01,694:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230220   152000    152959  1676878199    24470  24466.9 -0.000131
525  20230220   153000    153959  1676878799  24466.9  24512.8  0.001876
526  20230220   154000    154959  1676879399  24512.8  24503.2 -0.000392
527  20230220   155000    155959  1676879999  24503.3  24500.1 -0.000127
528  20230220   160000    160959  1676880599  24500.1  24516.6  0.000673
2023-02-20 16:10:01,694:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [20/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12537 

self.closeSec=1676881199, self.tradeDate='20230220', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='24516.6', self.close='24468.4'
2023-02-20 16:20:01,676:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676881199, self.tradeDate='20230220', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='24516.6', self.close='24468.4'
2023-02-20 16:20:01,722:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230220   153000    153959  1676878799  24466.9  24512.8  0.001876
526  20230220   154000    154959  1676879399  24512.8  24503.2 -0.000392
527  20230220   155000    155959  1676879999  24503.3  24500.1 -0.000127
528  20230220   160000    160959  1676880599  24500.1  24516.6  0.000673
529  20230220   161000    161959  1676881199  24516.6  24468.4 -0.001966
2023-02-20 16:20:01,722:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/percentile_regression_step2/log.txt ----- -----

127.0.0.1 - - [20/Feb/2023 15:00:01] "POST / HTTP/1.1" 200 -
2023-02-20 15:00:02,612:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/20 12:30:00  123000  24482.4  ...     NaN     NaN       0
145  2023/02/20 13:00:00  130000  24450.0  ...     NaN     NaN       0
146  2023/02/20 13:30:00  133000  24491.8  ...     NaN     NaN       0
147  2023/02/20 14:00:00  140000  24462.5  ...     NaN     NaN       0
148  2023/02/20 14:30:00  143000  24500.1  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [20/Feb/2023 15:30:02] "POST / HTTP/1.1" 200 -
2023-02-20 15:30:02,921:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/20 13:00:00  130000  24450.0  ...     NaN     NaN       0
145  2023/02/20 13:30:00  133000  24491.8  ...     NaN     NaN       0
146  2023/02/20 14:00:00  140000  24462.5  ...     NaN     NaN       0
147  2023/02/20 14:30:00  143000  24500.1  ...     NaN     NaN       0
148  2023/02/20 15:00:00  150000  24466.9  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [20/Feb/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-02-20 16:00:02,839:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/20 13:30:00  133000  24491.8  ...     NaN     NaN       0
145  2023/02/20 14:00:00  140000  24462.5  ...     NaN     NaN       0
146  2023/02/20 14:30:00  143000  24500.1  ...     NaN     NaN       0
147  2023/02/20 15:00:00  150000  24466.9  ...     NaN     NaN       0
148  2023/02/20 15:30:00  153000  24500.1  ...     NaN     NaN       0

[5 rows x 10 columns]


## /root/FIL/strategy/pyemd/log.txt ----- -----

17519  20230220   155000    155959  1676879999  24503.3  24500.1
2023-02-20 16:00:02,148:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [20/Feb/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12537 

self.closeSec=1676880599, self.tradeDate='20230220', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='24500.1', self.close='24516.6'
2023-02-20 16:10:01,680:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676880599, self.tradeDate='20230220', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='24500.1', self.close='24516.6'
2023-02-20 16:10:01,698:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230220   152000    152959  1676878199    24470  24466.9
17517  20230220   153000    153959  1676878799  24466.9  24512.8
17518  20230220   154000    154959  1676879399  24512.8  24503.2
17519  20230220   155000    155959  1676879999  24503.3  24500.1
17520  20230220   160000    160959  1676880599  24500.1  24516.6
2023-02-20 16:10:01,699:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [20/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12538 

self.closeSec=1676881199, self.tradeDate='20230220', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='24516.6', self.close='24468.4'
2023-02-20 16:20:01,712:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676881199, self.tradeDate='20230220', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='24516.6', self.close='24468.4'
2023-02-20 16:20:01,727:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230220   153000    153959  1676878799  24466.9  24512.8
17518  20230220   154000    154959  1676879399  24512.8  24503.2
17519  20230220   155000    155959  1676879999  24503.3  24500.1
17520  20230220   160000    160959  1676880599  24500.1  24516.6
17521  20230220   161000    161959  1676881199  24516.6  24468.4
2023-02-20 16:20:01,727:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230220   155000    155959  1676879999  24503.3  24500.1
2023-02-20 16:00:02,071:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12537 

self.closeSec=1676880599, self.tradeDate='20230220', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='24500.1', self.close='24516.6'
2023-02-20 16:10:01,676:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676880599, self.tradeDate='20230220', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='24500.1', self.close='24516.6'
127.0.0.1 - - [20/Feb/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-02-20 16:10:01,717:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230220   152000    152959  1676878199    24470  24466.9
12189  20230220   153000    153959  1676878799  24466.9  24512.8
12190  20230220   154000    154959  1676879399  24512.8  24503.2
12191  20230220   155000    155959  1676879999  24503.3  24500.1
12192  20230220   160000    160959  1676880599  24500.1  24516.6
2023-02-20 16:10:01,717:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12538 

self.closeSec=1676881199, self.tradeDate='20230220', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='24516.6', self.close='24468.4'
2023-02-20 16:20:01,660:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676881199, self.tradeDate='20230220', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='24516.6', self.close='24468.4'
127.0.0.1 - - [20/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-02-20 16:20:01,683:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230220   153000    153959  1676878799  24466.9  24512.8
12190  20230220   154000    154959  1676879399  24512.8  24503.2
12191  20230220   155000    155959  1676879999  24503.3  24500.1
12192  20230220   160000    160959  1676880599  24500.1  24516.6
12193  20230220   161000    161959  1676881199  24516.6  24468.4
2023-02-20 16:20:01,684:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=20506
self.closeSec=1676881199, self.tradeDate='20230220', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=24510.9, self.close=24468.4, self.high=24570.0, self.low=24466.5, self.vol=3564.948, self.amt=87391353.9046 
127.0.0.1 - - [20/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-02-20 16:20:01,636:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230220   155500    155959  ...         0.0        0.0       0
5952  20230220   160000    160459  ...         0.0        0.0       0
5953  20230220   160500    160959  ...         0.0        0.0       0
5954  20230220   161000    161459  ...         0.0        0.0       0
5955  20230220   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-20 16:20:01,636:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676881199, self.tradeDate='20230220', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=24510.9, self.close=24468.4, self.high=24570.0, self.low=24466.5, self.vol=3564.948, self.amt=87391353.9046, ukdf['pct'].iloc[-1]=-0.001734 , ukdf['amount'].iloc[-1]=87391353.9046, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=20507
self.closeSec=1676881499, self.tradeDate='20230220', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=24468.5, self.close=24510.1, self.high=24519.8, self.low=24468.4, self.vol=1238.474, self.amt=30333412.449 
127.0.0.1 - - [20/Feb/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-02-20 16:25:01,616:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230220   160000    160459  ...         0.0        0.0       0
5953  20230220   160500    160959  ...         0.0        0.0       0
5954  20230220   161000    161459  ...         0.0        0.0       0
5955  20230220   161500    161959  ...         0.0        0.0       0
5956  20230220   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-20 16:25:01,619:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676881499, self.tradeDate='20230220', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=24468.5, self.close=24510.1, self.high=24519.8, self.low=24468.4, self.vol=1238.474, self.amt=30333412.449, ukdf['pct'].iloc[-1]=0.001704 , ukdf['amount'].iloc[-1]=30333412.449, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230220   040000    075959  1676851199  ...    721  0.152017 -1.404157    -1.0
722  20230220   080000    115959  1676865599  ...    722  0.193163 -1.266190    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.465', 'enterprice': '24934.8', 'countrevence': '0', 'unrealprofit': '18958.1535', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24414.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=908338.234518, self.flagDict['side']='sell', self.tradeCount=21, self.count=522
self.closeSec=1676879999, self.tradeDate='20230220', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=24414.9, self.close=24500.1, self.high=24555.5, self.low=24398.7, self.vol=50497.845, self.amt=1236247565.095 127.0.0.1 - - [20/Feb/2023 16:00:01] "POST / HTTP/1.1" 200 -

2023-02-20 16:00:01,904:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1676879999, self.tradeDate='20230220', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=24414.9, self.close=24500.1, self.high=24555.5, self.low=24398.7, self.vol=50497.845, self.amt=1236247565.095 
2023-02-20 16:00:01,962:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230219   200000    235959  ...  103278.998  2.564951e+09  0.010813
720  20230220   000000    035959  ...  235528.484  5.813210e+09 -0.016830
721  20230220   040000    075959  ...   81659.528  1.993888e+09 -0.010060
722  20230220   080000    115959  ...  127984.816  3.095051e+09  0.006140
723  20230220   120000    155959  ...   50497.845  1.236248e+09  0.003490

[5 rows x 11 columns]
2023-02-20 16:00:04,148:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230219   200000    235959  1676822399  ...    719  0.433753 -0.664721    -1.0
720  20230220   000000    035959  1676836799  ...    720  0.282635 -1.069867    -1.0
721  20230220   040000    075959  1676851199  ...    721  0.152017 -1.404157    -1.0
722  20230220   080000    115959  1676865599  ...    722  0.193163 -1.266190    -1.0
723  20230220   120000    155959  1676879999  ...    723  0.179914 -1.278394    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.465', 'enterprice': '24934.8', 'countrevence': '0', 'unrealprofit': '15842.678643363', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24500.3374018', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


