<body>
  <div>
    <h1> 🔍Maximum elements In ArrayList</h1>
    <p>This repository contains a simple java program to find the <b>maximum elements</b> in a <b>ArrayList</b> using iteration </p>
  </div>
  <div>
    <h2>📍About The Program</h2>
  </div>
  <ul>
    <p>This program :</p>
    <li>Creates an <b>ArrayList</b> of integers</li>
    <li>Inserts mulitple values </li>
    <li>Traverse in the list using a<b>for loop</b></li>
    <li>Finds the maximum elements using <mark> <b> Math.max()</b> </li></mark>
  </ul>
  <div>
    <h2>📒Concept Used</h2>
    <ul>
      <li>Java Collection Framework </li>
      <li>ArrayList</li>
      <li> For loop</li>
      <li><mark><b>Integer.MIN_VALUE</b></mark></li>
      <li>Math.max()</li>
  </div>
      <div>
        <h2>⌛ Time Complexity</h2>
        <ol>
          <li>The <b>for loop</b> runs once for each elements in the Arraylist</li>
          <li>If the list has n elements the loop execute n times</li>
          <li>Each iteration perform  a constant time operation <b>(MATH.max)</b></li>
          <li>There are no nested loop in the program</li>
          <li>Therefore the total time taken increased linearly with n</li>
          <li><mark><b>Time Complexity = O(n)</b></mark></li>
        </ol>
      </div>
      <div>
        <h2>🫙 Sapce Complexity</h2>
          <ol>
            <li>Only one extra variable <b> (max)</b> is used to store the maxium value</li>
            <li>No additional data structure are created</li>
            <li>The size of the extra does not depend on input size</li>
            <li>The  ArrayList itself is part of the input..no extra space </li>
            <li>Hence..the sapace used remains constant</li>
            <li><mark><b>Space Complexity = O(1)</b></mark></li>
          </ol>
      </div>
</body>
    
     
