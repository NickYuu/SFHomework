# Homework for Software Engineering

* Team chosen language C#

* Setup .NET enviroment https://dotnet.microsoft.com/download

* Set homework tool
    will install coverlet and reportgenerator in global
    ```
    make setup
    ```

    graphviz download install http://www.graphviz.org/download/

* Build  

    please change directory to the homework[1-8] folder then type

    ```
    make build

    ```

* Test  

    please change directory to the homework[1-8] folder then type
    which will generate CoverletOutputFormat=cobertura -p:CoverletOutput=./.coverage.cobertura.xml

    ```
    make test

    ```
* Report homework 

    please change directory to the homework[1-8] folder then type
    which will run reportgenerator place html output to folder ./.coverage (please open the browser)

    ```
    make report

    ```

# C# test tool

reference https://docs.microsoft.com/zh-tw/dotnet/core/testing/?pivots=mstest

* MSTest 
* XUnit
* Nuint

# C# test coverage tool

reference https://docs.microsoft.com/zh-tw/dotnet/core/testing/unit-testing-code-coverage?tabs=linux

* coverage

# Team members

* 游X翰 4094W007
* 張X文 4094W010
* 李X成 4094W011
* 何X禹 4094W012
* 黃X賢 4094W008
