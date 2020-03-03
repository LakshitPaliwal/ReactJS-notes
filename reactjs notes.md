# Knowledge-about-ReactJS
<b>reactjs concepts</b> <br>
<b>what is Component ? </b>:- <br>
When we are creating and dividing a page  into multiple section and that section we called as Component. <br><br>
<b>Component Life Cycle Methode :-  </b><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;when we adding and removing in components at multiple times and vice versa or multilple change in single component.Till now there are two stages which are adding and deleting in component. But like this for a component there is going to be multiple phases. <br>
<br><br>
So there are mainly three phases in component’s lifecyle method :-  
                                        1).Mounting phase <br>
                                        2).Updating phase <br>
                                        3).Unmunting phase <br>
                                       <br>
<b>Mounting phase :-</b>&nbsp;&nbsp;Whenever a component is loading to the UI that we are going to called as a mounting, and when a component is being created and inserted into the DOM or UI that phase we called it mounting.<br><br>
<b>Updating phase :-</b>&nbsp;&nbsp;When a Component is beig Re-render due to their any changing in props and state or any user action, a component is going to Re-render on the UI or DOM that phase we are called as a updating life cycle  phase.<br>
whenever we are trying to change in state of a component then component will Re-render.<br><br>
<b>Unmounting phase :-</b>&nbsp;&nbsp;When a component is removing from UI or DOM and the new component is coming overthere, at that time a component is removing from the UI or DOM then Unmounting methode works.<br><br>
<b>Error handling :-</b> when there is a Error occur during the render or lifecycle methode or any of the component loading that time if somthing error happens then Error lifecycle methode happens. <br><br>
In<b>Mounting phase</b> there is two methodes :- <br> 
                                                  1). <code>Constructor()</code> methode <br> 
                                                  2). <code>static getDerivedStateFromProps ()</code>
                                                  <br><br>
<b>Eg.</b><br>
<code>Constructor()</code>{<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<code>super();</code><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<code>this,state = {</code><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<code>username : ''</code><br>
&nbsp;&nbsp;&nbsp;&nbsp;<code>}</code><br>
&nbsp;&nbsp;&nbsp;<code>}</code>

<br><br><br>
<b>Eg.</b><br>
<code>static getDerivedStateFromProps(props, state)</code>{<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<code>return null;</code><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<code>}</code> 
<br><br><br>
