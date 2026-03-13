# Nixie-Clock-V1

<p align="center">
  <img src="https://github.com/user-attachments/assets/b042b10e-0bf0-4d63-bf84-9d530f95d11d" alt="IN-12 Nixie Tube Clock">
</p>

<p align="center">
  <em>6-digit IN-12 Nixie tube clock with OLED interface</em>
</p>

<p>This repository contains the hardware design and firmware resources for a <strong>6-digit IN-12 Nixie tube clock</strong>. The device is powered via <strong>USB Type-C</strong> and uses a <strong>flyback converter</strong> to generate the high voltage required to drive the Nixie tubes.</p>

<p>The clock features an <strong>OLED display</strong> for a graphical user interface, an onboard <strong>buzzer</strong> for alarms and notifications, and a <strong>DS3231 RTC</strong> backed by a <strong>CR1220 coin cell</strong> to keep accurate time when USB power is off. Control is handled by an <strong>STM32L0 series microcontroller</strong>, providing low-power operation with precise timing and flexible firmware updates.</p>

<p>The goal of this repository is to provide all the files required to reproduce, manufacture, and program the clock. It is intended for <strong>electronics enthusiasts, hobbyists, and developers</strong> interested in Nixie tube technology, high-voltage power design, and custom hardware projects.</p>

<h2>Features</h2>
<ul>
  <li><strong>6-digit IN-12 Nixie tube display</strong></li>
  <li><strong>Low-profile design</strong></li>
  <li><strong>USB-C powered</strong></li>
  <li><strong>Integrated flyback converter</strong> for Nixie high-voltage generation</li>
  <li><strong>OLED display</strong> for graphical user interface</li>
  <li><strong>Onboard buzzer</strong> for alarms and notifications</li>
  <li><strong>DS3231 RTC</strong> with <strong>CR1220 battery backup</strong></li>
  <li><strong>STM32L0 series microcontroller</strong> for control logic</li>
</ul>

<h2>Hardware Overview</h2>
<ul>
  <li><strong>Power Supply:</strong> USB Type-C input with integrated flyback converter</li>
  <li><strong>Display:</strong> OLED graphical interface for settings and status</li>
  <li><strong>Timekeeping:</strong> DS3231 RTC with CR1220 coin cell backup</li>
  <li><strong>Control:</strong> STM32L0 series MCU for low-power operation</li>
  <li><strong>Buzzer:</strong> Onboard for alarms and notification feedback</li>
  <li><strong>PCB:</strong> Low-profile design with full schematics and Gerber files</li>
</ul>

<h2>Repository Contents</h2>
<ul>
  <li><strong>Altium Designer project</strong> – complete PCB design files</li>
  <li><strong>Schematics</strong> – circuit diagrams of the system</li>
  <li><strong>Gerber files</strong> – ready for PCB manufacturing</li>
  <li><strong>Firmware binary</strong> – compiled file for programming the microcontroller (soon to be available)</li>
</ul>
