<html>
<body>
  <h1 style="font-size: 18px; font-weight: bold; text-decoration: underline;">Part 1: Load and Analyze Windows Logs</h1>
  <p>In this first part, you will upload and analyze Windows security logs that represent “regular” activity for VSI into your Splunk environment. To do so, complete the following steps:</p>
  <ul style="list-style-type: none; padding: 0;">
    <li style="font-size: 14px; margin: 10px 0;">Select the “Add Data” option within Splunk.</li>
    <li style="font-size: 14px; margin: 10px 0;">Since you will upload the provided log file, select the “Upload” option under “Or get data in with the following methods.”</li>
    <li style="font-size: 14px; margin: 10px 0;">Then, click “Select File.”</li>
    <li style="font-size: 14px; margin: 10px 0;">Double-click the <code style="background-color: #eee; border-radius: 4px; padding: 2px 4px;">windows_server_logs.csv</code> file located in the <code style="background-color: #eee; border-radius: 4px; padding: 2px 4px;">/splunk/logs/Defensive-Project-Logs/</code> directory, as the following image shows:</li>
    <li style="font-size: 14px; margin: 10px 0;">You will be brought to the “Set Source Type” page.</li>
    <li style="font-size: 14px; margin: 10px 0;">You don't need to change any configurations on this page.</li>
    <li style="font-size: 14px; margin: 10px 0;">Select “Next” again.</li>
    <li style="font-size: 14px; margin: 10px 0;">You'll be brought to the “Input Settings” page.</li>
    <li style="font-size: 14px; margin: 10px 0;">This page contains optional settings for how the data is input.</li>
    <li style="font-size: 14px; margin: 10px 0;">In the “Host field value” field, Splunk uses a random value to name the machine or device that generated the logs.</li>
    <li style="font-size: 14px; margin: 10px 0;">Update the value to “Windows_server_logs” and then select “Review.”</li>
    <li style="font-size: 14px; margin: 10px 0;">On the “Review” page, verify that you've chosen the correct settings.</li>
    <li style="font-size: 14px; margin: 10px 0;">Select “Submit” to proceed with uploading your data into Splunk.</li>
    <li style="font-size: 14px; margin: 10px 0;">Once the file has successfully uploaded, a message that says “File
