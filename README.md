# FutuAPI-Intro
Learning how to use Futu API  
** Feb 20, 2021**  
  学习了怎样获取行情对象（然后才能对这个对象进行操作），怎样获取全局市场状态（看开闭市信息），怎样订阅一只股票（然后才能查它的历史数据等），以及怎样获取历史K线数据（分析股票回报率，绘图查看走势等）。  
  最重要的是，写了个程序调取了腾讯的历史K线数据并作图，见 “get_tencent_data_and_plot.ipynb”。  
** Feb 21, 2021**  
写了个基于参考点更新的双门槛交易策略，并检验了它在2017-02-01到2021-02-19的回测表现。  
见"two_level_strategy_for_tencent.ipynb"。发现，如果2017-02-01以5万港元开始这个策略，则此自融资投资组合在2021-02-19会增长到14万港元，收益率接近200%。  
见"Portfolio value by two level strategy_Tencent_since_20170201.jpg"  

  
  
