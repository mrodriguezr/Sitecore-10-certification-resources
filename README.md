# Sitecore 10 Certification Resources

## Sitecore Official Sites
* [Official Site](http://www.sitecore.com/) - Sitecore's offical site
* [Study guide](https://learning.sitecore.com/exam/study-guide-sitecore-10-net-developer-certification-exam) - Sitecore 10 .NET Developer Certification Exam

* [Sitecore Documentation](https://doc.sitecore.com/xp/en/developers/101/index.html) - Sitecore Documentation
* [Sitecore Downloads](https://dev.sitecore.net/) - Sitecore Downloads
* [Sitecore Knowledge Base](https://support.sitecore.com/kb) - Sitecore Knowledge Base
* [Sitecore Stack Exchange](https://sitecore.stackexchange.com/) - Sitecore Stack Exchange
* [Sitecore Slack Chanel](https://sitecore.chat/) - Sitecore Slack Chanel


## Exam recomendations
* 

## Exam competencies

Certified Sitecore 10 .NET Developers will be expected to have fundamental knowledge, skills, and abilities—or competencies—in seven distinct areas regarding developing on Sitecore XP: 

* Competency 1: Sitecore structure & platform - 12%
  * Define Sitecore-specific terminology in a Developer context. Terms include Content Editor, Experience Editor, component, rendering, placeholder, template, layout, item, and serialization.
  * Differentiate between Sitecore MVC and Sitecore Headless Development methods, tools, and processes at a high level.  
  * Identify the different deployment options for a Sitecore Experience Platform environment (e.g., on-premise, containers, Managed Cloud).  
  * Install Sitecore Experience Platform on a development workstation without the use of containers.
  * Create a .NET solution with the appropriate projects for your development method. 
  * Execute development tasks assigned from a development plan for a Sitecore environment.

* Competency 2: Security & user management - 16%
* Competency 3: Item management - 20%
* Competency 4: Layout & placeholders - 10% 
* Competency 5: Components, controls, & renderings - 26%
* Competency 6: Sitecore Content Serialization - 10%
* Competency 7: Containers - 6%



## Developer's Fundamentals 10 Collection
### Sitecore 10 Development Features Overview (3h) 
### Single 1: Discover the Sitecore 10 Development Offerings

#### TRACK 1: EXPLORE THE NEW TOOLS AVAILABLE WITH SITECORE 10
##### Sitecore 10 containers

##### Sitecore content serialization
Allows to login, manage and publish items directly from the command. Same features are available on Sitecore for Visual Studio
Other options available in the market
* Sitecore TDS
* Unicorn

##### Sitecore ASP.NET Core Rendering SDK
An additional headless development option, this SDK
Existing options for developing in Sitecore 10
* JSS
* ASP.NET SDK
* Sitecore MVC
* SXA


#### TRACK 2: REVIEW THE SITECORE 1- DEVELOPMENT EXPERIENCE
Five of the key benefits of Sitecore with containers, the new Sitecore Serialization option, and the new ASP.NET Core Rendering SDK
* Benefit 1: Increased Developer Productivity
* Benefit 2: Lower Cost of Ownership: Managed Cloud or containerized implementations. you won't need separate virtual machines for every customer project you work on as a partner Developer
* Benefit 3: Faster Developer Onboarding: development teams can emphasize consistency by containerizing their custom-build setup alongside Sitecore itself.
* Benefit 4: Updating to a Modern Development Stack: containers and ASP.NET Core
* Benefit 5: Getting Started Quickly with Sitecore 10: [Getting started template](https://doc.sitecore.com/xp/en/developers/100/developer-tools/walkthrough--using-the-getting-started-template.html)


#### TRACK 3: LOCATE THE RESOURCES FOR SITECORE 10 DEVELOPMENT

* Sitecore 10 documentation: https://doc.sitecore.com/ With a section dedicated to Developer and IT Pros, you will find all the latest information about any given Sitecore release provided directly by Sitecore
* Sitecore downloads: https://dev.sitecore.net/ On the downloads site, you will be able to download individual product packages or a full product SIF for your selected release version of Sitecore. Additionally, you can access the Knowledge Base (KB).  Downloading from this site requires you to be a registered Sitecore Developer or have temporary access for training to become a Sitecore Certified Developer.
* Sitecore Stack Exchange: https://sitecore.stackexchange.com/
* Sitecore Slack Community channels: https://sitecore.chat/
* The Sitecore Support Portal: As a Sitecore Certified Developer, you will gain access to the Sitecore Support Portal (support.sitecore.com). Training related support, type Sitecore Learning Management System

#### KNOWLEDGE CHECK
![image](https://user-images.githubusercontent.com/1063617/158073152-a77168cc-8568-4a40-a278-35ba82484fdf.png)
![image](https://user-images.githubusercontent.com/1063617/158073174-a90b1f34-47c9-4d73-b6c4-a71719fff2b6.png)
![image](https://user-images.githubusercontent.com/1063617/158073197-ad0e0afc-8103-421d-b63d-71bb75b40c69.png)
![image](https://user-images.githubusercontent.com/1063617/158073219-1d596d8d-4614-4f1a-8274-6140ea3569b3.png)

### Single 2: Develop with Sitecore 10
#### Track 1: Familiarize Yourself with Sitecore 10 Containers
#### Advantages of Sitecore with Containers
* First, as a Developer, you can develop the Sitecore product with containers regardless of the production environment's deployment method.
* Sitecore provides the specifications and support for running containers in both development with Docker and production with Kubernetes
* You can still containerize your development environment and retain your existing development artifacts for production deployment.
* You won't need to install Sitecore locally on your development workstation
* You can isolate customer instances and dependencies so you can shift easily and efficiently between customer projects
* You can avoid using the Sitecore Install Framework (SIF) by utilizing the base images provided with the Docker Compose files from Sitecore
* Simplicity of onboarding new Developers to a team or project. You will be able to clone your code repository and run a docker-compose up


#### Requirements to Get Started on Containers
* First, you need to be familiar with container-based computing.
* Next, you will need to install Docker Desktop for Windows
* Finally, you need to be aware that the Sitecore environment in Windows containers can utilize a great deal of memory on your Developer workstation. While 16 GB is the specified minimum,  we recommend 32 GB of memory for optimal settings

#### Track 2: Discover the Sitecore Content Serialization Feature
#### Why Content Serialization?
#### Sitecore Content Serialization
The Sitecore Content Serialization tool brings together the best of TDS and Unicorn alike. It has two parts: the Sitecore Command Line Interface (CLI), and the Sitecore for Visual Studio plug-in.

#### Track 3: Explore the ASP.NET Core Rendering SDK.
#### Features of the ASP.NET Core Rendering SDK
* A client API for the Sitecore Layout Service. This API provides classes for invoking the Layout Service. You can utilize the Layout Service Client from a scheduled job or a .NET CLI application.
* The second feature is the use of tag helpers to render Sitecore placeholders, including mapping to specific component implementations in the ASP.NET Core. Also included are tag helpers for rendering Sitecore fields, which come back in the Layout Services Client response. This helps with specific field types like images, dates, and rich text, helping ensure the fields are rendering properly for the Sitecore Experience Editor.
* The third helpful feature regards the structures and mechanisms built into the ASP.NET Core SDK for mapping requests to the Layout Service Client.
* The fourth feature is the inclusion of extensions to the model binding within Microsoft’s ASP.NET Core. This model binding extension takes the Layout Service Client response and maps it to a strongly-typed model
* The last feature is the integrations enabling the full Sitecore Experience Platform (XP) functionality, including the Experience Editor, analytics, and personalization features. 

#### When to Use the ASP.NET Core Rendering SDK
* The ASP.NET Core Rendering SDK is for Developers who do not require the rich front-end or Single Page App (SPA)
* The ASP.NET Core Rendering SDK is also a good fit for those who have used Sitecore MVC in the past without SXA
* Additionally, if you or a customer has an existing ASP.NET Core site or application, you can utilize the ASP.NET Core Rendering SDK to add Sitecore functionality, content, or routes to the existing site or application.

#### Advantages of the ASP.NET Core Rendering SDK
* One of the major advantages of headless rendering is that you will be building outside of Sitecore, so you are no longer building code into the Sitecore instance
* You will no longer have to recycle the entire application pool when you build a new rendering, so your development cycles will be faster
* It is advantageous to be working with the newest technologies on the market; ASP.NET Core is faster, more modular, and more modern than its .NET Framework predecessor, giving you an edge in development and deployment.

#### KNOWLEDGE CHECK
![image](https://user-images.githubusercontent.com/1063617/158095376-c80f2043-537c-4e4a-8bc3-6e787ff58aa6.png)
![image](https://user-images.githubusercontent.com/1063617/158095408-dccd3639-e861-418c-a423-be5dfe2967b0.png)
![image](https://user-images.githubusercontent.com/1063617/158095538-791372cc-85aa-460a-92c9-b4f3104797a5.png)
![image](https://user-images.githubusercontent.com/1063617/158095664-cf1035f3-3e87-4a4f-a48f-684d5c41e4d8.png)

### Single 3: Use the Getting Started Template to Set Up a Sitecore 10 Environment
#### Track 1: Prepare the Prerequisites.
* .NET Core 3.1 SDK
* .NET Framework 4.8 SDK
* Visual Studio 2019
* Docker for Windows
* PowerShell 5.1


#### Track 2: Install the getting started template

#### KNOWLEDGE CHECK
![image](https://user-images.githubusercontent.com/1063617/158099358-a854569d-7197-4b5f-8e31-0d329f608b0b.png)
![image](https://user-images.githubusercontent.com/1063617/158099402-c50ac834-58ca-47c4-889b-ce245c0463f3.png)
![image](https://user-images.githubusercontent.com/1063617/158099483-c2b3381a-3b76-4d41-851e-23cdaf59de03.png)
![image](https://user-images.githubusercontent.com/1063617/158099540-b4f8063b-36f9-4f29-b897-318d1b9d2709.png)


### Introduction to Sitecore Content Serialization 10 (3h)
### Single 1: Explore Sitecore Content Serialization
Sitecore Content Serialization allows you to easily put items into source control, build deployment scripts that push items to various environments, and create packages for later deployment

#### Track 1: Understand content serialization
* With Sitecore 10, the new Sitecore Command Line Interface (CLI) and Sitecore for Visual Studio bring about the best of both TDS and Unicorn to provide an optimized serialization experience for Developers

#### Track 2: Configure Sitecore Command Line Interface (CLI)
#### Track 3: Set up Sitecore for Visual Studio

### Single 2: Utilize Sitecore Content Serialization
#### Track 1: Create Modules for Serialization with Text Editor and SVS
* The Sitecore.json file is used to control how Sitecore serialization behaves. The modules section of this file is used by Sitecore serialization to locate all modules in your solution.
* src\TestModule\TestModule.module.json
* The .module.json requires a namespace value

#### Track 2: Configure Item Includes Using Text Editor and SVS.
##### Allowed Include Properties 
![image](https://user-images.githubusercontent.com/1063617/158726373-6f5e8fcf-b5d1-4226-a28b-0967539f3799.png)

#### Track 3: Edit Rules Using Text Editor and SVS
##### Rule Properties
![image](https://user-images.githubusercontent.com/1063617/158727783-2c9fe3c4-5dca-45c0-a768-147ea21805ef.png)

#### Track 4: Serialize Items
* To serialize items using Sitecore CLI, you must use the dotnet sitecore ser pull command, which will pull all of the Sitecore items from your content tree
* Note: The use of the -w or 'what-if' command helps you to see what the serialization of your module would look like without actually performing it.

Now, to run serialization using the Sitecore for Visual Studio plugin, follow the steps below:

* Step 1: In the Sitecore Module Explorer, right-click on Sitecore Configuration Root.
* Step 2: Click Pull items.

#### Track 5: Automation of Item Packaging and Deployment.
Packages contain everything a Developer needs to deploy to production. To successfully automate item packaging and deployment you will complete the following tasks:
* Create a package using either Sitecore for Visual Studio or Sitecore CLI, 
* Configure your environment for client credentials authentication, and 
* Install the package into your delivery pipeline.

##### Task 1: Create Package Using Sitecore for Visual Studio
* Add a new buid Sitecore for Visual Studio Project project. MyProject.build 
* Edit the Build Project
** Go to properties
** Select the Build Serialized Items Package
** In the Package Modules section, select Include All Modules
** Save the build project, and then build to create the package.


Create a Package Using Sitecore CLI (Theoretical)
* Step 1: Go to your project folder where your sitecore.json is located. 
* Step 2: To create the package, run the following command: 
> dotnet sitecore ser pkg create -o <name> 

##### Task 2: Configure your Environment for Client Credentials Authentication 
You will now configure your environment for client credentials authentication. To enable non-interactive client logins using client credential flows with your Sitecore instance, you must add additional configurations to your Identity Server and Content Management instances. 

###### Create new configuration patch for Sitecore Identity Server.
* Step 1: Create a file named Sitecore.IdentityServer.MyProject.xml in the \docker\build\id folder
* Step 2: Copy and paste the following code into the file:
 
 ```
 <?xml version="1.0" encoding="utf-8"?>
<!--
    From https://doc.sitecore.com/developers/100/developer-tools/en/configure-a-non-interactive-client-login.html
-->
<Settings>
  <Sitecore>
    <IdentityServer>
      <Clients>
        <!--
          Used to authenticate servers with client id and client secret.
          The name of this XML element is arbitrary, but in this example it must
          match the path used in the docker-compose.override.xml to set the ClientSecret1
          value.
        -->
        <MyProjectDeployment>
            <!--
              The ClientId and ClientName are arbitrary, but the ClientId must
              match the value we pass into the client-id argument when using the Sitecore CLI,
              and the client_id value in our claim mapping patch for the CM role.
            -->
            <ClientId>MyProjectDeployment</ClientId>
            <ClientName>MyProjectDeployment</ClientName>
            <AccessTokenType>0</AccessTokenType>
            <AccessTokenLifetimeInSeconds>3600</AccessTokenLifetimeInSeconds>
            <IdentityTokenLifetimeInSeconds>3600</IdentityTokenLifetimeInSeconds>
            <RequireClientSecret>true</RequireClientSecret>
            <AllowOfflineAccess>false</AllowOfflineAccess>
            <AllowedGrantTypes>
                <!--
                    client_credentials authenticates with client ID and client secret
                    which is good for CI, tools, etc. However, it's not tied to a USER,
                    it's tied to a client ID.
                -->
                <AllowedGrantType1>client_credentials</AllowedGrantType1>
            </AllowedGrantTypes>
            <ClientSecrets>
                <!-- Configured via environment variable. -->
                <ClientSecret1></ClientSecret1>
            </ClientSecrets>
            <AllowedScopes>
                <!-- this is required even if not a 'user' for Sitecore to like us -->
                <AllowedScope1>sitecore.profile.api</AllowedScope1>
            </AllowedScopes>
        </MyProjectDeployment>
      </Clients>
    </IdentityServer>
  </Sitecore>
</Settings>
 ```
 This patch defines a new login client for automated login using client credentials. The client secret value is intentionally left blank, so it can be configured via the environment variable.
 
###### Add directives to Identity Server Dockerfile.
The second task is to add directives to your Identity Server Dockerfile. You can do so by following the steps below:

* Step 1: Add directives to your Identity Server Dockerfile (docker/build/id/Dockerfile) by pasting the following configuration patch:
```
 WORKDIR c:\identity
 COPY Sitecore.IdentityServer.MyProject.xml .\Config
```
###### Add environment variable to id services.
 Your third task is to add an environment variable to the id services in your docker-compose.override.yml file which configures the client secret. This uses ASP.NET Core's ability to configure via environment variables to set the client secret value to an environment variable on the host, MY_PROJECT_DEPLOYMENT SECRET. Follow the steps below to add the new environment variable to id services:

* Step 1: Paste the following code in your docker-compose.override.yml file as a new environment variable to the id service. 
```
Sitecore_Sitecore__IdentityServer__Clients__MyProjectDeployment__ClientSecrets__ClientSecret1: ${MYPROJECT_DEPLOYMENT_SECRET}
```
###### Add a value to MY_PROJECT_DEPLOYMENT_SECRET variable.
* Step 1: In your Docker Compose .env (environment variable configuration), paste the code below to add a value for MYPROJECT_DEPLOYMENT_SECRET:
```
# Client Credentials Auth
MYPROJECT_DEPLOYMENT_SECRET=TTrp2QUBhCCEa8W_zKydu7hDxklilBnLTY2Rb
```

###### Add configuration patch to Platform web project.
* Step 1: Open your solution in Visual Studio. In the App_Config\Include\ folder of the Platform web project, create a new configuration patch MyProjectDeployment.ClaimMapping.config. 
* Step 2: Paste the contents found below.
```
 <?xml version="1.0" encoding="utf-8"?>
 <configuration xmlns:patch="http://www.sitecore.net/xmlconfig/" xmlns:role="http://www.sitecore.net/xmlconfig/role/" xmlns:set="http://www.sitecore.net/xmlconfig/set/">
   <sitecore role:require="Standalone or ContentManagement">
     <federatedAuthentication>
       <identityProviders>
         <identityProvider id="SitecoreIdentityServer" type="Sitecore.Owin.Authentication.IdentityServer.IdentityServerProvider, Sitecore.Owin.Authentication.IdentityServer" resolve="true">
           <transformations hint="list:AddTransformation">
             <transformation name="grant admin rights for MyProjectDeployment" type="Sitecore.Owin.Authentication.Services.DefaultTransformation, Sitecore.Owin.Authentication">
               <sources hint="raw:AddSource">
                 <!-- This needs to match the ClientId in the Identity Server configuration. -->
                 <claim name="client_id" value="MyProjectDeployment" />
               </sources>
               <targets hint="raw:AddTarget">
                 <claim name="name" value="sitecore\admin" />
                 <claim name="http://www.sitecore.net/identity/claims/isAdmin" value="true" />
               </targets>
               <keepSource>true</keepSource>
             </transformation>
           </transformations>
         </identityProvider>
       </identityProviders>
     </federatedAuthentication>
   </sitecore>
 </configuration>
```
This configuration patch adds a claim mapping to your CM role, which indicates that users who have logged in via the MyProjectDeployment client ID should be granted Admin rights.

###### Launch your environment.
* Step 1: Either run .\up.ps1, or docker-compose build, or docker-compose up -d if you have previously launched the environment.

 
##### Task 3: Install a Sitecore Content Serialization Package in Your Delivery Pipeline
To install the package you created into your delivery pipeline, run the following command:
```
 dotnet sitecore ser package install -f ​src\MyProject.build\bin\Debug\MyProject.build.itempackage 
```
#### KNOWLEDGE CHECK
![image](https://user-images.githubusercontent.com/1063617/160213509-5c9980f7-e10b-4115-b622-0c9a63fd010b.png)
![image](https://user-images.githubusercontent.com/1063617/160213553-3073d7ed-2c83-4718-9a57-46c4897b5da0.png)
![image](https://user-images.githubusercontent.com/1063617/160213707-ce581f98-a0cc-4ff2-b561-45f27728b8a6.png)
![image](https://user-images.githubusercontent.com/1063617/160213776-239bc5a3-f932-466f-9a6d-d51bf22c845d.png)

 
### Get Started with Containers for Sitecore (4h)
### Introduction to the Sitecore ASP.NET Core Rendering SDK (2h 45m)
### Developing with the ASP.NET Core Rendering SDK(2h 30m)

## Quiz
* [Quiz 1](https://quizlet.com/216770743/sitecore-developer-certification-flash-cards/) 
* [Quiz 2](https://quizlet.com/207158406/sitecore-flash-cards/) 



## Exam details
* Fifty question
* Multiple choice questions
* You must correctly answer at least 80% of the questions to pass the exam and earn certification.
* Is taken via [Kryterion Webassessor](https://www.webassessor.com/wa.do?page=publicHome&branding=SITECORE)
* You will have 100 minutes to complete the test.
