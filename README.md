# Tutorial - Jersey

## IntelliJ Steps
* File > New > Project
* Java Enterprise > Java EE 7 > Web Application checked & web.xml
* Right Click on project > Add Framework Support > Restful API Support
* Populate lib folder with jersey-1.19 jars
* Select src & Add new Class with package
* Update web.xml with Servlet pointing to Jersey Container

### Jersey LifeCycle
* Path’s are matched with Resource classes.
* Constructor is called.
* Dependencies are injected.
* Appropriate method is called.
* Resource is garbage collected.