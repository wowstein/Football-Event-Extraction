<h1>Football Event Extraction</h1>


<h2>Description</h2>
This project is an an event extraction program that can convert football match videos into 'goal', 'loss' and 'happy' moments. For this purpose, I have created a CNN-LSTM classifier model to categorize each moment of the match.
All predicted moments(with a confidence of 0.7 or more) are then extracted into clips and placed in their corresponding directories.


<h2>Libraries Used</h2>

- <b>Keras</b> 
- <b>OpenCV</b>
- <b>MoviePy</b>

<h2>Environment Used </h2>

- <b>Jupyter Notebook</b> 

<h2>Screenshots of extracted clips:</h2>

<p align="center">
Happy : <br/>
<img src="https://github.com/wowstein/Football-Event-Extraction/assets/142371525/855f4d5d-6fcc-464f-a258-c1cc45c9fd23"/>
<br />
<br />
Goal:  <br/>
<img src="https://github.com/wowstein/Football-Event-Extraction/assets/142371525/27991e2d-9b4b-4498-99ba-db7cc7b5b494"/>
<br />
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>

