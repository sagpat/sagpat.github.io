### My first React.Js Interview  

I had my first ReactJs interview on 30th August, 2017. It was telephonic interview so I was little relaxed but on the same time was well prepared for it. Below is the excerpt of the interview and my analyis about what went wrong and what was good.
After a formal greetings and asking about my personal and professional background the interviewer started asking questions.
1. How a browser works?Me: (This was a surprised question to me!) I thought a bit and said, once a user enters a url, the browser interacts over the     http or https protocol to the server. It then finds the location of requested files on the server and sends back the data over the air to     the browser. The browser renders the web page and shows the data.    
2. What happens next? How browser parse the page?Me: (I was aware of the DOM and its tree structure and how DOM creates a tree based on the HTML nodes.) I told him the same but he did not seem to be pleased by this answer.
My Analysis: Later, after the interview I researched about the browser's internal working and found where I lacked. I shouldhave elaborate about The browser engine, The rendering engine(HTML and CSS Parser), JavaScript interpreter, UI backend, and Data storage. 
I found a solid tutorial at, https://www.html5rocks.com/en/tutorials/internals/howbrowserswork/
3. What are some HTTP Response ports?Me: 404 Not Found, 200 Ok, 400 Bad Request, and 403 Forbidden. > He asked me couple more but I did not know. 
4. What is asynchronous?Me: In computer, asynchronous refers to the term where two processes works independently of each other. > Example?Me: In JavaScript?> Yes.Me: Clousuer with setTimeout. > He did not understand.Me: tried to tell him the code(Btw, It is hard to tell the code over phone)
 window.setTimeout(function() {     console.log("World"); }, 1000); console.log("Hello");
5. Do you know ajax?Me: Yes. (I was expecting something more!)> His response, Good!!
6. Tell me some Js events?Me: onMouseOver, onClick, onsubmit. 
7. What is JSON? Why it is used?Me: JSON is the data interchangability format which is used to send data from one medium to another and it can be effectively convert to other formats once receive.>Ok.
8. Have you worked on REST APIs?Me: No. > Ok. No Problem.
9. What is React Js? (I was expecting this to be first question!)Me: A front end Javascript library developed by facebook to develop front-end.
>Ok. Good.
10. What is the difference between ReactJs and Angular Js?Me: I don't know Angular Js but I have worked on similar framework ExtJs. I can tell the difference in both.>Ok. Me: The basic difference is rendering time. React only rerenders the DOM component which is changed recently and do not rerenders the whole page.     This increase the page load time. Where as Ext is used to make applications having desktop application look.> But Ext has ready templates to use. What's special about react?Me: (Told him about fast rendering of page. I did not know the exact difference)
11. What is state and prop?Me: Basically, props and state are two ways the component can know what and how to renders. State in React is mutable and its data changes as per user requirements. Whereas props are immutable and it is mostly read    only. Prop is used to pass data to the child components. Component can manage its state internally.> Ok. Good.
12. Tell me of React component lifecycle?Me: ReactJs component lifecycle will have three major methods, mounting, unmounting and updating.     Mounting will help to mount the component and call the componentDidMount method which helps to load data from remote location.    updating will have render method and it will render the data. unmounting will remove the component from DOM. 13. Do you know Redux?Me: No, I am currently learing React and haven't started Redux yet.> Ok.
After this, he declared the interview is over and the HR will let me know the result. In the evening I received a regret message! I was not selected but overall it was a good experience.
- Things I was expecting: 1. More questions on ReactJs.2. Questions on core Javascript concepts like, Closures(Higher order functions), IIFE, Prototypes in Js, functions.
- Things went well:1. I was able to answer for all the ReactJs questions correctly.
- Areas of Improvement: 1. Need to elaborate the answers with proper examples.2. Avoiding wrong answers saying straight No.3. Basic concepts of Js and web.4. Jquery.
