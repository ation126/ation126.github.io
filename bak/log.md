# 20230616 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=9472
self.closeSec=1686874799, self.tradeDate='20230616', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25523.8, self.close=25507.0, self.high=25534.8, self.low=25506.4, self.vol=1090.786, self.amt=27835247.0934 
127.0.0.1 - - [16/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-16 08:20:07,051:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230616   075500    075959  ...         0.0        0.0       0
5856  20230616   080000    080459  ...         0.0        0.0       0
5857  20230616   080500    080959  ...         0.0        0.0       0
5858  20230616   081000    081459  ...         0.0        0.0       0
5859  20230616   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-16 08:20:07,092:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686874799, self.tradeDate='20230616', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=25523.8, self.close=25507.0, self.high=25534.8, self.low=25506.4, self.vol=1090.786, self.amt=27835247.0934, ukdf['pct'].iloc[-1]=-0.000658 , ukdf['amount'].iloc[-1]=27835247.0934, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '18889.98016382862', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25508.44587363', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [16/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=9473
self.closeSec=1686875099, self.tradeDate='20230616', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25507.0, self.close=25457.6, self.high=25509.6, self.low=25420.1, self.vol=5538.906, self.amt=141054925.5183 
2023-06-16 08:25:00,808:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230616   080000    080459  ...         0.0        0.0       0
5857  20230616   080500    080959  ...         0.0        0.0       0
5858  20230616   081000    081459  ...         0.0        0.0       0
5859  20230616   081500    081959  ...         0.0        0.0       0
5860  20230616   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-16 08:25:00,809:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686875099, self.tradeDate='20230616', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=25507.0, self.close=25457.6, self.high=25509.6, self.low=25420.1, self.vol=5538.906, self.amt=141054925.5183, ukdf['pct'].iloc[-1]=-0.001937 , ukdf['amount'].iloc[-1]=141054925.5183, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '19599.4524', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25457.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1686874799, self.tradeDate='20230616', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25523.8, self.close=25507.0, self.high=25534.8, self.low=25506.4 
127.0.0.1 - - [16/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-16 08:20:04,572:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686874799, self.tradeDate='20230616', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=25523.8, self.close=25507.0, self.high=25534.8, self.low=25506.4   
2023-06-16 08:20:06,012:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230616   075500    075959  1686873599  ...  25575.0  0.000434   1535    5
1536  20230616   080000    080459  1686873899  ...  25512.6 -0.002005   1536    0
1537  20230616   080500    080959  1686874199  ...  25520.0 -0.000540   1537    1
1538  20230616   081000    081459  1686874499  ...  25521.0  0.000110   1538    2
1539  20230616   081500    081959  1686874799  ...  25506.4 -0.000658   1539    3

[5 rows x 11 columns]
2023-06-16 08:20:06,022:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [16/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=6, self.factor=0.5331368523709251, self.count=9475 

self.closeSec=1686875099, self.tradeDate='20230616', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25507.0, self.close=25457.6, self.high=25509.6, self.low=25420.1 
2023-06-16 08:25:00,723:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686875099, self.tradeDate='20230616', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=25507.0, self.close=25457.6, self.high=25509.6, self.low=25420.1   
2023-06-16 08:25:00,738:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230616   080000    080459  1686873899  ...  25512.6 -0.002005   1536    0
1537  20230616   080500    080959  1686874199  ...  25520.0 -0.000540   1537    1
1538  20230616   081000    081459  1686874499  ...  25521.0  0.000110   1538    2
1539  20230616   081500    081959  1686874799  ...  25506.4 -0.000658   1539    3
1540  20230616   082000    082459  1686875099  ...  25420.1 -0.001937   1540    4

[5 rows x 11 columns]
2023-06-16 08:25:00,738:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-16 08:00:19,751:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230616    052959  25556.7  ...  49.583333  0.547870  0.493248
5771  20230616    055959  25670.1  ...  49.166667  0.527010  0.473520
5772  20230616    062959  25558.0  ...  49.166667  0.531008  0.453422
5773  20230616    065959  25582.6  ...  49.166667  0.536358  0.432409
5774  20230616    072959  25615.6  ...  49.166667  0.529483  0.415312

[5 rows x 33 columns]
0.5378927911275416
acc is : 0.5378927911275416
2023-06-16 08:00:19,838:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.548445  0.451555       0  ...  1.030688   1.0    0.0  0.939829
537     1  0.493192  0.506808       1  ...  1.031680   1.0    0.0  0.940734
538     0  0.517989  0.482011       1  ...  1.033007   1.0    0.0  0.941944
539     0  0.542667  0.457333       0  ...  1.031527   1.0    0.0  0.940594
540     1  0.496931  0.503069       1  ...  1.031821   1.0    0.0  0.940863

[5 rows x 10 columns]
2023-06-16 08:00:19,861:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.548533  0.451467       0  ...  1.030688   1.0    0.0  0.940777
46     1  0.493493  0.506507       1  ...  1.031680   1.0    0.0  0.941641
47     0  0.518139  0.481861       1  ...  1.033007   1.0    0.0  0.943015
48     0  0.542667  0.457333       0  ...  1.031527   1.0    0.0  0.940594
49     1  0.496931  0.503069       1  ...  1.031821   1.0    0.0  0.940863

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.127', 'enterprice': '25424', 'countrevence': '0', 'unrealprofit': '4570.6375', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25586.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230616   075000    075959  1686873599    25578  25586.1  0.000313
2023-06-16 08:00:02,318:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [16/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4736 

self.closeSec=1686874199, self.tradeDate='20230616', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25586', self.close='25521'
2023-06-16 08:10:01,114:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686874199, self.tradeDate='20230616', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='25586', self.close='25521'
2023-06-16 08:10:01,133:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230616   072000    072959  1686871799  25590.9  25578.8 -0.000473
621  20230616   073000    073959  1686872399  25578.9    25548 -0.001204
622  20230616   074000    074959  1686872999    25548  25578.1  0.001178
623  20230616   075000    075959  1686873599    25578  25586.1  0.000313
624  20230616   080000    080959  1686874199    25586    25521 -0.002544
2023-06-16 08:10:01,134:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4737 

self.closeSec=1686874799, self.tradeDate='20230616', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25521', self.close='25507.1'
127.0.0.1 - - [16/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-16 08:20:07,023:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686874799, self.tradeDate='20230616', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='25521', self.close='25507.1'
2023-06-16 08:20:07,852:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230616   073000    073959  1686872399  25578.9    25548 -0.001204
622  20230616   074000    074959  1686872999    25548  25578.1  0.001178
623  20230616   075000    075959  1686873599    25578  25586.1  0.000313
624  20230616   080000    080959  1686874199    25586    25521 -0.002544
625  20230616   081000    081959  1686874799    25521  25507.1 -0.000545
2023-06-16 08:20:07,853:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230616   075000    075959  1686873599    25578  25586.1
2023-06-16 08:00:02,303:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4739 

self.closeSec=1686874199, self.tradeDate='20230616', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25586', self.close='25521'
2023-06-16 08:10:01,128:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686874199, self.tradeDate='20230616', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='25586', self.close='25521'
127.0.0.1 - - [16/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-06-16 08:10:01,150:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230616   072000    072959  1686871799  25590.9  25578.8
17469  20230616   073000    073959  1686872399  25578.9    25548
17470  20230616   074000    074959  1686872999    25548  25578.1
17471  20230616   075000    075959  1686873599    25578  25586.1
17472  20230616   080000    080959  1686874199    25586    25521
2023-06-16 08:10:01,150:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4740 

self.closeSec=1686874799, self.tradeDate='20230616', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25521', self.close='25507.1'
127.0.0.1 - - [16/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-16 08:20:08,886:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686874799, self.tradeDate='20230616', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='25521', self.close='25507.1'
2023-06-16 08:20:09,037:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230616   073000    073959  1686872399  25578.9    25548
17470  20230616   074000    074959  1686872999    25548  25578.1
17471  20230616   075000    075959  1686873599    25578  25586.1
17472  20230616   080000    080959  1686874199    25586    25521
17473  20230616   081000    081959  1686874799    25521  25507.1
2023-06-16 08:20:09,038:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230616   075000    075959  1686873599    25578  25586.1
2023-06-16 08:00:02,321:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4739 

self.closeSec=1686874199, self.tradeDate='20230616', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25586', self.close='25521'
2023-06-16 08:10:01,126:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686874199, self.tradeDate='20230616', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='25586', self.close='25521'
127.0.0.1 - - [16/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-06-16 08:10:01,137:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230616   072000    072959  1686871799  25590.9  25578.8
12141  20230616   073000    073959  1686872399  25578.9    25548
12142  20230616   074000    074959  1686872999    25548  25578.1
12143  20230616   075000    075959  1686873599    25578  25586.1
12144  20230616   080000    080959  1686874199    25586    25521
2023-06-16 08:10:01,137:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4740 

self.closeSec=1686874799, self.tradeDate='20230616', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25521', self.close='25507.1'
127.0.0.1 - - [16/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-16 08:20:08,555:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686874799, self.tradeDate='20230616', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='25521', self.close='25507.1'
2023-06-16 08:20:08,831:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230616   073000    073959  1686872399  25578.9    25548
12142  20230616   074000    074959  1686872999    25548  25578.1
12143  20230616   075000    075959  1686873599    25578  25586.1
12144  20230616   080000    080959  1686874199    25586    25521
12145  20230616   081000    081959  1686874799    25521  25507.1
2023-06-16 08:20:08,832:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=9472
self.closeSec=1686874799, self.tradeDate='20230616', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25523.8, self.close=25507.0, self.high=25534.8, self.low=25506.4, self.vol=1090.786, self.amt=27835247.0934 
127.0.0.1 - - [16/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-16 08:20:06,973:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230616   075500    075959  ...         0.0        0.0       0
5856  20230616   080000    080459  ...         0.0        0.0       0
5857  20230616   080500    080959  ...         0.0        0.0       0
5858  20230616   081000    081459  ...         0.0        0.0       0
5859  20230616   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-16 08:20:07,022:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686874799, self.tradeDate='20230616', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=25523.8, self.close=25507.0, self.high=25534.8, self.low=25506.4, self.vol=1090.786, self.amt=27835247.0934, ukdf['pct'].iloc[-1]=-0.000658 , ukdf['amount'].iloc[-1]=27835247.0934, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-49603.81580750817', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25508.44587363', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [16/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=9473
self.closeSec=1686875099, self.tradeDate='20230616', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25507.0, self.close=25457.6, self.high=25509.6, self.low=25420.1, self.vol=5538.906, self.amt=141054925.5183 
2023-06-16 08:25:00,809:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230616   080000    080459  ...         0.0        0.0       0
5857  20230616   080500    080959  ...         0.0        0.0       0
5858  20230616   081000    081459  ...         0.0        0.0       0
5859  20230616   081500    081959  ...         0.0        0.0       0
5860  20230616   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-16 08:25:00,810:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686875099, self.tradeDate='20230616', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=25507.0, self.close=25457.6, self.high=25509.6, self.low=25420.1, self.vol=5538.906, self.amt=141054925.5183, ukdf['pct'].iloc[-1]=-0.001937 , ukdf['amount'].iloc[-1]=141054925.5183, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-51495.9965', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25457.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230615   200000    235959  1686844799  ...    719  0.498045  0.326385     NaN
720  20230616   000000    035959  1686859199  ...    720  0.472700  0.235766     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '90174.3436', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25444', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1492324.2295523998, self.flagDict['side']='sell', self.tradeCount=4, self.count=197
self.closeSec=1686873599, self.tradeDate='20230616', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=25443.1, self.close=25586.1, self.high=25750.0, self.low=25205.0, self.vol=113154.066, self.amt=2888633155.03125 
127.0.0.1 - - [16/Jun/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-06-16 08:00:01,859:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1686873599, self.tradeDate='20230616', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=25443.1, self.close=25586.1, self.high=25750.0, self.low=25205.0, self.vol=113154.066, self.amt=2888633155.03125 
2023-06-16 08:00:01,884:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230615   120000    155959  ...   67274.308  1.680181e+09 -0.003201
718  20230615   160000    195959  ...   68636.788  1.711896e+09  0.001297
719  20230615   200000    235959  ...   70290.723  1.757902e+09 -0.002343
720  20230616   000000    035959  ...  112855.178  2.849100e+09  0.019829
721  20230616   040000    075959  ...  113154.066  2.888633e+09  0.005620

[5 rows x 11 columns]
2023-06-16 08:00:03,257:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230615   120000    155959  1686815999  ...    717  0.274178 -0.697865    -1.0
718  20230615   160000    195959  1686830399  ...    718  0.405072 -0.112337     NaN
719  20230615   200000    235959  1686844799  ...    719  0.498045  0.326385     NaN
720  20230616   000000    035959  1686859199  ...    720  0.472700  0.235766     NaN
721  20230616   040000    075959  1686873599  ...    721  0.448839  0.146325     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '82201.94459899796', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25588.51653194', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


