# MiniProject_2

Hey! Today, I'll be analyzing the **amount of successful operations made by clients depending on the platform.** Here is a list of tasks that I want to solve:

1. Import the pandas library as pd. Load the datasets user_data and logs. Check the size, data types, missing values, and descriptive statistics of the datasets.
2. Identify the client who made the most successful operations (where success == True).
3. Determine the platform from which the highest number of successful operations are made.
4. Identify the platform preferred by premium clients.
5. Visualize the distribution of clients' ages based on their type (premium or not).
6. Plot the distribution of successful operations.
7. Visualize the number of successful operations made on the computer platform by age using sns.countplot. Find out which age group made the most successful actions.

Here is a description of data:

**user_data:**

- client – user identifier
- premium – whether the client is premium
- age – age

**logs:**

- client – user identifier
- success – outcome (success - 1, no - 0)
- platform – platform
- time – time in Unix format
