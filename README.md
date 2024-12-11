# Campus Placement Prediction Using Machine Learning

This project predicts the likelihood of a student being placed in a campus recruitment drive based on their academic and personal profiles. It uses machine learning techniques to analyze and process the data, enabling better decision-making for students and recruiters.

---

## Table of Contents

1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Project Workflow](#project-workflow)
4. [Technologies Used](#technologies-used)
5. [Setup and Installation](#setup-and-installation)
6. [Results](#results)
7. [Future Enhancements](#future-enhancements)
8. [License](#license)

---

## Introduction

The project leverages exploratory data analysis (EDA) and machine learning models to predict whether a student will be placed and their expected salary range based on historical data.

---

## Dataset

- **Source:** Campus recruitment dataset (include the source link or reference if publicly available).


![Screenshot 2024-11-28 204858](https://github.com/user-attachments/assets/d563b282-a0d5-4817-9f44-cce80824289e)


- **Features:** Various attributes such as academic scores, work experience, and salary details.


![Screenshot 2024-11-28 205110](https://github.com/user-attachments/assets/c8446406-781a-4273-b557-a19a9c044ed3)

- **Target Variable:** Placement status (placed/unplaced).
- **Preprocessing:** Encoding categorical columns, handling null values, and feature scaling.
![Screenshot 2024-11-28 204946](https://github.com/user-attachments/assets/0b967f66-1a73-40bc-889e-2f892e6aa8af)

![Screenshot 2024-11-28 204934](https://github.com/user-attachments/assets/2b7da950-1d5c-4e43-8b7c-3cab4d4263f2)






---

## Project Workflow

1. **Data Exploration**
   - Displayed the top and bottom rows of the dataset.
   - Examined the dataset's shape and missing values.

   ![Screenshot 2024-11-28 204541](https://github.com/user-attachments/assets/5135939d-18fa-4056-b858-d481a5a89aa9)
![Screenshot 2024-11-28 204922](https://github.com/user-attachments/assets/c3944249-ed9f-4bb1-8cbf-6aff63a8089e)

2. **Exploratory Data Analysis**
   - Analyzed placement trends, salary distributions, and correlations.



![Screenshot 2024-11-29 102438](https://github.com/user-attachments/assets/9ffc8028-df59-459e-ad96-2b4f713d8a35)
![Screenshot 2024-11-29 102453](https://github.com/user-attachments/assets/1a5fd622-4b8b-4b32-ba8c-62359f67e86b)
![Screenshot 2024-11-29 102506](https://github.com/user-attachments/assets/5c8bf81e-34ca-427e-92f9-9d8e03438782)
![Screenshot 2024-11-29 102514](https://github.com/user-attachments/assets/913dd36e-ff3c-4623-a714-677228a5f8b8)
![Screenshot 2024-11-29 102540](https://github.com/user-attachments/assets/1ad6f91b-7cb6-404d-be96-fea024f5dbbc)
![Screenshot 2024-11-29 102646](https://github.com/user-attachments/assets/ef9a2dec-8253-41d3-9cf3-2b914f334d5e)

  ![Screenshot 2024-11-29 102521](https://github.com/user-attachments/assets/0a85cd88-4b77-4f63-bb16-949b6b1d1f77)

3. **Data Preprocessing**
   - Encoded categorical variables.
   - Split the data into training and testing sets.

![Screenshot 2024-11-28 205356](https://github.com/user-attachments/assets/68f86bdd-bf10-49eb-a629-6ccbd00f35da)
![Screenshot 2024-11-28 205409](https://github.com/user-attachments/assets/8d44e71d-aa6c-4570-911e-28d17a92d2e2)
![Screenshot 2024-11-28 205419](https://github.com/user-attachments/assets/e135347f-866a-48d3-bd73-1759becfe025)
![Screenshot 2024-11-28 205543](https://github.com/user-attachments/assets/89e51d7c-3866-434c-a653-3be0594fe3cc)
![Screenshot 2024-11-28 205555](https://github.com/user-attachments/assets/9b915605-4b8d-4541-8adf-24ba348c7f96)





4. **Model Training**
   - Tested multiple models including logistic regression, decision trees, and others.
   ![Screenshot 2024-11-28 205335](https://github.com/user-attachments/assets/c0d80c31-9a59-49e6-aa48-526ceff678cf)


   ![Screenshot 2024-11-28 205323](https://github.com/user-attachments/assets/4f9981d5-4a15-4dce-ad15-e93130752e6d)

5. **Model Evaluation**
   - Evaluated models using accuracy and other metrics.
   ![Screenshot 2024-11-28 205409](https://github.com/user-attachments/assets/8d44e71d-aa6c-4570-911e-28d17a92d2e2)


6. **Deployment**
   - Saved the final model using Joblib for future predictions.
   - Created a GUI for user interaction.



![Screenshot 2024-11-28 205759](https://github.com/user-attachments/assets/6ff2e57e-6922-4f5d-b9be-97095b870354)
![Screenshot 2024-11-28 205850](https://github.com/user-attachments/assets/285cfe07-674d-4a96-90e0-4adb171710c3)



---

## Technologies Used

- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Scikit-learn, Joblib
- **Tools:** Jupyter Notebook

---

## Setup and Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/CampusPlacementPrediction.git
   cd CampusPlacementPrediction
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:
   ```bash
   jupyter notebook Campus_Placement_Prediction.ipynb
   ```

4. Launch the GUI:
   ```bash
   python gui.py
   ```

---

## Results

- Achieved high accuracy in predicting placement outcomes.
- Visualized important insights from the dataset, such as:
  - Placement distribution.
  - Salary trends.
  ![Screenshot 2024-11-28 210002](https://github.com/user-attachments/assets/d28dd5be-60fe-4d20-a133-1962e1dd181d)






---

## Future Enhancements

- Integrate additional features like student projects or extracurricular activities.
- Improve the GUI for a better user experience.
- Add real-time prediction functionality via a web application.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
