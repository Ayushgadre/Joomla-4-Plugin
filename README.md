# Joomla-4-Plugin
This repo contains the plugin created by me for the coding task given for Joomla GSOC 2022.

# P2 Guided Tour - Evaluation task 
A headings plugin that concatenates your text with your site's heading.

## Installation:
<ol>
  <li> Download the zip file </li>
  <li> Visit Joomla Administration Panel of your website </li>
  <li> Go to the plugin installation page (Found under system settings) </li>
  <li> Upload the zip file </li>
</ol>

## Plugin Specifications:
- Type: <b> System </b> <br/>
- Events Used: <b> onBeforeCompileHead </b>
- Follows Joomla Coding Standards: <b> Yes </b> <br/>
- Follows Joomla Naming Conventions: <b> Yes </b> <br/>
- phpcs sniffer verified: <b> Yes </b> <br/>

## Plugin Folder Structure

    ├── language
    │   └── en-GB.plg_system_vsheadings.ini
    └── yvcookies.php
    └── yvcookies.xml


## Expected Output/Behaviour:
### 1. Entering the desired text into the input field

Note: Page is being reloaded in the gif

![Entering Text]

Here, I have entered my name 'Vanshita' and saved the changes.

### 2. Opening your joomla site 

Note: Page is being reloaded in the gif

![Displayed view]

After opening the site you will be able to see the concatenation of the two strings.
