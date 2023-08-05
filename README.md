# Dheeraj-steeleye-assignment2

The highlightHTMLContent function is a JavaScript function that takes three inputs: htmlContent, plainText, and plainTextPositions. The purpose of this function is to highlight certain portions of the htmlContent based on the positions specified in the plainTextPositions array.

#explanation of the code
The function begins by iterating through each element in the plainTextPositions array using plainTextPositions.forEach((d) => { ... }).




## Installation

Install and run frequency-app with npm-vite

```bash
npm create vite@latest
cd my-project
npm install
npm run dev 
```

Install the recharts npm package for histogram

```bash
npm install recharts
```
Install the axios npm package for fetching text file
```bash
npm install axios
```


    
## Documentation

1. Create a folder named components in src folder.
2. Create files named FileFetch.jsx , FileFetch.css in components folder.
3. Create a functional component in FileFetch.jsx.
4. import axios and some child components from recharts.

```bash
import axios from "axios";
import {
  ResponsiveContainer,
  BarChart,
  Bar,
  XAxis,
  YAxis,
  Tooltip,
  Label,
  LabelList,
} from "recharts";
```
# Count frequencies 
1. Call the function calculateLetterFrequencies on onclick with passing text file from submit button.

```bash

