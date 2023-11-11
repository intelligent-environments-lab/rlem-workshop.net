---
name: Introduction to the BOPTEST Framework for Testing and Benchmarking Advanced Controllers
speakers:
- Javier Arroyo
- David Blum
- Kyle Benne
categories:
- tutorial
permalink: /:collection/:categories/Tutorial 2
---

<h2>Description</h2>
<p>The Building Optimization Testing (BOPTEST) framework is used to evaluate the performance of building Heating Ventilation and Air Conditioning (HVAC) control algorithms by enabling co-simulation between detailed building models and external controllers written by users in separate software. The framework provides a standard simulation environment and is organized into specific building test cases.  The detailed building models are implemented in Modelica using libraries that extend the IBPSA Modelica Library, including the Modelica Buildings Library and the IDEAS Library,  and packaged as Functional Mockup Units for simulation within the standardized simulation environment.  An API for this environment allows users to advance the simulation of the detailed building model with input from their control algorithms, receive data back from the detailed building model, and report key performance indicators, such as total energy use, operating cost, and thermal discomfort, after co-simulation is complete. Moreover, the BOPTEST-Gym interface enables the implementation of Reinforcement Learning (RL) algorithms in BOPTEST emulators out of the box.<p>

<p>The focus of the workshop is to provide a hands-on introduction to the BOPTEST framework and its Gym interface, which aims to enable benchmarking and facilitate the development of advanced control strategies for buildings.  The key objectives are to provide participants with:</p>

<ul>
    <li>an overview of the BOPTEST project goals and approach</li>
    <li>a guided, hands-on experience with the software</li>
    <li>an opportunity to use the software for their own research and development</li>
    <li>an opportunity to provide feedback for project development/</li>
</ul>

<h2>Program</h2>
<p>The workshop has a total duration of <strong>3.5 hours</strong> and is divided into the following parts:</p>

<ol>
    <li>Presentation: BOPTEST motivation, goals, and approach <strong>(15m)</strong></li>
    <li>Exercise 1: Introductory hands-on <a href="https://colab.research.google.com/github/JavierArroyoBastida/project1-boptest/blob/issue585_rlem2023/docs/workshops/RlemWorkshop_20231112/Introduction_to_the_BOPTEST_framework.ipynb" target="_blank">tutorial</a></li> on the software <strong>(1h15m)</strong></li>
        <ol>
            <li>Introduce the Google Colab environment</li>
            <li>Selecting a test case</li>
            <li>Exploring the API</li>
            <li>Develop a feedback controller for the test case</li>
            <li>Add forecast to your feedback controller</li>
            <li>Reporting results</li>
        </ol>
    <li>Coffee break <strong>(10m)</strong></li>
    <li>Presentation 2: An example MPC controller in BOPTEST <strong>(10m)</strong></li>
    <li>Exercise 2: Learning BOPTEST-Gym, the Gym interface of BOPTEST <strong>(20m)</strong></li>
    <li>Exercise 3: Timed common exercise <strong>(1h10m)</strong></li>
        <ol>
            <li>Introduce exercise goals: optimize the controller from Exercise 1</li>
            <li>Complete exercise, submit results, produce presentation reports</li>
            <li>Volunteer participants present findings and group discussion</li>
        </ol>
    <li>Wrap-Up and follow-up explanation <strong>(10m)</strong></li>
</ol>

<h2>Participant Prerequisites</h2>
<ul>
    <li>Basic programming experience with Python</li>
    <li>Basic knowledge of feedback control</li>
    <li>Basic knowledge of building HVAC operation</li>
</ul>

<h2>Participant Equipment Requirements</h2>
<ul>
    <li>Own laptop</li>
    <li>Power outlet access</li>
    <li>WiFi</li>
</ul>

<h2>Target Audience</h2>
<p>Building control developers interested in using simulation for control development and benchmarking. The public may be broad, from beginners to advanced control experts.</p>

<h2>Pages of Interest</h2>
<ul>
    <li><a href="https://colab.research.google.com/github/JavierArroyoBastida/project1-boptest/blob/issue585_rlem2023/docs/workshops/RlemWorkshop_20231112/Introduction_to_the_BOPTEST_framework.ipynb" target="_blank">BOPTEST Tutorial Notebook</a></li>
    <li><a href="https://ibpsa.github.io/project1-boptest/" target="_blank">BOPTEST Home Page</a></li>
    <li><a href="https://github.com/ibpsa/project1-boptest" target="_blank">BOPTEST GitHub</a></li>
    <li><a href="https://github.com/ibpsa/project1-boptest-gym" target="_blank">BOPTEST-Gym GitHub</a></li>
</ul>