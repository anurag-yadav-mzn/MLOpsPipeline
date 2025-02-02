# MLOpsPipeline
MLOps Pipeline using Apache Airflow and Python<br/>
Objective:<br/>
A wellness app company wants to introduce a new feature to promote healthier screen usage habits. Using historical app usage data, they aim to predict daily screen time for specific apps and send personalized notifications encouraging breaks when the predicted usage is likely to exceed predefined thresholds.<br/>
The goal of this pipeline is to streamline the process of analyzing screentime data by automating its preprocessing and utilizing machine learning to predict app usage. To ensure seamless execution, we will design an Airflow DAG to schedule and automate daily data preprocessing tasks to support a robust and scalable workflow.<br/>
<ul>
Dataset contains app usage behaviour with five key columns:
<li>
Date (usage day)
</li>
<li>  
App (e.g., Instagram, WhatsApp)
</li>
<li>
Usage (minutes spent)
</li>
<li>
Notifications (alerts received)
</li>
<li>
Times Opened (app launches).
</li>
</ul>
