# Queries

a) [Issue](https://codesandbox.io/s/cool-hermann-hncn2)

Unable to use State properly in the comp when I use HOC on it.


b) Want to useState properly
[Issue](https://codesandbox.io/s/pensive-lumiere-lggyy)

Actually seState() promotes asynchronous updates to state as we know.
It achieved synchronous update when used promise. And also achieved synchronous update for counter in class comp using async/await.
But could not achieve the same scenario for useState. For useState, I need to compulsory follow reading the updated value in corresponding useEffect as like reading data in setState callback.Is there anything I am missing or correct me if I used bad approach or syntax. 


c) [Code](https://codesandbox.io/s/dazzling-bas-rwm88)
    Can HOC and RenderProps be together used on a component. ## MISCONCEPTION I guess.
    In the above example I want to create a HOC for DataFetcher to separate the Loading and data display logic. Is this a valid scenarion? Can u give me the rough overall idea to develop.    
    When we already have Render Props we can implement the logic of returning Loading or Error component
    [github code is in this link](https://github.com/Tirunagari-Harika/react-api-data-display/tree/master/RenderProps)






