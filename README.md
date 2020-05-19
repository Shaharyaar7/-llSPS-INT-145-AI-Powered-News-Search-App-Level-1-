llSPS-INT-145-AI-Powered-News-Search-App-Level-1-

AI Powered News Search App (Level-1)

Website:  https://node-red-izkrz.eu-gb.mybluemix.net/ui/

Video Presentation: https://drive.google.com/file/d/1BtW3VOI4pzPyGHWtHnK_gwrsZDPOfxj_/view

Feedback Video: https://drive.google.com/file/d/1LsLh7rvNtJeXd5GTjVfL3eTD-J4Hh-ch/view

AI Powered News Search App using IBM Cloud Services


The web is home to massive amounts of data, with more being created every day. Organizations can harness this constant stream of information to gain understanding, plan strategies, and find opportunities. Enriched news data can help your application make dynamic connections across current events faster.
In this project, we built a NEWS mining web application starting with the basics, using Node-RED / Python Web App and the IBM Watson Discovery Service.
To do this we start by building a Server-Side Application using Node-RED then we use the pre-built Watson Discovery News collection and access the Watson Discovery Service through the Discovery API. Optionally, we can choose to use a Slack interface to query the data, push news alerts out to web notification and deploy the app on IBM Cloud. In this project, we’ll start with the basics and build our own news mining web application using Node-RED / Python Web App and the IBM Watson Discovery Service.
The project revolves around:
1. Building a Server Side Application using Node-RED 
2. Using the pre-built Watson Discovery News collection 
3. Accessing the Watson Discovery Service through the Discovery API 
 
Additionally, we include:
1.	Deploy the app on IBM Cloud.
2.	Use a Slack interface to query the data  
3.	Push news alerts out to web notification

We propose the use of IBM Discovery, IBM Watson and IBM Node-RED.


Discovery: 
1.	The user interacts with the app UI(Built with Node-RED or Cloud or Local) to request relevant news content.
2.	The app sends user requests to Watson Discovery News.
3.	The Watson Discovery Service is continually crawling the web to update its Discovery News collection.
4.	The Watson Discovery Service responds to Slack search requests.
      •	Code is written in Node.js, with the server-side using the Express framework and the client using ReactJS.
      •	The pre-built Watson Discovery News collection was used.
      •	Access the Watson Discovery Service through the Discovery API.
      •	Use a Slack interface to query the data

 
Advantages and Disadvantages:

The following advantages and disadvantages are observed.

Advantages:

1.	The app uses standard search UI components such as filter lists, tag clouds, and sentiment graphs, but also more complex Discovery options such as the passages and highlight features.
2.	With these two features, the app identifies the most relevant snippets in your data based on your query and is more likely to return the data that you’re searching for.
3.	News coming with sentiment analysis done and only singular commands are needed for slack to get the requested news.
4.	The main benefit of using the Watson Discovery Service is its powerful analytics engine that provides cognitive enrichments and insights into our data. The app in this code pattern provides examples of how to showcase these enrichments through the use of filters, lists, and graphs.
5.	The project makes use of slack that has multiple APIs to create bots and to create a connection to Slack. Any request to the bot user, to the bot directly, or from a Slack channel in which the bot is a member, is sent to the server that starts the connection. Slack uses the bot token as a means to authenticate and all of these works due to the use of the Real Time Messaging API

Disadvantages:

Application Programming Interface (API) 
1.	One of the key problems that most of the developer’s encounter is the Application Programming Interface (API) keeps on changing at frequent intervals and does not remain stable.
2.	At times, a new API appears having a number of backwards-incompatible changes. As a result, the developers are forced to make changes in the accessible code bases to match the compatibility with the latest version of the Node.js API.

Sentiment Analysis:

1.	Sentiment analysis tools can identify and analyze many pieces of text automatically and quickly.
2.	But computer programs have problems recognizing things like sarcasm and irony, negations, jokes, and exaggerations.

APPLICATIONS

1.	A full-fledged software or website with real-time applications

2.	Can be used as an everyday-app to browse and get news real-time, anytime in the day

3.	Sentiment analysis on the news articles and different types of data.

4.	Getting news articles fast and reliable with score and other metadata information’s.



CONCLUSION

This application uses individual out-of-the-box UI components to extract and visualize the enriched data provided by the Discovery analytics engine. The web application includes Sentiment analysis, slack integration and embedded using Node-Red. 

FUTURE SCOPE

The future scope may include:

1.	Variations in phrasing:
2.	News search using audio and converting that using speech-to-text.
3.	Tracking conversations:
4.	Adding language translator with audio to enable search and results in regional language.


RESULT
The final application has 
1.	A user-interface is used to request the extraction of required news content.
2.	The app generates the latest news regarding request generated by user using the Watson Discovery News.
3.	It generates the URL it used to extract the news from.
4.	It displays the author who had submitted the news report.
5.	It provides with sentimental analysis that separate positive or negative opinion from good or bad news.

