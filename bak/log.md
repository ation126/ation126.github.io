# 20230221 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [21/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=24796
self.closeSec=1676967599, self.tradeDate='20230221', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25040.7, self.close=25069.7, self.high=25190.0, self.low=25016.8, self.vol=11679.444, self.amt=293003472.37757 
2023-02-21 16:20:01,779:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230221   155500    155959  ...         0.0        0.0       0
5952  20230221   160000    160459  ...         0.0        0.0       0
5953  20230221   160500    160959  ...         0.0        0.0       0
5954  20230221   161000    161459  ...         0.0        0.0       0
5955  20230221   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-21 16:20:01,780:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676967599, self.tradeDate='20230221', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25040.7, self.close=25069.7, self.high=25190.0, self.low=25016.8, self.vol=11679.444, self.amt=293003472.37757, ukdf['pct'].iloc[-1]=0.001158 , ukdf['amount'].iloc[-1]=293003472.37757, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-513836.8464', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25068.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=24797
self.closeSec=1676967899, self.tradeDate='20230221', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25069.7, self.close=25096.6, self.high=25116.5, self.low=25037.3, self.vol=3800.084, self.amt=95304451.9354 
127.0.0.1 - - [21/Feb/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-02-21 16:25:01,600:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230221   160000    160459  ...         0.0        0.0       0
5953  20230221   160500    160959  ...         0.0        0.0       0
5954  20230221   161000    161459  ...         0.0        0.0       0
5955  20230221   161500    161959  ...         0.0        0.0       0
5956  20230221   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-21 16:25:01,603:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676967899, self.tradeDate='20230221', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25069.7, self.close=25096.6, self.high=25116.5, self.low=25037.3, self.vol=3800.084, self.amt=95304451.9354, ukdf['pct'].iloc[-1]=0.001073 , ukdf['amount'].iloc[-1]=95304451.9354, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-515714.92228927232', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25099.40971632', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1676967599, self.tradeDate='20230221', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25040.7, self.close=25069.7, self.high=25190.0, self.low=25016.8 
127.0.0.1 - - [21/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-02-21 16:20:01,659:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676967599, self.tradeDate='20230221', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25040.7, self.close=25069.7, self.high=25190.0, self.low=25016.8   
2023-02-21 16:20:01,694:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230221   155500    155959  1676966399  ...  24990.7 -0.001816   1631    5
1632  20230221   160000    160459  1676966699  ...  24980.2  0.000768   1632    0
1633  20230221   160500    160959  1676966999  ...  25024.5  0.001802   1633    1
1634  20230221   161000    161459  1676967299  ...  25030.0 -0.001125   1634    2
1635  20230221   161500    161959  1676967599  ...  25016.8  0.001158   1635    3

[5 rows x 11 columns]
2023-02-21 16:20:01,694:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=311, self.factor=0.31487304523241577, self.count=25363 

self.closeSec=1676967899, self.tradeDate='20230221', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25069.7, self.close=25096.6, self.high=25116.5, self.low=25037.3 
2023-02-21 16:25:01,535:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676967899, self.tradeDate='20230221', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25069.7, self.close=25096.6, self.high=25116.5, self.low=25037.3   
127.0.0.1 - - [21/Feb/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-02-21 16:25:01,571:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230221   160000    160459  1676966699  ...  24980.2  0.000768   1632    0
1633  20230221   160500    160959  1676966999  ...  25024.5  0.001802   1633    1
1634  20230221   161000    161459  1676967299  ...  25030.0 -0.001125   1634    2
1635  20230221   161500    161959  1676967599  ...  25016.8  0.001158   1635    3
1636  20230221   162000    162459  1676967899  ...  25037.3  0.001073   1636    4

[5 rows x 11 columns]
2023-02-21 16:25:01,575:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-21 16:00:36,690:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230221    132959  24902.7  ...  48.750000  0.539503  0.321006
5787  20230221    135959  24906.1  ...  49.166667  0.546693  0.322564
5788  20230221    142959  24948.8  ...  48.750000  0.546021  0.324416
5789  20230221    145959  24945.6  ...  49.166667  0.561510  0.314982
5790  20230221    152959  25038.6  ...  48.750000  0.552850  0.311200

[5 rows x 33 columns]
0.5129151291512916
acc is : 0.5129151291512916
2023-02-21 16:00:36,843:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.507757  0.492243       1  ...  0.996955   1.0    0.0  1.143511
538     0  0.508863  0.491137       0  ...  0.996823   1.0    0.0  1.143360
539     0  0.507591  0.492409       1  ...  1.000535   1.0    0.0  1.147618
540     0  0.529790  0.470210       0  ...  0.998865   1.0    0.0  1.145702
541     0  0.505478  0.494522       1  ...  0.999180   1.0    0.0  1.146064

[5 rows x 10 columns]
2023-02-21 16:00:36,880:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.507769  0.492231       1  ...  0.996955   1.0    0.0  1.146680
46     0  0.508433  0.491567       0  ...  1.043414   1.0    0.0  1.142805
47     0  0.507625  0.492375       1  ...  1.000535   1.0    0.0  1.149024
48     0  0.529410  0.470590       0  ...  1.045551   1.0    0.0  1.144852
49     0  0.505478  0.494522       1  ...  0.999180   1.0    0.0  1.146064

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '34.222', 'enterprice': '24804.7', 'countrevence': '0', 'unrealprofit': '6471.86083875006', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24993.81404473', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230221   155000    155959  1676966399  25013.3  25004.6 -0.000348
2023-02-21 16:00:02,135:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12680 

self.closeSec=1676966999, self.tradeDate='20230221', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25004.6', self.close='25071.8'
2023-02-21 16:10:01,623:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676966999, self.tradeDate='20230221', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='25004.6', self.close='25071.8'
127.0.0.1 - - [21/Feb/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-02-21 16:10:01,659:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230221   152000    152959  1676964599  24988.1  24996.7  0.000340
525  20230221   153000    153959  1676965199  24996.7    24988 -0.000348
526  20230221   154000    154959  1676965799  24988.1  25013.3  0.001012
527  20230221   155000    155959  1676966399  25013.3  25004.6 -0.000348
528  20230221   160000    160959  1676966999  25004.6  25071.8  0.002688
2023-02-21 16:10:01,659:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [21/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12681 

self.closeSec=1676967599, self.tradeDate='20230221', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25071.7', self.close='25069.7'
2023-02-21 16:20:01,757:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676967599, self.tradeDate='20230221', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='25071.7', self.close='25069.7'
2023-02-21 16:20:01,798:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230221   153000    153959  1676965199  24996.7    24988 -0.000348
526  20230221   154000    154959  1676965799  24988.1  25013.3  0.001012
527  20230221   155000    155959  1676966399  25013.3  25004.6 -0.000348
528  20230221   160000    160959  1676966999  25004.6  25071.8  0.002688
529  20230221   161000    161959  1676967599  25071.7  25069.7 -0.000084
2023-02-21 16:20:01,798:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230221   155000    155959  1676966399  25013.3  25004.6
2023-02-21 16:00:02,121:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12681 

self.closeSec=1676966999, self.tradeDate='20230221', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25004.6', self.close='25071.8'
2023-02-21 16:10:01,620:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676966999, self.tradeDate='20230221', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='25004.6', self.close='25071.8'
127.0.0.1 - - [21/Feb/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-02-21 16:10:01,676:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230221   152000    152959  1676964599  24988.1  24996.7
17517  20230221   153000    153959  1676965199  24996.7    24988
17518  20230221   154000    154959  1676965799  24988.1  25013.3
17519  20230221   155000    155959  1676966399  25013.3  25004.6
17520  20230221   160000    160959  1676966999  25004.6  25071.8
2023-02-21 16:10:01,676:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12682 

self.closeSec=1676967599, self.tradeDate='20230221', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25071.7', self.close='25069.7'
127.0.0.1 - - [21/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-02-21 16:20:01,753:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676967599, self.tradeDate='20230221', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='25071.7', self.close='25069.7'
2023-02-21 16:20:01,788:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230221   153000    153959  1676965199  24996.7    24988
17518  20230221   154000    154959  1676965799  24988.1  25013.3
17519  20230221   155000    155959  1676966399  25013.3  25004.6
17520  20230221   160000    160959  1676966999  25004.6  25071.8
17521  20230221   161000    161959  1676967599  25071.7  25069.7
2023-02-21 16:20:01,791:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230221   155000    155959  1676966399  25013.3  25004.6
2023-02-21 16:00:02,154:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12681 

self.closeSec=1676966999, self.tradeDate='20230221', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25004.6', self.close='25071.8'
2023-02-21 16:10:01,593:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676966999, self.tradeDate='20230221', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='25004.6', self.close='25071.8'
127.0.0.1 - - [21/Feb/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-02-21 16:10:01,660:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230221   152000    152959  1676964599  24988.1  24996.7
12189  20230221   153000    153959  1676965199  24996.7    24988
12190  20230221   154000    154959  1676965799  24988.1  25013.3
12191  20230221   155000    155959  1676966399  25013.3  25004.6
12192  20230221   160000    160959  1676966999  25004.6  25071.8
2023-02-21 16:10:01,661:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [21/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12682 

self.closeSec=1676967599, self.tradeDate='20230221', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25071.7', self.close='25069.7'
2023-02-21 16:20:01,769:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676967599, self.tradeDate='20230221', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='25071.7', self.close='25069.7'
2023-02-21 16:20:01,821:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230221   153000    153959  1676965199  24996.7    24988
12190  20230221   154000    154959  1676965799  24988.1  25013.3
12191  20230221   155000    155959  1676966399  25013.3  25004.6
12192  20230221   160000    160959  1676966999  25004.6  25071.8
12193  20230221   161000    161959  1676967599  25071.7  25069.7
2023-02-21 16:20:01,822:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=20794
self.closeSec=1676967599, self.tradeDate='20230221', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25040.7, self.close=25069.7, self.high=25190.0, self.low=25016.8, self.vol=11679.444, self.amt=293003472.37757 
127.0.0.1 - - [21/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-02-21 16:20:01,715:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230221   155500    155959  ...         0.0        0.0       0
5952  20230221   160000    160459  ...         0.0        0.0       0
5953  20230221   160500    160959  ...         0.0        0.0       0
5954  20230221   161000    161459  ...         0.0        0.0       0
5955  20230221   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-21 16:20:01,715:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676967599, self.tradeDate='20230221', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25040.7, self.close=25069.7, self.high=25190.0, self.low=25016.8, self.vol=11679.444, self.amt=293003472.37757, ukdf['pct'].iloc[-1]=0.001158 , ukdf['amount'].iloc[-1]=293003472.37757, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=20795
self.closeSec=1676967899, self.tradeDate='20230221', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25069.7, self.close=25096.6, self.high=25116.5, self.low=25037.3, self.vol=3800.084, self.amt=95304451.9354 
127.0.0.1 - - [21/Feb/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-02-21 16:25:01,603:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230221   160000    160459  ...         0.0        0.0       0
5953  20230221   160500    160959  ...         0.0        0.0       0
5954  20230221   161000    161459  ...         0.0        0.0       0
5955  20230221   161500    161959  ...         0.0        0.0       0
5956  20230221   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-21 16:25:01,603:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676967899, self.tradeDate='20230221', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25069.7, self.close=25096.6, self.high=25116.5, self.low=25037.3, self.vol=3800.084, self.amt=95304451.9354, ukdf['pct'].iloc[-1]=0.001073 , ukdf['amount'].iloc[-1]=95304451.9354, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230221   040000    075959  1676937599  ...    721  0.197351 -1.167501    -1.0
722  20230221   080000    115959  1676951999  ...    722  0.389758 -0.650516    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.465', 'enterprice': '24934.8', 'countrevence': '0', 'unrealprofit': '339.64805462445', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24925.48564227', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [21/Feb/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=908338.234518, self.flagDict['side']='sell', self.tradeCount=21, self.count=528
self.closeSec=1676966399, self.tradeDate='20230221', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=24926.2, self.close=25004.6, self.high=25053.9, self.low=24855.2, self.vol=46758.131, self.amt=1167207525.5163 
2023-02-21 16:00:01,844:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1676966399, self.tradeDate='20230221', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=24926.2, self.close=25004.6, self.high=25053.9, self.low=24855.2, self.vol=46758.131, self.amt=1167207525.5163 
2023-02-21 16:00:01,888:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230220   200000    235959  ...  167345.352  4.170410e+09  0.001956
720  20230221   000000    035959  ...  102254.274  2.538101e+09 -0.002650
721  20230221   040000    075959  ...   38879.181  9.633554e+08 -0.001150
722  20230221   080000    115959  ...   76679.867  1.912971e+09  0.003070
723  20230221   120000    155959  ...   46758.131  1.167208e+09  0.003145

[5 rows x 11 columns]
2023-02-21 16:00:04,828:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230220   200000    235959  1676908799  ...    719  0.220485 -1.139201    -1.0
720  20230221   000000    035959  1676923199  ...    720  0.226097 -1.115725    -1.0
721  20230221   040000    075959  1676937599  ...    721  0.197351 -1.167501    -1.0
722  20230221   080000    115959  1676951999  ...    722  0.389758 -0.650516    -1.0
723  20230221   120000    155959  1676966399  ...    723  0.332460 -0.788208    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.465', 'enterprice': '24934.8', 'countrevence': '0', 'unrealprofit': '-2585.3685', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25005.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


