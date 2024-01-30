## README

CodeSolutions2 is the GitHub organization name for selling code-related projects independently and on Upwork. There is one independent project that will be for sell soon, and three coding projects for sell on Upwork. 

Projects include:

[0] Data Science Observations in a Chaotic World: How to be more responsible and why it is important [8,50 euro per webapp accesskey]

A self-help book, in the form of a huge webapp with LLM prompt exercises, on 22 Data Science case studies discusses common topics ranging from disaster, long-term goals, self-esteem, and lack of technological regulatory rules. The Data Science Prompts are webapps containing Large Language Model 
(LLM) data-driven horoscope-like applications, that help users have clarity on their lives based on their own data.

https://j622amilah.github.io/userservicesite/Observations_of_a_Data_Scientist.html


[1] Automatic csv file ingestion code in bash: sorting of files by header, upload to cloud [100 dollars]

The objective of this work was to create an automated bash script that sorts a folder of csv files, using the header name of the csv files. This project was for the final project of the Google Analytics Coursera Certification program (github.com/j622amilah/Case_Studies/tree/main/1_case_study_bikeshare). The bash code first reads in an initial header and labels this the current_header, it reads in each csv file and compares the new csv file header with the current_header. Each word/header in the current_header is compared with each word/header in the new csv file header, using both lexical matching and word similarity via a REST API Hugging Face model. Sufficiently similar words/headers in the new csv file are replaced by the equivalent word/header in the current_header. Once all the header words are compared, if the new csv file has the same header as the current_header it is moved to a folder called exact_match_header. If the new csv file has at least one header word that matches the current_header, the new csv file is moved to a folder called similar_match_header. If no header words match the current_header, it is moved to a folder called no_match_header.

https://www.upwork.com/services/product/development-it-automatic-csv-file-ingestion-sorting-of-files-by-header-upload-to-cloud-1740355723544662016


[2] Client-Server spreadsheet Google Apps Script code [30 dollars]

This is a JavaScript/Google Script and HTML framework for how to create a Server-side and Client-side web application. The Server-side is integrated to the google spreadsheet using google apps scripts commands, thus spreadsheet variables can be transferred to and from the deployed browser webapp. However, a client-side user may not be familiar with deploying google apps scripts to load spreadsheet variables to the browser supported web interface. Thus, at a basic level the client-side spreadsheet, for user distribution, launches a pop-up to the server webapp and a spreadsheet-like interface is available for the user to use with their client-side spreadsheet. A tensorflow.js model structure can be included in the code, if the client requests.

https://www.upwork.com/services/product/development-it-client-server-spreadsheet-google-apps-script-code-1740063136644558848


[3] Python Question Quiz Application chatgpt integration code [Starter: 30 dollars, Standard: 100 dollars, Advanced: 400 dollars]

The objective of this work was to create a Computer or web application that can present questions and answers to test-takers, grade test-taker performance, and allow for test-takers to view chatbot performance with respect to their performance. Adult professionals, in addition to young people, need to study for and pass career-related exams. A simplistic flash card-like application is useful for many people to practice their study content. There are several question quiz application programs that exist for the computer, cloud, and phone. However, many of the existing applications do not grade the user or record what questions were answered incorrectly for later study. In addition, none of the question quiz applications allow for usage with a chatbot to understand one's study competence with respect to an intelligent robot. There are three tiers of this workflow: PySimpleGUI Python code, JavaScript HTML webapp code, JavaScript HTML webapp w/BigQuery integration code. These code workflows/solutions will be delivered with instructions on how to use the code.

https://www.upwork.com/services/product/development-it-python-question-quiz-application-chatgpt-integration-1737089485247094784


[4] Tensorflow.js Image Labeling code [Starter: 30 dollars, Standard: 400 dollars, Advanced: 800 dollars]

The objective of this work was to create a web application that can automatically label images that are in a GitHub repository. The user inputs the Github repository url and the web application outputs a table/csv file of each repo image with a label. This application is useful for creating supervised image prediction models, because it is necessary to have a reliable label for each image that a supervised model will be trained on. 

There are three tiers of this workflow: Webapp code-Tensorflow models, Webapp code-Custom model, Webapp code-Custom BigData. 
Tier 1: read images from a GitHub repo, use a pre-trained Tensorflow.js model (mobilenet or ssdcoco) to detect objects in each image, create a table of the image name and predicted label.  
Tier 2: perform tier 1 functionality and train a Custom trained Tensorflow model specifically for the data.
Tier 3:  perform tier 2 functionality and  efficient memory usage strategies, such as batching reading and writing data to Cloud Storage, to accommodate large quantities of data (Big Data).

These code workflows/solutions will be delivered with instructions on how to use the code.

See test deployment for functionality: https://CodeSolutions2.github.io/test_4_webapps/index.html
(Upwork project submitted: link will be available soon)
