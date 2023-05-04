Download Link: https://assignmentchef.com/product/solved-csc519-hw1-vm-setup
<br>
<h2></h2>

Add the following required components to your project by editing the customize(name) function inside commands/up.js. You will want to take advantage of the VBoxManage.execute wrapper to execute VirtualBox commands.

<ul>

 <li>Add a NIC with NAT networking.</li>

 <li>Add a port forward from 2800 =&gt; 22 for guestssh.</li>

 <li>Add a port forward from 8080 =&gt; 9000 for a node application.</li>

</ul>

<h2>Post-Configuration</h2>

Add the following required components to your project by editing the postconfiguration(name) function inside the commands/up.js. You will want to take advantage of the ssh command wrapper to send commands to the VM.

<ul>

 <li>Install nodejs, npm, git</li>

 <li>Clone <u><a href="https://github.com/CSC-DevOps/App">https://github.com/CSC</a><a href="https://github.com/CSC-DevOps/App">–</a><a href="https://github.com/CSC-DevOps/App">DevOps/App</a></u></li>

 <li>Install the npm packages</li>

</ul>

<h2>SSH and App</h2>

Add a new command by creating a ssh.js inside the commands directory. When running v ssh it should ssh into your VM (25 points).

<ul>

 <li>Implement and demonstrate running v ssh.</li>

 <li>Manually run node main.js start 9000.</li>

 <li>Demonstrate you can visit localhost:8080 to see your running App.</li>

</ul>

<h2>Extra Requirements</h2>

You can complete some or all of the following activities for extra credit by modifying your code.

<ul>

 <li>Create a second NIC with either host-only or bridged networking enabled. Demonstrate that you can use your IP address to visit &lt;address&gt;:9000 to see your running App. (5 points)</li>

 <li>Create a shared sync folder. This is fairly involved, only attempt if experienced–limited help will be provided from teaching staff. (10 points)</li>

</ul>

<h1>Screencast</h1>

Create a screencast of your assignment:

    Demonstrate running your code to provision the VM (v up), running your customization and post-configuration steps, and ssh (v ssh) and a starting your App. Demonstrate your app running on your browser. Demonstrate any extra requirements fulfilled.

For guidelines, software, and recommendations see <u><a href="https://github.com/CSC-DevOps/Course/blob/master/HW/Screencasts.md">Screencasts</a></u><a href="https://github.com/CSC-DevOps/Course/blob/master/HW/Screencasts.md">.</a>

<h1>Evaluation</h1>

<ul>

 <li>Compete VM setup (40)</li>

 <li>Post-Configuration (25)</li>

 <li>SSH/APP (25)</li>

 <li>Screencast (10)</li>

 <li>Extra requirements (+5/+10)</li>

 <li>Answer a question (+5) Max possible score: 120/100.</li>

</ul>