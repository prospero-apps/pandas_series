# pandas_series

Basics of Pandas - blog post series

## Contents

### pandas Part 1 – Introduction to Pandas
Pandas is a Python module that builds on top of numpy and is used to deal with data in a comfortable way. Many of its features and operations should quickly become familiar to you if you use some database programs or spreadsheets. With pandas you can manipulate structured data, which can be easily labeled.

![image](https://github.com/user-attachments/assets/76fbe8ff-2b18-45fe-85d7-04b10b4d8c45)


### pandas Part 2 – the Series Class
In this part we'll be talking about the Series class, which is one of the fundamental data types in pandas.

![image](https://github.com/user-attachments/assets/bfc30e96-74c3-4d01-9548-e28c0fc3472b)


### pandas Part 3 – Creating Series Objects
Let's have a closer look at how Series objects can be created.

![image](https://github.com/user-attachments/assets/34569672-103a-4ffd-a788-1e63d9e2a875)


### pandas Part 4 – the DataFrame Class
In this part we'll be talking about another fundamental pandas data type, the DataFrame.

![image](https://github.com/user-attachments/assets/5fa63dce-50be-4e7c-b2a8-d2b069802927)


### pandas Part 5 – Creating DataFrame Objects
DataFrame objects can be created in a couple ways. Let's explore.

![image](https://github.com/user-attachments/assets/61974db6-b68b-4e7c-9f5f-60da53ae4f87)


### pandas Part 6 – the Index Class
In the previous parts of this series we discussed two of the three fundamental data types in pandas, the Series and the DataFrame. In this part we'll be talking about the third one, the Index.

![image](https://github.com/user-attachments/assets/9d3e1a39-02a9-4d5e-883b-00ba1b0ea883)


### pandas Part 7 – Slicing and Indexing Series Objects
In this part, we'll be talking about slicing and indexing Series objects.

![image](https://github.com/user-attachments/assets/36ec218c-a51e-4f4c-a3b5-c1529dde38ec)


### pandas Part 8 – The loc and iloc Indexers
In this part, we'll discuss the loc and iloc indexers.

![image](https://github.com/user-attachments/assets/71d4b831-bb38-41bc-be3e-06a9ef8cb952)


### pandas Part 9 – Indexing and Slicing DataFrame Objects
We know how to index and slice Series objects. What about DataFrames?

![image](https://github.com/user-attachments/assets/141c6b06-624b-4e53-9033-d91b0dab1d92)


### pandas Part 10 – Operations on Data
Pandas makes it easy to operate on data. In case of unary operations index and column labels are preserved. In case of binary operations indices are aligned.

![image](https://github.com/user-attachments/assets/7f66bffa-cbbe-49ac-82d7-e2547a584d9c)


### pandas Part 11 – Missing Data
In real-life scenarios data is seldom complete. How does pandas handle missing data?

![image](https://github.com/user-attachments/assets/9ab05bc2-94e6-4bab-a3f9-035affbdd7fd)


### pandas Part 12 – Pandas MultiIndex
The two data structures that you know, Series and DataFrame, are basically used for one- and two-dimensional data respectively. But you can also use them with higher-dimensional data. It consists of creating several index levels within a single index. We call it multi-indexing.

![image](https://github.com/user-attachments/assets/80494b16-8bf7-4ede-9f8a-bab483cedb87)


### pandas Part 13 – Stacking and Unstacking MultiIndices
In this article we'll be working on our example from the previous part. Our subject today is stacking and unstacking multi-indices.

![image](https://github.com/user-attachments/assets/72820c2e-a5be-4e50-833a-0e2a0fb65703)


### pandas Part 14 – Using Pandas MultiIndex for Multidimensional Data
We can use the MultiIndex for multidimensional data. Let's see how.

![image](https://github.com/user-attachments/assets/ae79eb9d-502c-4449-b5bb-875d669315ae)


### pandas Part 15 – Implicit Creation of Multi-Indexed Objects
In the previous couple articles in the Pandas series we were talking about multi-indexed objects. But sometimes multi-indexed objects are created behind the scenes.

![image](https://github.com/user-attachments/assets/04dab516-28f6-474e-ad1b-92268f732d4e)


### pandas Part 16 – Explicit Creation of Multi-Indexed Objects
In the previous part of the Pandas series we were creating multi-indexed objects implicitly, so actually they were created behind the scenes. But sometimes you may want to create them explicitly. We can explicitly create MultiIndex objects by means of some methods in the MultiIndex class.

![image](https://github.com/user-attachments/assets/ec99d744-6cbb-4521-8b61-72d983582d64)


### pandas Part 17 – Named MultiIndex Levels
Sometimes it's useful to name the levels of an MultiIndex object. 

![image](https://github.com/user-attachments/assets/7cdf4060-6633-4785-9c11-45866a4ea163)


### pandas Part 18 – Multi-Indexed DataFrame Columns
Up to now we've been using multi-level indexing for rows, but it also works with columns. In this part we'll create a four-dimensional DataFrame with two levels of indexing for the rows and two levels of indexing for the columns.

![image](https://github.com/user-attachments/assets/a4b12a49-7481-4bb7-a9a7-813a99561c92)


### pandas Part 19 – Indexing and Slicing Multiply Indexed Series
Indexing and slicing multiply indexed Series is intuitive.

![image](https://github.com/user-attachments/assets/968401b4-b063-43ab-8149-564164794a31)


### pandas Part 20 – Indexing and Slicing Multiply Indexed DataFrames
In the previous part of the Pandas series we were talking about indexing and slicing multiply indexed Series objects. Today we'll be talking about multiply indexed DataFrames. They behave very much like Series objects as far as indexing and slicing is concerned. 

![image](https://github.com/user-attachments/assets/6169b894-124c-4bb4-ab89-3a83706fd531)


### pandas Part 21 – Sorting MultiIndices
Sorting multi-indices is important because many slicing operations only work on sorted data.

![image](https://github.com/user-attachments/assets/68565278-f772-4102-af37-b8e2ce6f69a3)


### pandas Part 22 – Setting and Resetting Indices
In the previous part of the Pandas series we were talking about sorting indices. Today we'll be talking about another way of rearranging multi-indexed data, index setting and resetting.

![image](https://github.com/user-attachments/assets/646b911e-f35a-4e9f-bc64-b2b054910199)


### pandas Part 23 – Data Aggragation on MultiIndices
We can aggregate hierarchically indexed data using common aggragation methods like mean, sum, min or max. 

![image](https://github.com/user-attachments/assets/3571608d-c9ab-4c06-bdef-1ee7c5cf43e9)


### pandas Part 24 – Dataset Concatenation
We can concatenate Series and DataFrame objects using the pd.concat method.

![image](https://github.com/user-attachments/assets/31f65245-eb5b-452b-bb45-7681bbb69df3)

