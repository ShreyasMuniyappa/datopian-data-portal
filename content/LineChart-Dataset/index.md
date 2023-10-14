---
title: 'Bitcoin data in LineChart dataset'
author: 'Shreyas Muniyappa'
description: 'Bitcoin Price History by Year'
modified: '2023-10-14'
files: ['lineChart-data.csv']
group: 'Bitcoin'
---

## Bitcoin High Price History by Year
<LineChart 
    title="High Price of Year vs Year of Bitcon"  
    xAxis="Year"
    yAxis="High" 
    data="lineChart-data.csv"
/>

## Bitcoin Low Price History by Year
<LineChart 
    title="Low Price of Year vs Year of Bitcon"  
    xAxis="Year"
    yAxis="Low" 
    data="lineChart-data.csv"
/>