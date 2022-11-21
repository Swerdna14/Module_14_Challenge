# Module_14_Challenge

The first strategy we attempted was the base method that was predetermined for us. Both the SVM model and Logistics regression model were almost exactly the same with the actual profits till around 2019 before the crash in 2020 and then recovering in late 2020 to ultimately remain ahead of the actual profits (base_plot's).

I then altered the date and started the data from 2016 instead of 2015. There was a massive crash towards the end of 2015 and that helped the base data predict the future to make a profit whereas the sliced data starting from 2016 immediately fell behind the actual returns and got worse as it reached 2021. (altered_date)

A final strategy change was made, altering the SMA windows and reducing them by 25% (short window from 4 to 3 & long window from 100 to 75). This didn't have an as drastic change to the strategy returns as changing the beginning point of the data did. There was a period for most of 2018 when it fell behind but started to get better results in 2019 and pull ahead after the 2020 crash. (altered_SMA)

Overall, the base strategy had the best strategy returns compared to the other two altered strategies. Changing the starting date was by far the worst strategy being massively behind the actual returns. The altered SMA strategy returns did perform better than the actual returns but only just above, and ultimately not more than the base strategy returns.
