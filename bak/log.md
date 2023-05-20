# 20230520 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--: 127.0.0.1 - - [20/May/2023 08:20:00] "POST / HTTP/1.1" 200 -
 version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=1696
self.closeSec=1684541999, self.tradeDate='20230520', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26884.9, self.close=26864.1, self.high=26902.0, self.low=26864.1, self.vol=753.982, self.amt=20273079.2677 
2023-05-20 08:20:01,596:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230520   075500    075959  ...    0.337129   0.325059       0
5856  20230520   080000    080459  ...    0.336905   0.325013       0
5857  20230520   080500    080959  ...    0.336683   0.324971       0
5858  20230520   081000    081459  ...    0.336462   0.324929       0
5859  20230520   081500    081959  ...    0.336242   0.324888       0

[5 rows x 18 columns]
2023-05-20 08:20:01,607:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684541999, self.tradeDate='20230520', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26884.9, self.close=26864.1, self.high=26902.0, self.low=26864.1, self.vol=753.982, self.amt=20273079.2677, ukdf['pct'].iloc[-1]=-0.00077 , ukdf['amount'].iloc[-1]=20273079.2677, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.33624171693185784, signal=0, value_std=0.32488771795995186 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-5.76873492756', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26865.31424206', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [20/May/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=1697
self.closeSec=1684542299, self.tradeDate='20230520', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26864.1, self.close=26872.1, self.high=26882.1, self.low=26857.3, self.vol=389.003, self.amt=10451623.3974 
2023-05-20 08:25:00,438:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230520   080000    080459  ...    0.336905   0.325013       0
5857  20230520   080500    080959  ...    0.336683   0.324971       0
5858  20230520   081000    081459  ...    0.336462   0.324929       0
5859  20230520   081500    081959  ...    0.336242   0.324888       0
5860  20230520   082000    082459  ...    0.336019   0.324844       0

[5 rows x 18 columns]
2023-05-20 08:25:00,445:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684542299, self.tradeDate='20230520', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26864.1, self.close=26872.1, self.high=26882.1, self.low=26857.3, self.vol=389.003, self.amt=10451623.3974, ukdf['pct'].iloc[-1]=0.000298 , ukdf['amount'].iloc[-1]=10451623.3974, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.3360192228649271, signal=0, value_std=0.3248436398583318 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-124.40003637732', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26873.83293382', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1684541999, self.tradeDate='20230520', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26884.9, self.close=26864.1, self.high=26902.0, self.low=26864.1 
127.0.0.1 - - [20/May/2023 08:20:00] "POST / HTTP/1.1" 200 -
2023-05-20 08:20:01,378:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684541999, self.tradeDate='20230520', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26884.9, self.close=26864.1, self.high=26902.0, self.low=26864.1   
2023-05-20 08:20:01,956:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230520   075500    075959  1684540799  ...  26851.9  0.000581   1535    5
1536  20230520   080000    080459  1684541099  ...  26861.7  0.000156   1536    0
1537  20230520   080500    080959  1684541399  ...  26868.2 -0.000167   1537    1
1538  20230520   081000    081459  1684541699  ...  26865.2  0.000558   1538    2
1539  20230520   081500    081959  1684541999  ...  26864.1 -0.000770   1539    3

[5 rows x 11 columns]
2023-05-20 08:20:01,956:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=56, self.factor=0.5399059982091157, self.count=1699 

self.closeSec=1684542299, self.tradeDate='20230520', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26864.1, self.close=26872.1, self.high=26882.1, self.low=26857.3 
2023-05-20 08:25:00,381:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684542299, self.tradeDate='20230520', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26864.1, self.close=26872.1, self.high=26882.1, self.low=26857.3   
127.0.0.1 - - [20/May/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-05-20 08:25:00,417:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230520   080000    080459  1684541099  ...  26861.7  0.000156   1536    0
1537  20230520   080500    080959  1684541399  ...  26868.2 -0.000167   1537    1
1538  20230520   081000    081459  1684541699  ...  26865.2  0.000558   1538    2
1539  20230520   081500    081959  1684541999  ...  26864.1 -0.000770   1539    3
1540  20230520   082000    082459  1684542299  ...  26857.3  0.000298   1540    4

[5 rows x 11 columns]
2023-05-20 08:25:00,417:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-20 08:00:17,581:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230520    052959  26819.8  ...  50.000000  0.485218  0.523329
5771  20230520    055959  26880.3  ...  50.416667  0.489466  0.521598
5772  20230520    062959  26897.1  ...  50.000000  0.482244  0.523464
5773  20230520    065959  26867.3  ...  50.000000  0.480830  0.525884
5774  20230520    072959  26861.6  ...  50.416667  0.483468  0.526983

[5 rows x 33 columns]
0.5452865064695009
acc is : 0.5452865064695009
2023-05-20 08:00:17,665:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.509079  0.490921       1  ...  0.904738  -1.0    0.0  0.964915
537     0  0.509940  0.490060       0  ...  0.905737  -1.0    0.0  0.963849
538     1  0.496927  0.503073       0  ...  0.905933  -1.0    0.0  0.963641
539     1  0.499526  0.500474       1  ...  0.905599  -1.0    0.0  0.963997
540     0  0.504273  0.495727       0  ...  0.905646  -1.0    0.0  0.963946

[5 rows x 10 columns]
2023-05-20 08:00:17,677:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.509217  0.490783       1  ...  0.904738  -1.0    0.0  0.964950
46     0  0.509923  0.490077       0  ...  0.905737  -1.0    0.0  0.963569
47     1  0.497172  0.502828       0  ...  0.905933  -1.0    0.0  0.964233
48     1  0.499526  0.500474       1  ...  0.905599  -1.0    0.0  0.963997
49     0  0.504273  0.495727       0  ...  0.905646  -1.0    0.0  0.963946

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.758', 'enterprice': '26580.2', 'countrevence': '0', 'unrealprofit': '-7866.6172', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26863.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230520   075000    075959  1684540799  26875.8  26870.1 -0.000212
2023-05-20 08:00:01,772:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=848 

self.closeSec=1684541399, self.tradeDate='20230520', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26870.1', self.close='26869.8'
2023-05-20 08:10:00,362:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684541399, self.tradeDate='20230520', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26870.1', self.close='26869.8'
127.0.0.1 - - [20/May/2023 08:10:00] "POST / HTTP/1.1" 200 -
2023-05-20 08:10:00,377:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230520   072000    072959  1684538999  26861.7  26871.5  0.000365
621  20230520   073000    073959  1684539599  26871.4  26878.3  0.000253
622  20230520   074000    074959  1684540199  26878.4  26875.8 -0.000093
623  20230520   075000    075959  1684540799  26875.8  26870.1 -0.000212
624  20230520   080000    080959  1684541399  26870.1  26869.8 -0.000011
2023-05-20 08:10:00,377:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=849 

self.closeSec=1684541999, self.tradeDate='20230520', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26869.9', self.close='26864.1'
127.0.0.1 - - [20/May/2023 08:20:00] "POST / HTTP/1.1" 200 -
2023-05-20 08:20:02,147:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684541999, self.tradeDate='20230520', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26869.9', self.close='26864.1'
2023-05-20 08:20:02,426:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230520   073000    073959  1684539599  26871.4  26878.3  0.000253
622  20230520   074000    074959  1684540199  26878.4  26875.8 -0.000093
623  20230520   075000    075959  1684540799  26875.8  26870.1 -0.000212
624  20230520   080000    080959  1684541399  26870.1  26869.8 -0.000011
625  20230520   081000    081959  1684541999  26869.9  26864.1 -0.000212
2023-05-20 08:20:02,426:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230520   075000    075959  1684540799  26875.8  26870.1
2023-05-20 08:00:00,443:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [20/May/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=851 

self.closeSec=1684541399, self.tradeDate='20230520', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26870.1', self.close='26869.8'
2023-05-20 08:10:00,387:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684541399, self.tradeDate='20230520', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26870.1', self.close='26869.8'
2023-05-20 08:10:00,412:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230520   072000    072959  1684538999  26861.7  26871.5
17469  20230520   073000    073959  1684539599  26871.4  26878.3
17470  20230520   074000    074959  1684540199  26878.4  26875.8
17471  20230520   075000    075959  1684540799  26875.8  26870.1
17472  20230520   080000    080959  1684541399  26870.1  26869.8
2023-05-20 08:10:00,413:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=852 

self.closeSec=1684541999, self.tradeDate='20230520', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26869.9', self.close='26864.1'
127.0.0.1 - - [20/May/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-05-20 08:20:02,809:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684541999, self.tradeDate='20230520', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26869.9', self.close='26864.1'
2023-05-20 08:20:02,867:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230520   073000    073959  1684539599  26871.4  26878.3
17470  20230520   074000    074959  1684540199  26878.4  26875.8
17471  20230520   075000    075959  1684540799  26875.8  26870.1
17472  20230520   080000    080959  1684541399  26870.1  26869.8
17473  20230520   081000    081959  1684541999  26869.9  26864.1
2023-05-20 08:20:02,868:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230520   075000    075959  1684540799  26875.8  26870.1
2023-05-20 08:00:00,446:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [20/May/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=851 

self.closeSec=1684541399, self.tradeDate='20230520', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26870.1', self.close='26869.8'
2023-05-20 08:10:00,389:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684541399, self.tradeDate='20230520', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26870.1', self.close='26869.8'
2023-05-20 08:10:00,400:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230520   072000    072959  1684538999  26861.7  26871.5
12141  20230520   073000    073959  1684539599  26871.4  26878.3
12142  20230520   074000    074959  1684540199  26878.4  26875.8
12143  20230520   075000    075959  1684540799  26875.8  26870.1
12144  20230520   080000    080959  1684541399  26870.1  26869.8
2023-05-20 08:10:00,400:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=852 

self.closeSec=1684541999, self.tradeDate='20230520', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26869.9', self.close='26864.1'
127.0.0.1 - - [20/May/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-05-20 08:20:02,670:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684541999, self.tradeDate='20230520', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26869.9', self.close='26864.1'
2023-05-20 08:20:02,787:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230520   073000    073959  1684539599  26871.4  26878.3
12142  20230520   074000    074959  1684540199  26878.4  26875.8
12143  20230520   075000    075959  1684540799  26875.8  26870.1
12144  20230520   080000    080959  1684541399  26870.1  26869.8
12145  20230520   081000    081959  1684541999  26869.9  26864.1
2023-05-20 08:20:02,789:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=1696
self.closeSec=1684541999, self.tradeDate='20230520', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26884.9, self.close=26864.1, self.high=26902.0, self.low=26864.1, self.vol=753.982, self.amt=20273079.2677 
127.0.0.1 - - [20/May/2023 08:20:00] "POST / HTTP/1.1" 200 -
2023-05-20 08:20:01,496:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230520   075500    075959  ...    0.142770   0.283409       0
5856  20230520   080000    080459  ...    0.142555   0.283361       0
5857  20230520   080500    080959  ...    0.142338   0.283311       0
5858  20230520   081000    081459  ...    0.142121   0.283260       0
5859  20230520   081500    081959  ...    0.141898   0.283203       0

[5 rows x 18 columns]
2023-05-20 08:20:01,517:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684541999, self.tradeDate='20230520', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26884.9, self.close=26864.1, self.high=26902.0, self.low=26864.1, self.vol=753.982, self.amt=20273079.2677, ukdf['pct'].iloc[-1]=-0.00077 , ukdf['amount'].iloc[-1]=20273079.2677, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.14189801021946824, signal=0, value_std=0.2832031088155558 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '791.63226435046', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26865.31424206', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=1697
self.closeSec=1684542299, self.tradeDate='20230520', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26864.1, self.close=26872.1, self.high=26882.1, self.low=26857.3, self.vol=389.003, self.amt=10451623.3974 
127.0.0.1 - - [20/May/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-05-20 08:25:00,438:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230520   080000    080459  ...    0.142555   0.283361       0
5857  20230520   080500    080959  ...    0.142338   0.283311       0
5858  20230520   081000    081459  ...    0.142121   0.283260       0
5859  20230520   081500    081959  ...    0.141898   0.283203       0
5860  20230520   082000    082459  ...    0.141674   0.283145       0

[5 rows x 18 columns]
2023-05-20 08:25:00,445:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684542299, self.tradeDate='20230520', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26864.1, self.close=26872.1, self.high=26882.1, self.low=26857.3, self.vol=389.003, self.amt=10451623.3974, ukdf['pct'].iloc[-1]=0.000298 , ukdf['amount'].iloc[-1]=10451623.3974, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.14167432778708425, signal=0, value_std=0.28314548564024083 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '1108.02499500862', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26873.83293382', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230519   200000    235959  1684511999  ...    719  0.299043 -1.013582    -1.0
720  20230520   000000    035959  1684526399  ...    720  0.282814 -1.081324    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.549', 'enterprice': '27070.5', 'countrevence': '0', 'unrealprofit': '12732.72921308709', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26823.49755159', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1394061.7472955, self.flagDict['side']='sell', self.tradeCount=2, self.count=35
self.closeSec=1684540799, self.tradeDate='20230520', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26826.5, self.close=26870.1, self.high=26913.7, self.low=26791.0, self.vol=17666.894, self.amt=474451097.0932 
2023-05-20 08:00:00,380:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1684540799, self.tradeDate='20230520', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26826.5, self.close=26870.1, self.high=26913.7, self.low=26791.0, self.vol=17666.894, self.amt=474451097.0932 
127.0.0.1 - - [20/May/2023 08:00:00] "POST / HTTP/1.1" 200 -
2023-05-20 08:00:00,462:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230519   120000    155959  ...   28781.823  7.734667e+08  0.000630
718  20230519   160000    195959  ...   32361.524  8.685760e+08  0.000071
719  20230519   200000    235959  ...  157634.157  4.238887e+09  0.000972
720  20230520   000000    035959  ...   50110.954  1.346546e+09 -0.001619
721  20230520   040000    075959  ...   17666.894  4.744511e+08  0.001629

[5 rows x 11 columns]
2023-05-20 08:00:02,183:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230519   120000    155959  1684483199  ...    717  0.342365 -0.811255    -1.0
718  20230519   160000    195959  1684497599  ...    718  0.335530 -0.830864    -1.0
719  20230519   200000    235959  1684511999  ...    719  0.299043 -1.013582    -1.0
720  20230520   000000    035959  1684526399  ...    720  0.282814 -1.081324    -1.0
721  20230520   040000    075959  1684540799  ...    721  0.224054 -1.382607    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.549', 'enterprice': '27070.5', 'countrevence': '0', 'unrealprofit': '10330.4196', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26870.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


