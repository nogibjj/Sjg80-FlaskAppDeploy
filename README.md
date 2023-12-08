# Auto Scaling Flask App Using Azure Wep App

Video Tutorial: https://youtu.be/ruIbk7N_qEc

# Height vs Age Predictor Microservice

The **Height vs Age Predictor Microservice** is a Flask-based web application that predicts heights based on ages. It uses a machine learning model trained on provided age and height data to generate predictions and visualize the relationship between age and height.

<img width="975" alt="image" src="https://github.com/nogibjj/Sjg80-FlaskAppDeploy/assets/142270941/105658ac-673b-4f1d-99c8-82e162397c29">

## Dependencies

![image](https://github.com/nogibjj/Sjg80-FlaskAppDeploy/assets/142270941/f2dd6359-2200-4e10-a77f-a5d29d44c33f)

- Python 3.10
- Flask
- NumPy
- Scikit-learn
- Plotly
- Joblib

## How to Run the Program

### Running the Microservice

1. Ensure Python 3.10 is installed on your system.
2. Install the necessary dependencies using `pip install -r requirements.txt`.
3. Run the Flask app by executing `python app.py` from the project root.
4. Access the app in your browser at (https://flaskappregression.azurewebsites.net/)

<img width="1451" alt="image" src="https://github.com/nogibjj/Sjg80-FlaskAppDeploy/assets/142270941/5e45d027-ebc9-4296-a3a3-7117cbb88593">
<img width="757" alt="image" src="https://github.com/nogibjj/Sjg80-FlaskAppDeploy/assets/142270941/b6faf945-77d1-43f2-9b59-a5af5c138e3c">

### Using the Prediction Tool

1. Enter comma-separated ages into the input field.
2. Submit the form to receive a visualization of the predicted heights based on the provided ages.

<img width="519" alt="image" src="https://github.com/nogibjj/Sjg80-FlaskAppDeploy/assets/142270941/b1e68e05-b7e4-4217-a977-79cd7a449b7e">

## Recommendations to Management

**Actionable Insights:**

- Utilize this microservice as a tool for predicting heights based on age input, which could be valuable in various domains such as health, pediatrics, or educational research.
- Consider extending the microservice to handle larger datasets or additional features beyond age and height for more comprehensive predictive capabilities.

**Data-Driven Decision Making:**

- Leverage the model's predictions to gain insights into potential growth patterns or trends related to age and height, enabling data-driven decision-making in relevant fields.
- Explore ways to enhance the model's accuracy and robustness by incorporating more diverse datasets or utilizing advanced machine learning techniques.

**Scalability and Deployment:**

- Evaluate the microservice's scalability under increased user load to ensure seamless performance in production environments.

![image](https://github.com/nogibjj/Sjg80-FlaskAppDeploy/assets/142270941/77756310-b17e-4f64-9c75-169b6c15da0d)

**References**
https://learn.microsoft.com/en-us/azure/developer/python/tutorial-containerize-deploy-python-web-app-azure-03?tabs=azure-portal

https://www.jamessturtevant.com/posts/Deploying-Python-Website-To-Azure-Web-with-Docker/

https://learn.microsoft.com/en-us/azure/developer/python/tutorial-containerize-simple-web-app?tabs=web-app-flask

https://learn.microsoft.com/en-us/azure/app-service/deploy-github-actions?tabs=applevel#generate-deployment-credentials
