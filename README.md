# Exo-Planet Classification<br>
<h3>The aim of this project is to Detect Exoplanets from light curves of Kepler Mission using FFT and analyze to what extent they affect the accuracy of Exo-Planets Classification</h3>  
<br>
The quest for finding life and habitat in the universe other than earth has been going on since long. To uncover it, National Aeronautics and Space Administration (NASA) has Kepler Mission which captured data of brightness of stars which are called light curves. These are formed when a star transits from one place to another. This star could be an exo-planet and this is decided by checking its brightness. 

This data is in the form of time series format. Support Vector Machine is applied on this data. To improve the performance of models this research uses pre-processing technique like Fast Fourier Transform  before feeding the data to any models. Then Support Vector Machine was again used. 

Different patterns were plotted and time series data was analysed to check if the data point is exoplanet or not. Lastly, the results after FFT were compared with Time Series data. That is,the results for with and without pre processing techniques are compared. They show how FFT makes a difference in getting improved performance in terms of accuracy, precision, F1 score, etc.


<h3>Visualization of ExoPlanet and Non-ExoPlanet Data in Time Series, FFT </h3>
<table>
<tr>
  
  <th scope="col">Method</th>
  <th scope="col">Positive Data</th>
  <th scope="col">Negative Data</th>
</tr>

<tr>
  <th scope="row">Time Series</th>
  <td><img src="/Images/Time_Pos.JPG" width="350" height="200"></td>
  <td><img src="/Images/Time_Neg.JPG" width="350" height="200"></td>
</tr>
   
<tr>
  <th scope="row">FFT</th>
  <td><img src="/Images/FFT_Pos.JPG" width="350" height="200"></td>
  <td><img src="/Images/FFT_Neg.JPG" width="350" height="200"></td>
</tr>

  
</table>

<br><br>
NOTE:<br>
Due to hardware limitations the data used for training purpose is just a small portion of total data. Due to this, the accuracy has dropped drastically. The accuracy of the models can be increased by considering more data. The aim was to analyse the effect of FFT and Recurrence Plots on the accuracy of Exo-Planet classification.   
