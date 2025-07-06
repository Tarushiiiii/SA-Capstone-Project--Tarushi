# SA-Capstone-Project-Tarushi

###  Project Overview

This project presents a three-tiered solution for urban parking demand forecasting and dynamic pricing using real-world data. It was developed as part of the **Summer Analytics 2025 Capstone Project** and involves progressive model development using Pathway. The models ranges from  basic rule-based pricing to demand based pricing, considering various social factors and dynamic route routing conditions

----
###  Tech Stack

| Layer              | Tools/Technologies             |
| ------------------ | ------------------------------ |
| Language           | Python 3.10                     |
| Data Handling      | Pandas, NumPy                  |
| Visualization      | Bokeh                          |
| Model Evaluation   | MAE, RMSE, MAPE                |
| Real-time Pipeline | [Pathway](https://pathway.com) |
| IDEs               | Google Colab                   |
| Version Control    | Git, GitHub                    |

---

### Architecture Flow

#### **Combined**
![image](https://github.com/user-attachments/assets/0a39ff1d-1bf7-4d2c-b534-a127ccec0329)

#### **Model 1**
![image](https://github.com/user-attachments/assets/978be946-c57a-4b07-bb73-8b524553c1b8)

#### **Model 2**
![image](https://github.com/user-attachments/assets/d138d5a5-c142-49e1-b386-77542c9c089c)

#### **Model 3**
![image](https://github.com/user-attachments/assets/28828ab5-6d17-41da-bdef-2f0d2311a147)

---

### Model Descriptions

#### **Model 1: Baseline Pricing Model**

* Rule-based pricing using time, day, and vehicle type.
* Simple logic and static rates.
* [Google Colab](https://colab.research.google.com/github/Tarushiiiii/SA-Capstone-Project--Tarushi/blob/main/Model_1_SA_Capstone_Project.ipynb)

#### **Model 2: Demand-Based Pricing**

* Inputs: Occupancy rate, queue length, traffic congestion, event day flag.
* Dynamic adjustment of pricing using linear coefficients.
* [Google Colab](https://colab.research.google.com/github/Tarushiiiii/SA-Capstone-Project--Tarushi/blob/main/Model_2_SA_Capstone_Project.ipynb)

#### **Model 3: Optimal Routing and Competitive Pricing**

* Uses **Pathway** for real-time stream-based decision making.
* Recommends lots based on availability, congestion, and pricing competition.
* Competitive pricing with equilibrium logic and responsiveness.
* [Google Colab](https://colab.research.google.com/github/Tarushiiiii/SA-Capstone-Project--Tarushi/blob/main/Model_3_SA_Capstone_Project.ipynb)

---

### Visual Outputs

Each model outputs interactive **Bokeh plots** for pricing trends and lot utilization. These are saved as `.png` files in the repository.

---

### Running the Project

1. **Clone the repository**

   ```bash
   git clone https://github.com/Tarushiiiii/SA-Capstone-Project--Tarushi.git
   cd SA-Capstone-Project--Tarushi
   ```

2. **Run a specific model notebook or script**

   ```bash
   python model_1_sa_capstone_project.py
   ```

   Or open the respective `.ipynb` file in Google Colab or Jupyter.

---

### 📁 Repository Structure

```
├── Model_1_SA_Capstone_Project.ipynb
├── model_1_sa_capstone_project.py
├── bokeh_plot_model-1.png
├── Model_2_SA_Capstone_Project.ipynb
├── model_2_sa_capstone_project.py
├── bokeh_plot_model-2.png
├── Model_3_SA_Capstone_Project.ipynb
├── model_3_sa_capstone_project.py
├── bokeh_plot_model-3.png
├── project_report.pdf
└── README.md
```

---

### Author

**Tarushi Agarwal**
- Email: [agarwaltaru6@gmail.com](mailto:agarwaltaru6@gmail.com)
- LinkedIn: [Tarushi Agarwal](https://www.linkedin.com/in/tarushi-agarwal-ba0a5a325/)
- GitHub: [@Tarushiiiii](https://github.com/Tarushiiiii)
