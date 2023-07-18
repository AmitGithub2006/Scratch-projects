<h2>Screenshot</h2>
<img src="./ProjectSnap.png" />
<h3>Blocks</h3>
<img src="./Laptop.jpg" />
<img src="./Laptop1.jpg" />

<h3>Solution</h3>
<pre>
"solution": {
    "targets": [
      {
        "targetIndex": 0,
        "costumes": [
          {
            "name": "Bedroom 3"
          }
        ]
      },
      {
        "targetIndex": 1,
        "blocks": [
          {
            "opcode": "event_whenthisspriteclicked",
            "topLevel": true
          },
          {
             "opcode": "motion_gotoxy",
             "inputs": { "X": [1, [4, "*"]], "Y": [1, [4, "*"]] }
          },
          {
            "opcode": "motion_movesteps",
            "inputs": { "STEPS": [1, [4, "*"]] }
          }
        ]
      },
      {
        "targetIndex": 2,
        "blocks": [
          {
            "opcode": "event_whenflagclicked",
            "topLevel": true
          },
          {
             "opcode": "motion_movesteps",
             "inputs": { "STEPS": [1, [4, "*"]] }
          },
          {
            "opcode": "motion_movesteps",
            "inputs": { "STEPS": [1, [4, "*"]] }
          }
        ]
      }
    ]
  }
</pre>