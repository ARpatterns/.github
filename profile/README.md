# AR Patterns

> *Event-driven Design Patterns in Creating Augmented Reality Experiences*

## What are AR Patterns?
AR patterns encompass high-level design patterns covering fundamental concepts for crafting immersive Augmented Reality (AR) experiences. AR patterns serve as a valuable means of communicating proven, reusable solutions to recurring design problems encountered during AR development. A list of AR patterns is collected in a public catalog, including technical as well as User Experience (UX) aspects. Event-Condition-Action (ECA) is the core pattern to analyze and describe the behavior and interactivity of AR experiences. ECA diagrams foster a consistent presentation and technology-agnostic documentation of applied AR design patterns. The AR patterns in the catalog are documented by their title, a text description, illustration of the spatial scenario, and ECA diagram (as a kind of pseudo code). 

The purpose of the following repositories is to document, maintain and extend the [catalog of AR Patterns](https://github.com/ARpatterns/catalog) first published in the paper: ["AR Patterns: Event-Driven Design Patterns in Creating Augmented Reality Experiences"](https://link.springer.com/chapter/10.1007/978-3-031-48495-7_6). Additionally it provides reusable building blocks to illustrate and describe AR scenarios. 

## What are AR Scenarios?
An "AR scenario" in the context of AR Patterns refers to a detailed documentation of a specific scenario where combined AR patterns are applied with a particular HW/SW technology platform. It outlines how these elements are used to achieve a defined goal by creating a spatial AR user experience. An AR scenario includes sample screen recording, title, use case category, detailed description, explanatory illustration, enumeration of used AR patterns, ECA diagrams, and a sample project with source code and media assets to demonstrate the practical application of AR patterns.


## Table of Contents

### AR Patterns - Reusable Building Blocks for immersive AR Experiences
The concepts of AR Patterns are reflected in these repositories:
* [**catalog**](https://github.com/ARpatterns/catalog/) that lists [augmentation patterns](https://github.com/ARpatterns/catalog/#augmentation-patterns), [behavioral patterns](https://github.com/ARpatterns/catalog/#behavioral-patterns), and the core [Event-Condition-Action pattern](https://github.com/ARpatterns/catalog/#event-condition-action-pattern) used in AR experiences
* [**diagram**](https://github.com/ARpatterns/diagram/) which describes the way of documenting AR patterns in the form of Event-Condition-Action diagrams using markdown syntax
* [**illustration**](https://github.com/ARpatterns/Illustrations/): a toolbox for creating custom illustrations of AR scenarios
* [use cases](https://github.com/ARpatterns/catalog/blob/main/usecases.md) listing use case categories of AR scenarios
* [technology platforms](https://github.com/ARpatterns/catalog/blob/main/platforms.md) listing available technology platforms that showcase scenarios using various AR patterns 

<!--* [landingpage](https://github.com/ARpatterns/landingpage/) which is the Web page hosted at [arpatterns.dev](https://arpatterns.dev)  -->

### AR Scenarios - Technology-specific Use Cases using AR Patterns
AR Patterns applied with specific technologies:
* No-Code
  * AR Patterns using **Adobe Aero**
  * AR Patterns with [**Apple Reality Composer**](https://github.com/ARpatterns/AppleRealityComposer/)
  * AR Patterns using **Snap AR**

* Low-Code
  * AR Patterns in DeclARe using [**ARchi VR**](https://github.com/ARpatterns/declare/)
* Full-Code
  * AR Patterns with **AR.js** using WebXR/A-Frame/three.js
  * AR Patterns in C# using **Unity/ARFoundation**

## How to Contribute
This is a community-driven initiative, which means we need you as a contributor! We would love to see more examples of AR patterns applied in other technologies. Join us in documenting new patterns and enhancing the existing ones.

How to contribute is described in detail here: [Contributing](https://github.com/ARpatterns/catalog/blob/main/CONTRIBUTING.md)

## Acknowledgements
The creation of these github repositories and the [arpatterns.dev](https://arpatterns.dev) Web site as a "Community Platform to Promote AR Patterns" is funded by [DIZH](https://www.dizh.uzh.ch/en/), the Digitalization Initiative of the Zurich Higher Education Institutions. 

The project has been initiated and is run by
* [Philipp Ackermann](https://www.zhaw.ch/de/ueber-uns/person/acke/), ZHAW School of Engineering, Inventor of AR Patterns and ECA Diagram
* [Steven Häsler](https://www.zhaw.ch/de/ueber-uns/person/hasv/), ZHAW School of Engineering, Technical Implementation 
* [Alessandro Holler](https://www.zhdk.ch/person/alessandro-holler-184771), ZHdK Departement Design, Creator of Illustration Toolbox
* [Stefan Schmidlin](https://www.zhdk.ch/person/stefan-schmidlin-170111), ZHdK Departement Design, Conceptual Coaching
* Benjamin Stern, ZHAW School of Engineering, Technical Implementation
