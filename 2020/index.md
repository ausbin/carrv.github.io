# Fourth Workshop on Computer Architecture Research with RISC-V (CARRV 2020)

## [Virtual Workshop](https://iscaconf.org/isca2020/), Friday, May 29th, 2020, Co-located with ISCA 2020

The Fourth Workshop on RISC-V for Computer Architecture Research (CARRV) seeks original
research papers on the design, implementation, verification, and evaluation of RISC-V cores,
SoCs, and accelerators. Submission of early work is encouraged. The topics of specific
interest for the workshop include, but are not limited to:

* RISC-V cores and SoC architectures
* RISC-V silicon characterizations and system designs
* RISC-V simulation/emulation infrastructure
* RISC-V ISA extensions
* RISC-V-based hardware accelerators
* Security architectures and techniques
* Formal methods
* Verification methodologies
* Hardware/software interfaces
* RISC-V ISA and implementation performance analysis
* RISC-V compilers and dynamic translation tools

## CARRV Invited Talk

<b>CHERI-RISC-V – A Full Stack Solution Mitigating Spatial and Temporal Memory Vulnerabilities</b><br>
[Simon Moore](https://www.cl.cam.ac.uk/~swm11) (University of Cambridge)

<b>Abstract</b><br>
Originally prototyped on MIPS, we have now added CHERI security extensions to the RISC-V ISA, with multiple open-source cores with various microarchitectures prototyped on FPGA.  CHERI extensions for RISC-V provide low-level hardware primitives for in-memory capabilities that allows software to dramatically  improve security by mitigating many spatial and temporal memory safety vulnerabilities.  Spatial vulnerabilities like buffer-overflow and buffer-over read are typically eliminated through the compiler and linker capturing more of the programmer’s original intent.  Pointers are mapped into in-memory capabilities that include bounds, permissions and have integrity properties.  Temporal memory safety mitigates vulnerabilities like use-after-free through revocation of capabilities, offering a major performance improvement over existing techniques like address sanitiser.  Capabilities provide the basis for other software mitigations, including control-flow robustness and highly efficient compartmentalisation.

<b>Bio</b><br>
Simon Moore is a Professor of Computer Engineering at the University of Cambridge Department of Computer Science and Technology (previously the Computer Laboratory) in England, where he conducts research and teaching in the general area of computer architecture with particular interests in secure and rigorously-engineered processors and subsystems.  Robert Watson and Simon Moore lead the CHERI project in Cambridge.


## CARRV Preliminary Program

<table>
<tbody>

<tr>
<td>
10:00am - 11:00am EST - <b>Session 1</b>

<br><br>
<b>Welcome and opening remarks</b>

<br><br>
<b><u>Invited Talk</u> - CHERI-RISC-V – A Full Stack Solution Mitigating Spatial and Temporal Memory Vulnerabilities</b><br>
Simon Moore (University of Cambridge)

</td>
</tr>

<tr>
<td>
11:00am - 11:30am EST - <b>Session 2</b>

<br><br>
<b>TEE Boot Procedure with Crypto-accelerators in RISC-V Processors</b><br>
Ckristian Duran (University of Electro-Communications), Trong-Thuc Hoang (University of Electro-Communications), Akira Tsukamoto (National Institute of Advanced Industrial Science and Technology), Kuniyasu Suzaki (National Institute of Advanced Industrial Science and Technology), Cong-Kha Pham (University of Electro-Communications)

<a href="papers/CARRV2020_paper_1_Duran.pdf">[paper]</a>
<a href="videos/CARRV_1_Duran.html">[video]</a>

<br><br>
<b>Experiment on Replication of Side Channel Attack via Cache of RISC-V Berkeley Out-of-order Machine (BOOM) Implemented on FPGA</b><br>
Anh-Tien Le (The University of Electro-Communications (UEC)), Ba-Anh Dao (The University of Electro-Communications (UEC)), Kuniyasu Suzaki (Technology Research Association of Secure IoT Edge application based on RISC-V Open architecture (TRASIO)), Cong-Kha Pham (The University of Electro-Communications (UEC))

<a href="papers/CARRV2020_paper_2_Le.pdf">[paper]</a>
<a href="slides/CARRV2020_slides_2_Le.pdf">[slides]</a>
<a href="videos/CARRV_2_Le.html">[video]</a>

<br><br>
<b>Automatic Code Generation for Rocket Chip RoCC Accelerators</b><br>
Pengcheng Xu, Yun Liang (Peking University)

<a href="papers/CARRV2020_paper_3_Xu.pdf">[paper]</a>
<a href="slides/CARRV2020_slides_3_Xu.pdf">[slides]</a>
<a href="videos/CARRV_3_Xu.html">[video]</a>

<br><br>
<b>Efficient Multiple-ISA Embedded Processor Core Design Based on RISC-V</b><br>
Yuanhu Cheng, Libo Huang, Yijun Cui, Sheng Ma, Yongwen Wang, Bincai Sui (National University of Defense Technology)

<a href="papers/CARRV2020_paper_4_Cheng.pdf">[paper]</a>
<a href="slides/CARRV2020_slides_4_Cheng.pdf">[slides]</a>
<a href="videos/CARRV_4_Cheng.html">[video]</a>

</td>
</tr>

<tr>
<td>
11:30am - 12:00noon EST - <b>Session 3</b>

<br><br>
<b>PERC: Posit Enhanced Rocket Chip</b><br>
Arunkumar M V, Sai Ganesh Bhairathi, Harshal Hayatnagarkar (ThoughtWorks Technologies)

<a href="papers/CARRV2020_paper_5_MV.pdf">[paper]</a>
<a href="slides/CARRV2020_slides_5_MV.pdf">[slides]</a>
<a href="videos/CARRV_5_MV.html">[video]</a>

<br><br>
<b>Accelerate Cycle-Level Full-System Simulation of Multi-Core RISC-V Systems with Binary Translation</b><br>
Xuan Guo, Robert Mullins (University of Cambridge)

<a href="papers/CARRV2020_paper_6_Guo.pdf">[paper]</a>
<a href="videos/CARRV_6_Guo.html">[video]</a>

<br><br>
<b>A RISC-V SystemC-TLM simulator</b><br>
Màrius Montón (Universitat Autònoma de Barcelona)

<a href="papers/CARRV2020_paper_7_Monton.pdf">[paper]</a>
<a href="slides/CARRV2020_slides_7_Monton.pdf">[slides]</a>
<a href="videos/CARRV_7_Monton.html">[video]</a>

<br><br>
<b>Enabling Hardware Randomization Across the Cache Hierarchy in Linux-Class Processors</b><br>
Max Doblas Font (Barcelona Supercomputing Center (BSC)), Ioannis-Vatistas Kostalabros (Barcelona Supercomputing Center (BSC)), Miquel Moretó Planas (Barcelona Supercomputing Center (BSC)), Carles Hernández Luz (Universitat Politècnica de València)

<a href="papers/CARRV2020_paper_8_Doblas.pdf">[paper]</a>
<a href="slides/CARRV2020_slides_8_Doblas.pdf">[slides]</a>
<a href="videos/CARRV_8_Doblas.html">[video]</a>

</td>
</tr>


<tr>
<td>
12:00noon - 12:30pm EST - <b>Session 4</b>

<br><br>
<b>Recommendations for a Radically Secure ISA</b><br>
Mathieu	Escouteloup (Inria, Univ Rennes, CNRS, IRISA), Jacques Fournier (Univ. Grenoble Alpes, CEA Leti, DSYS/LSOSP), Jean-Louis Lanet (LHS-PEC), Ronan Lashermes (Inria/SED&LHS)

<a href="papers/CARRV2020_paper_9_Escouteloup.pdf">[paper]</a>
<a href="slides/CARRV2020_slides_9_Escouteloup.pdf">[slides]</a>
<a href="videos/CARRV_9_Escouteloup.html">[video]</a>

<br><br>
<b>Prevention of Microarchitectural Covert Channels on an Open-Source 64-bit RISC-V Core</b><br>
Nils Wistoff (ETH Zürich), Moritz Schneider (ETH Zürich), Frank K. Gürkaynak (ETH Zürich), Luca Benini (ETH Zürich), Gernot Heiser (UNSW and Data61 CSIRO)

<a href="papers/CARRV2020_paper_10_Wistoff.pdf">[paper]</a>
<a href="slides/CARRV2020_slides_10_Wistoff.pdf">[slides]</a>
<a href="videos/CARRV_10_Wistoff.html">[video]</a>

<br><br>
<b>Enabling Virtual Memory Research on RISC-V with a Configurable TLB Hierarchy for the Rocket Chip Generator</b><br>
Nikolaos Charalampos Papadopoulos, Vasileios Karakostas, Konstantinos Nikas, Nectarios Koziris and Dionisios Pnevmatikatos (National Technical University of Athens)

<a href="papers/CARRV2020_paper_11_Papadopoulos.pdf">[paper]</a>
<a href="slides/CARRV2020_slides_11_Papadopoulos.pdf">[slides]</a>
<a href="videos/CARRV_11_Papadopoulos.html">[video]</a>

<br><br>
<b>HW/SW Approaches for RISC-V Code Size Reduction</b><br>
Matteo Perotti (ETH Zürich), Pasquale Davide Schiavone (ETH Zürich), Giuseppe Tagliavini (University of Bologna), Davide Rossi (University of Bologna), Tariq Kurd (Huawei), Mark Hill (Huawei), Liu Yingying (Huawei), Luca Benini (ETH Zürich and University of Bologna)

<a href="papers/CARRV2020_paper_12_Perotti.pdf">[paper]</a>
<a href="slides/CARRV2020_slides_12_Perotti.pdf">[slides]</a>
<a href="videos/CARRV_12_Perotti.html">[video]</a>

</td>
</tr>


<tr>
<td>
12:30pm - 1:00pm EST - <b>Session 5</b>

<br><br>
<b>Software-Based Off-Chip Memory Protection for RISC-V Trusted Execution Environments</b><br>
Gui Andrade, Dayeol Lee, David Kohlbrenner, Krste Asanović, Dawn Song (University of California, Berkeley)

<a href="papers/CARRV2020_paper_13_Andrade.pdf">[paper]</a>
<a href="slides/CARRV2020_slides_13_Andrade.pdf">[slides]</a>
<a href="videos/CARRV_13_Andrade.html">[video]</a>

<br><br>
<b>Ariane + NVDLA: Seamless Third-Party IP Integration with ESP</b><br>
Davide Giri (Columbia University), Kuan-Lin Chiu (Columbia University), Guy Eichler (Columbia University), Paolo Mantovani (Columbia University), Nandhini Chandramoorthy (IBM Thomas J. Watson Research Center), Luca P. Carloni (Columbia University)

<a href="papers/CARRV2020_paper_14_Giri.pdf">[paper]</a>
<a href="slides/CARRV2020_slides_14_Giri.pdf">[slides]</a>
<a href="videos/CARRV_14_Giri.html">[video]</a>

<br><br>
<b>SonicBOOM: The 3rd Generation Berkeley Out-of-Order Machine</b><br>
Jerry Zhao, Ben Korpan, Abraham Gonzalez and Krste Asanović (University of California, Berkeley)

<a href="papers/CARRV2020_paper_15_Zhao.pdf">[paper]</a>
<a href="slides/CARRV2020_slides_15_Zhao.pdf">[slides]</a>
<a href="videos/CARRV_15_Zhao.html">[video]</a>

<br><br>
<b>Closing remarks</b>


</td>
</tr>

</tbody>
</table>

## Important Dates

* Abstract submission deadline: April 18, 2020, 23:59 PST
* Full paper submission deadline: April 30, 2020, 23:59 PST
* Author notification: May 15, 2020
* Camera-ready version due: May 22, 2020
* Workshop date (virtual): May 29, 2020

## Virtual Workshop Information <span style="color:#a94442">(updated)</span>

The ISCA 2020 conference, as well as all workshops and tutorials, will be taking place virtually
this year.
The new workshop format now includes all presentations and papers being immediately available online for viewing.
During the live workshop session, all authors will first present a short lightning-talk
overview of their work, followed by answering a selection of questions during a Q&A session.
During the week leading up to the workshop, registered attendees will be able to discuss and vote on
questions for the authors to address. Vote on or contribute your own questions for the authors, as
only top questions will be selected for response.
[ISCA Registration](https://iscaconf.org/isca2020/) will open on May 25th,
and registration is necessary to vote for questions and attend the live session on May 29th. If you still want to submit a question, but the sessions have already started, feel free to use the Q&A function of Zoom.


## Organizers

* Krste Asanović (University of California, Berkeley)
* Yungang Bao (ICT)
* Luca Benini (ETHZ)
* Alex Bradbury (lowRISC CIC)
* Trevor E. Carlson (National University of Singapore)
* Silviu Chiricescu (Draper)
* G S Madhusudan (IIT-Madras)
* Robert Mullins (Cambridge)
* Arun Thomas (Draper)

## Submission Guidelines

All papers should be submitted electronically by
[EasyChair](https://easychair.org/conferences/?conf=carrv2020). Submissions
in PDF format must be limited to 6 pages including figures and tables,
plus as many pages as needed for references. Papers must be in PDF
format and should include title, authors and affiliation, e-mail
address of the contact author.

Papers must be formatted in accordance to the ACM two column
style. ACM Word or LaTeX style templates are available
[here](http://www.acm.org/publications/proceedings-template).

Note: Workshop publications do not preclude publishing at future
conference venues.

## Contact

All questions about submissions can be emailed to Arun Thomas
<<arun.thomas@acm.org>>.

## Past CARRVs

* [CARRV 2019](https://carrv.github.io/2019/)
* [CARRV 2018](https://carrv.github.io/2018/)
* [CARRV 2017](https://carrv.github.io/2017/)
