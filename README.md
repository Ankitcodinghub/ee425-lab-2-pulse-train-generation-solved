# ee425-lab-2-pulse-train-generation-solved
**TO GET THIS SOLUTION VISIT:** [EE425 Lab 2-Pulse Train Generation Solved](https://www.ankitcodinghub.com/product/ee425-lab-2-pulse-train-generation-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95153&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EE425 Lab 2-Pulse Train Generation Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Pulse Train Generation

Objective: The experiment is designed to exhibit some of the capabilities of generating pulses at the ports of the PIC18F4520.

Specific Tasks:

Use the P0_template.asm file as a starting point in order to complete the following tasks.

</div>
</div>
<div class="layoutArea">
<div class="column">
1.

2.

</div>
<div class="column">
Write an assembly program that generates a pulse train at the RA2 bit of PORTA for each of the following cases. a. TH = TL = 0.1ms

b. TH = 0.1ms, TL = 0.3ms

Write an assembly program that generates a pulse train at the RA2 bit of PORTA for each of the following cases.

</div>
</div>
<div class="layoutArea">
<div class="column">
a. b. c.

</div>
<div class="column">
TH = TL = 0.2ms

TH = 0.3ms, TL = 0.2ms

TH = 0.25ms, TL = 0.35ms

</div>
</div>
<div class="layoutArea">
<div class="column">
By the end of this assignment you should have written five (5) different .asm files.

Notes:

Please observe the following items while working through this assignment.

<ol>
<li>Do not use the Prescaler option.</li>
<li>Do not modify any line of code of the LoopTime subroutine in the P0_template.asm file.</li>
<li>Do not call the LoopTime subroutine more than once.</li>
<li>Do not create a second subroutine similar to LoopTime.</li>
</ol>
Guidelines:

There are four distinct phases for the pulse train generation:

1. Configure the pins of the PORT as outputs.

2. Send your pulse to the configured pins using appropriate commands (review the following commands: btg, bsf, bcf). 3. Use conditional logic and a “delay” mechanism to control the duty cycle of the pulse trains.

4. Loop around indefinitely to generate a continuous pulse train.

To read or write anything from a port, it is necessary to configure the port pins accordingly, using the Special Function Register (SFR) TRISx, where x is the name of the port (e.g. TRISB configures the pins of port B).

In order to configure a pin as an output, put a 0 in the corresponding bit of TRISx. Similarly, to configure a pin as an input, put a 1 in the corresponding bit.

Example: to configure pin 4 of port B as an output and the others as inputs:

MOVLF B’11101111’, TRISB

where MOVLF is a macro defined as follows:

MOVLF macro literal, dest movlw literal

movwf dest endm

</div>
</div>
</div>
