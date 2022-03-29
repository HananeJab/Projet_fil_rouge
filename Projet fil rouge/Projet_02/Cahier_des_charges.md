# Project 2 : Youcode Chatbot

## What is Chatbot?
A chatbot is an intelligent piece of software that is capable of communicating and performing actions similar to a human. Chatbots are used a lot in customer interaction, marketing on social network sites and instantly messaging the client. There are two basic types of chatbot models based on how they are built; Retrieval based and Generative based models.

## Objective/ Vision
``Youcode Chatbot`` is an AI chatbot that receives questions from users, tries to understand the question, and provides appropriate answers. 

It does this by converting an English / French or Arabic sentence into a machine-friendly query, then going through relevant data to find the necessary information, and finally returning the answer in a natural language sentence. In other words, it answers your questions like a human does.

For example, when it receives the question "Where is Youcode ?", it will give a response “There is two Youcode one in Youssoufia and other in Safi, one do you want exactly ?.”

The goal is to provide *Youcode learners* and *trainer* a quick and easy way to have
their questions answered, as well as to offer other developers the means to incorporate
``Youcode Chatbot`` into their projects.

When we talk about *conversational interface*, we’re really talking about two very different interfaces: ``text conversation`` and ``voice``

## Achievements
The following goals were achieved:
* Investigated a range of algorithms for solving the problem of direct communication with Youcode and developed an algorithm that combines the use of keyword matching with
string distance.
* Designed and implemented a usable chat system, which has been extended after being
evaluated by users.
* Evaluated the extended system with users. The system was used by potential learners of Youcode.
* Completed a literature research in order to learn more about natural language processing,
investigated existing tools and established the requirements.*
* Build your smart chatbot using speech recognition technology and convert it into text.

## Functional Requirements
1. Chatting:
    a. The system should allow users to chat.
    b. The system shall inform the user if an answer is not available.
    c. The system shall inform the user about spelling mistakes.
    d. The system shall inform the user about the validity of the sentence.
2. Searching:
    a. The system should allow users to search for information about admissions.
    b. The system should allow users to search for information about registration.
    c. The system should allow users to search for information about accommodation.
3. Logs:
    a. The system should maintain a log of the current question and answer if the user is not satisfied.
4. Feedback:
    a. The user should be able to leave feedback, which is comprised of a text message and a rating.
5. Administrative system
    a. Information management: The administrator should be able to to add, update and delete questions, answers and keywords.
    b. Log management: The administrator should be able to view and delete logs.
    c. Feedback management: The administrator should be able to view and delete feedbacks.

## Non-Functional Requirements
1. User Interface:
    a. The system shall maintain an easy to use interface across all functionality and for all users
    b. The clients’ user interface should be compatible with all commonly used browsers, such as Internet explorer, Firefox, Google chrome and Safari.
2. Scalability:
    a. The system shall be able to scale based on the number of users using the system.
3. Security:
    a. The administrative system should be protected from unauthorized access.
    b. The database should protected from attacks and unauthorized access.
    c. The interface should be protected from attacks.
    d. All passwords should be stored as a secure hash of the administrator password.
4. Third party interactions:
    a. The system should be able to interact with the Google spelling server, which handles the spelling.
    b. The system should be able to interact with the Google search server, which is used for the customized search on the admissions website.
5. Portability:
    a. The system should run on a variety of operating systems.
    b. The system should run on a variety of hardware.
6. Maintainability:
    a. The system should be easy to maintain.
7. Exception handling:
    a. Exceptions should be reported effectively to the user if they occur.
8. Ethics:
    a. The system shall not store or process any information about its users

## Language
The system will support questions and answers in English, French or Arabic

## Software Requirements
You can develop this sowftware by using HTML, PHP(framework), MYSQL, JS(Framework), CSS(Framework)