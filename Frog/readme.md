<h2>Screenshot</h2>
<img src="./ProjectSnap.png" />
<h3>Blocks</h3>
<img src="./Frog.jpg" />

<h3>Solution</h3>
<pre>
 "solution": {
    "targets": [
      {
        "targetIndex": 0,
        "costumes": [
          {
            "name": "Pathway"
          }
        ]
      },
      {
        "targetIndex": 1,
        "blocks": [
          {
            "opcode": "event_whenflagclicked",
            "topLevel":true
          },
          {
            "opcode": "looks_switchcostumeto",
            "inputs": { "COSTUME": [1, "*"] }
          },
          {
            "opcode": "looks_costume"
          }
        ]
      },
      {
        "targetIndex": 2,
        "blocks":[],
        "name": "Diver2"
      }
    ]
  }
</pre>