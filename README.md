# Find-My-Yoga
Find My Yoga is an app found at findmyyoga.site.
In the app, a neural net powers the identification of four groups of yoga poses to enable users to select which yoga video they're most interested to watch.

Created by Julianne Freeman<br>
Insight Fellow 2018B<br>
<br>

# Data pipeline<br>
1. Download yoga video using url from YouTube
2. Split video into frames
3. Load frames into CNN
4. Identify yoga pose in each frame
5. Save in MySQL database<br>
<br>

# Transfer Learning to create CNN 
<i>ipynbs used for transfer learning available in repository</i>
1. Part 1: Data preprocessing
2. Part 2: Transfer Learning + Cross-validation

