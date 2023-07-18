<h2>Screenshot</h2>
<img src="./ProjectSnap.png" />
<h3>Blocks</h3>
<img src="./School.jpg" />

<h3>Solution</h3>
<pre>
"solution": {
    "targets": [
      {
        "targetIndex": 0,
        "costumes": [
          {
            "name": "School"
          },
          {
            "name": "Night City With Street"
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
            "opcode": "looks_switchbackdropto",
            "inputs": { "BACKDROP": [1, "*"] }
          },
          {
            "opcode": "looks_backdrops"
          }
        ]
      }
    ]
  }
</pre>