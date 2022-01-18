# To-Do List React App

### i. A description of the important libraries you used for each component and why you chose it:

-> Following are the libraries used in building the To-Do List Application:
   a. Create-React-App -
      Create-React-App is a command-line utility that doesn't require any additional building configuration. It simplifies the creation of your own boilerplate and allows you to jump right into the app development process. There is only one build dependency, thus there are no additional complexity. This CLI tool features Webpack Babel, EsLint, and other underlayers that make it more suitable for small web apps. As very suitable for creating a simple to-do list, I used create-react-app command.
   b. ES7 React Snippets -
      It is an extension that provides JavaScript and React/Redux snippets to automatically generate various block or structure of codes for easy development. It helped me getting fimiliar with the react scripts and save time on structuring and indendation.
   c. useState from React Hook -
      React's useState Hook is imported. In a function component, it allows us to preserve local state. Between re-renders, React will keep this state. useState returns a pair of values: the current state and a function to update it. This function can be called from an event handler or from anywhere else. I used the useState function to maintain the local state of the code during re-renders and does not merge the old and the new state together.
   d. useEffect from React Hook -
      useEffect is an Effect Hook that allows a function component to perform side effects. It accomplishes the same thing as React's componentDidMount, componentDidUpdate, and componentWillUnmount methods, but in a single API. As it works well with useState and allows me to mount, unmount and update component in a single command, I used usedEffect.

### ii. A description of how you store the list items on the backend - The data structure decision you made for storing them and why you made it:

-> I stored the list items using local storage. As the application is a very simple application with not much data needed, I chose to store it using useEffect and localStorage funcations. The data is stored in the form of JSON to minimise the disk space used. Thus, the array is "stringified" into JSON when it is stored and parsed back into an array for display on the application. The data structure is {id, text, isComplete}. "id" helps in seggregating any two tasks on the to-do list to update that individual task after adding to the list. "text" stores the actual task or 'to-do', to retrive after the list is closed or refreshed. "isComplete" is used to check whether the task is complete or not. This structure is the basic structure required for a to-do list to store all the basic information needed.
      
### iii. A description of your deployment architecture – include why you chose whichever deployment platform you did:

-> As I have never had to deploy a project manually before, I was given some suggestions like Heroku, Zeit Now (Vercel) and Netlify. Upon weighing all the pros and cons, I selected Heroku deployment platform. Some of the pros of Heroku are as follows:
   a. It is easy to deploy, specially linking it with Github repository.
   b. It is free for small and simple projects.
   c. As it is easy to deploy, it saves a lot of time for the same.
   d. Heroku is used for simple scaling of the project, which may be needed for applications like to-do list in future.
   e. Low devops skills are required and instructions are easy to understand, with easy setup.
   f. Simple Rollbacks from Production stage. Also helps in automatic deployment and option to check for buggy code. In case there is one, the deployment will throw an error.

### iv. Indication of what part of this project you had never done before –if you’ve never used React, or deployed before, or anything, please tell us:

-> 

### v. The GitHub links for each of the components (mono-repos are okay too):

-> Github link - https://github.com/anshulkhairari/To-Do-List-React/

### vi. The URL of the live deployments – we should be able to open the project and look at it:

-> Deployed Application Link: https://to-do-list-react-app-final.herokuapp.com/
