# Internal_data_sourcing_EDA

## Introduction
Performed exploratory data analysis on Müsli distribution company. Where the company wanted to understand if their delivery process is healthy. 
Here, I help them to improve the service they offer their customers by developing KPI's and performing EDA with my (other three) team members.

Provided data is of four consistent years from 2017-2020. Data was privately provided by our bootcamp institution. It contains approximately 1 million enteries with geographical locations. 
Overal annual sales fo the company showed gradual increase. That indicates the company is doing all well.
However, to avoid future catastrophies it is always good to keep a watch on current data. The delivery procedure of this distribution company is bit complex because its not even for all the week days.
Deep diving into data gave us completely different scenario. Hereby, I will
present our results from EDA and the regarding code can be found in the notebook file müsli_distributors.ipynb.

### Explanation: How the company functions towards Müsli distribution
![flowchart_müsli](https://github.com/prache/Internal_data_sourcing_EDA/assets/25516674/fc45de41-dbfb-475f-af64-16a745ec6174)

### Details about the delivery per week
To have even clear view about each weeks delivery process, we sketched this.
![understand](https://github.com/prache/Internal_data_sourcing_EDA/assets/25516674/9efab366-54e7-4a80-8663-cc7a07c58a72)

## Questions
Our aim was to test the health of the business based on the provided data. Therefore, we asked the following questions
1. How long does it take to process each step? (shipping, pick-up, and transport)
2. Are orders getting processed on time?
3. Are orders getting picked-up on time?
4. Are orders getting delivered on time?
5. What is the prediction of the whole time?
6. Is it beneficial to have daily Pick up?

## Results:
### Annual sales of the company
![annual sales_müsli](https://github.com/prache/Internal_data_sourcing_EDA/assets/25516674/320843fc-b7f0-4448-bb64-ee5699f3bd95)

### Question 1:
How long does it take to process each step? (shipping, pick-up, and transport)

![time](https://github.com/prache/Internal_data_sourcing_EDA/assets/25516674/fc3992d5-228a-4293-b1fa-e9ddf54cfd02)
### Question 2:
Are orders getting processed on time?

![processed](https://github.com/prache/Internal_data_sourcing_EDA/assets/25516674/dbb356e6-419c-4c59-ac9d-26aad7acd64d) ![express](https://github.com/prache/Internal_data_sourcing_EDA/assets/25516674/17dae445-c29b-4f81-b1f2-bf7d214b9583)
### Question 3:
Are orders getting picked-up on time?

![pickup](https://github.com/prache/Internal_data_sourcing_EDA/assets/25516674/3bad70b0-f269-481c-9152-72ca11010781) ![pickup express](https://github.com/prache/Internal_data_sourcing_EDA/assets/25516674/aa68160a-9238-496b-a1b2-1e47e46d5c49)
### Question 4:
 Are orders getting delivered on time?
 
![delivery](https://github.com/prache/Internal_data_sourcing_EDA/assets/25516674/c215baab-16a0-4290-82f1-f69c9d2a89e4) ![delivery_express](https://github.com/prache/Internal_data_sourcing_EDA/assets/25516674/ac2c48a6-3371-43ef-bccb-1637dfaeb6a9)
### Question 5:
What is the prediction of the whole time?

![pred1](https://github.com/prache/Internal_data_sourcing_EDA/assets/25516674/8931c4d9-8a7a-49c7-bfc8-6963da118dd9) ![pred2](https://github.com/prache/Internal_data_sourcing_EDA/assets/25516674/feec733c-51db-4988-bcd8-c04d8ed15db6)
### Question 6:
Is it beneficial to have daily Pick up?

![final](https://github.com/prache/Internal_data_sourcing_EDA/assets/25516674/4d42e832-26ba-40f2-ab7d-f9ac402dfd86)

## Recommendations:
1. Average order processing time: 10 days.
2. Check with logistics about the transit time insights. 
3. Order processing time for standard shipping mode needs to be controlled.
4. The daily pick-up option will have major impact on express mode as compared to standard mode. 

Best option is to employ more staff for order processing and consider all the orders as express shipping mode!


















