<h2>Screenshot</h2>
<img src="./ProjectSnap.png" />
<h3>Blocks</h3>
<img src="./Princess.jpg" />

<h3>Solution</h3>
<pre>
"solution": {
    "targets": [
      {
        "targetIndex": 0,
        "costumes": [
          {
            "name": "Theater"
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
            "opcode": "looks_say",
            "inputs": { "MESSAGE": [1, [10, "*"]] }
          }
        ]
      }
    ]
  }
</pre>