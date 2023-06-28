# 20230628 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=12928
self.closeSec=1687911599, self.tradeDate='20230628', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30629.2, self.close=30505.0, self.high=30629.3, self.low=30500.0, self.vol=3316.883, self.amt=101333694.39976 
127.0.0.1 - - [28/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-28 08:20:07,588:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230628   075500    075959  ...         0.0        0.0       0
5856  20230628   080000    080459  ...         0.0        0.0       0
5857  20230628   080500    080959  ...         0.0        0.0       0
5858  20230628   081000    081459  ...         0.0        0.0       0
5859  20230628   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-28 08:20:07,619:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687911599, self.tradeDate='20230628', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30629.2, self.close=30505.0, self.high=30629.3, self.low=30500.0, self.vol=3316.883, self.amt=101333694.39976, ukdf['pct'].iloc[-1]=-0.00412 , ukdf['amount'].iloc[-1]=101333694.39976, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-50603.0391250626', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30498.6095451', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [28/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=12929
self.closeSec=1687911899, self.tradeDate='20230628', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30504.5, self.close=30485.1, self.high=30525.2, self.low=30450.0, self.vol=3741.117, self.amt=114039368.47565 
2023-06-28 08:25:00,806:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230628   080000    080459  ...         0.0        0.0       0
5857  20230628   080500    080959  ...         0.0        0.0       0
5858  20230628   081000    081459  ...         0.0        0.0       0
5859  20230628   081500    081959  ...         0.0        0.0       0
5860  20230628   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-28 08:25:00,807:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687911899, self.tradeDate='20230628', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30504.5, self.close=30485.1, self.high=30525.2, self.low=30450.0, self.vol=3741.117, self.amt=114039368.47565, ukdf['pct'].iloc[-1]=-0.000652 , ukdf['amount'].iloc[-1]=114039368.47565, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-50420.4756', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30485.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1687911599, self.tradeDate='20230628', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30629.2, self.close=30505.0, self.high=30629.3, self.low=30500.0 
127.0.0.1 - - [28/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-28 08:20:04,928:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687911599, self.tradeDate='20230628', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30629.2, self.close=30505.0, self.high=30629.3, self.low=30500.0   
2023-06-28 08:20:06,488:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230628   075500    075959  1687910399  ...  30661.2 -0.000323   1535    5
1536  20230628   080000    080459  1687910699  ...  30661.7 -0.000482   1536    0
1537  20230628   080500    080959  1687910999  ...  30645.1 -0.000398   1537    1
1538  20230628   081000    081459  1687911299  ...  30587.0 -0.000815   1538    2
1539  20230628   081500    081959  1687911599  ...  30500.0 -0.004120   1539    3

[5 rows x 11 columns]
2023-06-28 08:20:06,507:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [28/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=34, self.factor=0.4258269255736668, self.count=12931 

self.closeSec=1687911899, self.tradeDate='20230628', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30504.5, self.close=30485.1, self.high=30525.2, self.low=30450.0 
2023-06-28 08:25:00,762:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687911899, self.tradeDate='20230628', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30504.5, self.close=30485.1, self.high=30525.2, self.low=30450.0   
2023-06-28 08:25:00,786:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230628   080000    080459  1687910699  ...  30661.7 -0.000482   1536    0
1537  20230628   080500    080959  1687910999  ...  30645.1 -0.000398   1537    1
1538  20230628   081000    081459  1687911299  ...  30587.0 -0.000815   1538    2
1539  20230628   081500    081959  1687911599  ...  30500.0 -0.004120   1539    3
1540  20230628   082000    082459  1687911899  ...  30450.0 -0.000652   1540    4

[5 rows x 11 columns]
2023-06-28 08:25:00,786:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-28 08:00:18,064:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...  alpha58   alpha67   alpha72
5770  20230628    052959  30636.4  ...    48.75  0.528745  0.386532
5771  20230628    055959  30635.5  ...    48.75  0.541299  0.384973
5772  20230628    062959  30716.6  ...    48.75  0.531228  0.388389
5773  20230628    065959  30660.1  ...    48.75  0.515654  0.399326
5774  20230628    072959  30569.8  ...    48.75  0.524702  0.404603

[5 rows x 33 columns]
0.5489833641404805
acc is : 0.5489833641404805
2023-06-28 08:00:18,137:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.490356  0.509644       1  ...  1.085864  -1.0    0.0  1.173083
537     0  0.509631  0.490369       0  ...  1.087869  -1.0    0.0  1.170917
538     1  0.489646  0.510354       0  ...  1.091069  -1.0    0.0  1.167472
539     1  0.486547  0.513453       1  ...  1.089020  -1.0    0.0  1.169665
540     0  0.505603  0.494397       1  ...  1.087029  -1.0    0.0  1.171803

[5 rows x 10 columns]
2023-06-28 08:00:18,148:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.489892  0.510108       1  ...  1.100658  -1.0    0.0  1.189077
46     0  0.509588  0.490412       0  ...  1.097703  -1.0    0.0  1.188644
47     1  0.489243  0.510757       0  ...  1.100932  -1.0    0.0  1.178018
48     1  0.486547  0.513453       1  ...  1.089020  -1.0    0.0  1.169665
49     0  0.505603  0.494397       1  ...  1.087029  -1.0    0.0  1.171803

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.381', 'enterprice': '30103.1', 'countrevence': '0', 'unrealprofit': '-16119.1947', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30691.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230628   075000    075959  1687910399  30646.5  30683.2  0.001194
2023-06-28 08:00:02,369:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6464 

self.closeSec=1687910999, self.tradeDate='20230628', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30683.2', self.close='30656.2'
2023-06-28 08:10:01,112:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687910999, self.tradeDate='20230628', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30683.2', self.close='30656.2'
127.0.0.1 - - [28/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-06-28 08:10:01,120:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230628   072000    072959  1687908599  30617.2  30627.2  0.000323
621  20230628   073000    073959  1687909199  30627.3  30646.4  0.000627
622  20230628   074000    074959  1687909799  30646.5  30646.6  0.000007
623  20230628   075000    075959  1687910399  30646.5  30683.2  0.001194
624  20230628   080000    080959  1687910999  30683.2  30656.2 -0.000880
2023-06-28 08:10:01,121:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6465 

self.closeSec=1687911599, self.tradeDate='20230628', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30656.2', self.close='30504.5'
127.0.0.1 - - [28/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-28 08:20:07,378:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687911599, self.tradeDate='20230628', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30656.2', self.close='30504.5'
2023-06-28 08:20:08,177:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230628   073000    073959  1687909199  30627.3  30646.4  0.000627
622  20230628   074000    074959  1687909799  30646.5  30646.6  0.000007
623  20230628   075000    075959  1687910399  30646.5  30683.2  0.001194
624  20230628   080000    080959  1687910999  30683.2  30656.2 -0.000880
625  20230628   081000    081959  1687911599  30656.2  30504.5 -0.004948
2023-06-28 08:20:08,177:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230628   075000    075959  1687910399  30646.5  30683.2
2023-06-28 08:00:02,361:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [28/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6467 

self.closeSec=1687910999, self.tradeDate='20230628', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30683.2', self.close='30656.2'
2023-06-28 08:10:01,133:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687910999, self.tradeDate='20230628', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30683.2', self.close='30656.2'
2023-06-28 08:10:01,149:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230628   072000    072959  1687908599  30617.2  30627.2
17469  20230628   073000    073959  1687909199  30627.3  30646.4
17470  20230628   074000    074959  1687909799  30646.5  30646.6
17471  20230628   075000    075959  1687910399  30646.5  30683.2
17472  20230628   080000    080959  1687910999  30683.2  30656.2
2023-06-28 08:10:01,149:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6468 

self.closeSec=1687911599, self.tradeDate='20230628', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30656.2', self.close='30504.5'
127.0.0.1 - - [28/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-28 08:20:09,481:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687911599, self.tradeDate='20230628', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30656.2', self.close='30504.5'
2023-06-28 08:20:09,613:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230628   073000    073959  1687909199  30627.3  30646.4
17470  20230628   074000    074959  1687909799  30646.5  30646.6
17471  20230628   075000    075959  1687910399  30646.5  30683.2
17472  20230628   080000    080959  1687910999  30683.2  30656.2
17473  20230628   081000    081959  1687911599  30656.2  30504.5
2023-06-28 08:20:09,614:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230628   075000    075959  1687910399  30646.5  30683.2
2023-06-28 08:00:02,380:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [28/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6467 

self.closeSec=1687910999, self.tradeDate='20230628', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30683.2', self.close='30656.2'
2023-06-28 08:10:01,134:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687910999, self.tradeDate='20230628', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30683.2', self.close='30656.2'
2023-06-28 08:10:01,149:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230628   072000    072959  1687908599  30617.2  30627.2
12141  20230628   073000    073959  1687909199  30627.3  30646.4
12142  20230628   074000    074959  1687909799  30646.5  30646.6
12143  20230628   075000    075959  1687910399  30646.5  30683.2
12144  20230628   080000    080959  1687910999  30683.2  30656.2
2023-06-28 08:10:01,149:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6468 

self.closeSec=1687911599, self.tradeDate='20230628', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30656.2', self.close='30504.5'
127.0.0.1 - - [28/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-28 08:20:09,061:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687911599, self.tradeDate='20230628', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30656.2', self.close='30504.5'
2023-06-28 08:20:09,337:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230628   073000    073959  1687909199  30627.3  30646.4
12142  20230628   074000    074959  1687909799  30646.5  30646.6
12143  20230628   075000    075959  1687910399  30646.5  30683.2
12144  20230628   080000    080959  1687910999  30683.2  30656.2
12145  20230628   081000    081959  1687911599  30656.2  30504.5
2023-06-28 08:20:09,339:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=12928
self.closeSec=1687911599, self.tradeDate='20230628', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30629.2, self.close=30505.0, self.high=30629.3, self.low=30500.0, self.vol=3316.883, self.amt=101333694.39976 
127.0.0.1 - - [28/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-28 08:20:07,598:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230628   075500    075959  ...         0.0        0.0       0
5856  20230628   080000    080459  ...         0.0        0.0       0
5857  20230628   080500    080959  ...         0.0        0.0       0
5858  20230628   081000    081459  ...         0.0        0.0       0
5859  20230628   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-28 08:20:07,629:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687911599, self.tradeDate='20230628', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30629.2, self.close=30505.0, self.high=30629.3, self.low=30500.0, self.vol=3316.883, self.amt=101333694.39976, ukdf['pct'].iloc[-1]=-0.00412 , ukdf['amount'].iloc[-1]=101333694.39976, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '135747.10902219272', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30498.91260392', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [28/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=12929
self.closeSec=1687911899, self.tradeDate='20230628', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30504.5, self.close=30485.1, self.high=30525.2, self.low=30450.0, self.vol=3741.117, self.amt=114039368.47565 
2023-06-28 08:25:00,789:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230628   080000    080459  ...         0.0        0.0       0
5857  20230628   080500    080959  ...         0.0        0.0       0
5858  20230628   081000    081459  ...         0.0        0.0       0
5859  20230628   081500    081959  ...         0.0        0.0       0
5860  20230628   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-28 08:25:00,789:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687911899, self.tradeDate='20230628', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30504.5, self.close=30485.1, self.high=30525.2, self.low=30450.0, self.vol=3741.117, self.amt=114039368.47565, ukdf['pct'].iloc[-1]=-0.000652 , ukdf['amount'].iloc[-1]=114039368.47565, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '135248.9515', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30485.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230627   200000    235959  1687881599  ...    719  0.026213 -1.386319    -1.0
720  20230628   000000    035959  1687895999  ...    720  0.424090 -0.345511     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '3713.95368957624', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30637.27795882', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [28/Jun/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1634064.775524, self.flagDict['side']='sell', self.tradeCount=8, self.count=269
self.closeSec=1687910399, self.tradeDate='20230628', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=30638.4, self.close=30683.2, self.high=30738.8, self.low=30533.1, self.vol=42008.165, self.amt=1286967959.6542 
2023-06-28 08:00:01,894:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1687910399, self.tradeDate='20230628', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=30638.4, self.close=30683.2, self.high=30738.8, self.low=30533.1, self.vol=42008.165, self.amt=1286967959.6542 
2023-06-28 08:00:01,924:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230627   120000    155959  ...   36501.042  1.107268e+09  0.001466
718  20230627   160000    195959  ...   81853.383  2.502512e+09  0.010380
719  20230627   200000    235959  ...  147090.862  4.514834e+09 -0.007575
720  20230628   000000    035959  ...   57462.807  1.760219e+09  0.004953
721  20230628   040000    075959  ...   42008.165  1.286968e+09  0.001462

[5 rows x 11 columns]
2023-06-28 08:00:03,288:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230627   120000    155959  1687852799  ...    717  0.108286 -1.222146    -1.0
718  20230627   160000    195959  1687867199  ...    718  0.057545 -1.332153    -1.0
719  20230627   200000    235959  1687881599  ...    719  0.026213 -1.386319    -1.0
720  20230628   000000    035959  1687895999  ...    720  0.424090 -0.345511     NaN
721  20230628   040000    075959  1687910399  ...    721  0.263494 -0.758499    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '1267.7784', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30683.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


