---
title: Getting Started
nav: true
--- 

When conducting college-level research, there is a general process to follow:

{% capture text %}

1. Select topic
2. Use Boolean logic to expand or narrow key concepts or keywords
3. Select a database
4. Evaluate and revise search strategy
5. Choose items and find full-text online or in print

{% endcapture %}

{% include card.md text=text header="Research Process" %}

Since you have already selected your topic, this guide will focus on the other aspects of the research process. First, let’s talk about Boolean logic. 

## Boolean Logic

Boolean logic uses Boolean operators (such as `AND`, `OR`, `NOT`) to narrow, expand, or define a search, and is applicable to conducting searches in library catalog and most databases. Writing out your search terms using Boolean operators by connecting pieces of information and coming up with synonyms is a good exercise as it can show wanted results and filter out unrelated results. Below are some of the most common Boolean operators you can use:

<html>
   <head>
      <style>
         table {width: 100%;}
         table, td, th {
            border-collapse: collapse;
            padding: 8px;
            border-bottom: 1px solid #ddd;
         
         th {            
            style="text-align:Center"
            border: 1px solid black;
            padding-top: 12px;
            padding-bottom: 12px;
            background-color: #f1b300;
            color: white;
            }
      </style>
   </head>
   <body>
      <table>
         <tr>
            <th style="background-color: #f1b300; color: white; text-align:Center">Boolean Operator</th>
            <th style="background-color: #f1b300; color: white; text-align:Center">Explanation</th>
            <th style="background-color: #f1b300; color: white; text-align:Center">Example</th>
         </tr>
         <tr>
            <th style="text-align:Center">AND</th>
            <td style="text-align:Left">Each result contains all search terms</td>
            <td style="text-align:Left">Antibiotic AND farm</td>
         </tr>
         <tr>
            <th style="text-align:Center">OR</th>
            <td style="text-align:Left">Each result contains at least one search term</td>
            <td style="text-align:Left">production OR lactation OR secretion OR yield</td>
         </tr>
         <tr>
            <th style="text-align:Center">" "</th>
            <td style="text-align:Left">Results must include search terms in the defined order</td>
            <td style="text-align:Left">“bovine somatotropin” OR “bovine growth hormone”</td>
         </tr>
          <tr>
            <th style="text-align:Center">NOT</th>
            <td style="text-align:Left">Results do not contain the specified terms</td>
            <td style="text-align:Left">“skim milk” NOT “powdered milk”</td>
         </tr>
         <tr>
            <th style="text-align:Center">*</th>
            <td style="text-align:Left">Results can include search terms with different endings of the root word</td>
            <td style="text-align:Left">Lactat* [for lactate, lactation, lactating, etc.]</td>
         </tr>         
         <tr>
            <th style="text-align:Center">?</th>
            <td style="text-align:Left">Results include words with alternative spellings</td>
            <td style="text-align:Left">“pasteuri?ed milk”</td>
         </tr>
          <tr>
            <th style="text-align:Center">( )</th>
            <td style="text-align:Left">Results include the phrase with the order of relationships organized</td>
            <td style="text-align:Left">(“low-fat milk” OR “skim milk”) AND “whole milk” AND consumption</td>
         </tr>
      </table>
   </body>
   <p>
   </p>
</html>

{% capture text %}You can check out [this guide](https://libguides.uidaho.edu/boolean) to learn more about Boolean logic.
{% endcapture %}
{% include alert.md text=text color="warning" %}
