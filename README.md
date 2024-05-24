# Cache, Ensemble and IRIS DynamicObject adapter
A package of classes that can "serialize" and "deserialize" class instances to and from DynamicObject instances

##### Key Features
 + "Serialize" any object that extends from the adapter into a DynamicObject.
 + "Deserialize" a DynamicObject to an instance of an object that extends the adapter.
 + Serialize embedded object references recursively.
 + Block the projection of a property.
 + Control how arrays are projected. As objects (native) or JSON arrays (jsonarray)
 + Populate arrays and lists of serial objects within another object in a songle call.

## Installation
Import into yout project. Compile the MasterLib.Util.DynamicObject package prior to compiling the classes where it will be used.

## Examples
See the Examples.DynamicObject package for usage examples.

## Docker    

### Prerequisites
Make sure you have [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) and [Docker desktop](https://www.docker.com/products/docker-desktop) installed.
### Installation
Clone/git pull the repo into any local directory
```
$ git clone https://github.com/rcemper/PR_DynamicObject-Adapter.git
```
to build and start the container run     
```
$ docker compose up -d && docker compose logs -f
```
A examples are ready to be used.   

To open IRIS Terminal do:   
```
$ docker-compose exec iris iris session iris 
USER>
```
or using **WebTerminal**     
http://localhost:42773/terminal/      

To access IRIS System Management Portal   
http://localhost:42773/csp/sys/UtilHome.csp    
