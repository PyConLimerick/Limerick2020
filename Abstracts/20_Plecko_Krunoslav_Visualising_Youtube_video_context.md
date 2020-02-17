### Visualising Youtube video context (NLP pipeline)	

This talk is about group UCD project of 6 engineers. Name of the project is Yousights. 

Vision behind the project: Refine time consuming YouTube searches for skill enhancement. 
We had idea to reduce the time to find most useful Youtube video, and increase user confidence in right choice. 

For this purpose we build NLP pipeline in python, using 5 microservices deployed in multi-clud environment (IBM PaaS, Google IaaS). Core of the project is advanced sorting algorithm based per similarity with books, e.g how similar is python video with most ranked Safari books. Second part is sorting youtube video comments based on sentiment, and third part automatically generating table of content based per video transcript.
Python is used for backend, to extract text from youtube video, process the text, and NLP machine learning part. 
All microservices on backend side use Python Flask, and our DB of choice is MongoDB.

My role was project management, architecture and development. 
Presentation will show advanced usage of Python and hardware like GPU for NLP in novel idea to visualise context on Youtube video.
Website can be tested here: https://yousight.eu-gb.mybluemix.net/
