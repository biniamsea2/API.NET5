# API.NET5  

*Author: Biniam Tesfamariam*  

##### Blazor Web Assembly added

## Program Summary 
Working with the new upgrades in .NET 5, WebAPI. Worked with the integration of OpenAPI and NSwagger into the project, how it works, and why it's useful. 

## Application Specifications

###### This application includes the following:  
 #### 1) Startup File 
- Cors enabled within ConfigureServices 
- Generator configuration 
- User Interface configuration 
- Policies Added

#### 2) Controller  
- WeatherForecastController (Default)

#### 3) Data  
- DBContext present and properly configured  
- DB Tables for each entity model (DbSet<Kobe>)  
- Composite key association present in OnModelCreating override.  
- appsettings.json file present with name of database updated.  
 
#### 4) Models  
- Each Entity from the DB Table converted into a Model  
- Proper naming conventions of Primary keys  
- Navigation properties present in each Model where required  

#### 5) Blazor App Project added to solution
- Swagger.Json file added

 
 
 
---

### Getting Started
Clone this repository to your local machine.

```
$ git clone https://github.com/biniamsea2/API.NET5.git
```

### To run the program from Visual Studio:
Select ```File``` -> ```Open``` -> ```Project/Solution```

Next navigate to the location you cloned the Repository.

Double click on the ```APINET5``` directory.

Then select and open ```APINET5.sln```

---

### Visuals  
### #1
![Image 1]()
### #2
![Image 2]()
### #3
![Image 3]()
