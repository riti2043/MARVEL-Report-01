---


---

<h2 id="task-1--3d-printing">TASK 1 : 3D PRINTING</h2>
<p>Understood the the complete printing workflow - from STL files (which contain 3D model data) to slicing to actual printing . I learned how to adjust important settings like bed temperature (for adhesion), infill density (for strength vs material usage), layer height (for quality), and print speed (balancing quality with time).</p>
<h3 id="d-printing-workflow-">3D Printing Workflow :</h3>
<ol>
<li><strong>Printer Setup</strong>: Configured 3D printer and established slicer software connection</li>
<li><strong>Model Selection</strong>: Obtained STL file from Thingiverse for printing</li>
<li><strong>Slicing Process</strong>: Utilized <strong>ULTIMAKER CURA Slicer</strong> to convert 3D model into printer-readable G-code. Configured layer height for optimal print quality and set appropriate infill density for structural integrity.</li>
<li><strong>File Transfer</strong>: Saved sliced file to SD card for printer.</li>
<li><strong>Print Execution</strong>:Loaded filament and leveled build plate for proper first layer adhesion. Monitored printing process through control panel.</li>
<li><strong>Post-Processing</strong>: Allowed build plate to cool completely before part removal.</li>
</ol>
<p><img src="https://github.com/riti2043/images-for-articles/blob/main/amongus.jpeg?raw=true" alt=""></p>
<h2 id="task-2---api">TASK 2 :  API</h2>
<p>An <strong>API (Application Programming Interface)</strong> is a set of rules and protocols that allows different software applications to communicate with each other.<br>
I implemented the <strong>Frankfurter API</strong> - a free, reliable financial data service that provides real-time exchange rates without requiring an API key - to make a <em><strong>live currency converter</strong></em> using HTML, CSS and JavaScript.<br>
From the Frankfurter API, I fetch two types of data: first, a complete list of all available currencies with their full names  which I use to populate the dropdown menus automatically, and second, real-time exchange rate calculations that convert any amount from one currency to another.<br>
<a href="https://riti2043.github.io/Live-Currency-Converter/">Live currency converter</a></p>
<p><img src="https://github.com/riti2043/images-for-articles/blob/main/Currency_Converter.jpeg?raw=true" alt=""></p>
<h2 id="task-3---working-with-github">TASK 3 :  Working with Github</h2>
<p><strong>GitHub</strong> is a web-based platform that provides hosting for Git repositories. It’s like a social network for developers, providing a centralized location to store your code and collaborate with others.<br>
<strong>Forking</strong> on GitHub is the process of creating a personal copy of a repository. This is a key part of the contribution workflow for open-source projects or any project where you don’t have direct write access.<br>
My process :</p>
<ul>
<li>Created a fork of the GitHub repository.</li>
<li>Fixed the error in the main file.</li>
<li>While committing, I chose to “Create a new branch for this commit and start a new pull request.”</li>
<li>The changes were automatically pushed when I clicked ‘Propose changes’.</li>
<li>Created a pull request after reviewing my changes between the new and main branch.</li>
</ul>
<p><img src="https://github.com/riti2043/images-for-articles/blob/main/git1.jpeg?raw=true" alt="github img"><br>
<img src="https://github.com/riti2043/images-for-articles/blob/main/git2.jpeg?raw=true" alt=""></p>
<h2 id="task-4--get-familiar-with-the-command-line-on-ubuntu">TASK 4 : Get familiar with the command line on ubuntu</h2>
<p>Ubuntu is a popular and user-friendly operating system based on Linux. It’s known for being open-source, which means it’s free to use, modify, and distribute. Ubuntu comes with a graphical user interface (GUI) that’s easy for beginners to navigate, but it’s also very powerful for experienced users and developers who prefer to use the command line.</p>
<ul>
<li>Created a new folder called <strong>test</strong> using <em>make directory</em>.</li>
<li><em>Changed directory</em> to the folder.</li>
<li>Created two new txt files using <em>touch</em>.</li>
<li><em>Listed</em> files in the folder.</li>
<li>Created 2600 folders in the <strong>test</strong> folder.</li>
<li>Entered text into two files.</li>
<li><em>Concatenated</em> the two files.</li>
</ul>
<pre class=" language-bash"><code class="prism  language-bash">  <span class="token function">mkdir</span> <span class="token function">test</span>
  <span class="token function">touch</span> blankfile1.txt
  <span class="token function">touch</span> blankfile2.txt
  <span class="token function">ls</span>
  <span class="token function">mkdir</span> R<span class="token punctuation">{</span>1. .2600<span class="token punctuation">}</span>
  <span class="token keyword">echo</span> <span class="token string">"What's cookin ,"</span><span class="token operator">&gt;</span>blankfile1.txt
  <span class="token keyword">echo</span> <span class="token string">"Good lookin' ?"</span><span class="token operator">&gt;</span>blankfile2.txt
  <span class="token function">cat</span> blankfile1.txt blankfile2.txt 
</code></pre>
<p><img src="https://github.com/riti2043/images-for-articles/blob/main/Ubuntu.jpeg?raw=true" alt=""></p>
<h2 id="task-5--build-your-own-brain--—linear-regression-from-scratch">TASK 5 : <em>Build Your Own Brain</em>  —Linear Regression from Scratch</h2>
<p>Studied the fundamental concepts of Linear Regression and understood how it finds the best-fit line through data using the equation y = mx + b. Learned about Gradient Descent as an optimization algorithm that minimizes prediction errors by iteratively adjusting weights and bias parameters. The theoretical study covered cost functions, derivatives, and parameter optimization techniques needed for implementation from scratch.<br>
<a href="https://github.com/riti2043/MARVEL-Report-01/blob/master/linear_regression.md"> LinearReg and Gradient Descent</a></p>
<h2 id="task-6--the-matrix-puzzle-—-decode-with-numpy--reveal-the-image">TASK 6 : The Matrix Puzzle — Decode with NumPy &amp; Reveal the Image</h2>
<p>I went through the tutorial videos to become familiar with NumPy and Matplotlib before starting the exercise. I worked on the matrix puzzle in Jupyter Notebook, and my process was as follows:</p>
<ol>
<li>Installed and Imported NumPy and Matplotlib libraries</li>
<li>Loaded the file containing the NumPy array</li>
<li>Reshaped it into a square matrix, which unscrambled the data</li>
<li>Rotated the array by 90 degrees to obtain the final image<br>
<a href="https://nbviewer.org/github/riti2043/MARVEL-Report-01/blob/master/puzzle.ipynb">Solved Puzzle in Notebook</a></li>
</ol>
<p><img src="https://github.com/riti2043/images-for-articles/blob/main/matrix_puxxle.jpeg?raw=true" alt=""></p>
<h2 id="task-7--create-a-portfolio-webpage">TASK 7 : Create a Portfolio Webpage</h2>
<p>I created a responsive portfolio website to showcase my work, interests, and projects using HTML for structure and CSS for styling. Successfully pushed the complete website code to GitHub repository.<br>
<a href="https://github.com/riti2043/portfolio-marvel">Repo Link</a><br>
<a href="https://riti2043.github.io/portfolio-marvel/">My portfolio</a></p>
<h2 id="task-8-writing-resource-article-using-markdown">TASK 8: Writing Resource Article using Markdown</h2>
<p><strong>Markdown</strong> is a simple markup language for formatting text using basic syntax without complex editors. It works consistently across different devices and platforms.<br>
I created a technical resource article about NLPs-Concepts and Approaches using Markdown formatting and published it on the MARVEL website.<br>
<a href="https://github.com/riti2043/MARVEL-Report-01/blob/master/nlp%20markdown.md">My article using Markdown on Understanding NLPs</a></p>
<h2 id="task-10--speed-control-of-dc-motor">TASK 10 : Speed Control of DC Motor</h2>
<p>DC motor control involves two key techniques: PWM (Pulse Width Modulation) to control speed by adjusting average voltage through rapid on/off switching, and H-Bridge circuits to control rotation direction by reversing current flow through four switching elements.</p>
<p>Arduino sends control signals to the L298N motor driver, which amplifies these weak signals to control the powerful motor. The Arduino controls direction by sending HIGH/LOW signals to different input pins, and controls speed using PWM signals that vary the motor’s power by switching it on and off rapidly.</p>
<p>Made the necessary connections between the Arduino, L298N driver, and DC motor with proper ground connections. Used code in Arduino IDE with two main functions: directionControl() for changing motor rotation direction and speedControl() for smooth acceleration and deceleration using PWM signals.<br>
<strong>CLICK ON THE PICTURE</strong></p>
<p><a href="https://drive.google.com/file/d/1o7on_bBQ0VIwlzwU7YvMnnf-qDekfqN7/view"><img src="https://github.com/riti2043/images-for-articles/blob/main/DC_thumb.jpeg?raw=true" alt=""></a></p>
<h2 id="task-11--led-toggle-using-esp32">TASK 11 : LED Toggle Using ESP32</h2>
<p>The ESP32 is a small, cheap microcontroller with built-in Wi-Fi and multiple GPIO pins that we can connect LEDs, sensors, and other components to. It’s programmable and perfect for IoT projects where we need wireless control of electronics.<br>
Created a remote-controlled LED system where we can turn two LEDs on/off from any device with a web browser connected to the same Wi-Fi network.</p>
<ul>
<li>The ESP32 connects to our Wi-Fi network and gets an IP address.</li>
<li>The ESP32 generates HTML code and sends it to our browser when we visit its IP address. The dynamically created webpage displays 2 buttons - one for each LED.</li>
<li>When we click a button, our browser sends an HTTP request to the ESP32 . The ESP32 reads this request, controls the corresponding GPIO pin to turn the LED on/off, and sends back updated HTML showing the new button state.</li>
</ul>
<p><img src="https://github.com/riti2043/images-for-articles/blob/main/esp32.jpeg?raw=true" alt=""><br>
<img src="https://github.com/riti2043/images-for-articles/blob/main/Led_toggle2.jpeg?raw=true" alt=""></p>
<h2 id="task-12--soldering-prerequisites">TASK 12 : Soldering Prerequisites</h2>
<p>Soldering is the process of joining electronic components together by melting a metal alloy called solder around the connection points. This creates a permanent electrical and mechanical bond between parts, which can also be reversed using de-soldering techniques when needed.</p>
<p>Practiced soldering by creating a simple LED and resistor circuit on a perf board. Successfully connected the components with clean solder joints and verified the circuit worked by powering it up to light the LED.</p>
<p><img src="https://github.com/riti2043/images-for-articles/blob/main/soldering.jpeg?raw=true" alt=""></p>
<h2 id="task-14-karnaugh-maps-and-deriving-the-logic-circuit">TASK 14: Karnaugh Maps and Deriving the logic circuit</h2>
<p>A Karnaugh Map (K-Map) is a graphical method used to simplify Boolean algebra expressions and minimize logic circuits by grouping adjacent cells with the same output values.</p>
<p>My burglar alarm system operates using two inputs: door status and key status, where door open and key pressed are represented as 0s, while door closed and key not pressed are represented as 1s.<br>
I implemented this logic using XOR gates to detect specific input combinations .</p>
<p><img src="https://github.com/riti2043/images-for-articles/blob/main/XOR.jpeg?raw=true" alt=""><br>
The alarm triggers (LED blinks) under two specific conditions:</p>
<ul>
<li>When the door is open (0) and key is not pressed (1) - unauthorized entry attempt.</li>
<li>When the door is closed (1) but a key is pressed (0) - indicating a wrong key being used.<br>
Used CircuitVerse simulation to verify that the LED alarm activates correctly for these two threat scenarios while remaining off for normal authorized access conditions. <strong>Press on the image</strong> to view.<br>
<a href="https://drive.google.com/file/d/1PenLF9EX8Ult_6CeAjtDSRTLt_d5xOv6/view?usp=drive_link"><img src="https://github.com/riti2043/images-for-articles/blob/main/thumbnail.jpeg?raw=true" alt=""></a></li>
</ul>
<h2 id="task-15-active-participation">TASK 15: Active Participation:</h2>
<p>I participated in CodeFury 8.0, an annual national level hackathon, gaining exposure to competitive programming and innovative problem-solving approaches.</p>
<p><img src="https://github.com/riti2043/images-for-articles/blob/main/Codefury.jpeg?raw=true" alt=""></p>
<p>I won the Marketing Ads Competition conducted at the college level, demonstrating creative and strategic thinking skills in digital marketing and advertisement design.</p>
<p><img src="https://github.com/riti2043/images-for-articles/blob/main/Rithya%20Jayaram.png?raw=true" alt=""></p>
<h2 id="task-16-datasheets-report-writing">TASK 16: Datasheets report writing:</h2>
<p>Studied the L293D motor driver IC datasheet and analyzed its internal components including transistors, logic gates, and protection circuits. I learned about H-bridge operation for motor direction control and PWM technique for speed control. The study covered how these integrated circuits work together to provide dual motor control capabilities.<br>
<a href="https://github.com/riti2043/MARVEL-Report-01/blob/master/datasheet_report.md">Datasheet Report on L293D</a></p>
<h2 id="task-17--introduction-to-vr">Task 17 : Introduction to VR</h2>
<p>Virtual Reality is a technology that creates a simulated environment , allowing users to feel like they are in a different place or a world by placing them inside a 3-dimensional experience.<br>
<a href="https://github.com/riti2043/MARVEL-Report-01/blob/master/Introduction%20to%20VR.md">Report on VR</a></p>
<h2 id="task-18-sad-servers---like-leetcode-for-linux">TASK 18: Sad servers - “Like LeetCode for Linux”</h2>
<p>Got familiar with Linux commands through the provided article before tackling the Command Line Murders scenario. I proceeded to solve the mystery by navigating directories and reading through various files to gather clues and hints. Used commands to locate suspicious phrases and evidence that helped track down the criminal. Successfully identified the perpetrator and echoed the name as the solution to make the servers happy.<br>
<img src="https://github.com/riti2043/images-for-articles/blob/main/Sad_server.jpeg?raw=true" alt=""></p>
<h2 id="task-20--notebook-ninja-–-getting-started-with-jupyter">Task 20 : Notebook Ninja – Getting Started with Jupyter</h2>
<p>Jupyter Notebook is an interactive web-based environment that allows combining code, text, and visualizations in a single document.<br>
Created a Jupyter notebook combining Markdown documentation with Python coding. Used structured sections with objectives, introduction, and conclusion along with formatted text and bullet points. Created a pie chart showing expense breakdown for categories like rent, food, and utilities using matplotlib.<br>
<a href="https://nbviewer.org/github/riti2043/MARVEL-Task-Matrix-puzzle-and-Jupyter-notebook/blob/main/Ninja.ipynb">My Jupyter Notebook</a></p>
<p><img src="https://github.com/riti2043/images-for-articles/blob/main/ninja.jpeg?raw=true" alt=""></p>
<h2 id="task-21-watch--reflect-–-intro-to-machine-learning">Task 21: Watch &amp; Reflect – Intro to Machine Learning</h2>
<p>I was introduced to <strong>regression</strong> through a simple example showing how <em>straight-line predictions</em> often work better than complex curved models on new data. I discovered that models fitting training data too perfectly usually perform poorly on real-world predictions.</p>
<p>I explored <em><strong>data preparation</strong></em> covering <em>labeling</em>, <em>data reduction, data wrangling</em>, and <em>feature engineering processes</em>. The article explains techniques like <em>dimensionality reduction, sampling, normalization</em>, and <em>formatting</em> to prepare quality datasets for machine learning models.</p>
<p>Created a comprehensive article covering these ML fundamentals and uploaded it to MARVEL resources.<br>
<a href="https://github.com/riti2043/MARVEL-Report-01/blob/master/ml.md">My Article on Intro To ML</a></p>

