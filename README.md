# ecs154a-homework-3-solved
**TO GET THIS SOLUTION VISIT:** [ECS154A-Homework 3 Solved](https://mantutor.com/product/ecs154a-homework-3-solved/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top kksr-disabled" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;74758&quot;,&quot;readonly&quot;:&quot;1&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;6&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (6 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ECS154A-Homework 3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (6 votes)    </div>
    </div>
<h1>Logisim</h1>
<ol>
<li>Use the <a href="https://drive.google.com/file/d/14uDb89VUd5yopoxduOR2lzd34VD3auQH/view?usp=sharing">version from the class Google Drive of Logisim Evolution</a>. Other versions may not work correctly.</li>
<li>Do not rename the files you receive. If you do so you will automatically fail the tester when you submit.</li>
<li>Put your solution for each problem into implementation subcircuit</li>
<li>Do not rename the implementation subcircuit anything else. If you do so you will automatically fail the tester when you submit.</li>
<li>Do not change the appearance of the implementation subcircuit from what it is set as. Doing so will cause you to automatically fail the tester when you submit.
<ol>
<li>That is this field right here</li>
</ol>
</li>
<li>Do not move the pins inside of the implementation subcircuit as that affects the appearance of the circuit on the outside as you saw in discussion. Doing so will cause you to automatically fail the tester when you submit.
<ol>
<li>If you want to “move the pins” instead connect tunnels to the pins and move the tunnels around.</li>
</ol>
</li>
<li>Do not name any of the subcirucits in your solution main. Doing so will cause you to automatically fail the tester when you submit.</li>
<li>You <strong>can </strong>create as many other subcircuits as you want in your solution. Just make sure your solution ends up in the implementation subcircuit</li>
</ol>
<h1>Restrictions</h1>
For all problems in this homework, you may only use

<ul>
<li>All of the components under Wiring</li>
<li>AND, OR, NOT, and XOR gates</li>
<li>All of the components under Plexers</li>
<li>All of the components under Arithmetic</li>
<li>All of the components under Memory <strong>EXCEPT</strong> for <strong>Counter, RAM, ROM, </strong>and <strong>Random</strong> Generator</li>
</ul>
Unless a problem specifies otherwise.

<h1>Problem 1: UpDownCounter.circ</h1>
Implement a 3 bit synchronous up/down counter that stops counting when it reaches the minimum/maximum count. For example, if the count is at 111 and you are told to count up you should stay at 111. Or if you were at 000 and told to count down you should stay at 000.

<strong>CountUpIn and CountDownIn in will never both be 1 at the same time.</strong>

This circuit should be constructed as a <strong>Moore</strong> Model Machine

<h2>Inputs</h2>
<table width="624">
<tbody>
<tr>
<td width="208">Pin</td>
<td width="208">Size (in bits)</td>
<td width="208">Explanation</td>
</tr>
<tr>
<td width="208">EnableIn</td>
<td width="208">1</td>
<td width="208">Connect to the enable port of your registers/flip-flops. When 1 your circuit works normally. When 0 your circuit does nothing.</td>
</tr>
<tr>
<td width="208">CountUpIn</td>
<td width="208">1</td>
<td width="208">Increase the count by 1 unless you are at 111.</td>
</tr>
<tr>
<td width="208">CountDownIn</td>
<td width="208">1</td>
<td width="208">Decrease the count by 1 unless you are at 000</td>
</tr>
<tr>
<td width="208">clkIn</td>
<td width="208">1</td>
<td width="208">Connect this to the clock ports of your registers/flip-flops. Do nothing else with this.</td>
</tr>
</tbody>
</table>
<h2>Outputs</h2>
<table width="624">
<tbody>
<tr>
<td width="208">Pin</td>
<td width="208">Size (in bits)</td>
<td width="208">Explanation</td>
</tr>
<tr>
<td width="208">Count</td>
<td width="208">3</td>
<td width="208">The current value of the counter</td>
</tr>
</tbody>
</table>
&nbsp;

<h1>Problem 2: FourBitParity.circ</h1>
Build a <strong>Moore </strong>Model circuit that calculates the even parity over a <strong>group of 4 bits</strong>. You will receive 1 bit of input at a time. The circuit should output a 1 if after receiving the last bit in the group there were an even number of 1’s in the group and a 0 at all other times. 0000 is considered to be an even number of 1’s.

This is not a sliding window problem but instead a chunk based problem. This means instead of looking at the last 4 bits received you look at the first group of 4 bits, then the second group of 4 bits, then the third group of 4 bits, etc.

<h2>Example Input and Output</h2>
Input:&nbsp;&nbsp;&nbsp; 0111 1000 1010 1100

Output: 0000 0000 0000 1000 1

If the output looks like it “is delayed one clock cycle” that is because you are building a Moore Model Machine and the output of a Moore Machine cannot change until the next rising clock edge because its output depends on state only.

<h2>Inputs</h2>
<table width="624">
<tbody>
<tr>
<td width="208">Pin</td>
<td width="208">Size (in bits)</td>
<td width="208">Explanation</td>
</tr>
<tr>
<td width="208">EnableIn</td>
<td width="208">1</td>
<td width="208">Connect to the enable port of your registers/flip-flops. When 1 your circuit works normally. When 0 your circuit does nothing.</td>
</tr>
<tr>
<td width="208">InputBitIn</td>
<td width="208">1</td>
<td width="208">The current bit being input into your circuit.</td>
</tr>
<tr>
<td width="208">ClkIn</td>
<td width="208">1</td>
<td width="208">Connect this to the clock ports of your registers/flip-flops. Do nothing else with this.</td>
</tr>
</tbody>
</table>
<h2>Outputs</h2>
<table width="624">
<tbody>
<tr>
<td width="208">Pin</td>
<td width="208">Size (in bits)</td>
<td width="208">Explanation</td>
</tr>
<tr>
<td width="208">IsEvenOut</td>
<td width="208">1</td>
<td width="208">1 if there were an even number of 1’s in the last group of 4 bits and 0 otherwise.</td>
</tr>
</tbody>
</table>
<h1>Problem 3: Vending.circ</h1>
Implement a <strong>Mealy</strong> model circuit to control a coin-operated vending machine. This machine only accepts quarters, dimes, and nickels. Coins are inserted until a total of 30 cents or more is deposited. <strong>Only 1 coin is deposited at a time</strong>. Once a total of 30 or more cents has been deposited your circuit should set Give_Mechandise to 1 to dispense the product in the vending machine. You should also set the change outputs for the circuit to give back the appropriate amount of change. Assume that the machine can give one dime and/or nickel back. If the customer does something silly like entering a quarter followed by a quarter (total of 50 cents), correct change does not have to be provided (20 cents) but the maximum amount of change should be given (15 cents). Note that only 1 input can be high at a time.

<h2>Inputs</h2>
<table width="624">
<tbody>
<tr>
<td width="208">Pin</td>
<td width="208">Size (in bits)</td>
<td width="208">Explanation</td>
</tr>
<tr>
<td width="208">EnableIn</td>
<td width="208">1</td>
<td width="208">Connect to the enable port of your registers/flip-flops. When 1 your circuit works normally. When 0 your circuit does nothing.</td>
</tr>
<tr>
<td width="208">QuarterReceived</td>
<td width="208">1</td>
<td width="208">1 if the user entered a quarter into the machine and 0 otherwise</td>
</tr>
<tr>
<td width="208">DimeReceived</td>
<td width="208">1</td>
<td width="208">1 if the user entered a dime into the machine and 0 otherwise</td>
</tr>
<tr>
<td width="208">NickelReceived</td>
<td width="208">1</td>
<td width="208">1 if the user entered a nickel into the machine and 0 otherwise</td>
</tr>
<tr>
<td width="208">ClkIn</td>
<td width="208">1</td>
<td width="208">Connect this to the clock ports of your registers/flip-flops. Do nothing else with this</td>
</tr>
</tbody>
</table>
<h2>Outputs</h2>
<table width="624">
<tbody>
<tr>
<td width="208">Pin</td>
<td width="208">Size (in bits)</td>
<td width="208">Explanation</td>
</tr>
<tr>
<td width="208">Give_Merchandise_Out</td>
<td width="208">1</td>
<td width="208">1 if the user has entered 30 cents and 0 otherwise</td>
</tr>
<tr>
<td width="208">Give_Dime_Out</td>
<td width="208">1</td>
<td width="208">1 if a dime should be given back as change and 0 otherwise</td>
</tr>
<tr>
<td width="208">Give_Nickel_out</td>
<td width="208">1</td>
<td width="208">1 if a nickel should be given back as change and 0 otherwise</td>
</tr>
</tbody>
</table>
<h1>Testing</h1>
Testing for this problem is much different than for previous assignments because we are building sequential circuits. After you finish building your circuit and are ready to test it

<ol>
<li>Open the associated grader circuit</li>
<li>Scroll down on the left and side until you find your circuit. Right-click on it and select Reload Library</li>
<li>Optionally turn StopOnMismatchIn on to have the testing stop on the first incorrect output
<ol>
<li>If testing stops because of this you’ll need to reset the simulation after you make your fixes otherwise you’ll be stuck here forever.</li>
</ol>
</li>
<li>Start the simulation by going to Simulate and Ticks Enabled (ctrl + k)
<ol>
<li>To increase the simulation speed go to Tick Frequency and select your desired frequency</li>
<li>You can manually do one tick at a time by selecting Tick Half Cycle (ctrl + t). This is useful when you are debugging</li>
<li>You can reset the simulation by selecting Reset Simulator (ctrl + r)</li>
</ol>
</li>
<li>The counter at the bottom will tell you how many you got right and listed next to it is the total number of points for the problem</li>
</ol>
<h1>Debugging</h1>
Here is my recommendation for how to debug

<ol>
<li>Turn on StopOnMismatchIn</li>
<li>Start the simulation</li>
<li>Note down the test number that your circuit fails on</li>
<li>Reset the simulation</li>
<li>Start ticking until you get to the test number two or three before the one you failed</li>
<li>Use the poke tool to go inside of your circuit</li>
<li>Check if everything is as you expect it to be. Check absolutely everything including state, next state, and output.</li>
<li>Tick to the next state.</li>
<li>Repeat 7 and 8 until you find your error</li>
<li>If go too far go back to step 4</li>
</ol>
&nbsp;

Debugging sequential circuits is much harder than combinational circuits as the output depends on both the current inputs and the <strong>current state</strong>. This means that you may be failing test case X not because it is doing something wrong on that test case but because you transitioned to the wrong state N test cases ago. So if you are failing test case X you may need to check all of the test cases before X to validate you are switching to the correct state prior to test case X

<h1>Making Fixes to Your Solution</h1>
After you make changes to your solution you will need to reload your circuit in the grader circuit. If you don’t it won’t see the updates. To reload your circuit, select your circuit in the grader, right-click it and select Reload Library.
