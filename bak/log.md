# 20230323 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=33244
self.closeSec=1679501999, self.tradeDate='20230323', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28514.9, self.close=28561.9, self.high=28561.9, self.low=28469.1, self.vol=3444.404, self.amt=98220448.2492 
127.0.0.1 - - [23/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-23 00:20:05,310:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230322   235500    235959  ...         0.0        0.0       0
5760  20230323   000000    000459  ...         0.0        0.0       0
5761  20230323   000500    000959  ...         0.0        0.0       0
5762  20230323   001000    001459  ...         0.0        0.0       0
5763  20230323   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-23 00:20:05,312:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679501999, self.tradeDate='20230323', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28514.9, self.close=28561.9, self.high=28561.9, self.low=28469.1, self.vol=3444.404, self.amt=98220448.2492, ukdf['pct'].iloc[-1]=0.001652 , ukdf['amount'].iloc[-1]=98220448.2492, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-724494.9696', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28568.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=33245
self.closeSec=1679502299, self.tradeDate='20230323', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28561.9, self.close=28564.4, self.high=28568.9, self.low=28510.3, self.vol=2041.223, self.amt=58251364.981 
127.0.0.1 - - [23/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-03-23 00:25:01,581:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230323   000000    000459  ...         0.0        0.0       0
5761  20230323   000500    000959  ...         0.0        0.0       0
5762  20230323   001000    001459  ...         0.0        0.0       0
5763  20230323   001500    001959  ...         0.0        0.0       0
5764  20230323   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-23 00:25:01,582:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679502299, self.tradeDate='20230323', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28561.9, self.close=28564.4, self.high=28568.9, self.low=28510.3, self.vol=2041.223, self.amt=58251364.981, ukdf['pct'].iloc[-1]=8.8e-05 , ukdf['amount'].iloc[-1]=58251364.981, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-724019.5792', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28561', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1679501999, self.tradeDate='20230323', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28514.9, self.close=28561.9, self.high=28561.9, self.low=28469.1 
127.0.0.1 - - [23/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-23 00:20:03,110:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679501999, self.tradeDate='20230323', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28514.9, self.close=28561.9, self.high=28561.9, self.low=28469.1   
2023-03-23 00:20:03,800:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230322   235500    235959  1679500799  ...  28553.0  0.000294   1727    5
1440  20230323   000000    000459  1679501099  ...  28540.1  0.000689   1440    0
1441  20230323   000500    000959  1679501399  ...  28547.6 -0.001975   1441    1
1442  20230323   001000    001459  1679501699  ...  28478.0 -0.001212   1442    2
1443  20230323   001500    001959  1679501999  ...  28469.1  0.001652   1443    3

[5 rows x 11 columns]
2023-03-23 00:20:03,809:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [23/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=252, self.factor=0.3516204495975228, self.count=33811 

self.closeSec=1679502299, self.tradeDate='20230323', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28561.9, self.close=28564.4, self.high=28568.9, self.low=28510.3 
2023-03-23 00:25:01,505:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679502299, self.tradeDate='20230323', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28561.9, self.close=28564.4, self.high=28568.9, self.low=28510.3   
2023-03-23 00:25:01,548:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230323   000000    000459  1679501099  ...  28540.1  0.000689   1440    0
1441  20230323   000500    000959  1679501399  ...  28547.6 -0.001975   1441    1
1442  20230323   001000    001459  1679501699  ...  28478.0 -0.001212   1442    2
1443  20230323   001500    001959  1679501999  ...  28469.1  0.001652   1443    3
1444  20230323   002000    002459  1679502299  ...  28510.3  0.000088   1444    4

[5 rows x 11 columns]
2023-03-23 00:25:01,548:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-23 00:00:33,331:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230322    212959  28207.0  ...  52.916667  0.552156  0.407588
5803  20230322    215959  28306.0  ...  52.916667  0.546216  0.396850
5804  20230322    222959  28269.7  ...  53.333333  0.561081  0.375284
5805  20230322    225959  28381.9  ...  53.750000  0.581510  0.366781
5806  20230322    232959  28545.9  ...  53.750000  0.596547  0.348824

[5 rows x 33 columns]
0.5349264705882353
acc is : 0.5349264705882353
2023-03-23 00:00:33,502:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.570129  0.429871       0  ...  1.240734   1.0    0.0  1.424568
540     0  0.524490  0.475510       1  ...  1.245662   1.0    0.0  1.430227
541     0  0.582100  0.417900       1  ...  1.252860   1.0    0.0  1.438491
542     0  0.605409  0.394591       1  ...  1.258509   1.0    0.0  1.444977
543     0  0.603946  0.396054       0  ...  1.254625   1.0    0.0  1.440517

[5 rows x 10 columns]
2023-03-23 00:00:33,532:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.569186  0.430814       0  ...  1.240734   1.0    0.0  1.393022
46     0  0.523644  0.476356       1  ...  1.245662   1.0    0.0  1.399838
47     0  0.581559  0.418441       1  ...  1.252860   1.0    0.0  1.407927
48     0  0.605551  0.394449       1  ...  1.258509   1.0    0.0  1.420278
49     0  0.603946  0.396054       0  ...  1.254625   1.0    0.0  1.440517

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [23/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-23 00:00:03,755:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42042F1679500803071I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1679500803445137, 'quantity': '27.638', 'price': '28595.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1679500802492, 'updatetime': 1679500803445, 'tradetype': 'usdt', 'selfid': 42042, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1679500803445, 'clientorderid': '42042F1679500803071I0L59', 'price': '28595.7', 'quantity': '27.638', 'commission': '790.3279566', 'commissionasset': 'USDT', 'tradetime': 1679500803445, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1679500803445}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16904 

self.closeSec=1679501399, self.tradeDate='20230323', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28586.1', self.close='28549.4'
127.0.0.1 - - [23/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-03-23 00:10:01,723:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679501399, self.tradeDate='20230323', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='28586.1', self.close='28549.4'
2023-03-23 00:10:01,731:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230322   232000    232959  1679498999  28635.9  28674.7  0.001355
573  20230322   233000    233959  1679499599  28674.7  28634.4 -0.001405
574  20230322   234000    234959  1679500199  28634.4  28474.4 -0.005588
575  20230322   235000    235959  1679500799  28462.3  28586.2  0.003926
576  20230323   000000    000959  1679501399  28586.1  28549.4 -0.001287
2023-03-23 00:10:01,736:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16905 

self.closeSec=1679501999, self.tradeDate='20230323', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28547.7', self.close='28561.9'
127.0.0.1 - - [23/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-23 00:20:04,450:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679501999, self.tradeDate='20230323', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='28547.7', self.close='28561.9'
2023-03-23 00:20:05,041:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230322   233000    233959  1679499599  28674.7  28634.4 -0.001405
574  20230322   234000    234959  1679500199  28634.4  28474.4 -0.005588
575  20230322   235000    235959  1679500799  28462.3  28586.2  0.003926
576  20230323   000000    000959  1679501399  28586.1  28549.4 -0.001287
577  20230323   001000    001959  1679501999  28547.7  28561.9  0.000438
2023-03-23 00:20:05,049:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

127.0.0.1 - - [23/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-23 00:00:03,226:INFO:pyemd2:main.py:303:handleOrderFilled:185189: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42041F1679500802818I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1679500802991464, 'quantity': '36.905', 'price': '28595.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1679500802520, 'updatetime': 1679500802991, 'tradetype': 'usdt', 'selfid': 42041, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1679500802991, 'clientorderid': '42041F1679500802818I0L57', 'price': '28595.7', 'quantity': '36.905', 'commission': '1055.3243085', 'commissionasset': 'USDT', 'tradetime': 1679500802991, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1679500802991}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [23/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16905 

self.closeSec=1679501399, self.tradeDate='20230323', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28586.1', self.close='28549.4'
2023-03-23 00:10:01,758:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679501399, self.tradeDate='20230323', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='28586.1', self.close='28549.4'
2023-03-23 00:10:01,781:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230322   232000    232959  1679498999  28635.9  28674.7
17421  20230322   233000    233959  1679499599  28674.7  28634.4
17422  20230322   234000    234959  1679500199  28634.4  28474.4
17423  20230322   235000    235959  1679500799  28462.3  28586.2
17424  20230323   000000    000959  1679501399  28586.1  28549.4
2023-03-23 00:10:01,781:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16906 

self.closeSec=1679501999, self.tradeDate='20230323', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28547.7', self.close='28561.9'
127.0.0.1 - - [23/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-23 00:20:07,172:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679501999, self.tradeDate='20230323', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='28547.7', self.close='28561.9'
2023-03-23 00:20:07,314:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230322   233000    233959  1679499599  28674.7  28634.4
17422  20230322   234000    234959  1679500199  28634.4  28474.4
17423  20230322   235000    235959  1679500799  28462.3  28586.2
17424  20230323   000000    000959  1679501399  28586.1  28549.4
17425  20230323   001000    001959  1679501999  28547.7  28561.9
2023-03-23 00:20:07,315:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [23/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-23 00:00:03,563:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42043F1679500803084I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1679500803334922, 'quantity': '39.175', 'price': '28595.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1679500802773, 'updatetime': 1679500803334, 'tradetype': 'usdt', 'selfid': 42043, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1679500803334, 'clientorderid': '42043F1679500803084I0L2', 'price': '28595.7', 'quantity': '39.175', 'commission': '1120.2365475', 'commissionasset': 'USDT', 'tradetime': 1679500803334, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1679500803334}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [23/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16905 

self.closeSec=1679501399, self.tradeDate='20230323', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28586.1', self.close='28549.4'
2023-03-23 00:10:01,793:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679501399, self.tradeDate='20230323', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='28586.1', self.close='28549.4'
2023-03-23 00:10:01,821:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230322   232000    232959  1679498999  28635.9  28674.7
12237  20230322   233000    233959  1679499599  28674.7  28634.4
12238  20230322   234000    234959  1679500199  28634.4  28474.4
12239  20230322   235000    235959  1679500799  28462.3  28586.2
12240  20230323   000000    000959  1679501399  28586.1  28549.4
2023-03-23 00:10:01,821:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16906 

self.closeSec=1679501999, self.tradeDate='20230323', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28547.7', self.close='28561.9'
127.0.0.1 - - [23/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-23 00:20:06,671:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679501999, self.tradeDate='20230323', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='28547.7', self.close='28561.9'
2023-03-23 00:20:06,965:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230322   233000    233959  1679499599  28674.7  28634.4
12238  20230322   234000    234959  1679500199  28634.4  28474.4
12239  20230322   235000    235959  1679500799  28462.3  28586.2
12240  20230323   000000    000959  1679501399  28586.1  28549.4
12241  20230323   001000    001959  1679501999  28547.7  28561.9
2023-03-23 00:20:06,965:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=29242
self.closeSec=1679501999, self.tradeDate='20230323', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28514.9, self.close=28561.9, self.high=28561.9, self.low=28469.1, self.vol=3444.404, self.amt=98220448.2492 
127.0.0.1 - - [23/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-23 00:20:01,615:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230322   235500    235959  ...         0.0        0.0       0
5760  20230323   000000    000459  ...         0.0        0.0       0
5761  20230323   000500    000959  ...         0.0        0.0       0
5762  20230323   001000    001459  ...         0.0        0.0       0
5763  20230323   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-23 00:20:01,619:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679501999, self.tradeDate='20230323', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28514.9, self.close=28561.9, self.high=28561.9, self.low=28469.1, self.vol=3444.404, self.amt=98220448.2492, ukdf['pct'].iloc[-1]=0.001652 , ukdf['amount'].iloc[-1]=98220448.2492, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=29243
self.closeSec=1679502299, self.tradeDate='20230323', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28561.9, self.close=28564.4, self.high=28568.9, self.low=28510.3, self.vol=2041.223, self.amt=58251364.981 
127.0.0.1 - - [23/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-03-23 00:25:01,595:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230323   000000    000459  ...         0.0        0.0       0
5761  20230323   000500    000959  ...         0.0        0.0       0
5762  20230323   001000    001459  ...         0.0        0.0       0
5763  20230323   001500    001959  ...         0.0        0.0       0
5764  20230323   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-23 00:25:01,595:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679502299, self.tradeDate='20230323', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28561.9, self.close=28564.4, self.high=28568.9, self.low=28510.3, self.vol=2041.223, self.amt=58251364.981, ukdf['pct'].iloc[-1]=8.8e-05 , ukdf['amount'].iloc[-1]=58251364.981, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230322   120000    155959  1679471999  ...    723  0.493981 -0.688068    -1.0
724  20230322   160000    195959  1679486399  ...    724  0.444860 -0.872578    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '-1188.78444105408', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28113.23503968', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1507151.9559834, self.flagDict['side']='sell', self.tradeCount=27, self.count=704
self.closeSec=1679500799, self.tradeDate='20230322', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=28113.5, self.close=28586.2, self.high=28758.1, self.low=28090.4, self.vol=220961.586, self.amt=6291734510.61832 
127.0.0.1 - - [23/Mar/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-03-23 00:00:01,924:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1679500799, self.tradeDate='20230322', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=28113.5, self.close=28586.2, self.high=28758.1, self.low=28090.4, self.vol=220961.586, self.amt=6291734510.61832 
2023-03-23 00:00:01,967:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230322   040000    075959  ...   50579.928  1.418130e+09 -0.000587
722  20230322   080000    115959  ...   62536.552  1.756711e+09  0.001659
723  20230322   120000    155959  ...   54361.466  1.530369e+09 -0.001759
724  20230322   160000    195959  ...   61658.449  1.732829e+09  0.000901
725  20230322   200000    235959  ...  220961.586  6.291735e+09  0.016814

[5 rows x 11 columns]
2023-03-23 00:00:04,881:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230322   040000    075959  1679443199  ...    721  0.438918 -0.819217    -1.0
722  20230322   080000    115959  1679457599  ...    722  0.541432 -0.515098     NaN
723  20230322   120000    155959  1679471999  ...    723  0.493981 -0.688068    -1.0
724  20230322   160000    195959  1679486399  ...    724  0.444860 -0.872578    -1.0
725  20230322   200000    235959  1679500799  ...    725  0.475192 -0.815555    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '-27100.0476', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28595.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


