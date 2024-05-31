# ABOUT MY FIRST PROJECT
creating a bar chart or histogram to visualize the distribution of a categorical or continuous variable,such as the distribution of ages or genders in a population
import matplotlib.pyplot as plt
import numpy as np

# Generate random ages for demonstrationn
ages = np.random.randint(18, 80, size=100)

# Create histogram
plt.hist(ages, bins=10, edgecolor='black')
plt.title('Distribution of Ages')
plt.xlabel('Age')
plt.ylabel('Count')
plt.show()

import matplotlib.pyplot as plt

# Sample data
genders = ['Male', 'Female', 'Non-binary']
counts = [300, 350, 50]

# Create bar chart
plt.bar(genders, counts)
plt.title('Distribution of Gender')
plt.xlabel('Gender')
plt.ylabel('Count')
plt.show()
