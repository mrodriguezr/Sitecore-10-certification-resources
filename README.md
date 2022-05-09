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
 #### Single 1: Prepare to Run Sitecore Using Docker
 #### Track 1: Check the System Prerequisites.
 ##### Review Software Prerequisites Guide
 * Windows 10 Professional or Enterprise version 1809 (2019 LTSC) or later: The first software prerequisite is Windows 10 version 1809 or later. In order to enable process isolation, version 1909 is recommended. 
 * Hyper-V: The second software prerequisite is to enable Hyper-V, which allows you to run multiple operating systems as VM's on Windows. 
 * Docker Desktop for Windows
 
 * Docker Compose:  Docker Compose is included as part of the Docker Desktop installation. Sitecore for Docker Compose deployments require two text files to deploy the containers: 
- docker-compose.yaml is a Docker Compose configuration file that contains information about the different containers and configuration of each Sitecore role.
- .env is an environment variable configuration file that stores the configuration information for the environment you want to deploy. You can edit this file outside the main Docker Compose configuration. You can see a list of all of the .env variables needed by clicking the image below. 
 ![image](https://user-images.githubusercontent.com/1063617/160492080-b9a59bc2-e3ea-404d-8306-7c50b94e2fc6.png)
 * Visual Studio and/or Visual Studio Code
 
 
 ##### Confirm Hardware Settings
* Running Hyper-V
* Sitecore development
** 32GB Ram 
** CPU Quad Core or higher
** 40GB free disc space (SSD disks strongly recommended)
* Networking: To verify your networking access, ensure that the TCP ports that are used by your containers do not have any other process accessing them
![image](https://user-images.githubusercontent.com/1063617/160492330-c4a09f8e-031c-4655-bcda-3241906c4c64.png)

 ##### Verify Configuration Files
* Sitecore license file: Your Sitecore license gives you access to the Sitecore environment for development
* Environment variable (.env) file: The environment variable file (or .env) is the mechanism used by Sitecore to pass its configuration settings into containers. The environment variables for Docker Compose are stored in the .env file, which enables automatic loading of the variables during startup using Docker Compose

#### Track 2: Prepare to Launch Your Sitecore Environment.
##### Clone the Docker Examples Repository
 Repo https://github.com/Sitecore/docker-examples

 ##### Docker Compose Files
 * docker-compose.yml: this Compose file is used by the docker-compose command. It contains information about the containers (referred to as services) and their configuration.
* .env file: This environment file contains values that represent the default values for any environment variables referenced in the Compose file or used to configure Compose. 
 
 ##### Install SitecoreDockerTools
To install SitecoreDockerTools via script, run the code below:
```
 Register-PSRepository -Name "SitecoreGallery" -SourceLocation "https://sitecore.myget.org/F/sc-powershell/api/v2"
 Install-Module SitecoreDockerTools
```
##### Populate Environment File
* SITECORE_ADMIN_PASSWORD: Set your Sitecore Admin password
* SQL_SA_PASSWORD: Set your SQL Admin password
* TELERIK_ENCRYPTION_KEY:  Run the following PowerShell script as an Administrator from the same folder as your environment file C:\sitecore\docker-examples\getting-started to set the TELERIK_ENCRYPTION_KEY
 ```
 Import-Module SitecoreDockerTools
 Set-DockerComposeEnvFileVariable "TELERIK_ENCRYPTION_KEY" -Value (Get-SitecoreRandomString 128)
 ```
* SITECORE_IDSECRET, SITECORE_ID_CERTIFICATE and SITECORE_ID_CERTIFICATE_PASSWORD: Run the following PowerShell script to populate the variables required for Identity server.
 ```
Import-Module SitecoreDockerTools
Set-DockerComposeEnvFileVariable "SITECORE_IDSECRET" -Value (Get-SitecoreRandomString 64 -DisallowSpecial)
$idCertPassword = Get-SitecoreRandomString 12 -DisallowSpecial
Set-DockerComposeEnvFileVariable "SITECORE_ID_CERTIFICATE" -Value (Get-SitecoreCertificateAsBase64String -DnsName "localhost" -Password (ConvertTo-SecureString -String $idCertPassword -Force -AsPlainText))
Set-DockerComposeEnvFileVariable "SITECORE_ID_CERTIFICATE_PASSWORD" -Value $idCertPassword
 ```
#### Track 3: Populate Sitecore License Variable.
##### Identify Supported Sitecore Topologies
 Sitecore XP 10.0 has three specific topologies designed for containers: XP Workstation, XM Server, and XP Server.
 
 ###### XP Workstation
 The first topology is the Sitecore Experience Platform (XP) workstation, which is designed to be used as a Developer workstation for Docker (see Figure 2). As a Developer, you want to use this topology if you are looking to reduce memory overhead, download size, or complexity, and to improve startup or shutdown time. The Sitecore Roles for XP Workstation Guide contains a list of the roles that are supported by the XP Workstation.
![image](https://user-images.githubusercontent.com/1063617/160496868-270b8d64-6caa-4cd2-8e85-cd776805f6c1.png)

 ###### XX Server
 The second topology is the Sitecore Experience Manager (XM) Server, which is designed for use in production and non-production environments for Docker (see Figure 3). You'll want to use this topology if you are looking to reduce deployment time and lower the resource overhead in non-production environments. This is accomplished by removing the Content Delivery role from the Docker Compose configuration. The Sitecore Roles for XM Server Guide consists of a list of roles that are supported by the XM Server.
 ![image](https://user-images.githubusercontent.com/1063617/160496848-380fb860-f6ab-4edb-90c0-0c6e36a71a53.png)

 ###### XP Server
The third topology is the Sitecore Experience (XP) Server. The Sitecore Experience Server is designed for production and non-production environments for Docker (see Figure 4). As a Developer, you'll want to use this topology when you want to mimic the exact configuration that is used in production.
 ![image](https://user-images.githubusercontent.com/1063617/160497006-766c02a3-4406-433b-a73d-670e1a7a331d.png)

 ##### Convert the License File
Run the following PowerShell script, replacing the –Path with the location of your Sitecore license file.
 ```
Import-Module SitecoreDockerTools
Set-DockerComposeEnvFileVariable "SITECORE_LICENSE" -Value (ConvertTo-CompressedBase64String -Path "C:\License\license.xml")
 ```
##### Mount your File
The second option of converting your license—  mounting the license file—is an alternative to using the .env file. 
 
 To use a mounted license file, you must populate the SITECORE_LICENSE_LOCATION environment variable on each service with a volume-mounted path containing your Sitecore license key. In Figure 6, we have also used an environment variable, HOST_LICENSE_FOLDER, to configure the path on the container host which contains our license.xml.
 
 There is a significant difference when mounting the license file for xConnect roles as opposed to all other services. To mount the license, you still need to populate SITECORE_LICENSE_LOCATION, but it should point to the volume-mounted path containing the license.xml rather than to the file itself. In Figure 7, we use the same HOST_LICENSE_FOLDER environment variable, but have adjusted SITECORE_LICENSE_LOCATION to be the folder path. For an example of how to mount the file as a volume file, you can also refer to the Sitecore Docker Examples on GitHub.

#### Track 4: Configure HTTPS Certificates and Windows Hosts File.
To configure HTTPS certificates and Windows hosts file, you should first examine the Traefik folder, then generate the HTTPS certificates, and finally add the hostnames to your Windows hosts file.

 ##### Install mkcert with Windows

* Step 1: Download the latest Windows executable (e.g. mkcert-v1.4.1-windows-amd64.exe)
* Step 2: Rename the file to mkcert.exe
* Step 3: Move the file to a directory that is in one of your PATH environment variables. This will allow you to run mkcert without a full path specified.
* Step 4: Open a command prompt in administrator mode and run the following command: 
```
 mkcert -install
```
 
##### Install mkcert with Windows

* Step 1: Open up your hosts file (see Figure 4) (e.g. C:\Windows\System32\drivers\etc\hosts) 
* Step 2: Add the following entries.
```
127.0.0.1   xp0cm.localhost
127.0.0.1   xp0id.localhost
```
 
### Introduction to the Sitecore ASP.NET Core Rendering SDK (2h 45m)
### Developing with the ASP.NET Core Rendering SDK(2h 30m)

#### Track 5: Launch Your Sitecore Environment in Docker. 
##### Start Sitecore
* Step 1: In the same folder as your Compose file, run `docker-compose up -d`

 This will do a few things:
* Download all required images from the Sitecore Container Registry,
* Create a default network to use,
* Create a container for each configured service, and
* Start the containers with their configured ENTRYPOINTS.

 ##### Access Sitecore
* Browse to https://xp0cm.localhost and you should see the Sitecore default website.

 You can also access additional containers:
* Sitecore Content Management (cm) = https://xp0cm.localhost
* Sitecore xConnect Server (xconnect) = http://localhost:8081
* Sitecore Identity Server (id) = https://xp0id.localhost
* Apache Solr (solr) = http://localhost:8984 
* Microsoft SQL Server (mssql) = localhost,14330 


#### KNOWLEDGE CHECK
![image](https://user-images.githubusercontent.com/1063617/162045343-849a519a-db98-4852-b6d1-a8f9835846fc.png)
![image](https://user-images.githubusercontent.com/1063617/162045527-4ebc0303-eb7a-4d16-9b68-6ec9f30f3db0.png)
![image](https://user-images.githubusercontent.com/1063617/162045783-500358ea-b0b3-4017-bb47-5a20082e704a.png)

 #### Extended Track: Launch the Sitecore Container Support Package.
![image](https://user-images.githubusercontent.com/1063617/162082909-69a1c4d4-3800-4cfa-b123-50a694491e0b.png)

### Extended Track: Additional Docker Commands.
 ![image](https://user-images.githubusercontent.com/1063617/162263459-13ef0de8-7831-4364-b700-eb087b4cb15b.png)
![image](https://user-images.githubusercontent.com/1063617/162263690-cb774916-c295-4754-b1f1-62967dcc61c2.png)

### Single 2: Examine How to Create Custom Sitecore Container Images
#### TRACK 1: BUILD YOUR SITECORE SOLUTION USING DOCKER

 ##### Run the init.ps1 Script 
* Step 1: Navigate to C:\Sitecore\docker-examples\custom-images.
* Step 2: Run the init.ps1 script below (see Figure 1), replacing the license path with the path of your Sitecore license.
 ```
 .\init.ps1 -LicenseXmlPath C:\License\license.xml
 ```
##### Explore Dockerfile
The first file you will look at is the Dockerfile. Building your application directly in a Dockerfile like this has advantages over a more traditional build, including:

* Portability—The entire build process is "containerized." Build agents and local environments do not need to have anything installed other than Docker.
* Control over the build environment—The solution owns which build dependencies (and which versions) are used.
* Efficiency—Even if build steps are very verbose, use of Docker's build cache optimizes rebuilds.
* Plays nice in Docker ecosystem—Builds can be triggered using Docker commands. Retrieving build artifacts for use in other images is simple with Dockerfile FROM instructions.
 
##### Examine Build Command Configured in Docker Compose
##### Build the Solution Image
* Step 1: Open a PowerShell prompt and run the following command from C:\sitecore\docker-examples\custom-images.
```docker-compose build solution```
* Step 2: Once the build process has finished, you can confirm the image was created by listing all of the Docker images using Docker images. You have now built your solution image.

 
#### TRACK 2: UNDERSTAND THE STRUCTURE OF A CUSTOM SITECORE IMAGE
![image](https://user-images.githubusercontent.com/1063617/164999980-2668bb14-39bf-45bf-922c-734113cac907.png)
 
 To understand the structure of a custom Sitecore image, you will:

##### Explore the Docker Build Folder
 The docker/build folder contains files and folders to support Docker development and contains each of the Sitecore service topologies.
 At a minimum, the service folders contain a Sitecore runtime Dockerfile, which is used as the Docker build context for the corresponding service in the Docker Compose file.
 
 ###### Sitecore runtime Dockerfiles
 Within each topology in the docker/build folder, you will find a Dockerfile. You'll want to create a Sitecore runtime Dockerfile for each container that makes up your Sitecore topology (see Figure 3), even if you do not have any customizations at present. This is recommended so that there is a dedicated layer for you to make hotfixes or future customizations and you have a resulting image that you "own" which can be named, tagged, labeled, and stored as appropriate for your solution

##### Examine a service Dockerfile
 This Dockerfile is an example of using the build artifacts from your solution image.
 
##### View the configurations in Docker Compose
 Similar to the solution image, the build for custom Sitecore runtime images is also configured in the docker-compose.override.yml file. Recall that the docker-compose.yml file is the out-of-the-box Docker Compose file that comes with Sitecore, and the docker-compose.override.yml extends the main file with overrides and extensions necessary for custom Sitecore image build and development purposes. 
 
 Some important things to note in CM docker compose overwrite configuration:
* Variable values (e.g. ${SITECORE_DOCKER_REGISTRY}) can be sourced from either the environment file (.env), system environment variables on local development machines, or secrets on your build server.
* The image name uses a "-xp0-cm" suffix. With the default variable values, the tagged version will be docker-examples-xp0-cm:latest
* The build context is set to ./docker/build/cm. Docker Compose will use the Sitecore runtime Dockerfile located here (see Figure 7).
* depends_on is set to the solution service to ensure it is built first.
 
##### Build the Sitecore image(s)
 ```
 docker-compose build
 ```
 This will initiate the build process for the solution image and then all custom Sitecore runtime images defined. The custom Sitecore runtime images will be created when complete.
You can confirm the images were created by listing all Docker images by running `docker images`.
 
#### TRACK 3: EXECUTE CONFIGURATION TRANSFORMS
 To execute configuration transforms, you will need to:

##### Ensure custom image is prepared

Execute:
 ```
 .\init.ps1 -LicenseXmlPath C:\License\license.xml 

 ```
 Now that your Docker Examples has been prepared, you can examine the two Docker Examples transform files. 


##### Examine the Docker Examples transform files
 * Solution Transform: \src\DockerExamples.Website\Web.config.xdt
 * Role Transform: \docker\build\cm\transforms\Web.config.xdt 

##### Understand solution transforms
The solution Dockerfile copies the xdt from the builder stage to the final image with the following structure: \artifacts\transforms then the service (cm, id, etc.) executes Invoke-XdtTransform.ps1 script 

##### Understand role transforms
 Configuration transforms that apply only to a specific Sitecore role can be stored inside that role's dedicated docker\build folder. 
 
##### Run Docker Examples
 * Step 1: Open a PowerShell prompt and navigate to the custom-images folder.  
 * Step 2: Run Docker Examples using the Docker Compose up command 
 ```
 docker-compose -f docker-compose.xm1.yml -f docker-compose.xm1.override.yml up -d 
 ```
 * Step 3: Access your Sitecore Experience Management (XM1) containers with the following:
 - Sitecore Content Management (cm): https://cm.dockerexamples.localhost 
 - Sitecore Content Delivery (cd): https://cd.dockerexamples.localhost 
 
 * Step 4: Once the instance is up and running, use your browser's Developer tools to inspect the http headers.  

##### Apply updates to running containers.
 * Step 1: Change the solution transform value to "My transform". 
 * Step 2: Since an image build is required for config transform changes to take effect, you will need to run the following command to see the change applied in the running containers. 
 ```
 docker-compose -f docker-compose.xm1.yml -f docker-compose.xm1.override.yml up --build -d 
 ```
 * Step 3: You can also be more selective, building only the affected containers. 
 ```
 docker-compose -f docker-compose.xm1.yml -f docker-compose.xm1.override.yml build solution cm cd
 docker-compose -f docker-compose.xm1.yml -f docker-compose.xm1.override.yml up -d 
 ```
 
In both cases, when the up command is called, Docker will recreate only the cm and cd containers. The rest of the roles will continue on running. When you're done, stop and remove the containers using the down command. 
 ```
 docker-compose -f docker-compose.xm1.yml -f docker-compose.xm1.override.yml down 
 ```
 
#### TRACK 4: EXPLORE HOW TO ADD SITECORE MODULES
 ##### Understanding Sitecore module asset images
 Sitecore provides officially supported module asset images that contain the required files and scripts for you to install a Sitecore module when building your custom Sitecore images. 
 Each module asset image contains resources adhering to the following file structure.
* C:\module\[role]\content—content to overlay base Sitecore images
* C:\module\db—dacpac files with changes to databases required by the module
* C:\module\solr—files used to deploy Solr cores required for the module
* C:\module\tools—additional tools and scripts to be executed during Docker image build process
 
 ##### Viewing Dockerfile instructions
 * First, in the Sitecore runtime Dockerfile for the CM role (C:\sitecore\docker-examples\custom-images\docker\build\cm\Dockerfile), you can see the module asset images for SPE and SXA brought in at the start with ARGs (see Figure 1) and then initiated as named build stages SPE and SXA to be used later on.
 * You will also see the required CM Dockerfile instructions are added for both SPE and SXA, just after the WORKDIR instruction.
 
 ##### Exploring Docker Compose file
 Now that you've viewed the Dockerfiles for the three roles, you can see how the docker-compose.yml file configures the SPE_IMAGE and SXA_Image values. 
open the docker-compose.override.yml file at C:\sitecore\docker-examples\custom-images\docker-compose.override.yml. Next, notice that the SPE_IMAGE and SXA_IMAGE values are configured to use the Docker image repositories for each module according to the Sitecore module reference

 ##### Running Docker Examples
 ```
 docker-compose up -d
 ```
 
#### TRACK 5: DEPLOY SITECORE ITEMS INTO CONTAINERS
 ##### Review Sitecore Item Deployment
 For production deployment, you can create Sitecore Content Serialization packages to support a continuous integration pipeline. Sitecore Content Serialization (SCS) packages (file extension .itempackage) contain specified modules and all their serialized items.
 
 ##### Explore Serialization Tools
 With the release of Sitecore 10 came two new tools that support content serialization—the Sitecore Command Line Interface (CLI) and Sitecore for Visual Studio.
 
 ###### Sitecore Command Line Interface (CLI)
 The Sitecore CLI includes the ability to log in to a remote Sitecore instance, publish content, and serialize items—all from the command line. You can also create item packages which contain everything a Developer needs to deploy to production. Once you create an item package, you can use the Sitecore CLI to install it into your delivery pipeline.
 
 ###### Sitecore for Visual Studio
 Similar to Sitecore CLI, Sitecore for Visual Studio gives you a graphical way to interact with your Sitecore instance
 
 ###### Additional Serialization Tools
* Sitecore TDS
* Unicorn

 
#### KNOWLEDGE CHECK
 ![image](https://user-images.githubusercontent.com/1063617/165105231-9460f107-acf8-479e-94a7-0c416107801c.png)
 ![image](https://user-images.githubusercontent.com/1063617/165105399-fca3f841-bcdf-42eb-83ac-370357df62bf.png)
 ![image](https://user-images.githubusercontent.com/1063617/165105611-952877fb-7547-4b9a-aa9e-d15cf539f3d9.png)
 ![image](https://user-images.githubusercontent.com/1063617/165105694-974ee953-b063-4020-a9b3-9f6fe74a5bfb.png)

### Single 3: Develop and Debug in a Local Environment
 
 #### Track 1: Understand How to Deploy Files into a Running Container.
In this Track, you will understand how to deploy files into a running container by completing the following tasks:

##### Understanding ENTRYPOINT scripts
 A Docker ENTRYPOINT provides the command to execute when the container is first run. All Sitecore runtime images have a default ENTRYPOINT configured in the Dockerfile instructions. To see the default ENTRYPOINT for any image you are using, you can 
 `run docker inspect`
 
 ![image](https://user-images.githubusercontent.com/1063617/165197786-37446369-21ba-47fe-aa28-465c96877a0c.png)

##### Reviewing the docker\deploy folder
 When developing Sitecore with Docker, recall that there is a docker folder that contains files and folders to support Docker development. Within the docker folder, there is also a deploy folder which contains environment folders that serve as destinations for your code deployment and a source for the development ENTRYPOINT watch script
 
##### Exploring file deployment scenarios
 DockerDeploy publish profile (pubxml) in the solution publishes the code to docker/deploy folders
 
##### Applying ENTRYPOINTS and deployment to Sitecore runtime images
 
##### Running the Docker Examples

 #### Track 2: Explore Synchronizing Items with a Running Container

 ##### Explore Serialization Tools for Item Sync
Item sync refers to the pushing and pulling of serialized items in and out of your solution. This process can be accomplished using a number of serialization tools: Sitecore Command Line Interface (CLI), Sitecore Content Serialization plugin, Sitecore TDS, and Unicorn.
 
 
 #### Track 3: Examine Debugging in a Local Container
 ##### Review Debugging Prerequisites
 * Visual Studio 2019 version 16.5.0 or later
 * The second prerequisite is that you will also need to ensure that debug symbols have been deployed to the container.
 
 ##### Explore Attach to Process Options
 In Visual Studio, you have two options for attaching to a process in a container—using the Containers window and using the Debug menu. 

 ###### Option 1: Use the Containers Window
* Step 1: In the list of running containers, right-click on the one you'd like to debug. 
* Step 2: Click Attach to Process (see Figure 2). The Attach to Process dialog appears and shows the available processes that are running in the container.
* Step 3: Select the process (e.g., w3wp.exe) as usual (check Show processes from all users if not visible).
* Step 4: Click Attach.
* Step 5: In Visual Studio, set your breakpoint(s).
* Step 6: Refresh your site to trigger a request to hit the breakpoints you've set in your code.  

###### Option 2: Use the Debug Menu
* Step 1: From the top Debug menu, select Attach to Process.
* Step 2: For Connection type, select Docker (Windows Container).
* Step 3: For Connection target, click the Find button. Running containers will appear in the list. 
* Step 4: Select the container you’d like to debug. 
* Step 5: Click OK.
* Step 6: For Attach to, ensure Managed Code (v4.6, v4.5, v4.0) is selected (this should be the default).
* Step 7: Select the process that you see in Figure 3 (check Show processes from all users if not visible).
* Step 8: Click Attach.
* Step 9: In Visual Studio, set your breakpoint(s).
 * Step 10: Refresh your site to trigger a request to hit the breakpoints you've set in your code. 

 #### KNOWLEDGE CHECK
![image](https://user-images.githubusercontent.com/1063617/165211582-da3de691-ec4d-41c9-833d-065136e83925.png)
![image](https://user-images.githubusercontent.com/1063617/165211654-36096e8d-552e-4d30-aff9-2b4659c1ed80.png)
![image](https://user-images.githubusercontent.com/1063617/165211699-3f98b350-0ad3-4f0c-8a90-72b4e36be188.png)

 
 ## INTRODUCTION TO THE SITECORE ASP.NET CORE RENDERING SDK
 ### Single 1: Prepare your Workstation for Sitecore Headless Development
 #### Track 1: Discover the Basics of Headless Rendering

 ##### Sitecore Rendering Host
The Sitecore ASP.NET Core Rendering SDK introduces the Sitecore Rendering Host that operates outside of the Content Delivery instance and provides you with the tools for faster development iterations. The Sitecore Rendering Host is the front-end section that requests data from the Layout Service (see Figure 2). The Layout Service then retrieves data from the Content Delivery instance and returns the content data in JSON format to the Rendering Host.

 ##### Sitecore Architecture with the Rendering Host
 Like the JSS Rendering Host, the ASP.NET Core Rendering Host receives an HTTP request from the browser, then forwards the request for Sitecore- specific content data to the Content Delivery instance via the Layout Service. The Layout Service response is the content in JSON format with no HTML or markup attached. The Rendering Host then combines the content data received from the Layout Service with the .NET Core code and returns it as HTML to the browser in response to the HTTP request. 
 
 ##### Benefits of Headless Rendering Host for Sitecore Development

* The first benefit is when working headlessly with the ASP.NET Core Rendering SDK; you are building a small, light-weight, .NET Core application that does not require a full restart of the Sitecore environment to preview the code changes
 * The second benefit is that you can now run the Rendering Host application directly from Microsoft Visual Studio.
 * The third benefit of using headless development with Sitecore is the seamless interaction between the .NET Core application and your existing architecture. In practice, you will need to build and maintain the .NET Core application alongside the existing elements in your current environment architecture
 
 #### Track 2: Use the Getting Started Template
 ##### Prerequisites for Installation
 * Sitecore license
 * .NET Core 3.1 SDK
 * .NET Framework 4.8 SDK
 * .NET Framework 4.8 SDK
 * Docker for Windows
 * PowerShell 5.1
 
##### Installing the Getting Started Template
Follow the steps
 
  #### KNOWLEDGE CHECK
 ![image](https://user-images.githubusercontent.com/1063617/166125441-cf9bd93c-2191-4df6-9f76-53f60a957069.png)
 ![image](https://user-images.githubusercontent.com/1063617/166125463-7ca017aa-eddf-458a-90a1-536079b9fe05.png)
![image](https://user-images.githubusercontent.com/1063617/166125471-07a16f04-5a90-4273-915c-d37eae87a1cc.png)
![image](https://user-images.githubusercontent.com/1063617/166125482-23683788-b2b1-4fba-8020-976f61f690e8.png)
![image](https://user-images.githubusercontent.com/1063617/166125502-7fb4103c-8707-4126-a84b-dd4164be3581.png)
![image](https://user-images.githubusercontent.com/1063617/166125509-eabf49a8-3c1a-47b9-91df-cfc7fa1575a8.png)

 ### Single 2: Explore Components in ASP.NET Core
 #### Track 1: Review Site Requirements
 ##### Layout and Site Requirements
 #####  Requirement 1: Configure Site Definition
 The first requirement to check is the configuration of your site definition.
 ###### Configuration 1: Configure Root Path
 A single Sitecore instance uses multiple websites to manage content delivery, content management, and many other features. However, by default there is only one published website. This website corresponds to the <site name="website"…/> definition in the Sitecore.config file. When configuring a site definition for your ASP.NET Core rendered site, configure the rootPath as you would for any Sitecore site.

 ###### Configuration 2: Configure Host Names
When configuring a site definition for your ASP.NET Core rendered site, you must configure the hostName or targetHostName URL as the external-facing host name of your Content Delivery (CD) server. This host is used when the Layout Service outputs media library URLs (if you are not using a CDN). Additionally, the site name values should be configured in the Layout Service client default request values which are located in the appsettings.json file within the Rendering Host project.
 
 ##### Requirement 2: Configure Experience Editor Support
 This configuration involves several settings in various files within the project. 
 * One of these settings can be found in the appsettings.json file of the Rendering Host, “EnableExperienceEditor” = false. 
 * If utilizing Docker, you can find an environment setting with a value of true (Sitecore__EnableExperienceEditor: “true”) in the docker-compose.override.yml file
 * Additionally, to support Experience Editor, you must use JSON renderings and dynamic placeholders

 ###### Guide: Dependencies to Support the Experience Editor
 * JSON Renderings
 * Dynamic Placeholders

 ##### Requirement 3: Understand the HTTP Request Process
 An HTTP request comes in from the browser to be processed. Once it is determined that there is Sitecore-specific data to be rendered, the request goes through to the Rendering Engine middleware. The Rendering Engine then submits a Layout Service request that communicates with the Content Delivery instance for the JSON formatted data. The JSON is combined with the Rendering Context and model, then returned as HTML to the browser per the HTTP request.
 As a Developer, before you begin writing component code, you will need to configure the Rendering Engine within your application with the correct middleware and routing. Take a look at how to configure the Rendering Engine routing and the Rendering Engine middleware in the guide below.
 
 ###### Configure Rendering Engine Routing
 The routing configuration is necessary for HTTP requests to be appropriately matched to the data from the Layout Service. These are configured in the Startup.cs file of the Rendering Host project and can be found in the Configure method (see figure below). If you look at the UseEndpoints field, you will see a route for errors, a route to check Sitecore first to see if the request is Sitecore specific, and then a fallback to get data from non-Sitecore areas or systems.
 
 ###### Configure Middleware

The last configuration to check is Middleware. Middleware is how .NET Core handles requests and responses that come into the program. Sitecore has several pieces of middleware that are configured in the Startup.cs file of the Rendering Host project. The middleware includes the integration for the Experience Editor and how HTTP requests are handled to receive information from the Layout Service. In the ConfigureServices method, under the AddSitecoreRenderingEngine service, you’ll find the .WithExperienceEditor field that enables support for the Experience Editor. Much of this is also dependent upon the NuGet packages that must be referenced. If you review the NuGet packages for the MyProject solution, you’ll find one labeled Sitecore.AspNet.ExperienceEditor, which is the dependency for Experience Editor support.

#### Track 2: Review View Types
##### Model Bound Views
 Uou must map the Layout Service response to the view component with the AddModelBoundView<TModel>() extension method.
 
##### Custom View Components

A view component consists of three files:
* The view component class 
* The Razor view
* The view model class
 
##### Partial Views
A partial view renders HTML output within another view's rendered output. Creating partial views in a Sitecore rendering host application follows the standard MVC conventions. Similarly, partial view discovery in a Sitecore rendering host follows the standard rules in ASP.NET Core MVC. You must map the Layout Service response to the partial view. These mappings are configured in the ConfigureServices() method in the Startup class 

#### Track 3: Understand the Use of Tag Helpers

When developing with Sitecore's ASP.NET Core Rendering SDK, you can use tag helpers to render Sitecore placeholders and content fields. The six following tag helpers are available in the Sitecore.AspNet.RenderingEngine library:
 
##### Placeholder tag helper
 <sc-placeholder name="main"></sc-placeholder>

##### Text Field tag helper
 @model MyComponentModel
 <div asp-for="@Model.Description" editable="false"></div>
 
##### Rich Text Field tag helper
 * Add it as a standalone tag:
  @model MyComponentModel
  <sc-text asp-for="@Model.Content"></sc-text>
 * Add the name of a RichField property in the asp-for attribute on an HTML element:
@model MyComponentModel
<div asp-for="@Model.Content"></div>

##### Hyperlink tag helper
 * Add it as a standalone tag:

@model MyComponent
<sc-link asp-for="MyLink"></sc-link>

 * Add the name of a HyperLinkField property in the asp-for attribute on an a HTML element:
@model MyComponentModel
<a asp-for="@Model.MyLink">It is my link!</div>
 
##### Date tag helper
 * Add it as a standalone tag:

@model MyComponent
<sc-date asp-for="MyDate"></sc-date>

 * Add the name of a Date property in the asp-for attribute on an HTML element:

@model MyComponent
<span asp-for="MyDate" ></span>
 
##### Image tag helper
* Add it as a standalone tag:

@model MyComponentModel
<sc-img asp-for="@Model.Image" />

 * Add the name of an ImageField property in the asp-for attribute on an img HTML element:

@model MyComponentModel
<img asp-for="@Model.Image" />

 #### KNOWLEDGE CHECK
 ![image](https://user-images.githubusercontent.com/1063617/167277790-8726cec6-54ba-43bf-b556-b95b967faab1.png)
![image](https://user-images.githubusercontent.com/1063617/167277801-8ec3a366-1f9f-4001-b0bd-fca2af399317.png)
![image](https://user-images.githubusercontent.com/1063617/167277831-62ff2154-20ba-45fc-815e-c5bbe3c56680.png)

### Single 3: ASP.NET Production Considerations

 #### Track 1: Implement Output Caching for Layout Services
In this Track, you will learn how to implement output caching for Layout Services by completing the following four tasks:

##### Understand how to harness caching
 ASP.NET Core uses JSON renderings with the Layout Service. Keep in mind that for this reason, the JSON of a rendering’s layout is saved instead of the rendered HTML. When a call is made to the Layout Service, instead of reserializing the data source items, or re-executing a custom rendering contents resolver (if one exists), the cached JSON is returned.
 
##### Set-up your patch config file for caching
  You need to perform three steps to set up your patch.config file; use the guide below to explore these three steps using the MyProject solution.
 * Step 1: Enable Caching for Your Site: Edit the sites.config patch file to set the cacheHtml property of the site to true, i.e., cacheHtml = “true”.
 * Step 2: Modify the Default Cache Size: Set the htmlCacheSize property to an adequate value. In this example, the default cache size is set to 50 MB, i.e., htmlCacheSize= “50MB”.
 * Step 3: Configure Cache Clearing: Add the preventHtmlCacheClear attribute to the site definition in the patch file, i.e., preventHtmlCacheClear= “true”.
 
##### Determine which renderings to cache
 * Understand the factors impacting caching.
* Identify the needs of your business for locating renderings best suitable for caching.
* Examine examples to study the impacts of caching.
 
##### Enable caching on renderings
Enabling caching on renderings follows the same process regardless of whether the site uses headless rendering methods such as ASP.NET Core and JSS or non-headless options such as SXA and Sitecore MVC.
 
 * Option 1: Per-Usage Basis
 * Option 2: Global Default Setting
 
 ![image](https://user-images.githubusercontent.com/1063617/167278085-e7fcf2cd-1edd-40f1-b3bc-aa26c4fa3ddf.png)

 #### Track 2: Consider Scaling ASP.NET Core in Production
This Track will review the differences between scaling a Sitecore XP and Sitecore XM environment, how content impacts scaling needs, and the importance of performance testing.

 ##### Differences between Scaling a Sitecore XP and XM Environment
 To better understand the scaling concept with a Rendering Host within the architecture, you will need to complete the three actions mentioned below:

###### Take a closer look at the Layout Service.
 The Layout Service exists within the Content Delivery instance (see Figure 2), so you are basically adjusting the scale of that Layout Service with regards to the ASP.NET Core Rendering Host. Keep in mind that these features are the result of separating the content data from the presentation data. At the time of this writing, preliminary testing indicates that the recommended scale ratio is 0.8 Rendering Host to Layout Service in a Sitecore XP topology. In a Sitecore XM topology, the recommended scale ratio increases to 1.5 Rendering Host to Layout Service.
 

 ###### Explore the two types of scaling.
 The Rendering Host and Layout Service supports both horizontal and vertical scaling. Horizontal scaling (see Figure 3) is when additional instances are created to support the load and is also known as scaling out. Vertical scaling (see Figure 3) is when other resources are added to a single instance to support the load and is also known as scaling up. For optimizing the scaling costs with a Sitecore environment, it is recommended to use horizontal scaling for both the Rendering Host and the Layout Service.

 ###### Understand additional scaling considerations. 
 It is also important to consider the impact that scaling can have on the Sitecore environment's other features such as databases, Redis, xConnect, and the tracker.

 ##### Impact of Content Size
 With little content, you can push the Rendering Host to near 100% capacity of its CPU. However, if the content is large, the CPU usage will get stuck at or below 90%. The process is very input-output bound, which creates a throughput issue. By decreasing the content data, you can increase the performance level of the Rendering Host

 ##### Performance Testing
 Because each implementation is different, only after completing a performance test or load test will you determine how to scale the various pieces of the architecture appropriately. As you prepare your test environment, it is critical to keep it as close as possible to your production environment; any major differences between the environments could lead to inaccurate test results.
 
 #### KNOWLEDGE CHECK
 ![image](https://user-images.githubusercontent.com/1063617/167322228-1c2677ef-a4a9-4035-a72f-5fd498595671.png)
 ![image](https://user-images.githubusercontent.com/1063617/167322284-68ffa832-3ba9-4e3b-b18d-4f71d6cbe2b0.png)
![image](https://user-images.githubusercontent.com/1063617/167322358-a4aef9ca-fb1a-4edc-af29-80446cb5c537.png)
![image](https://user-images.githubusercontent.com/1063617/167322376-e4ea89e2-aed3-4f08-829f-6de102f9fbf8.png)




 
## Quiz
* [Quiz 1](https://quizlet.com/216770743/sitecore-developer-certification-flash-cards/) 
* [Quiz 2](https://quizlet.com/207158406/sitecore-flash-cards/) 

## Exam details
* Fifty question
* Multiple choice questions
* You must correctly answer at least 80% of the questions to pass the exam and earn certification.
* Is taken via [Kryterion Webassessor](https://www.webassessor.com/wa.do?page=publicHome&branding=SITECORE)
* You will have 100 minutes to complete the test.
