# cpuvinf 1.1
CPUVInf - Raspberry Pi Diagnostics Tool<br />
Homepage: https://cpuvinf.tny.im/ or https://cpuvinf.eu.org/ <br /><br /><br />
<B>What is CPUVINF?</B><br /><br />
CPUVInf is a tiny, simple and useful diagnostics tool for the Raspberry Pi minicomputer series written purely in shell scripting language. It is compatible with all Raspberry Pi 1 and all Raspberry Pi 2 minicomputers and therefore with all available Linux based operating systems for the Raspberry Pi series. It started off as a small script to read CPU temperature and voltage but has become much more than that.<br /><br /><br />
<B>Full list of compatible OS:</B>
<ul>
<li>Raspbian</li>
<li>Pidora</li>
<li>Arch Linux ARM</li>
<li>Ubuntu MATE</li>
<li>Snappy Ubuntu Core</li>
<li>Media center Distros with access to console based on one of the above listed OS
</ul><br /><br />
<B>Features:</B><br /><br />
CPU & GPU Temperature<br />
CPUVInf can read CPU and GPU temperatures from the hardware sensors. Conversion of the sensor output is done into °F/°C values.<br /><br />
CPU & GPU Clocks<br />
CPUVInf can retrieve the minimum, maximum and current CPU and GPU clocks. Moreover it is also possible to retrieve the CPU governer. Output is converted into MHz values.<br /><br />
System Voltages<br />
CPUVInf is capable of reading various system voltages and converting the output into Volt values. Voltage types: core, SDRAM core, SDRAM I/O and SDRAM PHY voltages.<br /><br />
Memory Split<br />
CPUVInf can display the assigned RAM for the internal GPU and system RAM (usable RAM) in MB values.<br /><br /><br />
<B>Usage</B><br /><br />
CPU & GPU Temperature<br />
<pre>cpuvinf -t 
or
cpuvinf --temperature
</pre>
Screenshot: https://cpuvinf-cdn.hiddenrefuge.eu.org/images/temp11.png<br /><br />
CPU & GPU Clocks<br />
<pre>cpuvinf -c
or
cpuvinf --clocks
</pre>
Screenshot: https://cpuvinf-cdn.hiddenrefuge.eu.org/images/clock11.png<br /><br />
System Voltages<br />
<pre>cpuvinf -v
or
cpuvinf --voltages
</pre>
Screenshot: https://cpuvinf-cdn.hiddenrefuge.eu.org/images/voltages11.png<br /><br />
Memory Split<br />
<pre>cpuvinf -m
or 
cpuvinf --memory
</pre>
Screenshot: https://cpuvinf-cdn.hiddenrefuge.eu.org/images/memory11.png<br /><br />
Everything at once<br />
<pre>cpuvinf -a
or
cpuvinf --all
</pre>
Screenshot: https://cpuvinf-cdn.hiddenrefuge.eu.org/images/all11.png<br /><br /><br />
<B>CPUVInf is licensed under the GNU GPL 3 license.<br />
Part of <a href="https://i.tny.im/"><img src="https://tny.im/tnyimimages/tny-line-16.png" alt="TNY Network"></a></B>
