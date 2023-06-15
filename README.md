<h1 align="center">
  NBA All-Star Predictor
  </br>
</h1>

## Background and Leading Question

NBA All-Star Predictor is a set of models designed to examine players in the modern era of basketball, focusing on the year 1990 to the present (2022). The introduction of the three-point arc during this time had a significant impact on the pace and style of the game, making it an intriguing period to study.

Our model employs two different prediction models based on a K-Nearest Neighbor and a Neural Network. Both of these techniques have proven to be highly effective, achieving comparable accuracy rates in the range of 90-92%. These predictions allow us to gain valuable insights into player performance and make informed evaluations.

While the primary focus lies within the modern era, a stretch goal is to include data from pre-1990. This expansion would enable a broader capture of the historical context and examine the evolution of basketball over time.

## Repository Breakdown
- data: Repository that stores prescraped player counting stats in the form of a csv for both all stars and non-allstars. 
- allstars.ipyn: The code base that includes the data processing, KNN/NN, the data cleaning, and the data visualization
- requirements.txt: List of python package requirements and their versions. 

### Running the Project

- `Python 3.8.5`
- `pip install -r requirements.txt`
- After downloading the requirements above, simply go to the ipython file and run the individual cells. 

### Viewing the Results
- Simply click on the ipython notebook to see confusion matrices and other results for the various models. 