# Postman  ![postman-logo-icon-orange](https://user-images.githubusercontent.com/43212219/206572553-5f96ba62-267a-485a-9434-00cc25e31c21.svg)


###### Introduction to the Postman world

-------

### Table of contents

...

...


...

--------
### 0. Intro

Postman is more than just an API-client that Postman is known for. Postman is a platform with a set of very useful tools that will make creating and managing APIs easier, and besides, Postman can save developers a lot of time and effort.

---------

### 1. Installation

Developers can use Postman in different ways, Postman can be used both as a web-app and as a Desktop-app, in addition, Postman is available for different operating systems such as Linux, Windows, etc.

And developers can also use Postman without having to register, but registration is recommended as it has some advantages, e.g. data backup, because Postman is cloud-based or registration is mandatory if developers want to set up a public workspace or network. I've already registered so that I can show all the important parts of Postman in the course of this tutorial.

The following screenshot shows what Postman looks like after installation, the developer can register or log in directly or at the bottom left there is also the possibility to use Postman directly without an account.

![Screenshot from 2022-12-08 20-56-03](https://user-images.githubusercontent.com/43212219/206555066-4ce9d7b4-42e2-439d-8533-b6f45260aeec.png)

---------

### 2. API-Repository

Developers can store, catalog and collaborate on one central platform. Postman provides us with a cloud-based and centralized repository throughout the API-Lifecycle, so we will have no any kind of problem by storing and managing of API specifications, tests, workflow, documentation, etc. And it doesn't matter if we have only one API or multiple APIs, we can very well organize and simplify everything around API world with Postman-API-Repository.


#### 2.1. API-Network

 ##### 2.1.1. Private API-Network
 
Teams and organizations can set up a private API network with Postman, which is only visible to authorized people and supports creating API versions.
 

 ##### 2.1.2. Public API-Network
 
 According to Postman, Postman's Public-API-Network is the world's largest public API-Hub, which many well-known companies like Microsoft, Google, etc.    are on. With the help of Public-API-Network we can release Worksapces, APIs, and other things worldwide

---------
### 3. Workspace

When we start postman, the first thing we have to do is create a workspace so that we can use the postman tools at all.

There are four workspace types in postman, these are:

+ **Personal Workspace**: As the name suggests, this is mainly personal and it contains all the tools we need to build, manage APIs. Everything in this area happens in real time, so we can easily switch between the Postman-instances, web- and desktop-app at any time.

+ **Team Workspace** (more than 3 members -> Pro or Enterprise edition): This allows creating a workspace for multiple people, and even assign them specific roles like admin, editor and viewer.

+ **Private Workspace** (only available in the Pro and Enterprise editions): There is the possibility that not all team members have access, but only members who receive an invitation.

+ **Partner Worspace**: Is similar to a private workspace, you can not only invite team members but also external users as partners.
Unlike the other workspaces, we cannot create a partner workspace directly, it is invisible at first. For this you have to go through a few steps first, see how to create [Partner-Workspace](https://blog.postman.com/introducing-partner-workspaces/) via Postman.

+ **Public Workspace**: We can publish or make our APIs available worldwide by setting up a public workspace.


The following image shows how to create a workspace, we simply have to click on workspace in the top left of the Postman web or desktop app, then give the workspace a name and next select the workspace type, e.g. Personal and finally click on Create Workspace.

![create_workspace](https://user-images.githubusercontent.com/43212219/207112977-c257b31f-4aa2-497a-a840-973af1fc78c2.png)


-------

### 4. Tools

We have the ability to manage the API-Lifecycle from design to testing, documenting, API-mocking and etc. all of this can be done with the helpful and user-friendly tools of Postman. In this section I will introduce the Postman-Tools and make a small example of it so that we can get an idea of them.

If we now go to our already created workspace, we will see the tools (Collections. APIs, Environments, Mock Servers, Monitors and Flows) on the left side. We will look at these tools next by using examples.

![Untitled](https://user-images.githubusercontent.com/43212219/207124332-b74adea7-8454-4a5c-93aa-20d1ea6f373e.png)




#### 4.1. API-Client

The foundational tool for which POstman is well known among developers. No matter if we want to test or debug the APIs or define simple and complex API-Requests for HTTP, REST, GraphQL and WebSocktes, we can do all these with Postman API Client. In addition, the API client can automatically recognize a lot more, for example the language of the response or authentication types to the server.

First we should create a collection by simply clicking the Plus button, then a collection will be automatically generated, we can name it whatever we want, in my case it's called My Collection.

we can now click Add a request to make an API call.

![coolll](https://user-images.githubusercontent.com/43212219/207129448-77515cad-5744-4ae6-ab11-5d4dd201158a.png)


Here I create an API-request called FetchUsers because I want to fetch a List of User. We now have the ability to use different HTTP methods(1) and we can call any API URL(2), for that I used the https://gorest.co.in/  to get back a list of test users.

![MS Paint _ Microsoft Paint Online](https://user-images.githubusercontent.com/43212219/207147530-339cda91-33d9-4c30-bb9b-dc2f4dd4f420.png)

If we now click on send, we get back a JSON file in pretty-print as a response. We can also change the representation on different data structures.

![Screenshot from 2022-12-12 21-28-51](https://user-images.githubusercontent.com/43212219/207148688-a2386719-2ede-4377-bd50-833164d67a46.png)

We can also call google.com and display it as a Perview.

![Screenshot from 2022-12-12 21-35-13](https://user-images.githubusercontent.com/43212219/207149181-dcdf04dd-cf54-4dd1-904f-5f8070693f64.png)

If we want to use an HTTP-Post, then we can enter the data directly as a body, and if authentication against the server is required, as in our example, this can be set under Authorization, there are different types.

![Screenshot from 2022-12-12 21-40-51](https://user-images.githubusercontent.com/43212219/207150074-e418138b-3e8c-4cd5-82c8-0034261cd499.png)

---------------

API-Documentation

![Screenshot from 2022-12-13 12-41-10](https://user-images.githubusercontent.com/43212219/207309682-1dcf710c-7109-4af7-acad-c362b9e668c1.png)

[Screenshot from 2022-12-12 22-08-00](https://user-images.githubusercontent.com/43212219/207154849-dc2ad323-7b04-46b4-a058-c17ae9646f18.png)

![Screenshot from 2022-12-13 12-40-15](https://user-images.githubusercontent.com/43212219/207309516-21c793d7-b2d4-4194-83e5-557339feee82.png)




---------
API-Design


![Screenshot from 2022-12-12 22-01-14](https://user-images.githubusercontent.com/43212219/207153852-6e05aa75-60e7-477d-a2fb-8b6dc9e86026.png)







-------------------
AP-Tests



------

Mock-Server






-------
Monitores




------


Flows




----------

Explore




