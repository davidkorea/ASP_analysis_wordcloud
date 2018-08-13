# ASP_wordcloud

# Issue 1 - Kaggle install jieba (custom packages)

```python
!pip install jieba # is not supported. Install as followings
``` 


![](https://github.com/davidkorea/ASP_wordcloud/blob/master/README/1.jpg)

![](https://github.com/davidkorea/ASP_wordcloud/blob/master/README/2.jpg)


# Issue 2 

After sorted by  ```data_df[data_df['language']=='zh-CN']```, can not cut by jieba.

Only when you ```to_csv``` to make a new csv file and re-read with ```pd.Dataframe``` can you continue to cut words by jieba.
