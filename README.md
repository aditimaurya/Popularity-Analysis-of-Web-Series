# Pocket-Aces-Task
Hello ,
The reports of bothe the tasks have been found here: 
1. [Task 1](https://docs.google.com/document/d/11y8Dp0pxtM7VRwwtngeAQUTne2u-YtYo0XMWZZg41uE/edit#heading=h.pl1udho7yq8v) ( Comparative Analysis of two different shows).
2. [Task2](https://docs.google.com/document/d/1eBPrYeclbIQFf2dxNq0plP1t-BlmQgmVqXpeiRBLEpQ/edit?usp=sharing) Popularity Analysis of Ayush and Barkha in PFA Season 2.

Below is the brief disscussion that how to use this repository:
### end to end process:
![1212](https://user-images.githubusercontent.com/50532530/135895881-b197fd48-496e-40c1-8432-3c9315895917.PNG)

- Use [Dataset Cleaning code](https://github.com/aditimaurya/Pocket-Aces-Task/blob/main/Code/Data_Preprocessing%20and%20scoring.ipynb) For cleaning the data.
- USe for [Model Making code](https://github.com/aditimaurya/Pocket-Aces-Task/blob/main/Code/Sentiment%20classifier.ipynb) making the model
```
df = pd.read_csv('Dataset file path')
```

Add your dataset like this in the .ipynb.
Here are the dataset folder for using the datasets: 
For making the plots these have been used :
- [tableau](https://www.tableau.com/)
- [matplotlib](https://matplotlib.org/)
- [plotly](https://plotly.com/)

An eample of making the plots:
```
sns.lineplot(x="hour", y="empath_score", data=YOUR_DATA)
plt.show()   
```
Output:

![8xR5yt99AAAAAElFTkSuQmCC](https://user-images.githubusercontent.com/50532530/135898354-40359cec-5d30-4711-90c8-10c0928e0697.png)

# Random forest model for classification 
random forest model has been used for future prediction and there lots of things can be updated.
![index](https://user-images.githubusercontent.com/50532530/135898051-6d7cd636-b8e5-4f17-89e1-1f8abba9fda5.png)

### Thank You.
