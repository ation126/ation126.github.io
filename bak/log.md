# 20230526 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=3424
self.closeSec=1685060399, self.tradeDate='20230526', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26439.3, self.close=26456.0, self.high=26456.0, self.low=26439.2, self.vol=343.074, self.amt=9074614.4415 
127.0.0.1 - - [26/May/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-05-26 08:20:05,420:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230526   075500    075959  ...    0.068253   0.240333       0
5856  20230526   080000    080459  ...    0.068069   0.240132       0
5857  20230526   080500    080959  ...    0.067884   0.239928       0
5858  20230526   081000    081459  ...    0.067699   0.239723       0
5859  20230526   081500    081959  ...    0.067509   0.239504       0

[5 rows x 18 columns]
2023-05-26 08:20:05,459:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685060399, self.tradeDate='20230526', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26439.3, self.close=26456.0, self.high=26456.0, self.low=26439.2, self.vol=343.074, self.amt=9074614.4415, ukdf['pct'].iloc[-1]=0.000635 , ukdf['amount'].iloc[-1]=9074614.4415, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.06750861391787481, signal=0, value_std=0.23950431750617257 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '5695.734', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26455.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [26/May/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=3425
self.closeSec=1685060699, self.tradeDate='20230526', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26456.0, self.close=26477.1, self.high=26488.8, self.low=26455.0, self.vol=837.356, self.amt=22165185.0961 
2023-05-26 08:25:00,824:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230526   080000    080459  ...    0.068069   0.240132       0
5857  20230526   080500    080959  ...    0.067884   0.239928       0
5858  20230526   081000    081459  ...    0.067699   0.239723       0
5859  20230526   081500    081959  ...    0.067509   0.239504       0
5860  20230526   082000    082459  ...    0.067318   0.239284       0

[5 rows x 18 columns]
2023-05-26 08:25:00,824:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685060699, self.tradeDate='20230526', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26456.0, self.close=26477.1, self.high=26488.8, self.low=26455.0, self.vol=837.356, self.amt=22165185.0961, ukdf['pct'].iloc[-1]=0.000798 , ukdf['amount'].iloc[-1]=22165185.0961, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.06731766130698917, signal=0, value_std=0.23928392569245666 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '5383.54196349882', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26478.31792593', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1685060399, self.tradeDate='20230526', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26439.3, self.close=26456.0, self.high=26456.0, self.low=26439.2 
127.0.0.1 - - [26/May/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-05-26 08:20:02,739:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685060399, self.tradeDate='20230526', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26439.3, self.close=26456.0, self.high=26456.0, self.low=26439.2   
2023-05-26 08:20:04,130:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230526   075500    075959  1685059199  ...  26459.3  0.000091   1535    5
1536  20230526   080000    080459  1685059499  ...  26461.7  0.000423   1536    0
1537  20230526   080500    080959  1685059799  ...  26430.0 -0.001624   1537    1
1538  20230526   081000    081459  1685060099  ...  26425.5  0.000348   1538    2
1539  20230526   081500    081959  1685060399  ...  26439.2  0.000635   1539    3

[5 rows x 11 columns]
2023-05-26 08:20:04,140:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [26/May/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=20, self.factor=0.43459243073403786, self.count=3427 

self.closeSec=1685060699, self.tradeDate='20230526', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26456.0, self.close=26477.1, self.high=26488.8, self.low=26455.0 
2023-05-26 08:25:00,726:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685060699, self.tradeDate='20230526', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26456.0, self.close=26477.1, self.high=26488.8, self.low=26455.0   
2023-05-26 08:25:00,783:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230526   080000    080459  1685059499  ...  26461.7  0.000423   1536    0
1537  20230526   080500    080959  1685059799  ...  26430.0 -0.001624   1537    1
1538  20230526   081000    081459  1685060099  ...  26425.5  0.000348   1538    2
1539  20230526   081500    081959  1685060399  ...  26439.2  0.000635   1539    3
1540  20230526   082000    082459  1685060699  ...  26455.0  0.000798   1540    4

[5 rows x 11 columns]
2023-05-26 08:25:00,783:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-26 08:00:31,828:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230526    052959  26476.0  ...  45.833333  0.489902  0.334401
5771  20230526    055959  26438.7  ...  46.250000  0.496278  0.331766
5772  20230526    062959  26465.9  ...  45.833333  0.493076  0.330840
5773  20230526    065959  26452.0  ...  45.416667  0.491539  0.333476
5774  20230526    072959  26445.4  ...  45.833333  0.500917  0.331088

[5 rows x 33 columns]
0.5360443622920518
acc is : 0.5360443622920518
2023-05-26 08:00:31,972:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.495830  0.504170       1  ...  0.909058  -1.0    0.0  0.981498
537     1  0.497466  0.502534       0  ...  0.909536  -1.0    0.0  0.980983
538     1  0.490771  0.509229       0  ...  0.909763  -1.0    0.0  0.980738
539     1  0.489133  0.510867       1  ...  0.908421  -1.0    0.0  0.982184
540     0  0.501375  0.498625       0  ...  0.909196  -1.0    0.0  0.981346

[5 rows x 10 columns]
2023-05-26 08:00:32,012:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.495711  0.504289       1  ...  0.909058  -1.0    0.0  0.977633
46     1  0.497651  0.502349       0  ...  0.909536  -1.0    0.0  0.978732
47     1  0.490882  0.509118       0  ...  0.909763  -1.0    0.0  0.981568
48     1  0.489133  0.510867       1  ...  0.908421  -1.0    0.0  0.982184
49     0  0.501375  0.498625       0  ...  0.909196  -1.0    0.0  0.981346

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.287', 'enterprice': '26103', 'countrevence': '0', 'unrealprofit': '-10096.19', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26473', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230526   075000    075959  1685059199  26459.4  26461.8  0.000087
2023-05-26 08:00:02,297:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [26/May/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1712 

self.closeSec=1685059799, self.tradeDate='20230526', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26461.7', self.close='26429.7'
2023-05-26 08:10:01,201:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685059799, self.tradeDate='20230526', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26461.7', self.close='26429.7'
2023-05-26 08:10:01,251:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230526   072000    072959  1685057399  26486.9  26484.4 -0.000091
621  20230526   073000    073959  1685057999  26484.4  26466.3 -0.000683
622  20230526   074000    074959  1685058599  26466.3  26459.5 -0.000257
623  20230526   075000    075959  1685059199  26459.4  26461.8  0.000087
624  20230526   080000    080959  1685059799  26461.7  26429.7 -0.001213
2023-05-26 08:10:01,251:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1713 

self.closeSec=1685060399, self.tradeDate='20230526', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26429.8', self.close='26456'
127.0.0.1 - - [26/May/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-05-26 08:20:06,019:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685060399, self.tradeDate='20230526', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26429.8', self.close='26456'
2023-05-26 08:20:06,619:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230526   073000    073959  1685057999  26484.4  26466.3 -0.000683
622  20230526   074000    074959  1685058599  26466.3  26459.5 -0.000257
623  20230526   075000    075959  1685059199  26459.4  26461.8  0.000087
624  20230526   080000    080959  1685059799  26461.7  26429.7 -0.001213
625  20230526   081000    081959  1685060399  26429.8    26456  0.000995
2023-05-26 08:20:06,619:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230526   075000    075959  1685059199  26459.4  26461.8
2023-05-26 08:00:02,247:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1715 

self.closeSec=1685059799, self.tradeDate='20230526', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26461.7', self.close='26429.7'
2023-05-26 08:10:01,173:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685059799, self.tradeDate='20230526', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26461.7', self.close='26429.7'
127.0.0.1 - - [26/May/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-05-26 08:10:01,201:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230526   072000    072959  1685057399  26486.9  26484.4
17469  20230526   073000    073959  1685057999  26484.4  26466.3
17470  20230526   074000    074959  1685058599  26466.3  26459.5
17471  20230526   075000    075959  1685059199  26459.4  26461.8
17472  20230526   080000    080959  1685059799  26461.7  26429.7
2023-05-26 08:10:01,201:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1716 

self.closeSec=1685060399, self.tradeDate='20230526', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26429.8', self.close='26456'
127.0.0.1 - - [26/May/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-05-26 08:20:07,480:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685060399, self.tradeDate='20230526', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26429.8', self.close='26456'
2023-05-26 08:20:07,591:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230526   073000    073959  1685057999  26484.4  26466.3
17470  20230526   074000    074959  1685058599  26466.3  26459.5
17471  20230526   075000    075959  1685059199  26459.4  26461.8
17472  20230526   080000    080959  1685059799  26461.7  26429.7
17473  20230526   081000    081959  1685060399  26429.8    26456
2023-05-26 08:20:07,591:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230526   075000    075959  1685059199  26459.4  26461.8
2023-05-26 08:00:02,311:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1715 

self.closeSec=1685059799, self.tradeDate='20230526', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26461.7', self.close='26429.7'
127.0.0.1 - - [26/May/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-05-26 08:10:01,230:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685059799, self.tradeDate='20230526', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26461.7', self.close='26429.7'
2023-05-26 08:10:01,252:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230526   072000    072959  1685057399  26486.9  26484.4
12141  20230526   073000    073959  1685057999  26484.4  26466.3
12142  20230526   074000    074959  1685058599  26466.3  26459.5
12143  20230526   075000    075959  1685059199  26459.4  26461.8
12144  20230526   080000    080959  1685059799  26461.7  26429.7
2023-05-26 08:10:01,252:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1716 

self.closeSec=1685060399, self.tradeDate='20230526', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26429.8', self.close='26456'
127.0.0.1 - - [26/May/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-05-26 08:20:07,202:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685060399, self.tradeDate='20230526', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26429.8', self.close='26456'
2023-05-26 08:20:07,448:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230526   073000    073959  1685057999  26484.4  26466.3
12142  20230526   074000    074959  1685058599  26466.3  26459.5
12143  20230526   075000    075959  1685059199  26459.4  26461.8
12144  20230526   080000    080959  1685059799  26461.7  26429.7
12145  20230526   081000    081959  1685060399  26429.8    26456
2023-05-26 08:20:07,448:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=3424
self.closeSec=1685060399, self.tradeDate='20230526', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26439.3, self.close=26456.0, self.high=26456.0, self.low=26439.2, self.vol=343.074, self.amt=9074614.4415 
127.0.0.1 - - [26/May/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-05-26 08:20:05,404:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230526   075500    075959  ...         0.0        0.0       0
5856  20230526   080000    080459  ...         0.0        0.0       0
5857  20230526   080500    080959  ...         0.0        0.0       0
5858  20230526   081000    081459  ...         0.0        0.0       0
5859  20230526   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-26 08:20:05,439:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685060399, self.tradeDate='20230526', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26439.3, self.close=26456.0, self.high=26456.0, self.low=26439.2, self.vol=343.074, self.amt=9074614.4415, ukdf['pct'].iloc[-1]=0.000635 , ukdf['amount'].iloc[-1]=9074614.4415, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-14414.4221', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26455.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [26/May/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=3425
self.closeSec=1685060699, self.tradeDate='20230526', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26456.0, self.close=26477.1, self.high=26488.8, self.low=26455.0, self.vol=837.356, self.amt=22165185.0961 
2023-05-26 08:25:00,825:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230526   080000    080459  ...         0.0        0.0       0
5857  20230526   080500    080959  ...         0.0        0.0       0
5858  20230526   081000    081459  ...         0.0        0.0       0
5859  20230526   081500    081959  ...         0.0        0.0       0
5860  20230526   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-26 08:25:00,827:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685060699, self.tradeDate='20230526', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26456.0, self.close=26477.1, self.high=26488.8, self.low=26455.0, self.vol=837.356, self.amt=22165185.0961, ukdf['pct'].iloc[-1]=0.000798 , ukdf['amount'].iloc[-1]=22165185.0961, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-13581.79791303387', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26478.31792593', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230525   200000    235959  1685030399  ...    719  0.581766  1.282105     1.0
720  20230526   000000    035959  1685044799  ...    720  0.573831  1.220977     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '18220.80221106556', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26457.99424444', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [26/May/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1442113.3648782002, self.flagDict['side']='buy', self.tradeCount=3, self.count=71
self.closeSec=1685059199, self.tradeDate='20230526', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26458.0, self.close=26461.8, self.high=26545.8, self.low=26420.6, self.vol=28461.259, self.amt=753318299.2479 
2023-05-26 08:00:01,841:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1685059199, self.tradeDate='20230526', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26458.0, self.close=26461.8, self.high=26545.8, self.low=26420.6, self.vol=28461.259, self.amt=753318299.2479 
2023-05-26 08:00:01,901:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230525   120000    155959  ...   40575.044  1.063439e+09 -0.001991
718  20230525   160000    195959  ...   40284.053  1.056670e+09  0.006264
719  20230525   200000    235959  ...  110196.106  2.902615e+09 -0.002496
720  20230526   000000    035959  ...   80074.610  2.114028e+09  0.009193
721  20230526   040000    075959  ...   28461.259  7.533183e+08  0.000147

[5 rows x 11 columns]
2023-05-26 08:00:03,751:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230525   120000    155959  1685001599  ...    717  0.521366  0.807871     1.0
718  20230525   160000    195959  1685015999  ...    718  0.573660  1.166532     1.0
719  20230525   200000    235959  1685030399  ...    719  0.581766  1.282105     1.0
720  20230526   000000    035959  1685044799  ...    720  0.573831  1.220977     1.0
721  20230526   040000    075959  1685059199  ...    721  0.598183  1.345687     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '18518.21740023278', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26463.37742222', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


