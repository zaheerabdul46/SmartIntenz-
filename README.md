llSPS-INT-501-Intelligent-Customer-Help-Desk-with-Smart-Document-Understanding
Intelligent Customer Help Desk with Smart Document Understanding

This repository contains the documentation and code elements of the Intelligent Customer Help Desk with Smart Document Understanding chat bot developed using various IBM Watson Services for backend and Node-Red for front end. It comprises of the project report, the IBM Discovery functions, Watson Assistant skills and the Node-Red flow of the chatbot.

Problem Description: The typical customer care chatbot can answer simple questions, such as store locations and hours, directions, and maybe even making appointments. When a question falls outside of the scope of the pre-determined question set, the option is typically to tell the customer the question isn’t valid or offer to speak to a real person.

In this project, there will be an added feature. If the customer asks a question outside of scope, say with respect to the operations of a device, the application shall pass the question onto the Watson Discovery Service, which has been pre-loaded and trained with the device’s owners-manual. So now, instead of “Would you like to speak to a customer representative?” it can return some relevant sections of the owners-manual to help solve the customers’ problems. This avoids most queries from being directed to the customer representative, until explicitly asked by the customer or in the case of an unusal query, making it more effective and time saving.

The Smart Document Understanding of the Watson Discovery is used to train the bot on what text in the owners-manual is relevant and what is not, leading to improved results to queries. It can then be integrated with Watson Assistant using cloud functions and using the Watson Assistant skills in the Node-RED, it presents the perfect UI that users can easily chat with.

Guide used in Watson Discovery: ecobee3_userguide.

Watson Assistant Preview :  https://web-chat.global.assistant.watson.cloud.ibm.com/preview.html?region=eu-gb&integrationID=c6709e1c-b255-48f4-9937-0f82de147f21&serviceInstanceID=50e10cf8-38e7-4bd4-bcbb-f3aa332f2216

Node-Red Dashboard link after deploying :  https://zaheerabdul.eu-gb.mybluemix.net/ui/#!/0?socketid=qqu8vjQnhlPR8secAAAt

Youtube video link:
