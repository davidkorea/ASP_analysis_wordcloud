# ASP_wordcloud

# Issue 1 - Kaggle install jieba (custom packages)

```python
!pip install jieba # is not supported. Install as followings
``` 


![](https://github.com/davidkorea/ASP_wordcloud/blob/master/README/1.jpg)

![](https://github.com/davidkorea/ASP_wordcloud/blob/master/README/2.jpg)


# Issue 2 

After sorted by  ```data_df[data_df['language']=='zh-CN']```, can not cut by jieba. ERROR as below.

Only when you ```to_csv``` to save as a new csv file and re-read with ```pd.Dataframe``` can you continue to cut words by jieba.

```python

KeyError                                  Traceback (most recent call last)
<ipython-input-11-ec7f6ed39bb2> in <module>()

pandas/_libs/index.pyx in pandas._libs.index.IndexEngine.get_value()
pandas/_libs/index.pyx in pandas._libs.index.IndexEngine.get_loc()
pandas/_libs/hashtable_class_helper.pxi in pandas._libs.hashtable.Int64HashTable.get_item()
pandas/_libs/hashtable_class_helper.pxi in pandas._libs.hashtable.Int64HashTable.get_item()
KeyError: 0
```
# Issue 3 - Kaggle use costom font

upload *.tff file as dataset.
 
