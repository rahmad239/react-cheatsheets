#PROPS and STATE
There are two types of Model data in React. They are called Props(properties)and State. 

##Terms##
These are the most important terms to know. 
###*Props*
*These are data points that are not changable. "We determine the value of a prop and use it as part of the blueprint BEFORE the component is built. So the value of prop will NEVER change. 
*Curley brackets {} are used to indicate to react that we are going to use a place holder
*props itself is a container for all of the property values of a component. S


###*State*
*This is data that CAN change after a component is built. For example if a prop is a window (unchanging once built), the status of the window...wheather the window is open or closed is state. *This is usually altered by some external factor, user input,  passage of time, data passed from the server 
*State is also a container that holds all of the state values of a component
*State is private to a component.The status of state is only visible from within the component. It has no interation with other components or the app overall.


##Steps and Tutorials##

**How to declare a Props

**How to declare State 

                class ToDos extends Component {
                constructor (props) {
                    super(props)

                    this.state = {
                    newTodo: '',
                    }
                    }

**How to pass Props

**How to pass State

**How do we call props 
props.color or props.material

**How do we call state
state.[something]


##Links to Resources##
1. https://learnreact.design/2017/08/16/components-props-and-state/
###### This site has plain english and DOODLES :)
1. 
https://learnreact.design/
###### This is a full webcoarse on react design.