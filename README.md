Download Link: https://assignmentchef.com/product/solved-cse234-lab-4-traffic-light-controller-lab
<br>
<strong>Session (Exact Duration: 75min): </strong>

You will design an FSM for a traffic light controller with following input and output signals:

<strong>req (input):</strong> this is pedestrian request button to cross the street. 1 means there are pedestrians who want to cross and 0 means there is no one. <strong>p3s (input):</strong> it is the timer signal which shows that 3 seconds have passed. <strong>p7s (input):</strong> it is the timer signal which shows that 7 seconds have passed. <strong>p37s (input):</strong> it is the timer signal which shows that 37 seconds have passed. <strong>resetT (output):</strong> if 1, the timer initializes to zero. <strong>redL (output):</strong> if 1, red led is turned on otherwise it is off.  <strong>orangeL (output):</strong> if 1, orange led is turned on otherwise it is off.    <strong>greenL (output):</strong> if 1, green led is turned on otherwise it is off.

<u>Assume you have these signals, therefore do not design your timer. </u>During simulation you will give input signals by hand. Connect the led outputs to leds in right color in Logisim.

If there is a pedestrian who pushed the button and made <strong>req</strong> signal 1, then after <em>three</em> <em>seconds</em> the traffic light turns to orange and waits there for <em>four</em> <em>seconds</em>. Then it turns to green and waits there for <em>30 seconds</em> and then turns to red.

(<em>Hint look at the time differences in between three pXs signals. It can be easily implemented with 4 states.</em>)

<ol>

 <li>First draw the state diagram for this problem.</li>

 <li>Then draw state table for next state logic.</li>

 <li>Then write down and simplify the Boolean expression for next state bits.</li>

 <li>Design your resultant simplified circuit using Logisim.</li>

 <li>Simulate your resultant circuit to be sure it works flawless.</li>

</ol>

<strong>Rules: </strong>

DO NOT USE ANALYZE CIRCUIT PROPERTY OF LOGISIM.




<strong>Demo Session: </strong>

During demo, explain and simulate each step of your design. Do not forget you only have at most 4 minutes for that. Also you will answer any questions asked by the TA.