## Tasks Accomplished

- [x] **Real-Time Monitoring** : The model continuously monitors audio input in real-time, ready to detect and classify any potential threats.
- [x] **Anomaly detection** :  The model based on the audio will display alerts or anomalies on the screen if it is perceived as a threat to women's  safety .
- [x] **Automated Decision-Making** : If a threat is perceived, the screen will display the threat along with options for the user to send their live location, report the threat to the police, and call the police directly. There will also be an option to classify the alert as a false alarm.
- [x] **Customizable Dashboards** : The dashboards display data in easy-to-understand charts and graphs, helping users quickly see trends and patterns. Users can adjust alerts, themes, and what is flagged as risky, making the app feel personal and relevant.
- [x] **Data Integration and Processing** : Customer review management and trend analysis :- Whenever we get feedback from users about problems they've faced, we analyze this information to understand where these issues are happening. We sort the problems based on different locations like clubs, lonely roads, workplaces, or homes.

## Technology Stack

The project leverages the following technologies:
- **[Azure](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/speech-to-text):** It is used for real time audio input into text. It is used because of it’s high accuracy.

- **[Roberta](https://huggingface.co/docs/transformers/en/model_doc/roberta):** Roberta is fine tuned on the natural language processing dataset for women safety and is used because of it’s high accuracy of 99 percent on the dataset it is trained.

- **[Flask](https://flask.palletsprojects.com/en/3.0.x/):** Flask is used to handle HTTP requests, interact with the machine learning model, and serve the results to the frontend or other applications.

- **[MongoDB](https://www.mongodb.com/):** MongoDB is used to store critical application data, including user login details and CRM (Customer Relationship Management) data. Its document-oriented structure is well-suited for handling unstructured data like audio metadata and real-time processing needs.

- **[React](https://react.dev/):** React is used to build the frontend of the application, providing an intuitive and user-friendly interface. It allows developers to create dynamic and responsive web applications with a component-based architecture.


## Key Features

- **Feature 1:** Real-Time Monitoring by converting audio to input and threat detection.
- **Feature 2:** Anomaly detection based on real time audio in terms of women safety.
- **Feature 3:** Automated Decision-Making by displaying the threat, options for the user to send their live location, report the threat to the police, and call the police directly. There will also be an option to classify the alert as a false alarm.


## Local Setup Instructions (Write for both windows and macos)

Follow these steps to run the project locally

1. **Download From Drive**
   Drive link : https://drive.google.com/drive/folders/1c0Cku6gPVaLMlmCuhlTv3g5zBno_-JT-?usp=drive_link

2. **Set Up and Run the Flask Backend**
   ```bash
   cd AlgoXen2
   pip install -r requirements.txt
   python app.py
   ```
3. **Set Up and Run the React Frontend**
   ```bash
   cd AlgoXen
   npm i
   npm run start
   ```