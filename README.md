# plantuml

## How to use theme
There are a few ways you can use these themes:

1. You can clone this repo, or you could download the theme file from the repo. Remeber about the same structure in the files.
To invoke a local theme, you have to use the following directive:
```
!theme d-white from /themes
```

2. Use the themes from a URL. Plantuml allows you to include files on the internet with this syntax:
```
!include https://raw.githubusercontent.com/agat46/plantuml/main/themes/puml-theme-d-white.puml
```

3. Every diagram contains the header, caption and footer like below:<br /><br />


![alt text](https://raw.githubusercontent.com/agat46/plantuml/main/graphics/example.png)<br />

To change this you can write in your diagram whatever you want or write empty ""

```
header ""

(Some text in this place)

caption Some caption
footer Some footer
```
![alt text](https://raw.githubusercontent.com/agat46/plantuml/main/graphics/example2.png)<br />

## Tips
- links to generate diagrams online <br />
https://www.planttext.com/<br />http://www.plantuml.com/plantuml/uml<br /><br />
- sometimes for better readability it's worth to chagne line type by command:<br />
```
skinparam linetype ortho
```

## Examples of diagrams
- Conditional - Activity Diagram <br /><br />
![alt text](https://raw.githubusercontent.com/agat46/plantuml/main/examples/1-conditional.png) <br />

- Relationships - Class Diagram <br /><br />
![alt text](https://raw.githubusercontent.com/agat46/plantuml/main/examples/2-relations-class.png) <br />

- Activity - Parallel Diagram <br /><br />
![alt text](https://raw.githubusercontent.com/agat46/plantuml/main/examples/3-parallel-activity.png) <br />

- Packages - Class Diagram <br /><br />
![alt text](https://raw.githubusercontent.com/agat46/plantuml/main/examples/4-class-packages.png) <br />

- Packages - Component Diagram <br /><br />
![alt text](https://raw.githubusercontent.com/agat46/plantuml/main/examples/5-components-packages.png) <br />

- Mixed - Deployment Diagram <br /><br />
![alt text](https://raw.githubusercontent.com/agat46/plantuml/main/examples/6-deployment-mixed.png) <br />

- Mindmap Diagram <br /><br />
![alt text](https://raw.githubusercontent.com/agat46/plantuml/main/examples/7-mindmap.png) <br />

- Sequence Diagram <br /><br />
![alt text](https://raw.githubusercontent.com/agat46/plantuml/main/examples/8-sequence.png) <br />

- State Diagram <br /><br />
![alt text](https://raw.githubusercontent.com/agat46/plantuml/main/examples/9-state.png) <br />

- Use Case Diagram <br /><br />
![alt text](https://raw.githubusercontent.com/agat46/plantuml/main/examples/10-usecase.png) <br />
