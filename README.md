The Jupyter Notebook builds and runs the hyperparameter tuning job as well as the CICD pipleline. 

The CICD pipeline run by a Google Clound Function. The deployed Google Cloud function is triggered by Google Pub/Sub topic messege to which the Github Actions sends a messege when there is a push to the repository.
