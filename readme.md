---


---

<h1 id="ubuntu-installation-guide-in-vm-ware">Ubuntu Installation Guide In VM Ware</h1>
<h2 id="step-1-download-vmware-and-the-ubuntu-iso-file">Step 1: Download VMware and the Ubuntu ISO File</h2>
<h2 id="download-vmware-workstation">Download VMware Workstation:</h2>
<ol>
<li>Visit the official VMware website at  <a href="https://www.vmware.com/">vmware.com</a>.</li>
<li>Look for the VMware Workstation product and navigate to the download section.</li>
<li>Click on the option that says  <em>“Try Workstation 17 Player for Windows”</em>  to download the installer.</li>
</ol>
<p><img src="images/1.png" alt="Download VMware Workstation"></p>
<h2 id="step-2-create-a-new-virtual-machine">Step 2: Create a new Virtual Machine</h2>
<ol>
<li>Once the VMware Workstation is installed, open the application.</li>
<li>Click on  <em>“Create a New Virtual Machine”</em>  to start the virtual machine creation wizard.</li>
</ol>
<p><img src="images/2.png" alt="Create a new Virtual Machine"></p>
<h2 id="step-3-select-the-iso-file">Step 3: Select the ISO file</h2>
<ol>
<li>During the virtual machine creation process, you’ll be prompted to select the installation method. Choose  <em>“Installer disc image file (iso)”</em>.</li>
<li>Click  <em>“Browse”</em>  to locate and select the Ubuntu ISO file you’ve downloaded.</li>
<li>Proceed to the next step by clicking  <em>“Next”</em>.</li>
</ol>
<p><img src="images/3.png" alt="Select the ISO file"></p>
<h2 id="step-4-set-username-and-password">Step 4: Set Username and Password</h2>
<ol>
<li>Enter the name for your Linux distribution (e.g., Ubuntu).</li>
<li>Choose a username and set a password for your Ubuntu system.</li>
<li>Click  <em>“Next”</em>  to continue.</li>
</ol>
<p><img src="images/4.png" alt="Set Username and Password"></p>
<h2 id="step-5-set-path-for-virtual-machine">Step 5: Set Path for Virtual Machine</h2>
<ol>
<li>Specify a name and location for your virtual machine.</li>
<li>Click  <em>“Next”</em>  to proceed.</li>
</ol>
<p><img src="images/5.png" alt="Set Path for Virtual Machine"></p>
<h2 id="step-6-give-disk-space-to-your-virtual-machine">Step 6: Give Disk Space to your Virtual Machine</h2>
<ol>
<li>Determine the amount of disk space you want to allocate to your Ubuntu virtual machine.</li>
<li>Click  <em>“Next”</em>  to move on.</li>
</ol>
<p><img src="images/6.png" alt="Give Disk Space to your Virtual Machine"></p>
<h2 id="step-7-customize-the-hardware-for-virtual-machine">Step 7: Customize the Hardware for Virtual Machine</h2>
<ol>
<li>Adjust hardware settings such as the number of processors, amount of RAM, and other options based on your system’s capabilities.</li>
<li>Click  <em>“Next”</em>  to proceed.</li>
</ol>
<p><img src="images/7.png" alt="Customize the Hardware for Virtual Machine"></p>
<h2 id="step-8-wait-for-ubuntu-to-install">Step 8: Wait for Ubuntu to Install</h2>
<ol>
<li>The Ubuntu installation process will begin. Wait for the system to copy files and install the operating system.</li>
</ol>
<p><img src="images/8.png" alt="Wait for Ubuntu to Install"></p>
<h2 id="step-9-set-username-and-password">Step 9: Set Username and Password</h2>
<ol>
<li>During the Ubuntu installation, you’ll be asked to set a username and password for your Ubuntu user account.</li>
<li>Provide the required information and wait for the installation to complete.</li>
</ol>
<p><img src="images/9.png" alt="Set Username and Password"></p>
<h2 id="step-10-complete-the-installation">Step 10: Complete the Installation</h2>
<ol>
<li>Once the installation is finished, Ubuntu will prompt you to remove the installation medium (the ISO file). Follow the instructions to eject the virtual disk and press Enter…</li>
</ol>
<h2 id="step-11-installing-gcc-compiler">Step 11: Installing gcc compiler</h2>
<p>Open the terminal in Ubuntu and execute the following command to install the GCC compiler for the C language:<br>
<em>“sudo apt install gcc”</em><br>
If prompted, type ‘y’ and press Enter to confirm the installation.<br>
<img src="Compiler/1.jpg" alt="Install GCC"></p>
<h2 id="step-12-write-code-in-c-language">Step 12: Write code in C language</h2>
<p>Open a text editor and write a simple “Hello World” program in C. Save the file as  <em>“code1.c”</em></p>
<p><img src="Compiler/2.jpg" alt="Code in C language"></p>
<h2 id="step-13-run-your-code">Step 13: Run your code</h2>
<p>In the terminal, convert your C code into an executable file named  <em>“code1.exe”</em>  using the following commands:<br>
<em>“gcc code1.c -o code1.exe”</em><br>
Now run you file by writing the command.<br>
<em>“./code1.exe”</em><br>
You should see the “Hello World” output.</p>
<p><img src="Compiler/3.jpg" alt="Run the Code"></p>
<h2 id="step-14-installing-g-compiler">Step 14: Installing g++ Compiler</h2>
<p>Open the terminal in Ubuntu and execute the following command to install the G++ compiler for the C++ language:<br>
<em>“sudo apt install g++”</em><br>
If prompted, type ‘y’ and press Enter to confirm the installation.<br>
<img src="Compiler/4.jpg" alt="Installing g++ compiler"></p>
<h2 id="step-15-write-code-in-c-language">Step 15: Write code in C++ language</h2>
<p>Open a text editor and write a simple “Hello World” program in C. Save the file as  <em>“code.cpp”</em>.</p>
<p><img src="Compiler/5.jpg" alt="Code in C++ language"></p>
<h2 id="step-16-run-your-code">Step 16: Run your code</h2>
<p>In the terminal, convert your C++ code into an executable file named  <em>“code.exe”</em>  using the following commands:<br>
<em>“g++ code.c -o code.exe”</em><br>
Now run you file by writing the command.<br>
<em>“./code.exe”</em><br>
You should see the “Hello World” output.</p>
<p><img src="Compiler/6.jpg" alt="Run the Code"></p>
<h3 id="github-repository-link">Github Repository link</h3>
<p><a href="https://github.com/mohsin-ali9900/OS-Lab">https://github.com/mohsin-ali9900/OS-Lab</a></p>

