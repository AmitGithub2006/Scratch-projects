<h2>Screenshot</h2>
<img src="./ProjectSnap.png" />
<h3>Blocks</h3>
<img src="./Blackboard.jpg" />
<img src="./Blackboard1.jpg" />

<h3>Solution</h3>
<pre>
"solution": {
    "targets": [
      {
        "targetIndex": 0,
        "costumes": [
          {
            "name": "Chalkboard"
          }
        ]
      },
      {
        "targetIndex": 1,
        "blocks": [
          {
            "opcode": "event_whenflagclicked",
            "topLevel": true
          },
          {
            "opcode": "looks_sayforsecs",
            "inputs": {
              "MESSAGE": [1, [10, "*"]],
              "SECS": [1, [4, "*"]]
            }
          }
        ]
      },
      {
        "targetIndex": 2,
        "blocks": [
        ]
      },
      {
        "targetIndex": 3,
        "blocks": [
            {
              "opcode": "event_whenflagclicked",
              "topLevel": true
            },
            {
              "opcode": "looks_changesizeby",
              "inputs": { "CHANGE": [1, [4, "*"]] }
            }
        ]
      }
    ]
  }
</pre>