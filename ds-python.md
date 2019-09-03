# Data Scientist / Python

As a **Data Scientist**, you will clean and explore datasets, and make predictions that deliver business value. Your day-to-day will involve training and optimizing models, and often deploying them to production.

**Required skills:**
- Python programming skills
- Solid foundation in SQL
- Numpy, scikit-learn, Pandas
- TensorFlow/PyTorch
- Cloud containerization environments and micro-services: Docker, Kubernetes

**Desired skills:**
- Experience working with SQL and noSQL databases using Python APIs: IBM DB2, IBM DashDB, Cloudant
-	Understanding of REST principles and experience with web services frameworks like Flask
- Experience working with Apache Spark
-	Experience with web scraping frameworks
- Experience with NLP frameworks: SpaCy, NLTK

## Jupyter Notebooks
- Start with installing Anaconda and check Jupyter notebooks there - https://www.anaconda.com/distribution/
- Read the user documentation and play with samples - https://jupyter-notebook.readthedocs.io/en/stable/examples/Notebook/examples_index.html
- Jupyter Notebook Tips, Tricks, and Shortcuts - https://www.dataquest.io/blog/jupyter-notebook-tips-tricks-shortcuts/

## Data Science Basics
- Start with these learning paths and courses
  - Data Science Foundations - https://cognitiveclass.ai/learn/data-science/
  - Applied Data Science with Python - https://cognitiveclass.ai/learn/data-science-with-python/
  - Machine Learning with Python - https://cognitiveclass.ai/courses/machine-learning-with-python/
  
## IBM Cloud + Watson Studio
- Create IBM Cloud account - https://cloud.ibm.com/registration
- Create Watson Studio account - https://dataplatform.cloud.ibm.com/
  - Go through the Watson Studio Overview - https://dataplatform.cloud.ibm.com/docs/content/wsj/getting-started/overview-ws.html
  
## Training Project - Data Analysis and Visualization
- Create a project in Watson Studio
- Create a notebook in Watson Studio
- Publish the notebook to GitHub and share with your supervisor
- Perform exploratory analysis and initial visualization for the *Boston house prices dataset* - https://scikit-learn.org/stable/datasets/index.html#boston-dataset

## Machine Learning Specialization
Complete *Machine Learning Specialization*. You will gain applied experience in major areas of Machine Learning including Prediction, Classification, Clustering, and Information Retrieval. You will learn to analyze large and complex datasets, create systems that adapt and improve over time, and build intelligent applications that can make predictions from data.
- Machine Learning Specialization - https://www.coursera.org/specializations/machine-learning

## Docker + Kubernetes
- Quick introduction videos
  - Learn Docker in 12 Minutes - https://www.youtube.com/watch?v=YFl2mCHdv24
  - Docker Compose in 12 Minutes - https://www.youtube.com/watch?v=Qw9zlE3t8Ko
- Complete the following courses
  - Docker Essentials: A Developer Introduction - https://cognitiveclass.ai/courses/docker-essentials/
  - Container & Kubernetes Essentials with IBM Cloud - https://cognitiveclass.ai/courses/kubernetes-course/
  
## Training Project
The main goal of this project is to get practical working experience in the following areas:
- NLP and text processing
- REST services
- Web scrapping
- Containerization technologies
- Microservices architecture

The application is intended to automate data collcetion and analysis. The application should include the following components:
- **Data collection component** - uses frameworks like *Scrapy* (https://scrapy.org/) and *Beautiful Soup* (https://www.crummy.com/software/BeautifulSoup/) to extract source data from websites
- **Entity Extraction service** - a REST service that is created using *Flask* framework (https://palletsprojects.com/p/flask/) and extracts named entities from the source documents using *SpaCy* (https://spacy.io/) NLP model(s)
- **Visualization service** - a REST service that takes a set of documents as an input and generates a visual representation of links between these documents

### Tutorials and guides
- Scrappy
  - How To Crawl A Web Page with Scrapy and Python 3 - https://www.digitalocean.com/community/tutorials/how-to-crawl-a-web-page-with-scrapy-and-python-3
- REST architectural style and APIs
  - REST API Tutorial - https://restfulapi.net/
  - Thoughts on RESTful API Design - https://restful-api-design.readthedocs.io/en/latest/intro.html
- Flask
  - Flask documentation - https://flask.palletsprojects.com/en/1.1.x/#
  - Standalone WSGI Containers - https://flask.palletsprojects.com/en/1.1.x/deploying/wsgi-standalone/#gunicorn
  - Building beautiful REST APIs using Flask, Swagger UI and Flask-RESTPlus - http://michal.karzynski.pl/blog/2016/06/19/building-beautiful-restful-apis-using-flask-swagger-ui-flask-restplus/
  - How to build a simple Flask RESTful API with Docker-Compose - https://medium.com/@daniel.carlier/how-to-build-a-simple-flask-restful-api-with-docker-compose-2d849d738137
