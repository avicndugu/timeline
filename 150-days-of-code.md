#150 DAYS OF CODE ALC 4.0


##Day 1 - 17-6-2019
ALC 4.0
    I was accepted in ALC 4.0 stage 2. There will be a live youtube session ongoing.
    I need to read the update.
    Download slack and join the slack group.
        I used the online version of slack.
    Join the lessons channels.
        I was able to join one channel. The second channel was not valid.
    Watch the onboarding live video: watched upto 5:09.
        Focus on  learning phase 1: main track and deep dive.
        If you have problem, go to plural site help center.
        150 days of alc- Document and share your journey its a hashtag. Brad-Photographer.
        Peer learning group-
        Meetups offline- at andela locations 29th 
        August 6- learning phase 1 closes on august 6.
        Expert on skill IQ test or/and watching 4 hours of content.
    Watched about 60 mnutes of html course.
        platform.html5.org- check here to see the living standard.
        HTML5 no longer exist, we now have the html living standard.
        ECMA, WHAT WG, W3C  WG
        What apis are available in the browser:
            semantic html
            time, figure and figcaption, details and summary, mark, bdi, wbr, embed, output
            canvas, audio, video, meter, progress, math, datalist, 
            JAVASCRIPT APIS
                Canvas, web animations.
                interactions, events and messaging.
                Storage and files
                Real time communication:push api, server-sent events, websockets.
                Web components: custom elements, shadow dom, templates.
                Perfomance optimisation and analysis: navigation timing, page visibility, high resolution timing, user timing, webworker.
                Security and privacy: content security policy, referrer policy, web cryptography.
                Other features: scripts-async & defer, contentEditable, drag and drop, history, service workers.
        Why?-Browser support
            First look out for the needs of your project.
            Then you need to look out for browser implementations.    
        Its advisable to use html5 boilerplate: has normalize that is helpful.
        caniuse.com: check features support manually.
        modernizer: detects user's browser features automatically ie features detections.
        Fallbacks and polyfills: Check html5please.com to see more on fallbacks and polyfills.

Day 2 - 18-6-2019
HARVARD CS50:WEEK 0
    Finish watching the first video.
    Draft a project on paper.
    Code the project.
        Implemented the following features
            Bullet moves towards the bell.
            Bullet deforms the ball on strike.
            the gun and bullet rotates towards the bell.
CHINGU
    GIT NOTES
        Hi guys I think so I wrote an outline of the git commands process I am using during this CHINGU. Maybe the to help you overcome the hurdle of using git and github. For this project. So here is my work flow.
        If I don't have the repository on my computer, I do: git clone name-of-repository
        I the enter the folder: cd name-of repository
        I create a new branch by: git branch name-of-new-feature-i-am-working-on
        I enter switch to that branch by: git checkout name-of-new-feature-i-am-working-on
        I can check on which branch I am currently working on anytime using: git status
        I make some changes.
        I add the changes to git by: git add .
        I commit the changes: git commit -m "message"
        I push the changes to github online by: git push origin name-of-new-feature-i-am-working-on
        Repeat this until the feature is complete:
            I make some changes.
            I add the changes to git by: git add .
            I commit the changes: git commit -m "message"
            I push the changes to github online by: git push origin name-of-new-feature-i-am-working-on

Day 3 - 19-6-2019
ALC 4:  
    Watch 10 minutes of content.
    DOM SELECTION API
    document.getElementByClassName('class-name');
    document.querySelector('.class-name') returns the first item that matches the selector
    document.querySelectorAll('.class-name')  return a nodelist
    iterating through a nodelist:
        1. Using a for loop
            for(n=0; n< items.length; n++){
                console.log(items[i].innerText);
            }
        2. Using forEach
            var forEach=Array.prototype.forEach;
            forEach.call(items, function(item){
                console.log(item.innerText);
            })
    Check for updates on slack.
    #150DaysOfALC4 @Andela_Kenya @googleafrica @pluralsight


Day 4 - 20-6-2019
HAVARD CS50
    Code the project
        Features to implement
            Points counter. Loose a life if you shoot a human. You get points for shooting balls.
            A human who moves across the field who you are not supposed to shoot.
        Check the requirements again. Finalise the requirements.
        Setting up submit50.
        Submit the project and fill the googleform.

ALC4.0
    Tackle 10 minutes of the html course.
        getElementByClassName gives a live result, ie. any new items added will get automatically detected as added.
        querySelectorAll gives a static result. Any new item added will not be recognised as added.
        If you need to keep track of what items have been added, use getElementByClassName .
    CSS Course: Watched one module of CSS
        I know most of the stuff but something I learnt today is:
        div > p { } the rules only apply to the direct p descendants of div not all p like this one:
        <div>
            <p></p> <!--This one will be affected-->
            <div>
                <p></p><!--This one won't be affected.-->
            </div>
        </div>
        While div p { } selects all p's inside it.
        image[alt=spacer]{ } Selection using attributes.
        pseudo classes eg. a:visited { }
    NODE:
        Listened to the intoduction of node basics.

###Day 9 - 24-6-2019
Mozilla science clone:
    Complete one feature on moz science: Put logo and text of supporters side by side.
    Layout for supporters section complete.
    Layout for what's new section complete.

###Day 10 - 25-6-2019
Mozilla science clone:
    Adjust colors of subscribe section and footer section.
Chingu MVP:
    Successfully completed background color switching feature.
    Resized the nav bar.

###27-6-2019
CHINGU
    Feature Color switching of text in dark light theme.
    Completed the color switching feature of background and text. Awaiting atleast one reviewer.



###2-7-2019
ALC 4.0
    Planning to Start Angular lessons very soon. But before I go to angular I need to understand how to setup my dev environment. So I am first taking this 50 minutes course called 'Building a JavaScript Development Environment by Cory House' https://app.pluralsight.com/library/courses/javascript-development-environment/description
    Do CSS positioning course when I don't need an intensive course.
    Doing Javascript: Getting started. I have to finish what I started here since it is useful and finishing what I start is a good habit to form.
        Removing and adding HTML elements.
            use style.display="none" or "block";
        Change text in a DOM.
        Handle button click.
    Practical Design Patterns in JavaScript
        What Is a Design Pattern Anyway?
            Make javascript more readable and understandable.
            What where, when, who to use them.
            Every time think of the problem and the solution you provide should solve the problem.
            Design patterns are good because: you can reuse someones solution, and you can have more common language.
            Types
                Creational
                    Constructor pattern(specific to javascript)
                    module pattern(specific to javascript)
                    factory pattern
                    singleton pattern
                Structural patterns
                    Decorator
                    Facade
                    flyweight
                Behavioral patterns
                    Command
                    Mediator
                    Observer
        2. Objects in JavaScript
            Creating object:
                var obj={}; or
                var newObj=Object.create(Object.prototype) //Useful when you want inheritance
                var anotherObj=new Object();
            Assigning values and keys
                obj.hive="new Value";
                obj['tuktuk']="killer 1";
                bracket notation works will with variable eg obj[variable]="23dd";







###4th July 2019
ALC 4.0:
    Practical Design Patterns in JavaScript
        Example available in: avicndugu.github.io/projects/practical-design/task.js
        Defining object properties: defineProperty
        Why we would use one
        Writable prevent accidentally overwrite of an object by setting writable to false.
        Enumerable prevents this object property appearing in a console.log. i.e. it is not viewable by others.
        configurable prevents someone else comming in and changing these 2 settings above.
    NODE.JS:
        1. What is covered
            Getting started
            Modern javascript
            NPM
            modules and concurrence
            Working with web servers
            Working with operation systems
        .editor opens a text editor in the NODE REPL.
        .break will get you out of editor easily.

5th July 2019
    ALC 4.0:
        JavaScript Objects and Prototypes    
            1. Object literals
                cat={name:"Fluffy", color:"White"};
            2. Constructor functions
                function Cat(name, color){
                    this.name:name;
                    this.color:color;;
                }
                var cat= new Cat('Fluffy', 'White');
                console.log(cat);
            3. Using Object.create()
                var cat=Object.create(Object.prototype,
                    {
                        name:{
                            value:"Fluffy",
                            enumerable:true,
                            writable:true,
                            configurable:true
                        }
                        color:{
                            value:"White",
                            enumerable:true,
                            writable:true,
                            configurable:true
                        }
                    })
            4. Using ES6 classes
                class Cat {
                    constructor(name,color){
                        this.name=name
                        this.color=color
                    }
                    speak(){
                        console.log("Meooow") // Method
                    }
                }
                var cat= new Cat('Fluffy', 'White');
                console.log(cat);
                console.log(cat.speak());
            Javascript Object Property
                Accessing objects
                    Using javascript bracket notation
                    Using javascript dot notation
                Javascript property descriptor
                    cat={name:"Fluffy", color:"White"};
                    console.log(Object.getOwnPropertyDescriptor(cat,'name'));
                Changing object properties
                    Writable:
                        Object.defineProperty(cat, 'name', {writable:false}) //Set to unwritable
                        This prevents the object from being rewritten. But if the object contains an object, the value of the object inside can be rewritten.
                    Enumerable:
                        looping through an object:
                            for (var propertyName in cat) {
                                console.log(propertyName);
                            }
                        When enumerable is set to false, that property does not show up in the loop or in the Object.keys(cat), if you JSONstringify, it still does not appear there;
                        Object.defineProperty(cat, 'name', {enumerable:false}) //Set to viewable
                        Object.keys(cat); // Name does not appear
                    Configurable:
                        Prevents Objects property:enumerable and configurable from being changed when set to false. You cannot delete object property once configurable is set to false.
                        Object.defineProperty(cat, 'name', {configurable:false}) //Set to viewable
                    Using getters and setters
                        Getters:
                            cat={
                                name:{first:"Fluffy",last:"Kilsu"}, color:"White"
                                };
                            Object.defineProperty(cat, "fullName",
                            {
                                get:function() {
                                    return this.name.first
                                }
                                set:function(value) {
                                    var nameParts=value.split(' ');
                                    this.name.first=nameParts[0];
                                    this.name.last=nameParts[1]; 
                                }
                            })
                            console.log(cat.fullName);
                            cat.fullName="Kuku Mbaya";
                            console.log(cat.fullName);
