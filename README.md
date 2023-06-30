<h1>XecuteMate - Shell Script Executor</h1>

XecuteMate is a command-line application that helps you find shell scripts starting with "#!/bin/bash" under your user's home directory, identify non-executable scripts, and make them executable.
    
<h2>Installation</h2>
    
To use XecuteMate, follow these steps:
<ol>
  <li>Download the XecuteMate script</li>
  <li>Navigate to the directory where you downloaded the script</li>
  <li>Open the directory in terminal</li>
  <li>Make the script executable by running this command:</li>
  <pre><code>chmod +x XecuteMate</code></pre>
</ol>
    
<h2>Usage</h2>
Once the installation is complete, you can run the XecuteMate script by double-clicking it or from the command prompt.
    
<p>The script will search for shell scripts starting with "#!/bin/bash" under your user's home directory, exclude files in hidden folders, and display a list of non-executable scripts.</p>
<p>Follow the prompts to select a non-executable script, and the script will make it executable.</p>

<h2>Example</h2>
Here's an example run of the XecuteMate script when the script location is '/home/user/run/XecuteMate':

<pre><code>$ run/XecuteMate

Total shell scripts detected: 5
Scripts without executable permission: 2
Non-executables:
[0] script1.sh
[1] script2.sh

Choose an index to make the script executable: 0

File details:
Name: script1.sh
Location: /home/user/scripts
Created: 2023-06-30 14:25:10

Confirm execution of this file? (Y/N): y
File is now executable.</code></pre>

<h2>License</h2>

This project is licensed under the [MIT License](LICENSE).
