<!DOCTYPE html>
<html>
<head>
  <title>Designing Your Defensive Solution</title>
</head>
<body>
  <h1>Designing Your Defensive Solution</h1>
  <p>Today, you will create a monitoring solution to protect VSI. Specifically, you will:</p>
  <ol>
    <li>Load and analyze Windows logs.</li>
    <li>Create reports, alerts, and dashboards for the Windows logs.</li>
    <li>Load and analyze Apache logs.</li>
    <li>Create reports, alerts, and dashboards for the Apache logs.</li>
    <li>Install an add-on Splunk application for additional monitoring.</li>
  </ol>
  <h2>Resources</h2>
  <ul>
    <li>Splunkbase</li>
    <li>Splunk Documentation</li>
    <li>Splunk Add-Ons Guide</li>
  </ul>
  <h2>Getting Started / Prerequisites</h2>
  <p>You will use your local Vagrant virtual machine for this week's activities.</p>
  <ul>
    <li>This week's classes will use the same Splunk Docker container to run Splunk from inside the local virtual machine that was used during the Splunk lessons. In the /splunk directory inside the virtual machine, you will find a splunk.sh script that can be run to start and stop the container as needed.</li>
    <li>If needed, refer back to the guide from Module 19 to configure Splunk on your VM.</li>
    <li>Once the container is running, Splunk can be accessed at http://localhost:8000 on the virtual machine.</li>
  </ul>


  <h2>Instructions</h2>
  <ul>
    <li>Today, you will play the role of an SOC analyst at a small company called Virtual Space Industries (VSI), which designs virtual-reality programs for businesses.</li>
    <li>VSI has heard rumors that a competitor, JobeCorp, may launch cyberattacks to disrupt VSI’s business.</li>
    <li>As an SOC analyst, you are tasked with using Splunk to monitor against potential attacks on your systems and applications.</li>
    <li>The VSI products that you have been tasked with monitoring include:
      <ul>
        <li>An administrative webpage: https://vsi-corporation.azurewebsites.net/</li>
        <li>An Apache web server, which hosts this webpage</li>
        <li>A Windows operating system, which runs many of VSI’s back-end operations</li>
      </ul>
    </li>
    <li>Your networking team has provided you with past logs to help you develop baselines and create reports, alerts, dashboards, and more.
      <ul>
        <li>Windows Server Logs
