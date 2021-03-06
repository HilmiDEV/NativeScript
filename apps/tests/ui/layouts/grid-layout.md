---
nav-title: "grid-layout How-To"
title: "grid-layout"
description: "Examples for using grid-layout"
previous_url: /ApiReference/ui/layouts/grid-layout/HOW-TO
---
# GridLayout
Using a GridLayout requires the GridLayout module.
<snippet id='grid-layout-require'/>

### Declaring a GridLayout
``` XML
<GridLayout columns="80, *, auto" rows="auto, *" >
 <Button col="0" />
 <Button col="1" />
 <Button col="2" />
 // by default column and row are set to 0
 <Button row="1" colSpan="3" />
</GridLayout>
```

## Add views to grid layout
<snippet id='grid-layout-addviews'/>

## Set column property on views - btn1 in first column, btn2 is second and btn3 in third
<snippet id='grid-layout-setcolumn'/>

## Set row property on btn4.
<snippet id='grid-layout-setrow'/>

## Set columnSpan property on btn4 to stretch into all columns
<snippet id='grid-layout-columnspan'/>

## Create ItemSpec for columns and rows 3 columns - 80px, *, auto size and 2 rows - 100px and auto size
<snippet id='grid-layout-itemspec'/>

## Add columns and rows to GridLayout
<snippet id='grid-layout-add-rowscols'/>
