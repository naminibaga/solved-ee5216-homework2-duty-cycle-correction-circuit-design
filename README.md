Download Link: https://assignmentchef.com/product/solved-ee5216-homework2-duty-cycle-correction-circuit-design
<br>
<ul>

 <li></li>

 <li><strong>Experience to be Learnt from this Homework: </strong></li>

</ul>

To get familiar with the design process of a timing circuit and a hybrid simulation method performed on a system consisting of both netlists and behavior model extracted from SPICE simulation.

<ul>

 <li><strong>Step-by-Step Procedure </strong></li>

</ul>

Consider a design process for a duty-cycle corrector for a 1GHz input clock signal, denoted as <em>clk_in</em>. The output clock signal is denoted as <em>clk_dcc</em><u>.</u> Once locked, <em>clk_dcc</em> will have a duty cycle very close to 50%.

<ul>

 <li>(20%) Draw a block diagram of your design and summarizing how you plan to achieve the duty-cycle correction with a paragraph.</li>

 <li>(20%) Realize the design as a synthesizable Verilog code. (Your design can be a mixed format containing both netlists and RTL codes). (Hint: you may need Tunable Delay Lines, A Phase Detector, and a Controller, etc.) In this homework, we only need to use simple TDL, e.g., path-selection-based TDL, and some cell-based Phase Detector from homework #1). Resolution is not a concern in this homework.</li>

 <li>(15%) Try to use Design Compiler to synthesize your design into standard-cell netlists.</li>

 <li>(15%) Verify the correctness of your design by running gate-level Verilog simulation using as accurate delay model as possible. (Note: you may need to use your behavior model from homework #1 for the PD part). Show the waveforms of <em>clk_in</em> and <em>clk_dcc</em>. Try the following input duty cycle samples for <em>clk_in</em> – {30%, 40%, 50%, 60%, 70%}.</li>

 <li>(15%) Try to use SOC Encounter to generate the layout of your design. What is the size of your layout?</li>

 <li>(15%) Try to re-do what you have done for problem (d), but back-annotated with the post-layout SDF information except the PD part. Compare your results with those derived in the pre-layout simulation.</li>

</ul>