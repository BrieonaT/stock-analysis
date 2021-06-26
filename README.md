The original task of this assignment was to help a man named Steve's parents decide on which were the best green energy stocks to invest in. This was done by collecting and forming a sheet in Excel with multiple stocks dealing in green energy. This then branched out, with Steve wanting a way to analyze more stocks in the market. The original code would not work as well for thousands of stocks compared to the dozen we were tasked with analyzing, so this led to the code needing to be refactored to be able to be used for a wider range of data.

After building out the code from it's original state into the refactored code, we were able to get results on not only the stock analysis, but also how the refactored code faired against the original code in terms of which was more condusive to get the stock results. The actual stock results showed a major dip in most of the stocks' yearly returns. This is evident in the data exhibited below, showing that most stocks had a negative return during 2018, except for ENPH and RUN, who remained in positive returns between the years. A further look at this shows that ENPH went down in yearly returns (From 129.5% in 2017 to 81.9% in 2018), but RUN actually went up by a considerable amount (from 5.5% in 2017 to 84.0% in 2019).

![2017 Refactored Code](https://github.com/BrieonaT/stock-analysis/blob/main/VBA_Challenge_2017.png)
![2018 Refactored Code](https://github.com/BrieonaT/stock-analysis/blob/main/VBA_Challenge_2018.png)

As for how the refactored code held against the original, it's quite evident that the refactored code significantly improves upon the original. This is shown comparing the above image featuring the run times of the refactored code against the images below of the original code. The refactored code for both 2017 and 2018 took less than a second to show the selected data, whereas the old code took over a second to show the selected data. In addition, the refactored code could be used for larger sets of data and take less time to enact versuses the original code.

![2017 and 2018 Un-refactored code times](https://github.com/BrieonaT/stock-analysis/blob/main/VBA_Challenge_Original_Code_Times.png.png)

In conclusion, the information we can gather from the stocks is that it would be best to invest in RUN out of all of these. In addition, there are some pros and cons that come with refactoring the code. A pro would include the fact that it helps run the data in a more smooth manner. Again, this is shown by the difference in run times between the original and refactored code. A con however would be the fact that getting the code refactored takes additional time onto what you've already spent making the original code. In this specific VBA script, it took me a few days to fix issues within the refactored code, whereas the original code took much less time and I ran into less bugs while coding it in. However, I believe the refactoring is worth it when you account in the run-times on a client's end, especially if the data set was much larger than the one used for this assignment.
