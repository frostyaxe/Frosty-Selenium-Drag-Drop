# Frosty-Selenium-Drag-Drop
Actions class seems to be pretty old now to handle the drag and drop action. Frosty selenium drag drop helps the user to simulate the drag and drop action with the help of JQuery. Thanks to rcorreia for creating the helper js file. You can view that JS file [here](https://gist.github.com/rcorreia/2362544)

## Download and Installation
Just download the jar file from [here](https://github.com/frostyaxe/Frosty-Selenium-Drag-Drop/raw/master/frosty-selenium-drag-drop.jar).
Add this jar file in the project build path and you are ready to use this jar file in your project.

## Usage
As it is based on the Jquery, you must have the basic knowledge of JQuery selectors. If you want to know more about the Jquery Selectors then click [here](https://www.w3schools.com/jquery/jquery_selectors.asp)

```
Step 1: Object creation
DragAndDropAction action = new DragAndDropAction()

Step 2: Finding selector data
You can use source and target elements ID in order to perform the drag and drop operation.

Step3: Calling perform method.
action.perform(driver, "#source", "#target"); // here # is means we are using ID selector to perform drag and drop operation.

```

## Sample Script

```
WebDriver driver = new ChromeDriver();
driver.get("http://www.seleniumframework.com/Practiceform/");
driver.manage().window().maximize();
new DragAndDropAction().perform(driver, "#draga", "#dragb");
```

 ## Built With

* [Java](https://docs.oracle.com/javase/8/docs/) - The programming language used
* [Maven](https://maven.apache.org/) - Dependency Management

# Authors

* **Abhishek Prajapati** - *Initial work* - [Frostyaxe](https://github.com/frostyaxe)

# Contact

* **GitHub:** [Frostyaxe](https://github.com/frostyaxe)
*  **Gmail:** *prajapatiabhishek1996@gmail.com*

 
