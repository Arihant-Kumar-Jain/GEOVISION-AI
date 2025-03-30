# GEOVISION-AI
Disaster detection and prediction AI based web app.


We have used U-net(backboned by efficientnet) and sen1floods11 dataset to make this. (for  flood-detection).
We have used FastAI(based on pytorch) for forest-coverage model.
We have used flask for deployement.

Docker file github link(couldn't deploy on render due to high size >4gb after installing dependencies) : https://github.com/Arihant-Kumar-Jain/EnvironmentAnalyzerAI


Youtube link: https://youtu.be/bNaZQ8Ch2UM

how to run?:
pip install -r requirements.txt
python app.py


accuracy went from 60% using efficientnet to 99% using U-net.
and nearly 97% by using FastAI.

rest detailed graphs and confusion matrix can be found in the .ipynb files attached.
