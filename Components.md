#Components#
These are the building blocks of a react apps. They should be "FIRST". Focused, Independent, Reusable, Small, Testable. Require one method (render()). Actual logic can be performed inside of components


##Terms##
*Template- The html-ish (JSX) code that creates a component.
Virtual-Dom- The virtual version of the real dom, where changes are made then compared to the real dom then differences are the only things that are updates

###*Concepts*
*Contain JSX
*May have state or be stateless if they are render only 
*importing dependencies and associated files happens at the top of the screen
*components are exported using "export defauls (ComponentName)

##Steps and Tutorials##

Here is an example of one. 

                class WaitingRoomWall extends Component {
                render() {
                    return (
                    <div>
                        <NamePlate title={"Dr"} name={"Diane"} />
                        <NamePlate title={"Mr"} name={"Ndromo"} />
                        <NamePlate title={"Ms"} name={"Lovelace"} />
                    </div>
                    )
                }