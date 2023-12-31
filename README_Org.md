>   **Abstract:**

>   My final capstone project is continuation of assigmnet 20 , which reflects my culmination of learning and understanding in ML in this coures, I have realized that there is still much more to learn to effectively apply it in a real-world context.

>   We are currently in the process of developing an initial Pay-Per-Use dermatology Electronic Medical Record (EMR) solution specifically designed for the Indian market. One essential feature that would greatly assist doctors is a patient complaint triage system. However, our platform, https://symabMED.in, is not yet ready for deployment. To ensure the efficacy and dependability of our solution in real-world situations in India, our system needs to operate continuously for 12 to 18 months. During this phase, we will collect relevant metadata and high-resolution images, accurately categorized, which is crucial for the success of our solution.

![A screenshot of a computer Description automatically generated with medium confidence](media/08a7bc76cabdf26c35148bb6281cfc58.png)

>   In the interim, it would be advantageous to develop a generic framework using the HAM10000 dataset. This dataset can serve as a valuable resource for training and conducting initial system testing. By constructing and refining the framework using this dataset, you can evaluate its performance, make necessary enhancements, and acquire valuable insights before incorporating the authentic data from the Indian market. This approach will provide a solid foundation and enable you to iteratively improve the system based on the lessons learned.

>   Skin cancers encompass a range of diseases marked by the presence of abnormal growths or persistent sores that do not heal, as well as alterations in the size, shape, or colour of moles. There are two primary types: melanoma (less prevalent but more hazardous) and non-melanoma skin cancers (more common but less severe).

>   Notably, India experiences a relatively lower incidence of skin cancer than Western countries. This can be attributed, in part, to individuals with darker skin being less susceptible to this condition. The higher levels of melanin in darker skin provide a certain degree of protection against damage caused by UV radiation, thereby reducing the risk of developing skin cancer

>   However, regional variations can play a role in the prevalence of skin cancer in India: our system, in addition to other standard data like age, gender and what is included in the HAM dataset, a new training data may include the following features.

>   Latitude: Regions closer to the equator receive more intense sunlight, increasing the risk of skin cancer. Hence, regions in the southern part of India may see a slightly higher incidence rate.

>   Altitude: Higher altitudes receive more UV radiation. Therefore, areas at higher elevations could potentially have a higher incidence of skin cancer.

>   Outdoor occupations: In regions where more people work outdoors (like farming communities), there are increased sun exposure and a potentially higher risk of skin cancer.

>   Urban vs rural: Urban areas might see different rates due to lifestyle differences, including more indoor work and potentially more access to healthcare for early detection.

>   Cultural and social practices: Clothing, sunscreens, and shade can vary by region and influence skin cancer rates. Some traditional attire covers much of the body, providing natural sun protection

>   I intend to build a generic framework as part of my capstone project. This framework consists of the following routines by taking in DataFrame.

-   Pre and post-reports to provide details of the dataset
-   Remove corrupt images
-   Blancding the dataset
-   standardize the image files
-   feature cleaning and normalization (such as one-hot encoding and replacing null values)
-   identify a suitable machine-learning model for categorization prediction.
-   and if time permits implimating API to input data to get the prdiction.

>   By developing and implementing these routines, I aim to enhance the quality and consistency of the metadata within the dataset, ensuring that it is well-organized and suitable for further analysis, ensuring that the dataset remains reliable and accurate for subsequent image-based analysis and processing.

>   I intend to test this routine using the HAM10000 dataset from the year 2020.

>   If all components of the project work as intended, you will have a comprehensive codebase capable of handling any DataFrame for image classification. Furthermore, the framework will facilitate data visualization and preparation for ML modelling, including selecting appropriate models. Additionally, I aim to provide an API that can be utilized as a real-world service.

>   **Problem Statement**:

>   "Develop a machine learning model to assist dermatologists in India with triaging skin conditions. The model should classify different skin conditions based on images, aiding in quicker and more efficient preliminary diagnosis. The target is to improve the efficiency of dermatologists by reducing their workload, enabling them to focus on more complex and urgent cases. The model is not intended to replace human diagnosis but to supplement it, serving as a first-line screening tool."

-   Step 1: define the row CSV file
-   Step 2: write a code for pre-processing the dataset
    -   Create DataFrame
    -   Sumerzies the datset inormation
    -   Visualize the data set
    -   Report the issues
-   Step 3: write a code for processing the dataset
    -   remove corrupt images and balance the data in the dataset if it is not Balanced.
    -   feature cleaning and normalization (such as one-hot encoding and replacing null values)
    -   standardize the image files and 
    -   Write a new CSV file and images files
-   Step 4: write a code for Post-processing the dataset
    -   Create DataFrame from the new CSV file
    -   Sumerzies the datset inormation
    -   Visualize the data set
    Step 5: write a code to identify a suitable machine-learning model
    -   Compare machine-learning model using Train and Test dataset
    -   Visualize the result
-   Step 6: write an API to execute the model for prediction

\-------------------- -------------------- ----------------

