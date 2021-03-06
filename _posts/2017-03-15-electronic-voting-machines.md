---
layout: post
title: "Electronic Voting Machines, a primer"
microblog: false
audio: 
photo: 
date: 2017-03-15 16:19:28 +0400
guid: http://chirag.micro.blog/2017/03/15/electronic-voting-machines.html
---
<p>EVMs have been used in all elections in India since 2000, and began their use in Lok Sabha elections in 2004. Quite naturally, there are a few advantages to the EVMs over the traditional ballot paper usage in India. EVMs are cost-efficient, less prone to booth capture and rigging while also severely reduce polling and counting times. In fact, a Madras High Court judgement from 2005 <a href="https://indiankanoon.org/doc/605347/" target="_blank">estimates cost of printing and counting using ballots to be 30–40% of total election expenses</a>.</p>
<h4>The machines</h4>
<p>An EVM comprises two units — a Ballot Unit and a Control Unit. The program used in EVMs is burnt into a one-time programmable chip so that it cannot be altered with thereafter. The machines are not networked in any way to ensure prevention of external interference. EVMs are powered by a 6V battery, and therefore do not rely on an external power source.</p>
<p>In 2006, newer EVMs were introduced with features such as dynamic coding between Ballot Unit and Control Unit, real-time clock, full display, and data and time stamp of each key press.</p>
<p>The EC has now received approval to introduce an upgrade to the EVM, dubbed the ‘M3’ which <a href="https://ekdrishti.in/all-pre-2006-evms-to-be-replaced-with-new-m3s-7353a8cd2e1c#.cqel52lu0" target="_blank">will replace all pre-2006 EVMs</a> last used during the 2014 Lok Sabha elections. This would mean that older machines without the date-time stamp and other features introduced in 2006 will no longer be in use. The newer machines also have a digital verification system to oversee the contact between two component units, making it further tamper proof by turning the machine inoperative upon fault or change in components. 5.5 lakh M3 EVMs have already been ordered, costing Rs. 3000 crore.</p>
<p>During the 2017 Assembly elections, as part of a United Nations Development Program initiative, <a href="https://ekdrishti.in/13-representatives-from-election-management-bodies-are-in-new-delhi-to-witness-ongoing-assembly-d318acb50cf9#.d2u9iihg1" target="_blank">5 countries were given briefings on the Indian electoral process</a>, including the use of EVMs and Voter Verified Paper Audit Trail (VVPAT).</p>
<h4>Manufacture</h4>
<p>Two indigenous companies currently build the EVMs: Bharat Electronics Ltd. (BEL), a PSU under Ministry of Defense, and Electronics Corporation of India Ltd. (ECIL), a PSU under the Ministry of Atomic Energy.</p>
<p>The EC has <a href="https://ekdrishti.in/all-pre-2006-evms-to-be-replaced-with-new-m3s-7353a8cd2e1c#.cqel52lu0" target="_blank">requested approval for a third — Central Electronics Ltd. — to be added to help with production of newer M3 units</a>, this approval is still pending.</p>
<p>The EC notes that various levels of testing is performed at these sites before any machines are put into production, including independent units that perform Quality Assurance of the machines. Further, manufacturers do not have information about candidates several years into the future, or what constituency or the sequence of candidates in the Ballot Unit.</p>
<h4>Procedure</h4>
<p>Before every election, the EC begins a series of checks¹:</p>
<ul>
<li>A first level check (FLC) is done in the presence of political parties’ representatives. Manufacturers certify all components are original within the operational EVMs (malfunctioning EVMs are not used in the election).</li>
<li>The plastic cabinet of the Control Unit are then sealed, and signed by the parties’ representatives. Access to any internal components does not occur thereafter.</li>
<li>The parties representatives then randomly select 5% of the EVMs, on which a minimum of 1,000 votes are cast. Results of this ‘mock poll’ and all votes are printed and shared with the representatives, and the poll is videographed.</li>
<li>EVMs are randomized once for allocation of machines to constituencies, and a second time to the individual polling stations in the presence of candidates or their representatives. Final list of EVM serial numbers allocated to a polling station are provided to the parties or their candidates.</li>
<li>Candidates and their representatives are allowed to conduct additional mock polls at candidate setting.</li>
<li>They can also conduct a mock poll before the actual poll on poll day.</li>
<li>Once the candidate setting is complete, the Ballot Unit of the EVM is also sealed, preventing access to the inside of the Ballot Unit. This is also signed by the candidate/representatives.</li>
<li>On polling day, a mock poll with a minimum of 50 votes is conducted at each polling station in the presence of representatives.</li>
<li>An additional thread seal and paper seal are now put on the EVMs to block access to all buttons except those needed for the poll. Candidates/representatives are allowed to sign off on this as well.</li>
<li>At the end of polling, the presiding officer presses the ‘close’ button on the EVM in the presence of polling agents. No votes can be polled thereafter.</li>
<li>Now the EVM is sealed entirely, and candidates/representatives are allowed to sign off are they are satisfied.</li>
<li>Strong rooms where EVMs are sealed between polling and counting. Candidates/representatives are allowed to place their own seals, and have their own watchers. The EC posts its own watchers 24x7.</li>
</ul>
<hr>

<h4>Historically speaking…</h4>
<p>Before and after EVMs were introduced, numerous committees were constituted to review their use. To start of, a technical expert committee was appointed by the GoI in 1990, headed by Prof. S. Sampath, with Prof. P. V. Indiresan, and Dr. C. Rao Kasarbada as members. In November 2010, this Committee was expanded to add two additional experts in Prof. D. K. Sharma and Prof. Rajat Moona (now Director General, C-DAC).</p>
<p>The courts were involved as well. The Madras High Court started by rejecting tampering allegations all the way back in 2001, followed by the Kerala High Court in 2002. In 2004, the Karnataka High Court Judge K S Rai said:</p>
<blockquote>After thorough practical experimentation and research the present version of EVM is designed. This invention is undoubtedly a great achievement in the electronic and computer technology and a national pride.</blockquote>
<p>A Mumbai High Court judgement was also issued in 2005.</p>
<p>In 2010, Hari K. Prasad² along with Alex Halderman and Rop Gonggrijp, published a study wherein they claimed to have proved that Indian EVMs were hackable.</p>
<p>Their paper implies that it is not a ‘hack’ of the original system using a vulnerability in software, they physically replaced one of the components with a look-alike. This look-alike was then remotely instructed to modify votes. Their second option also involved breaking into the machine between polling and counting since there is often a delay between these two events. In either case, some kind of physical access to the device was needed to perform any tampering, meaning their claims were based on procedural issues in delivering and storing EVMs, and physically replacing components. These issues are addressed by the detailed process described above, and further improved by newer digitally-encoded EVMs.</p>
<p>Finally, in 2013, the Supreme Court, on petition by Subramanian Swamy overturning the High Court of Delhi, ruled that the <a href="https://www.eff.org/deeplinks/2013/10/supreme-court-india-voter-verifiable-paper-audit-trails-must-be-used" target="_blank">EC needed to add Voter Verifiable Paper Audit Trail (VVPAT) system to EVMs</a> as a requirement for free and fair elections, and to add to voter confidence.</p>
<p>20,000 VVPATs were purchased in 2013, and 33,500 came through in 2016. The assembly elections in Goa had all 40 constituencies with VVPAT.</p>
<p>In the 2014 Lok Sabha elections, VVPAT was available in 8 constituencies. The announcement of the new M3 machines by the EC is congruent with the Supreme Court verdict towards replacing all old EVMs prior to the 2019 Lok Sabha elections.</p>
<hr>

<p>¹ Based on the process as described by the <a href="http://eci.pib.in" target="_blank">Election Commission of India</a>.</p>
<p>² Hari Prasad was reportedly arrested sometime in 2010. While there is not much additional information, it is believed the reason for his arrest was not his research findings, but the fact that <a href="http://timesofindia.indiatimes.com/city/mumbai/Man-who-stole-EVM-in-Mumbai-held-in-Hyderabad/articleshow/6398910.cms" target="_blank">he had obtained an EVM and refused to reveal his source</a>, as it did not come from the EC.</p>
<hr>
<p>Updated (9 Apr 2017) to include additional details regarding new M3 EVMs</p>
